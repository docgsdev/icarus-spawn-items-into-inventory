# Manual: Editando o Inventário do Save do Icarus no Linux (Proton)

## ⚠️ Antes de começar: uso responsável

Este manual existe para **destravar missões que já passaram do tempo razoável de
conclusão** — por exemplo, quando um item específico simplesmente não aparece
com frequência suficiente no mapa e você já passou horas procurando sem sucesso.

**Não é recomendado** usar isso para pular o jogo inteiro, evitar todo o grind, ou
completar missões que ainda estão dentro de um tempo normal de progresso. Parte
da graça do Icarus é a jornada de conseguir os recursos — use isso como último
recurso, não como atalho padrão.

Pontos importantes de segurança:

- O Icarus **não tem anti-cheat** (nem VAC, nem EAC) — não há risco de banimento
  de conta por editar seu próprio save local.
- Isso edita **arquivos locais no seu computador**. Só afeta sessões onde você é
  o host.
- **Sempre feche o jogo completamente** antes de editar qualquer arquivo, e
  **sempre faça backup antes de mexer em qualquer coisa**.
- Se você joga com amigos, teste as mudanças numa sessão solo/privada primeiro,
  salve corretamente saindo pro menu, e só depois abra a sessão para os amigos.
  Editar o save enquanto outros jogadores estão conectados pode causar
  dessincronização e corromper itens.

---

## O que você vai precisar

- Icarus instalado via Steam, rodando por Proton ou GE-Proton
- Um terminal
- `git`
- Python 3.8+
- `pip` (no Arch/CachyOS, se não tiver: `sudo pacman -S python-pip`)
- Um editor de texto de terminal, como `nano` (ou qualquer editor gráfico)

---

## Passo 1 — Localize seu arquivo de save

No Windows, os saves ficam em:
```
%LocalAppData%\Icarus\Saved\PlayerData\<SEU_STEAMID64>\Prospects\
```

No Linux, como o Icarus roda através do Proton, esse mesmo caminho existe —
só que "dentro" de um prefixo Wine que o Steam cria para o jogo. O AppID do
Icarus na Steam é **1149460**.

Para achar a pasta `compatdata` no seu sistema:

```bash
find ~/.steam ~/.local/share/Steam -maxdepth 4 -iname 'compatdata' 2>/dev/null
```

O caminho completo geralmente fica assim (ajuste a base conforme o resultado
do comando acima):

```
~/.local/share/Steam/steamapps/compatdata/1149460/pfx/drive_c/users/steamuser/AppData/Local/Icarus/Saved/PlayerData/<SEU_STEAMID64>/Prospects/
```

Dentro dessa pasta `Prospects`, cada sessão/mundo que você já jogou tem seu
próprio arquivo `.json` — o nome geralmente é o mesmo nome que você deu ao
prospect no jogo.

**Dica:** se seu gerenciador de arquivos não mostra `.steam` ou `.local`,
aperte `Ctrl+H` para mostrar arquivos/pastas ocultos.

---

## Passo 2 — Faça backup ANTES de qualquer coisa

Com o jogo **fechado**:

```bash
cp -r ~/.local/share/Steam/steamapps/compatdata/1149460/pfx/drive_c/users/steamuser/AppData/Local/Icarus/Saved/PlayerData/<SEU_STEAMID64> ~/icarus_backup_$(date +%Y%m%d)
```

Isso copia toda a sua pasta de saves para um lugar seguro. Se algo der errado
mais tarde, você restaura esse backup e volta ao ponto de partida.

Também vale desativar temporariamente o Steam Cloud para o Icarus (Propriedades
do jogo na Steam → aba de Cloud), para que ele não sobrescreva seu arquivo
editado com uma versão antiga quando você abrir o jogo de novo.

---

## Passo 3 — Baixe a ferramenta de edição

Vamos usar a ferramenta de código aberto `icarus-save-editor`, que já entende
o formato interno do arquivo (explicado no Passo 4).

```bash
cd ~
git clone https://github.com/N30Z/icarus-save-editor
cd icarus-save-editor
pip install customtkinter --break-system-packages
```

Copie o `.json` do prospect que você quer editar para dentro da pasta
`savegames/` deste projeto (facilita rodar os comandos):

```bash
cp ~/.local/share/Steam/steamapps/compatdata/1149460/pfx/drive_c/users/steamuser/AppData/Local/Icarus/Saved/PlayerData/<SEU_STEAMID64>/Prospects/<NOME_DO_PROSPECT>.json ~/icarus-save-editor/savegames/
```

---

## Passo 4 — Como o arquivo é estruturado (o que você precisa saber)

Você **não** deve tentar editar o `.json` do prospect diretamente num editor de
texto comum. Ele tem só dois campos no nível principal:

- `ProspectInfo` — metadados simples (nome da missão, dificuldade, etc.), texto
  normal e legível.
- `ProspectBlob` — **todo o resto do mundo** (seu personagem, inventário,
  construções, etc.), guardado assim:

```
ProspectBlob (texto)
  └─ campo "BinaryBlob" dentro dele
       └─ codificado em base64
            └─ que quando decodificado é dados comprimidos em zlib
                 └─ que quando descomprimidos são o formato binário
                    proprietário da Unreal Engine (não é texto, não dá
                    pra editar num editor comum)
```

É por isso que **precisamos de uma ferramenta específica** (como a que
baixamos no Passo 3) em vez de simplesmente abrir o arquivo e mudar um número.
A ferramenta cuida de descomprimir, editar a estrutura binária certinho, e
recomprimir tudo de volta no formato exato que o jogo espera.

---

## Passo 5 — Descubra seu Steam ID e slot de personagem dentro do save

```bash
cd ~/icarus-save-editor
python3 gd_inventory_cli.py savegames/<NOME_DO_PROSPECT>.json list
```

Isso mostra algo como:

```
<SEU_STEAMID64>  slot=2  [inv2:11, inv3:16, inv4:2, inv5:9, inv11:0, inv12:1]
```

O número depois de `slot=` é o **slot do seu personagem** dentro dessa conta
(pode ser 0, 1, 2... dependendo de quantos personagens você já criou). Anote
esse número — vamos precisar dele.

Os números entre colchetes (`inv3:16`, etc.) são a **capacidade de slots** de
cada tipo de inventário, não quantos itens você tem.

### IDs de inventário (usados em todos os comandos abaixo)

| ID | O que é |
|----|---------|
| 2  | Equipamento / Hotbar |
| 3  | **Mochila** (backpack — o principal, onde você normalmente quer adicionar itens) |
| 4  | Cinto |
| 5  | Armadura / Cosméticos |

---

## Passo 6 — Veja o que já tem no inventário

⚠️ **Atenção a um bug conhecido da ferramenta**, explicado com detalhes na
seção de Troubleshooting no final deste manual: os comandos `items`, `set`,
`add`, `remove` e `clear` do CLI (`gd_inventory_cli.py`) **sempre assumem que
seu personagem está no slot 0**, mesmo que o comando `list` mostre um slot
diferente. Se seu personagem **não** estiver no slot 0, esses comandos vão
dar erro (`Player ... slot 0 not found`) ou mostrar "No items found" mesmo
quando você tem itens.

Por isso, este manual usa um **script Python próprio** que contorna esse
problema, chamando a biblioteca por trás do CLI diretamente e informando o
slot correto. Copie e adapte o script abaixo.

Crie o arquivo:

```bash
cd ~/icarus-save-editor
nano meu_editor.py
```

Cole isto dentro (ajuste os placeholders `<...>` no topo):

```python
from gd_inventory_editor import GdInventoryEditor

# ==== AJUSTE ESTES VALORES ====
ARQUIVO_SAVE = "savegames/<NOME_DO_PROSPECT>.json"
STEAM_ID     = "<SEU_STEAMID64>"      # veja no comando 'list'
CHAR_SLOT    = 0                       # veja no comando 'list' (campo slot=)
INV_ID       = 3                       # 3 = Mochila (veja tabela acima)
# ===============================

editor = GdInventoryEditor(ARQUIVO_SAVE)
editor.load()   # ESSENCIAL — sem essa linha, o editor fica vazio


def listar_itens():
    """Mostra tudo que já está no inventário escolhido."""
    items = editor.get_items(STEAM_ID, INV_ID, char_slot=CHAR_SLOT)
    if not items:
        print("Nenhum item encontrado (inventário vazio ou parâmetros errados).")
        return
    for it in sorted(items, key=lambda x: x['location']):
        print(f"  slot {it['location']:>3}: {it['item']} x{it['count']}")


def adicionar_item(nome_interno, quantidade):
    """Adiciona um item no primeiro slot livre."""
    items = editor.get_items(STEAM_ID, INV_ID, char_slot=CHAR_SLOT)
    ocupados = {it['location'] for it in items}
    slot = 0
    while slot in ocupados:
        slot += 1
    editor.set_item(
        steam_id=STEAM_ID, inv_id=INV_ID, location=slot,
        item_name=nome_interno, count=quantidade, durability=None,
        char_slot=CHAR_SLOT,
    )
    print(f"Adicionado: {nome_interno} x{quantidade} no slot {slot}")


def editar_item_no_slot(slot, nome_interno, quantidade):
    """Sobrescreve um slot específico com outro item/quantidade."""
    editor.set_item(
        steam_id=STEAM_ID, inv_id=INV_ID, location=slot,
        item_name=nome_interno, count=quantidade, durability=None,
        char_slot=CHAR_SLOT,
    )
    print(f"Slot {slot} agora tem: {nome_interno} x{quantidade}")


def remover_item(slot):
    """Remove o que estiver num slot específico."""
    editor.remove_item(STEAM_ID, INV_ID, slot, char_slot=CHAR_SLOT)
    print(f"Slot {slot} removido")


# ==== CHAME AS FUNÇÕES QUE VOCÊ QUISER AQUI EMBAIXO ====

listar_itens()

# Exemplos (descomente e ajuste as linhas que quiser usar):
# adicionar_item("Watermelon", 20)
# editar_item_no_slot(5, "Carrot", 50)
# remover_item(7)

editor.save(backup=True)
print("Salvo (com backup automático em .backup)")
```

Salve (`Ctrl+O`, `Enter`, `Ctrl+X`) e rode:

```bash
python3 meu_editor.py
```

Isso vai listar todos os itens que já existem no inventário escolhido, com o
slot de cada um.

---

## Passo 7 — Adicionar, editar ou remover itens

Edite o bloco final do `meu_editor.py` (a parte "CHAME AS FUNÇÕES") e escolha
o que quer fazer:

- **Adicionar um item novo** (no próximo slot livre):
  ```python
  adicionar_item("Watermelon", 20)
  ```

- **Adicionar vários itens do mesmo tipo em slots separados** (útil quando a
  quantidade que você quer passa do limite de pilha de um único slot — veja
  a tabela na próxima seção):
  ```python
  for _ in range(5):
      adicionar_item("Watermelon", 20)   # 5 slots de 20 = 100 no total
  ```

- **Editar/sobrescrever um item que já está num slot específico:**
  ```python
  editar_item_no_slot(5, "Carrot", 50)
  ```

- **Remover um item de um slot:**
  ```python
  remover_item(7)
  ```

Depois de editar o script, rode de novo com `python3 meu_editor.py`.

**Nome interno do item:** o jogo não usa o nome que aparece na tela (ex:
"Melancia"), e sim um nome interno em inglês (ex: `Watermelon`). Veja a tabela
de referência abaixo, ou descubra outros procurando dentro dos dados da
própria ferramenta baixada:

```bash
cd ~/icarus-save-editor
grep -ri "nome_do_item_em_ingles" data/Items/D_ItemsStatic.json | grep '"Name"'
```

---

## Passo 8 — Confira o resultado antes de levar pro jogo

Rode o script de novo (ele reimprime a lista no início, antes de salvar) ou
adicione só `listar_itens()` sem chamar nenhuma função de edição, para
conferir que ficou como você queria.

---

## Passo 9 — Copie o arquivo editado de volta para o jogo

```bash
cp ~/icarus-save-editor/savegames/<NOME_DO_PROSPECT>.json ~/.local/share/Steam/steamapps/compatdata/1149460/pfx/drive_c/users/steamuser/AppData/Local/Icarus/Saved/PlayerData/<SEU_STEAMID64>/Prospects/<NOME_DO_PROSPECT>.json
```

Abra o Icarus, carregue esse prospect, e confira o inventário in-game.

---

## Tabela de referência: itens comuns

Nome interno (o que você usa no script) e limite máximo de pilha por slot.
**Respeite esse limite** — passar dele em um único slot pode fazer o jogo
simplesmente descartar aquele item ao carregar o save (sem aviso de erro, ele
só some). Se quiser mais que o limite, use vários slots (veja exemplo no
Passo 7).

| Item (nome em jogo) | Nome interno | Pilha máxima |
|---|---|---|
| Melancia | `Watermelon` | 20 |
| Cenoura | `Carrot` | 50 |
| Madeira | `Wood` | 100 |
| Graveto | `Stick` | 100 |
| Fibra | `Fiber` | 200 |

Essa é só uma amostra rápida. A lista **completa** (mais de 2.400 itens,
extraídos direto dos arquivos de dados do jogo, organizados por categoria —
comida, munição, armas, ferramentas, recursos, construção, etc.) está no
arquivo separado `tabela-completa-itens-icarus.md`, que acompanha este
manual.

---

## Troubleshooting (problemas comuns)

### `KeyError: Player '...' slot 0 not found`
Você está usando o `gd_inventory_cli.py` diretamente (não o script deste
manual), e seu personagem não está no slot 0. Use o `meu_editor.py` deste
manual, que pede o slot certo explicitamente — descubra o slot certo com o
comando `list` (Passo 5).

### "No items found" mesmo tendo itens
Mesmo bug acima — o CLI original sempre olha o slot 0 por padrão nos
comandos `items`, `set`, `add`, `remove` e `clear`. Use o script deste manual.

### Lista de jogadores vem vazia (`Jogadores encontrados: []`)
Você esqueceu de chamar `editor.load()` depois de criar o `GdInventoryEditor(...)`.
Esse passo não aparece nos exemplos do README do projeto, mas é obrigatório —
sem ele, o arquivo nunca é de fato lido.

### O item que adicionei sumiu depois de eu carregar o save
Bem provável que você tenha colocado uma quantidade maior que o limite de
pilha daquele item num slot só (veja a tabela acima). O jogo não avisa erro —
ele só ignora aquele slot como inválido. Solução: divida a quantidade em
vários slots, cada um dentro do limite.

### Terminal trava depois de colar um bloco de código com `<< 'EOF'`
Isso é um problema comum no shell **fish** com heredocs. Evite esse método —
use `nano nome_do_arquivo.py`, cole o conteúdo, salve com `Ctrl+O` → `Enter`
→ `Ctrl+X`.

---

## Resumo do fluxo completo

1. Feche o jogo
2. Backup da pasta inteira de saves
3. Copie o `.json` do prospect para a pasta `savegames/` do projeto
4. Rode `list` para achar seu Steam ID e slot de personagem
5. Edite `meu_editor.py` com o que você quer adicionar/editar/remover
6. Rode o script, confira a lista impressa
7. Copie o arquivo de volta para o caminho do Proton
8. Abra o jogo numa sessão solo/privada e confirme que está tudo certo antes
   de jogar com outras pessoas
