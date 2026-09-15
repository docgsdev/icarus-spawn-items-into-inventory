# Tabela Completa de Itens do Icarus (Nome Interno + Pilha Máxima)

> Este arquivo é um complemento do `manual-editar-inventario-icarus-linux.md`. Use o **Nome interno** aqui listado como o `nome_interno` no script de edição, e a **Pilha máx.** como referência de quantos itens colocar por slot.

## Sobre esta lista

- **2453 itens** extraídos diretamente dos arquivos de dados do próprio jogo (não de wikis de terceiros) — via o repositório da ferramenta de edição de save que usamos no manual principal.
- Ficaram de fora **itens de Workshop/Meta** (versões usadas no carregamento orbital, guardadas num arquivo separado — `MetaInventory.json` — e fora do escopo deste manual) e itens marcados internamente como **descontinuados/de teste** pelos próprios desenvolvedores.
- **Pilha máx.** = quantidade máxima recomendada por slot (ver aviso no manual principal: passar disso pode fazer o jogo descartar o item silenciosamente ao carregar).
- **Peso** é por unidade, em kg — útil para não estourar sua capacidade de carga ao adicionar itens em massa.
- Sobre criaturas específicas: procurei por um item chamado "Dodo" nos dados do jogo e não existe — o Icarus não tem essa criatura. Se você quis dizer **"dados"** (mais informações/detalhes), é isso que a coluna de peso adiciona; se quis dizer outra coisa, me avise.
- Use `Ctrl+F` no seu editor/navegador para achar o item pelo nome em português aproximado ou pelo nome em inglês mostrado aqui.

### Proveniência e nível de confiança (verificado)

- **Como os dados são gerados:** o script `update_data.py` do repositório extrai esses arquivos diretamente do `data.pak` do jogo instalado, usando o **UnrealPak** (ferramenta oficial da Epic Games para pacotes Unreal Engine) — não são digitados à mão nem copiados de wiki.
- **Quem mantém o repositório:** é um projeto pessoal pequeno (`N30Z/icarus-save-editor` no GitHub — 2 estrelas, 1 fork, 40 commits), feito por uma pessoa só, não afiliado à RocketWerkz (desenvolvedora do Icarus). Não passou por revisão de uma comunidade grande.
- **Idade dos dados:** o último commit é de **11 de abril de 2026**. O Icarus recebe patches de balanceamento com frequência (mods de terceiros na Nexus precisam ser "reconstruídos" a cada atualização por causa disso), então alguns valores aqui podem estar desatualizados em relação à versão mais recente do jogo.
- **Confirmação real:** testamos ao vivo dois itens desta lista (melancia x20 e cenoura x100) — os dois bateram exatamente com o que esta tabela indicava, e funcionaram no save de verdade. Essa é a evidência mais forte que temos: pelo menos para esses itens, os dados batem com a versão do jogo atualmente instalada.
- **Recomendação:** trate esta tabela como a melhor fonte disponível (mais confiável que uma wiki isolada, por vir direto dos arquivos do jogo), mas sempre confira no jogo depois de adicionar qualquer item novo — é a única forma de ter certeza para a versão exata que você está jogando agora.

---

## Comida e Bebida (288 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Agave | `Agave` | 100 | 0.25 |
| Agave Syrup | `Agave_Syrup` | 10 | 0.15 |
| Animal Bait | `Bait` | 5 | 0.05 |
| Avocado | `Avocado` | 100 | 0.25 |
| Azure Danio | `Fish_10_Var2` | 1 | — |
| Bacon Butty | `Bacon_Sandwich` | 10 | 0.25 |
| Banana | `Banana` | 30 | 0.01 |
| Banana Bread | `Banana_Bread` | 10 | 0.15 |
| Banana Porridge | `Banana_Porridge` | 10 | 0.15 |
| Banana Tart | `Banana_Tart` | 10 | 0.15 |
| Banana Toast | `Banana_Toast` | 10 | 0.2 |
| Banded Discus | `Fish_14_Var3` | 1 | — |
| Banded Dory | `Fish_11` | 1 | — |
| Banded Gar | `Fish_17_Var3` | 1 | — |
| Banded Jack | `Fish_02_Var2` | 1 | — |
| Banded Tetra | `Fish_08_Var4` | 1 | — |
| Barbecue Carrot | `Cooked_Carrot` | 10 | 0.5 |
| Basic Dried Meat | `Dried_Meat_Generic` | 10 | 0.25 |
| Beer | `Beer` | 12 | 0.5 |
| Berry & Seed Bar | `Food_Berry_Bar` | 25 | 0.2 |
| Berry Jam | `Glass_Jar_Jam` | 20 | 0.5 |
| Berry Smoked Saltwater Fillet | `Smoked_Saltwater_Fillet` | 10 | 0.25 |
| Big Breakfast | `Big_Breakfast` | 10 | 0.5 |
| Black Diamond Discus | `Fish_14` | 1 | — |
| Bread | `Food_Bread` | 50 | 0.05 |
| Bread Dough | `Dough_Bread` | 50 | 0.05 |
| Broiled Kumara | `Cooked_Kumara` | 10 | 0.5 |
| Canteen | `Canteen` | 1 | 0.5 |
| Caramel Berry Tart | `Caramel_Fruit_Tart` | 10 | 0.2 |
| Caramel Pastry | `Salted_Caramel_Pastry` | 10 | 0.25 |
| Caramelized Onions | `Caramelized_Onions` | 10 | 0.15 |
| Carrot | `Carrot` | 100 | 0.03 |
| Carrot Cake | `Carrot_Cake` | 1 | 2.0 |
| Carrot Cake Piece | `Carrot_Cake_Piece` | 8 | 0.5 |
| Cat Food Bowl | `Cat_Bowl_Food` | 1 | 0.5 |
| Chargrilled Chicken | `Grilled_Chicken` | 20 | 0.5 |
| Charred Corn | `Cooked_Corn` | 10 | 0.5 |
| Cheese | `Cheese` | 50 | 0.25 |
| Cheese Pizza Slice | `Cheese_Pizza` | 8 | 0.25 |
| Cheese Roll | `Cheese_Roll` | 10 | 0.25 |
| Chewy Coconut Cookie | `Coconut_Cookie` | 20 | 0.15 |
| Choc-Chip Cookie | `Choc_Chip_Cookie` | 20 | 0.15 |
| Chocolate Cake | `Chocolate_Cake` | 1 | 2.0 |
| Chocolate Cake Piece | `Chocolate_Cake_Piece` | 8 | 0.5 |
| Cobalt Puffer | `Fish_18_Var3` | 1 | — |
| Cocoa Smoked Soft Meat | `Smoked_Soft_Meat` | 20 | 0.05 |
| Coconut Cake | `Coconut_Cake` | 1 | 2.0 |
| Coconut Cake Piece | `Coconut_Cake_Piece` | 8 | 0.5 |
| Coffee Smoked Fatty T-bone | `Smoked_Fatty_Tbone` | 20 | 0.5 |
| Cooked Agave | `Cooked_Agave` | 10 | 0.25 |
| Cooked Bacon | `Cooked_Bacon` | 50 | 0.1 |
| Cooked Fatty T-Bone | `Fatty_Tbone_Cooked` | 20 | 0.5 |
| Cooked Gamey Meat | `Gamey_Meat_Cooked` | 20 | 0.25 |
| Cooked Garlic | `Cooked_Garlic` | 10 | 0.15 |
| Cooked Giant Steak | `Giant_Steak_Cooked` | 20 | 1.0 |
| Cooked Meat | `Cooked_Meat` | 20 | 0.05 |
| Cooked Onion | `Cooked_Onion` | 10 | 0.15 |
| Cooked Prickly Pear | `Cooked_PricklyPear` | 10 | 0.25 |
| Cooked Soft Meat | `Soft_Meat_Cooked` | 20 | 0.2 |
| Cooked Stringy Meat | `Stringy_Meat_Cooked` | 20 | 0.25 |
| Cooked Truffle | `Cooked_Truffle` | 10 | 0.1 |
| Cooked White Meat | `White_Meat_Cooked` | 20 | 0.2 |
| Coral Danio | `Fish_10_Var3` | 1 | — |
| Coral Darter | `Fish_05_Var4` | 1 | — |
| Coral Dorado | `Fish_13_Var2` | 1 | — |
| Coral Ripjaw | `Fish_04` | 1 | — |
| Corn | `Corn` | 100 | 0.1 |
| Creamed Corn | `Food_Creamed_Corn` | 10 | 0.5 |
| Crimson Darter | `Fish_05_Var2` | 1 | — |
| Crimson Dory | `Fish_11_Var3` | 1 | — |
| Crimson Piranha | `Fish_03_Var2` | 1 | — |
| Crimson Snapper | `Fish_01_Var3` | 1 | — |
| Crimson Springfield | `Fish_19` | 1 | — |
| Crimson Triggerfish | `Fish_06_Var2` | 1 | — |
| Crimson Wrasse | `Fish_12` | 1 | — |
| Crispy Bacon | `Crispy_Bacon` | 50 | 0.1 |
| Crispy Potato | `Cooked_Potato` | 10 | 0.5 |
| Crumbed Saltwater Fillet | `Crumbed_Saltwater_Fillet` | 10 | 0.5 |
| Crunchy Soy Bean | `Cooked_Soy_Bean` | 10 | 0.5 |
| Crystal Discus | `Fish_14_Var4` | 1 | — |
| Crystal Piranha | `Fish_03_Var3` | 1 | — |
| Crystal Puffer | `Fish_18_Var4` | 1 | — |
| Crystal Wrasse | `Fish_12_Var2` | 1 | — |
| Dog Food Bowl | `Dog_Bowl_Food` | 1 | 0.5 |
| Dried Avocado | `Dried_Avocado` | 20 | 0.1 |
| Dried Banana Chips | `Dried_Banana` | 10 | 0.15 |
| Dried Fatty T-Bone | `Fatty_Tbone_Dried` | 20 | 0.5 |
| Dried Freshwater Fillet | `Dried_Freshwater_Fillet` | 10 | 0.25 |
| Dried Gamey Meat | `Gamey_Meat_Dried` | 20 | 0.25 |
| Dried Giant Steak | `Giant_Steak_Dried` | 20 | 1.0 |
| Dried Kiwifruit Chips | `Dried_Kiwifruit` | 20 | 0.02 |
| Dried Rhubarb | `Dried_Rhubarb` | 20 | 0.1 |
| Dried Saltwater Fillet | `Dried_Saltwater_Fillet` | 10 | 0.25 |
| Dried Soft Meat | `Soft_Meat_Dried` | 20 | 0.2 |
| Dried Stringy Meat | `Stringy_Meat_Dried` | 20 | 0.25 |
| Dried Tomato | `Dried_Tomato` | 20 | 0.1 |
| Dried White Meat | `White_Meat_Dried` | 20 | 0.2 |
| Egg | `Egg` | 100 | 0.25 |
| Electric Wraith | `Fish_16` | 1 | — |
| Electronic Food Trough | `Food_Trough_T4` | 1 | 3.0 |
| Ember Dorado | `Fish_13_Var4` | 1 | — |
| Ember Gar | `Fish_17` | 1 | — |
| Ember Jack | `Fish_02_Var4` | 1 | — |
| Ember Perch | `Fish_07_Var4` | 1 | — |
| Ember Snapper | `Fish_01_Var2` | 1 | — |
| Ember Trout | `Fish_09_Var3` | 1 | — |
| Ember Wrasse | `Fish_12_Var4` | 1 | — |
| Emerald Danio | `Fish_10` | 1 | — |
| Emerald Dorado | `Fish_13` | 1 | — |
| Emerald Jack | `Fish_02_Var3` | 1 | — |
| Emerald Snapper | `Fish_01_Var4` | 1 | — |
| Energy Bar | `Energy_Bar` | 10 | 0.5 |
| Fish Chunk Stew | `Fish_Chunk_Stew` | 10 | 0.15 |
| Fish Chunks | `Fish_Chunks` | 20 | 0.05 |
| Fish Pie | `Fish_Fillet_Pie` | 10 | 0.5 |
| Flatbread | `Food_Flatbread` | 100 | 0.03 |
| Flatbread Dough | `Dough_Flatbread` | 100 | 0.03 |
| Food Trough | `Food_Trough` | 1 | 3.0 |
| French Onion Soup | `French_Onion_Soup` | 10 | 0.2 |
| Freshwater Fillet Curry | `Freshwater_Fillet_Curry` | 10 | 0.3 |
| Freshwater Fish Fillet | `Freshwater_Fish_Fillet` | 25 | 0.25 |
| Fried Chicken | `Fried_Chicken` | 10 | 0.5 |
| Fried Chunky Vegetables | `Fried_Chunky_Vegetables` | 10 | 0.5 |
| Fried Eggs | `Cooked_Eggs` | 10 | 0.5 |
| Fried Fish Chunks | `Fried_Fish_Chunks` | 10 | 0.1 |
| Fried Tomato | `Cooked_Tomato` | 10 | 0.5 |
| Frozen Banana | `Frozen_Banana` | 10 | 0.15 |
| Fruit Muffin | `Fruit_Muffin` | 10 | 0.5 |
| Fruit Pie | `Food_Fruit_Pie` | 10 | 0.5 |
| Fruit Salad | `Food_Fruit_Salad` | 10 | 0.5 |
| Fruit Snack Pack | `Fruit_Snack_Pack` | 25 | 0.5 |
| Garlic | `Garlic` | 100 | 0.25 |
| Garlic Bread | `Garlic_Bread` | 10 | 0.2 |
| Garlic Butter | `Garlic_Butter` | 10 | 0.15 |
| Garlic Pizza | `Garlic_Pizza` | 10 | 0.25 |
| Ghostly Puffer | `Fish_18` | 1 | — |
| Ghostly Tang | `Fish_15` | 1 | — |
| Glass Food Trough | `Food_Trough_Glass` | 1 | 3.0 |
| Glazed Carrots | `Glazed_Carrots` | 10 | 0.15 |
| Gorse Smoked Gamey Meat | `Smoked_Gamey_Meat` | 20 | 0.25 |
| Grilled Freshwater Fillet | `Grilled_Freshwater_Fish` | 20 | 0.05 |
| Grilled Pumpkin | `Cooked_Pumpkin` | 10 | 0.5 |
| Grilled Saltwater Fillet | `Grilled_Saltwater_Fish` | 20 | 0.05 |
| Gruel | `Gruel` | 100 | 0.01 |
| Hearty Salad | `Food_Hearty_Salad` | 10 | 0.5 |
| Honey | `Honey` | 50 | 0.5 |
| Honey Glazed Pastry | `Honey_Pastry` | 20 | 0.5 |
| Honey Mead | `Honey_Mead` | 20 | 0.5 |
| Honey Smoked Bacon | `Smoked_Bacon` | 25 | 0.5 |
| Honeycomb | `Honeycomb` | 25 | 1.0 |
| Honeycomb Bar | `Food_Honey_Bar` | 25 | 0.2 |
| Jarred Honey | `Glass_Jar_Honey` | 20 | 0.5 |
| Kiwifruit | `Kiwi_Fruit` | 100 | 0.05 |
| Kiwifruit Jam | `Kiwifruit_Jam` | 20 | 0.5 |
| Kiwifruit Sorbet | `Kiwifruit_Sorbet` | 5 | 0.75 |
| Kumara | `Kumara` | 100 | 0.1 |
| Large Food Trough | `Food_Trough_Large` | 1 | 3.0 |
| Mature Coconut | `Coconut_mature` | 10 | 0.8 |
| Meat Pie | `Food_Meat_Pie` | 10 | 0.5 |
| Melon Smoked Giant Steak | `Smoked_Giant_Steak` | 20 | 1.0 |
| Metal Food Trough | `Food_Trough_Metal` | 1 | 3.0 |
| Mixed Berries | `Mixed_Berries` | 10 | 0.5 |
| Mushroom | `Mushroom` | 100 | 0.1 |
| Mushroom Omlette | `Mushroom_Omlette` | 10 | 0.5 |
| Mushroom Soup | `Food_Mushroom_Soup` | 10 | 0.5 |
| Neon Dorado | `Fish_13_Var3` | 1 | — |
| Neon Dory | `Fish_11_Var2` | 1 | — |
| Neon Puffer | `Fish_18_Var2` | 1 | — |
| Neon Tetra | `Fish_08` | 1 | — |
| Oceanic Piranha | `Fish_03` | 1 | — |
| Onion | `Onion` | 100 | 0.15 |
| Onion Rings | `Onion_Rings` | 10 | 0.1 |
| Onion Souffle | `Onion_Souffle` | 10 | 0.2 |
| Opal Discus | `Fish_14_Var2` | 1 | — |
| Opal Ripjaw | `Fish_04_Var3` | 1 | — |
| Opal Trout | `Fish_09_Var2` | 1 | — |
| Oxite | `Oxite` | 50 | 0.4 |
| Oxygen Bladder | `Oxygen_Bladder` | 1 | 0.25 |
| Oxygen Tank | `Oxygen_Tank` | 1 | 0.5 |
| Pastry | `Pastry` | 10 | 0.5 |
| Pavlova | `Pavlova` | 5 | 0.25 |
| Pearl Danio | `Fish_10_Var4` | 1 | — |
| Pearl Perch | `Fish_07` | 1 | — |
| Pickled Avocado | `Pickled_Avocado` | 20 | 0.5 |
| Pickled Carrot | `Food_Pickled_Carrot` | 20 | 0.5 |
| Pickled Eggs | `Pickled_Eggs` | 20 | 0.5 |
| Pickled Freshwater Fillet | `Pickled_Freshwater_Fillet` | 20 | 0.5 |
| Pickled Tomato | `Food_Pickled_Tomato` | 20 | 0.5 |
| Plain Jerky | `Smoked_Meat_Generic` | 10 | 0.25 |
| Poisoned Animal Bait | `Poisoned_Bait` | 5 | 0.05 |
| Potato | `Potato` | 100 | 0.3 |
| Potato and Carrot Fries | `Food_Potato_Carrot_Fries` | 10 | 0.5 |
| Potato Bread | `Food_Potato_Bread` | 10 | 0.5 |
| Prickly Pear | `PricklyPear` | 100 | 0.25 |
| Prickly Pear Jelly | `PricklyPear_Jelly` | 10 | 0.1 |
| Prickly Pear Margarita | `PricklyPear_Margarita` | 10 | 0.1 |
| Prickly Pear Muffins | `PricklyPear_Muffins` | 10 | 0.2 |
| Pumpkin | `Pumpkin` | 20 | 0.5 |
| Pumpkin Bread | `Food_Pumpkin_Bread` | 10 | 0.5 |
| Pumpkin Pie | `Pumpkin_Pie` | 10 | 0.3 |
| Raw Bacon | `Raw_Bacon` | 50 | 0.1 |
| Raw Chicken | `Raw_Chicken` | 5 | 1.0 |
| Raw Fatty T-Bone | `Fatty_Tbone` | 20 | 0.5 |
| Raw Fish | `Raw_Fish` | 20 | 0.05 |
| Raw Gamey Meat | `Gamey_Meat` | 20 | 0.25 |
| Raw Giant Steak | `Giant_Steak` | 20 | 1.0 |
| Raw Meat | `Raw_Meat` | 20 | 0.05 |
| Raw Soft Meat | `Soft_Meat` | 20 | 0.2 |
| Raw Stringy Meat | `Stringy_Meat` | 20 | 0.25 |
| Raw White Meat | `White_Meat` | 20 | 0.2 |
| Rhubarb | `Rhubarb` | 100 | 0.1 |
| Rhubarb Stew | `Rhubarb_Stew` | 10 | 0.5 |
| Ripe Coconut | `Coconut_mid` | 10 | 0.8 |
| Roast Chicken | `Roast_Chicken` | 10 | 0.5 |
| Roast Squash | `Cooked_Squash` | 10 | 0.5 |
| Roast Vegetables | `Food_Roasted_Vegetables` | 10 | 0.5 |
| Roasted Banana | `Cooked_Banana` | 10 | 0.15 |
| Rustic Food Trough | `Food_Trough_Rustic` | 1 | 3.0 |
| Saltwater Fillet Sashimi | `Saltwater_Fillet_Sashimi` | 10 | 0.3 |
| Saltwater Fish Fillet | `Saltwater_Fish_Fillet` | 25 | 0.25 |
| Sauteed Rhubarb | `Cooked_Rhubarb` | 10 | 0.5 |
| Savory Roll | `Savory_Roll` | 10 | 0.5 |
| Scrambled Eggs | `Scrambled_Eggs` | 10 | 0.5 |
| Sea Darter | `Fish_05` | 1 | — |
| Seared Mushroom | `Cooked_Mushroom` | 10 | 0.5 |
| Seed Bread | `Food_Seed_Bread` | 20 | 0.5 |
| Seed Cracker | `Food_Seed_Cracker` | 100 | 0.05 |
| Shepherd\'s Pie | `Food_Shepherds_Pie` | 10 | 0.5 |
| Shepherd\'s Roll | `Shepherds_Roll` | 10 | 0.5 |
| Smashed Avocado Toast | `Smashed_Avocado` | 10 | 0.5 |
| Smoked Garlic | `Smoked_Garlic` | 10 | 0.15 |
| Soy Bean | `Bean` | 100 | 0.03 |
| Soy Bean Stir-fry | `Food_Fried_Soy_Beans` | 10 | 0.5 |
| Speckled Gar | `Fish_17_Var4` | 1 | — |
| Spoiled Meat | `Spoiled_Meat` | 100 | 0.05 |
| Spoiled Plants | `Spoiled_Plants` | 100 | 0.03 |
| Sponge | `Sponge` | 1 | 0.1 |
| Spotted Gar | `Fish_17_Var2` | 1 | — |
| Spotted Perch | `Fish_07_Var2` | 1 | — |
| Spotted Snapper | `Fish_01` | 1 | — |
| Spotted Tetra | `Fish_08_Var2` | 1 | — |
| Spotted Wrasse | `Fish_12_Var3` | 1 | — |
| Squash | `Squash` | 100 | 0.1 |
| Steamed Fish | `Cooked_Fish` | 20 | 0.05 |
| Stew | `Food_Meat_Stew` | 10 | 0.5 |
| Strawberries & Cream | `Strawberries_And_Cream` | 10 | 0.25 |
| Strawberry | `Strawberry` | 100 | 0.1 |
| Strawberry Hard Candy | `Strawberry_Candy` | 50 | 0.01 |
| Strawberry Jam | `Strawberry_Jam` | 20 | 0.5 |
| Stringy Jerky | `Smoked_Stringy_Meat` | 20 | 0.25 |
| Striped Springfield | `Fish_19_Var2` | 1 | — |
| Stuffed Avocado | `Stuffed_Avocado` | 10 | 0.5 |
| Sunset Darter | `Fish_05_Var3` | 1 | — |
| Sunset Jack | `Fish_02` | 1 | — |
| Sunset Perch | `Fish_07_Var3` | 1 | — |
| Sunset Ripjaw | `Fish_04_Var4` | 1 | — |
| Sunset Springfield | `Fish_19_Var3` | 1 | — |
| Sunset Tetra | `Fish_08_Var3` | 1 | — |
| Sunset Triggerfish | `Fish_06_Var3` | 1 | — |
| Sunset Trout | `Fish_09` | 1 | — |
| Sweetcorn Soup | `Food_Corn_Soup` | 10 | 0.5 |
| Tea Smoked Freshwater Fillet | `Smoked_Freshwater_Fillet` | 10 | 0.25 |
| Thermos | `Thermos` | 1 | 0.75 |
| Titan Dory | `Fish_11_Var4` | 1 | — |
| Titan Piranha | `Fish_03_Var4` | 1 | — |
| Titan Ripjaw | `Fish_04_Var2` | 1 | — |
| Titan Triggerfish | `Fish_06` | 1 | — |
| Tomato | `Tomato` | 100 | 0.3 |
| Tomato & Egg Bowl | `Egg_Salad` | 10 | 0.5 |
| Tomato Soup | `Food_Tomato_Soup` | 10 | 0.5 |
| Transgenic Tomato | `Mission_Tomato` | 100 | 0.3 |
| Truffle | `Truffle` | 100 | 0.1 |
| Truffle Focaccia | `Truffle_Focaccia` | 10 | 0.1 |
| Truffle Fries | `Truffle_Fries` | 10 | 0.15 |
| Truffle Pasta | `Truffle_Pasta` | 10 | 0.3 |
| Vegetable Pie | `Food_Vegetable_Pie` | 10 | 0.5 |
| Vegetable Roll | `Vegetable_Roll` | 10 | 0.5 |
| Void Springfield | `Fish_19_Var4` | 1 | — |
| Void Triggerfish | `Fish_06_Var4` | 1 | — |
| Void Trout | `Fish_09_Var4` | 1 | — |
| Watermelon | `Watermelon` | 20 | 0.5 |
| Watermelon Lollypop | `Watermelon_Lollypop` | 50 | 0.01 |
| Waterskin | `Waterskin` | 1 | 0.25 |
| White Jerky | `Smoked_White_Meat` | 20 | 0.05 |
| Wild Berry | `Berry` | 100 | 0.01 |
| Wild Salad | `Food_Wild_Salad` | 10 | 0.5 |
| Wine | `Wine` | 12 | 0.5 |
| Young Coconut | `Coconut_young` | 10 | 0.8 |

## Remédios e Primeiros Socorros (31 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Anti-parasitic Paste | `Antiparasitic_Paste` | 10 | 0.25 |
| Anti-parasitic Pill | `Antiparasitic_Pill` | 10 | 0.01 |
| Anti-parasitic Tonic | `Antiparasitic_Tonic` | 10 | 0.25 |
| Anti-poison Paste | `Antipoison_Paste` | 10 | 0.25 |
| Anti-poison Pill | `Antipoison_Pill` | 10 | 0.01 |
| Anti-poison Tonic | `Antipoison_Tonic` | 10 | 0.25 |
| Anti-Radiation Tonic | `AntiRadiation_Tonic` | 10 | 0.25 |
| Anti-Radiation Transfusion | `AntiRadiation_Transfusion` | 10 | 0.25 |
| Antibiotic Paste | `Antibiotic_Paste` | 10 | 0.25 |
| Antibiotic Pill | `Antibiotic_Pill` | 10 | 0.01 |
| Antibiotic Tonic | `Antibiotic_Tonic` | 10 | 0.25 |
| Basic Bandage | `Bandage_Basic` | 10 | 0.1 |
| Blood Thinning Paste | `Blood_Thinning_Paste` | 10 | 0.25 |
| Blood Thinning Pill | `Blood_Thinning_Pill` | 10 | 0.01 |
| Blood Thinning Tonic | `Blood_Thinning_Tonic` | 10 | 0.25 |
| Cooling Bandage | `Bandage_Cooling` | 10 | 0.1 |
| Garganutan Frenzy Tonic | `Ape_Tonic` | 10 | 0.25 |
| Health Recovery Concoction | `Health_Remedy` | 10 | 0.25 |
| Health Recovery Elixir | `Health_Elixir` | 10 | 0.5 |
| Health Recovery Tonic | `Health_Enhancement_Tonic` | 10 | 0.25 |
| Heat Bandage | `Bandage_Heat` | 10 | 0.1 |
| Luriform Serum | `Enzyme_Elixir` | 10 | 0.5 |
| Medical Satchel | `Item_Medicine_Bag` | 1 | 2.0 |
| Splint | `Splint` | 10 | 1.0 |
| Stamina Enhancement Tonic | `Stamina_Enhancement_Tonic` | 10 | 0.25 |
| Strength Enhancement Tonic | `Strength_Enhancement_Tonic` | 10 | 0.25 |
| Survival Kit | `Dressing_Kit` | 10 | 1.0 |
| Sustenance Enhancement Tonic | `Sustenence_Enhancement_Tonic` | 10 | 0.25 |
| Suture Kit | `Suture_Kit` | 10 | 0.2 |
| Vitamins | `Vitamins` | 20 | 0.5 |
| Water Treatment Pill | `Purification_Pill` | 10 | 0.01 |

## Recursos / Matéria-Prima (156 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| 12-Gauge Casing | `Shotgun_Casing` | 200 | 0.01 |
| Acidic Glands | `Acidic_Glands` | 50 | 0.25 |
| Active Lithium | `Lithium_Refined` | 50 | 0.1 |
| Aluminium Ingot | `Aluminium` | 20 | 0.25 |
| Aluminium Ore | `Bauxite` | 100 | 0.4 |
| Aluminium Screw | `Aluminium_Screw` | 100 | 0.01 |
| Ammo Casing | `Ammo_Casing` | 200 | 0.01 |
| Animal Fat | `Animal_Fat` | 10 | 0.5 |
| Arctic Pelt | `Polarbear_Pelt` | 50 | 0.5 |
| Basic Fertilizer | `Basic_Fertilizer` | 20 | 2.0 |
| Beeswax | `Beeswax` | 50 | 0.25 |
| Biofuel Can | `Jerrycan` | 1 | 3.0 |
| Black Wolf Fur | `Black_Fur` | 25 | 1.0 |
| Black Wolf Tooth | `Black_Wolf_Tooth` | 20 | 0.05 |
| Bone | `Bone` | 100 | 0.01 |
| Bottled Tequila | `Tequila` | 10 | 0.1 |
| Butter | `Butter` | 20 | 0.05 |
| Carbon Fiber | `Carbon_Fiber` | 20 | 0.25 |
| Carbon Paste | `Carbon_Paste` | 20 | 0.25 |
| Charcoal | `Charcoal` | 500 | 0.1 |
| Clay | `Clay` | 100 | 0.25 |
| Clay Brick | `Clay_Brick` | 100 | 0.3 |
| Coal Ore | `Coal_Ore` | 100 | 0.5 |
| Cold Steel Ingot | `Cold_Steel_Ingot` | 20 | 0.4 |
| Composite Paste | `Composite_Paste` | 20 | 0.25 |
| Composites | `Composites` | 20 | 0.25 |
| Compounds | `Compounds` | 100 | 0.1 |
| Concrete Mix | `Concrete_Mix` | 100 | 0.15 |
| Condensed Enzymes | `Condensed_Enzymes` | 100 | 0.2 |
| Copper Ingot | `Refined_Copper` | 20 | 0.25 |
| Copper Ore | `Copper_Ore` | 50 | 0.4 |
| Copper Wire | `Copper_Wire` | 200 | 0.03 |
| Cream | `Cream` | 50 | 0.05 |
| Crushed Bone | `Crushed_Bone` | 50 | 0.01 |
| Crushed Limestone | `Crushed_Limestone` | 100 | 0.2 |
| Crystallised Miasma | `Raw_Iron_Wood` | 200 | 0.1 |
| Cured Leather | `Advanced_Leather` | 250 | 0.01 |
| Dirt | `Dirt` | 50 | 0.2 |
| Distilled Miasmic Coating | `Refined_Iron_Wood` | 50 | 0.3 |
| Electronics | `Electronics` | 100 | 0.01 |
| Elephant Tusk | `Elephant_Tusk` | 1 | 7.5 |
| Epoxy | `Epoxy` | 100 | 0.01 |
| Exotic Shard | `Condensed_Exotic` | 1 | 40.0 |
| Flour | `Flour` | 100 | 0.03 |
| Frozen Ore | `Frozen_Ore` | 50 | 0.25 |
| Frozen Wood | `Frozen_Wood` | 100 | 0.15 |
| Frozen Wool | `Frozen_Wool` | 25 | 1.0 |
| Fur | `Fur` | 100 | 0.05 |
| Fur Stack | `Fur_Stack` | 1 | 12.5 |
| Garganutan Hide | `Ape_Hide` | 5 | 1.0 |
| Garganutan Tendon | `Ape_Bicep` | 5 | 1.0 |
| Glass | `Glass` | 20 | 0.25 |
| Glass Bottle | `Glass_Bottle` | 12 | 0.15 |
| Glass Jar | `Glass_Jar` | 20 | 0.1 |
| Gold Ore | `Gold_Ore` | 50 | 0.4 |
| Gold Wire | `Gold_Wire` | 200 | 0.03 |
| Growth Fertilizer | `Speed_Fertilizer` | 20 | 2.0 |
| Guano | `Guano` | 500 | 0.0 |
| Gunpowder | `Gunpowder` | 100 | 0.01 |
| Hammerhead Skin | `Slug_Skin` | 5 | 1.0 |
| Hammerhead Slime | `Slug_Slime` | 5 | 1.0 |
| Hardened Horn | `Lava_Hunter_Horn` | 5 | 1.0 |
| Hardened Magma | `Lava_Hunter_Magma` | 5 | 1.0 |
| High-Quality Fertilizer | `Yield_Fertilizer` | 20 | 2.0 |
| Ice | `Ice` | 100 | 0.02 |
| Ice Armor Fragment | `Ice_Armor_Fragment` | 25 | 1.0 |
| Inert Uranium Ingot | `Uranium_Inert` | 20 | 0.25 |
| Inert Volatile Substance | `Volatile_Substance_Inert` | 25 | 0.25 |
| Infected Bark | `Infected_Bark` | 50 | 0.25 |
| Iron Ingot | `Refined_Metal` | 20 | 0.25 |
| Iron Ore | `Metal_Ore` | 50 | 0.4 |
| LAB-01 Access Card | `Mission_ELY3_AccessCard` | 1 | 0.5 |
| Leather | `Leather` | 100 | 0.01 |
| Limestone | `Limestone` | 100 | 0.3 |
| Mammoth Tusk | `Mammoth_Tusk` | 1 | 15.0 |
| Noxious Crust (Aluminium) | `Pyritic_Crust_Bauxite` | 50 | 0.25 |
| Noxious Crust (Clay) | `Pyritic_Crust_Clay` | 50 | 0.25 |
| Noxious Crust (Coal) | `Pyritic_Crust_Coal` | 50 | 0.25 |
| Noxious Crust (Copper) | `Pyritic_Crust_Copper` | 50 | 0.25 |
| Noxious Crust (Exotic) | `Pyritic_Crust_Purple_Exotic` | 50 | 0.25 |
| Noxious Crust (Gold) | `Pyritic_Crust_Gold` | 50 | 0.25 |
| Noxious Crust (Iron) | `Pyritic_Crust_Iron` | 50 | 0.25 |
| Noxious Crust (Limestone) | `Pyritic_Crust_Limestone` | 50 | 0.25 |
| Noxious Crust (Lithium) | `Pyritic_Crust_Lithium` | 50 | 0.25 |
| Noxious Crust (Obsidian) | `Pyritic_Crust_Obsidian` | 50 | 0.25 |
| Noxious Crust (Oxite) | `Pyritic_Crust_Oxite` | 50 | 0.25 |
| Noxious Crust (Platinum) | `Pyritic_Crust_Platinum` | 50 | 0.25 |
| Noxious Crust (Ruby) | `Pyritic_Crust_Ruby` | 50 | 0.25 |
| Noxious Crust (Salt) | `Pyritic_Crust_Salt` | 50 | 0.25 |
| Noxious Crust (Scoria) | `Pyritic_Crust_Scoria` | 50 | 0.25 |
| Noxious Crust (Silica) | `Pyritic_Crust_Silicon` | 50 | 0.25 |
| Noxious Crust (Stone) | `Pyritic_Crust_Stone` | 50 | 0.25 |
| Noxious Crust (Sulfur) | `Pyritic_Crust_Sulfur` | 50 | 0.25 |
| Noxious Crust (Titanium) | `Pyritic_Crust_Titanium` | 50 | 0.25 |
| Noxious Crust (Volatile Raw Exotic) | `Pyritic_Crust_Red_Exotic` | 50 | 0.25 |
| Obsidian | `Obsidian` | 100 | 0.3 |
| Oil Barrel | `Oil_Barrel` | 1 | 5.0 |
| Oil Can | `Oil_Can` | 1 | 3.0 |
| Organic Resin | `Organic_Resin` | 100 | 0.01 |
| Packed Fuel Brick | `Packed_Fuel_Brick` | 25 | 0.5 |
| Paints | `Paints` | 500 | 0.01 |
| Plastics | `Plastics` | 50 | 0.5 |
| Platinum Ingot | `Platinum_Ingot` | 20 | 0.25 |
| Platinum Ore | `Platinum_Ore` | 100 | 0.4 |
| Platinum Sheath | `Platinum_Shealth` | 25 | 0.25 |
| Platinum Weave | `Platinum_Weave` | 250 | 0.01 |
| Poison Paste | `Poison_Paste` | 20 | 0.15 |
| Poison Sac | `Poison_Sack` | 25 | 1.0 |
| Portable Biofuel Tank | `Portable_Tank_Biofuel` | 1 | 5.0 |
| Portable Water Tank | `Portable_Tank_Water` | 1 | 5.0 |
| Powerbank | `Powerbank` | 1 | 3.0 |
| Progenitive Fertilizer | `Seed_Fertilizer` | 20 | 2.0 |
| Quarrite Core | `Rock_Golem_Core` | 5 | 1.0 |
| Quarrite Fragment | `Rock_Golem_Fragment` | 5 | 1.0 |
| Queen Bee | `Queen_Bee` | 1 | 0.1 |
| Raw Uranium | `Uranium_Raw` | 10 | 1.0 |
| Recovery Fertilizer | `Quailty_Fertilizer` | 20 | 2.0 |
| Refined Gold | `Refined_Gold` | 20 | 0.25 |
| Refined Wood | `Wood_Refined` | 100 | 0.07 |
| Resistance Fertilizer | `Resistance_Fertilizer` | 20 | 2.0 |
| Rope | `Rope` | 100 | 0.01 |
| Salt | `Salt` | 500 | 0.01 |
| Sand | `Sand` | 50 | 0.05 |
| Sandworm Scale | `Sandworm_Scale` | 5 | 1.0 |
| Sandworm Tendon | `Sandworm_Tendon` | 25 | 1.0 |
| Sandwyrm Queen Egg | `Sandwyrm_Egg` | 25 | 1.0 |
| Scoria | `Scoria` | 100 | 0.35 |
| Scoria Brick | `Scoria_Brick` | 100 | 0.3 |
| Scorpion Carapace | `Scorpion_Carapace` | 5 | 1.0 |
| Seed | `Seed` | 400 | 0.01 |
| Shaped Obsidian | `Shaped_Obsidian` | 100 | 0.3 |
| Shaped Ruby | `Ruby_Shaped` | 50 | 0.1 |
| Silica Ore | `Silica` | 50 | 0.4 |
| Spider Silk | `Spider_Silk` | 200 | 0.01 |
| Steel Bloom | `Steel_Bloom` | 50 | 0.25 |
| Steel Ingot | `Steel_Ingot` | 20 | 0.25 |
| Steel Rebar | `Steel_Rebar` | 50 | 0.03 |
| Steel Screw | `Steel_Screw` | 100 | 0.0 |
| Stone | `Stone` | 100 | 0.3 |
| Stone Brick | `Stone_Brick` | 100 | 0.3 |
| Sugar Cubes | `Sugar` | 500 | 0.1 |
| Sulfur | `Sulfur` | 50 | 0.4 |
| Super Cooled Ice | `Super_Cooled_Ice` | 100 | 0.3 |
| Synthetic Enzymes | `Synthetic_Enzymes` | 100 | 0.2 |
| Synthetics | `Synthetics` | 50 | 0.2 |
| Titanium Ingot | `Titanium_Ingot` | 20 | 0.25 |
| Titanium Ore | `Titanium_Ore` | 100 | 0.4 |
| Titanium Plate | `Titanium_Plate` | 25 | 0.25 |
| Tree Sap | `Tree_Sap` | 100 | 0.01 |
| Vegetable Oil | `Seed_Oil` | 100 | 0.05 |
| Venom Sac | `Venom_Sac` | 25 | 1.0 |
| Volatile Substance | `Volatile_Substance` | 25 | 0.25 |
| Wood | `Wood` | 100 | 0.15 |
| Wool | `Wool` | 50 | 0.5 |
| Worker Bee | `Worker_Bee` | 5 | 0.1 |
| Worm Scale | `Caveworm_Scale` | 25 | 1.0 |

## Sementes e Plantio (12 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Cocoa | `Cocoa` | 100 | 0.1 |
| Coffee Bean | `Coffee` | 100 | 0.1 |
| Fiber | `Fiber` | 200 | 0.01 |
| Gorse Flower | `WildTea` | 100 | 0.05 |
| Lily | `Lily` | 100 | 0.01 |
| Reed Flower | `Reed_Flower` | 100 | 0.01 |
| Sugar Cane | `Sugar_Cane` | 100 | 0.25 |
| Tainted Plant DNA | `Plant_Extract` | 200 | 0.01 |
| Tea | `GreenTea` | 100 | 0.05 |
| Volatile Raw Exotic | `Exotic_Red_Raw` | 10 | 2.5 |
| Wheat | `Wheat` | 100 | 0.03 |
| Yeast | `Yeast` | 100 | 0.01 |

## Munição (74 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| 12-Gauge Buckshot Shell | `Ammo_Shell_Buckshot` | 100 | 0.01 |
| 12-Gauge Cold Steel Shell | `Ammo_Shell_ColdSteel` | 100 | 0.01 |
| 12-Gauge Explosive Shell | `Ammo_Shell_Explosive` | 100 | 0.01 |
| 12-Gauge Lithium Shell | `Ammo_Shell_Lithium` | 100 | 0.01 |
| 12-Gauge Miasmic Shell | `Ammo_Shell_Ironwood` | 100 | 0.01 |
| 12-Gauge Obsidian Shell | `Ammo_Shell_Obsidian` | 100 | 0.01 |
| 12-Gauge Slug | `Ammo_Shell_Slug` | 100 | 0.01 |
| 12-Gauge Uranium Shell | `Ammo_Shell_Uranium` | 100 | 0.01 |
| 5.56mm Armor Piercing Round | `Ammo_AssaultRifle_Round_Armor_Piercing` | 100 | 0.01 |
| 5.56mm Cold Steel Round | `Ammo_AssaultRifle_Round_Cold_Steel` | 100 | 0.01 |
| 5.56mm Explosive Round | `Ammo_AssaultRifle_Round_Explosive` | 100 | 0.01 |
| 5.56mm Incendiary Round | `Ammo_AssaultRifle_Round_Incendiary` | 100 | 0.01 |
| 5.56mm Lithium Round | `Ammo_AssaultRifle_Round_Lithium` | 100 | 0.01 |
| 5.56mm Miasmic Round | `Ammo_AssaultRifle_Round_Iron_Wood` | 100 | 0.01 |
| 5.56mm Obsidian Round | `Ammo_AssaultRifle_Round_Obsidian` | 100 | 0.01 |
| 5.56mm Round | `Ammo_AssaultRifle_Round` | 100 | 0.01 |
| 5.56mm Uranium Round | `Ammo_AssaultRifle_Round_Uranium` | 100 | 0.01 |
| 7.62mm Armor Piercing Round | `Ammo_Rifle_Round_Armor_Piercing` | 100 | 0.01 |
| 7.62mm Cold Steel Round | `Ammo_Rifle_Round_Cold_Steel` | 100 | 0.01 |
| 7.62mm Explosive Round | `Ammo_Rifle_Round_Explosive` | 100 | 0.01 |
| 7.62mm Incendiary Round | `Ammo_Rifle_Round_Incendiary` | 100 | 0.01 |
| 7.62mm Lithium Round | `Ammo_Rifle_Round_Lithium` | 100 | 0.01 |
| 7.62mm Miasmic Round | `Ammo_Rifle_Round_Iron_Wood` | 100 | 0.01 |
| 7.62mm Obsidian Round | `Ammo_Rifle_Round_Obsidian` | 100 | 0.01 |
| 7.62mm Round | `Ammo_Rifle_Round` | 100 | 0.01 |
| 7.62mm Uranium Round | `Ammo_Rifle_Round_Uranium` | 100 | 0.01 |
| 9mm Armor Piercing Round | `Ammo_Pistol_Round_Armor_Piercing` | 100 | 0.01 |
| 9mm Cold Steel Round | `Ammo_Pistol_Round_Cold_Steel` | 100 | 0.01 |
| 9mm Explosive Round | `Ammo_Pistol_Round_Explosive` | 100 | 0.01 |
| 9mm Incendiary Round | `Ammo_Pistol_Round_Incendiary` | 100 | 0.01 |
| 9mm Lithium Round | `Ammo_Pistol_Round_Lithium` | 100 | 0.01 |
| 9mm Miasmic Round | `Ammo_Pistol_Round_Iron_Wood` | 100 | 0.01 |
| 9mm Obsidian Round | `Ammo_Pistol_Round_Obsidian` | 100 | 0.01 |
| 9mm Round | `Ammo_Pistol_Round` | 100 | 0.01 |
| 9mm Uranium Round | `Ammo_Pistol_Round_Uranium` | 100 | 0.01 |
| Aluminium Arrow | `Aluminium_Arrow` | 100 | 0.01 |
| Black Wolf Arrow | `Black_Wolf_Arrow` | 100 | 0.01 |
| Bone Arrow | `Bone_Arrow` | 100 | 0.01 |
| Carbon Arrow | `Carbon_Arrow` | 100 | 0.01 |
| Caveworm Arrow | `Caveworm_Arrow` | 100 | 0.01 |
| Cold Steel Arrow | `Cold_Steel_Arrow` | 100 | 0.03 |
| Cold Steel Bolt | `Cold_Steel_Bolt` | 100 | 0.01 |
| Composite Arrow | `Composite_Arrow` | 100 | 0.01 |
| Copper Bolt | `Copper_Bolt` | 100 | 0.01 |
| Copper Nail | `Copper_Nail` | 100 | 0.01 |
| Crude Ammo | `Ammo_Crude` | 100 | 0.01 |
| Crude Ammo | `Soldier_Rifle_Round` | 100 | 0.01 |
| Enzymatic Mutation Ammo | `Ammo_EDS` | 100 | 0.01 |
| Fire Arrow | `Fire_Arrow` | 100 | 0.01 |
| Flare (Blue) | `Flare_Blue` | 10 | 0.01 |
| Flare (Green) | `Flare_Green` | 10 | 0.01 |
| Flare (Red) | `Flare_Red` | 10 | 0.01 |
| Flare (Yellow) | `Flare_Yellow` | 10 | 0.01 |
| Flare Arrow | `Flare_Arrow` | 100 | 0.01 |
| Flint Arrow | `Flint_Arrow` | 100 | 0.01 |
| Iron Bolt | `Metal_Bolt` | 100 | 0.01 |
| Iron Nail | `Iron_Nail` | 100 | 0.01 |
| Lithium Arrow | `Lithium_Arrow` | 100 | 0.03 |
| Lithium Bolt | `Lithium_Bolt` | 100 | 0.01 |
| Miasmic Arrow | `Iron_Wood_Arrow` | 100 | 0.03 |
| Miasmic Bolt | `Iron_Wood_Bolt` | 100 | 0.01 |
| Obsidian Arrow | `Obsidian_Arrow` | 100 | 0.03 |
| Obsidian Bolt | `Obsidian_Bolt` | 100 | 0.01 |
| Platinum Bolt | `Platinum_Bolt` | 100 | 0.01 |
| Poison Arrow | `Poison_Arrow` | 100 | 0.01 |
| Prototype Drill Arrow | `Drill_Arrow` | 100 | 0.05 |
| Sandworm Arrow | `Sandworm_Arrow` | 100 | 0.01 |
| Steel Arrow | `Steel_Arrow` | 100 | 0.01 |
| Steel Bolt | `Steel_Bolt` | 100 | 0.01 |
| Stone Arrow | `Stone_Arrow` | 100 | 0.01 |
| Titanium Arrow | `Titanium_Arrow` | 100 | 0.01 |
| Titanium Bolt | `Titanium_Bolt` | 100 | 0.01 |
| Uranium Arrow | `Uranium_Arrow` | 100 | 0.03 |
| Uranium Bolt | `Uranium_Bolt` | 100 | 0.01 |

## Armas (64 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Advanced Pistol | `Pistol_T4` | 1 | 1.8 |
| Assault Rifle | `Rifle_Assault_T4` | 1 | 5.5 |
| Bolt Action Rifle | `Rifle_BoltAction` | 1 | 4.0 |
| Bone Javelin | `Bone_Throwing_Spear` | 20 | 0.4 |
| Bone Spear | `Bone_Spear` | 1 | 1.0 |
| Carbon Javelin | `Carbon_Throwing_Spear` | 20 | 0.4 |
| Carbon Spear | `Carbon_Spear` | 1 | 1.0 |
| Caveworm Bow | `Caveworm_Bow` | 1 | 1.0 |
| Caveworm Javelin | `Caveworm_Throwing_Spear` | 20 | 0.4 |
| Caveworm Spear | `Caveworm_Spear` | 1 | 1.0 |
| Cold Steel Javelin | `Cold_Steel_Throwing_Spear` | 20 | 0.5 |
| Cold Steel Spear | `Cold_Steel_Spear` | 1 | 0.5 |
| Composite Javelin | `Composite_Throwing_Spear` | 20 | 1.0 |
| Composite Spear | `Composite_Spear` | 1 | 1.0 |
| Compound Bow | `Compound_Bow` | 1 | 1.0 |
| Crossbow | `Crossbow` | 1 | 1.0 |
| Flamethrower | `Flame_Thrower` | 1 | 2.5 |
| Flare Gun | `Flare_Gun` | 1 | 0.8 |
| Frag Grenade | `Frag_Grenade` | 5 | 0.5 |
| Garganutan Grenade | `Ape_Grenade` | 5 | 0.05 |
| Hammerhead Grenade | `Slug_Grenade` | 5 | 0.5 |
| Hunting Rifle | `Rifle_Hunting` | 1 | 4.0 |
| Impact Grenade | `Frag_Grenade_Impact` | 5 | 0.5 |
| Iron Javelin | `Metal_Throwing_Spear` | 20 | 0.4 |
| Iron Spear | `Metal_Spear` | 1 | 1.0 |
| Laser Sidearm | `Laser_Pistol` | 1 | 2.5 |
| Lithium Bow | `Lithium_Bow` | 1 | 2.5 |
| Lithium Crossbow | `Lithium_Crossbow` | 1 | 2.5 |
| Lithium Javelin | `Lithium_Throwing_Spear` | 20 | 1.0 |
| Lithium Spear | `Lithium_Spear` | 1 | 1.0 |
| Longbow | `Longbow` | 1 | 1.0 |
| Miasmic Javelin | `Iron_Wood_Throwing_Spear` | 20 | 0.5 |
| Miasmic Spear | `Iron_Wood_Spear` | 1 | 0.5 |
| Obsidian Javelin | `Obsidian_Throwing_Spear` | 20 | 0.5 |
| Obsidian Spear | `Obsidian_Spear` | 1 | 0.5 |
| One-Shot Pistol | `Pistol_Handgun` | 1 | 0.8 |
| Platinum Crossbow | `Platinum_Crossbow` | 1 | 1.0 |
| Platinum Javelin | `Platinum_Throwing_Spear` | 20 | 0.4 |
| Platinum Spear | `Platinum_Spear` | 1 | 1.0 |
| Quarrite Grenade | `Rock_Golem_Grenade` | 1 | 0.5 |
| Quarrite Gun | `Rock_Golem_Gun` | 1 | 1.0 |
| Recurve Bow | `Recurve_Bow` | 1 | 1.0 |
| Rimetusk Javelin | `IceMammoth_Throwing_Spear` | 20 | 0.75 |
| Rimetusk Spear | `IceMammoth_Spear` | 1 | 2.0 |
| Rusty Shotgun | `Farmers_Shotgun` | 1 | 3.0 |
| Sandworm Bow | `Sandworm_Bow` | 1 | 1.0 |
| Sandworm Javelin | `Sandworm_Throwing_Spear` | 20 | 0.4 |
| Sandworm Spear | `Sandworm_Spear` | 1 | 1.0 |
| Sandwyrm Queen Bow | `Sandwyrm_Bow` | 1 | 2.5 |
| Scorpion Crossbow | `Scorpion_Crossbow` | 1 | 1.5 |
| Scouts Submachine Gun | `Submachine_Gun_Scout` | 1 | 3.0 |
| Semi-Automatic Pistol | `Pistol_T3` | 1 | 1.5 |
| Shotgun | `Shotgun` | 1 | 4.0 |
| Smoke Grenade | `Smoke_Grenade` | 5 | 0.5 |
| Steel Javelin | `Steel_Throwing_Spear` | 20 | 0.4 |
| Steel Spear | `Steel_Spear` | 1 | 1.0 |
| Submachine Gun | `Submachine_Gun` | 1 | 3.0 |
| Titanium Crossbow | `Titanium_Crossbow` | 1 | 1.0 |
| Titanium Javelin | `Titanium_Throwing_Spear` | 20 | 0.4 |
| Titanium Spear | `Titanium_Spear` | 1 | 1.0 |
| Trench Shotgun | `Shotgun_T4` | 1 | 4.5 |
| Wood Bow | `Wood_Bow` | 1 | 1.0 |
| Wood Javelin | `Wood_Throwing_Spear` | 20 | 0.4 |
| Wood Spear | `Wood_Spear` | 1 | 1.0 |

## Ferramentas (105 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Advanced Carcass Harvesting Attachment | `Knife_Attachment_Bone_Yield_2` | 1 | 1.0 |
| Advanced Leather Attachment | `Knife_Attachment_Leather_Yield_2` | 1 | 1.0 |
| Advanced Prime Meat Attachment | `Knife_Attachment_Prime_Meat_Chance_2` | 1 | 1.0 |
| Basic Fishing Rod | `Basic_Fishing_Rod` | 1 | 1.0 |
| Battery Powered Lantern | `Battery_Lantern` | 1 | 0.25 |
| Binoculars | `Binoculars` | 1 | 0.25 |
| Biofuel Lamp | `Biofuel_Lamp` | 1 | 0.25 |
| Black Wolf Knife | `Black_Wolf_Knife` | 1 | 0.5 |
| Black Wolf Throwing Knife | `Black_Wolf_Throwing_Knife` | 50 | 0.2 |
| Bone Knife | `Bone_Knife` | 1 | 0.5 |
| Bone Sickle | `Bone_Sickle` | 1 | 0.5 |
| Bone Throwing Knife | `Bone_Throwing_Knife` | 50 | 0.2 |
| Carcass Harvesting Attachment | `Knife_Attachment_Bone_Yield_1` | 1 | 1.0 |
| Caveworm Knife | `Caveworm_Knife` | 1 | 0.5 |
| Caveworm Throwing Knife | `Caveworm_Throwing_Knife` | 50 | 0.2 |
| Chainsaw | `Chainsaw` | 1 | 5.0 |
| Cold Steel Axe | `Cold_Steel_Axe` | 1 | 0.5 |
| Cold Steel Knife | `Cold_Steel_Knife` | 1 | 0.5 |
| Cold Steel Pickaxe | `Cold_Steel_Pickaxe` | 1 | 0.5 |
| Cold Steel Sickle | `Cold_Steel_Sickle` | 1 | 0.5 |
| Cold Steel Sledgehammer | `Cold_Steel_Sledgehammer` | 1 | 0.5 |
| Cold Steel Throwing Knife | `Cold_Steel_Throwing_Knife` | 50 | 0.25 |
| Combat Knife | `Combat_Knife` | 1 | 0.5 |
| Crude Oil Piping Tool | `SplineTool_Crude_Oil` | 1 | 0.1 |
| Electricity Tool | `SplineTool_Electricity` | 1 | 0.1 |
| Exotic Infused Pickaxe | `Metal_Exotic_Infused_Pickaxe` | 1 | 1.0 |
| Fire Extinguisher | `FireExtinguisher` | 1 | 1.0 |
| Fire Whacker | `FireWhacker` | 1 | 0.5 |
| Flashlight | `Flashlight` | 1 | 0.25 |
| Hammerhead Axe | `Slug_Axe` | 1 | 0.5 |
| Homestead Pitchfork | `Homestead_Pitchfork` | 1 | 2.5 |
| Iron Axe | `Metal_Axe` | 1 | 0.5 |
| Iron Hammer | `Iron_Hammer` | 1 | 1.5 |
| Iron Knife | `Metal_Knife` | 1 | 0.5 |
| Iron Pickaxe | `Metal_Pickaxe` | 1 | 0.5 |
| Iron Shears | `Iron_Shears` | 1 | 1.0 |
| Iron Shovel | `Shovel` | 1 | 0.5 |
| Iron Sickle | `Sickle` | 1 | 0.5 |
| Iron Sledgehammer | `Metal_Sledgehammer` | 1 | 5.0 |
| Iron Throwing Knife | `Metal_Throwing_Knife` | 50 | 0.2 |
| Jackhammer | `Jackhammer` | 1 | 5.0 |
| Knife Vestige Attachment | `Knife_Attachment_VestigeChance_1` | 1 | 1.0 |
| Lantern | `Lantern` | 1 | 0.5 |
| Lava Hunter Sickle | `Lava_Hunter_Sickle` | 1 | 0.5 |
| Leather Attachment | `Knife_Attachment_Leather_Yield_1` | 1 | 1.0 |
| Lithium Axe | `Lithium_Axe` | 1 | 1.0 |
| Lithium Knife | `Lithium_Knife` | 1 | 1.0 |
| Lithium Pickaxe | `Lithium_Pickaxe` | 1 | 1.0 |
| Lithium Sickle | `Lithium_Sickle` | 1 | 1.0 |
| Lithium Sledgehammer | `Lithium_Sledgehammer` | 1 | 1.0 |
| Lithium Throwing Knife | `Lithium_Throwing_Knife` | 50 | 1.0 |
| Machete | `Machete` | 1 | 0.5 |
| Miasmic Axe | `Iron_Wood_Axe` | 1 | 0.5 |
| Miasmic Knife | `Iron_Wood_Knife` | 1 | 0.5 |
| Miasmic Pickaxe | `Iron_Wood_Pickaxe` | 1 | 0.5 |
| Miasmic Sickle | `Iron_Wood_Sickle` | 1 | 0.5 |
| Miasmic Sledgehammer | `Iron_Wood_Sledgehammer` | 1 | 0.5 |
| Miasmic Throwing Knife | `Iron_Wood_Throwing_Knife` | 50 | 0.25 |
| Mining Laser | `Mining_Laser` | 1 | 2.5 |
| Nailgun | `Nailgun` | 1 | 2.0 |
| Obsidian Axe | `Obsidian_Axe` | 1 | 0.5 |
| Obsidian Knife | `Obsidian_Knife` | 1 | 0.5 |
| Obsidian Pickaxe | `Obsidian_Pickaxe` | 1 | 0.5 |
| Obsidian Sickle | `Obsidian_Sickle` | 1 | 0.5 |
| Obsidian Sledgehammer | `Obsidian_Sledgehammer` | 1 | 0.5 |
| Obsidian Throwing Knife | `Obsidian_Throwing_Knife` | 50 | 0.25 |
| Platinum Axe | `Platinum_Axe` | 1 | 1.0 |
| Platinum Hammer | `Platinum_Hammer` | 1 | 2.0 |
| Platinum Knife | `Platinum_Knife` | 1 | 0.5 |
| Platinum Pickaxe | `Platinum_Pickaxe` | 1 | 1.0 |
| Platinum Shovel | `Platinium_Shovel` | 1 | 0.5 |
| Platinum Sickle | `Platinum_Sickle` | 1 | 1.0 |
| Platinum Throwing Knife | `Platinum_Throwing_Knife` | 50 | 0.2 |
| Prime Meat Attachment | `Knife_Attachment_Prime_Meat_Chance_1` | 1 | 1.0 |
| Quarrite Sledgehammer | `Rock_Golem_Sledgehammer` | 1 | 0.5 |
| Refined Wood Fishing Rod | `Refined_Wood_Fishing_Rod` | 1 | 1.0 |
| Sandworm Knife | `Sandworm_Knife` | 1 | 0.5 |
| Sandworm Throwing Knife | `Sandworm_Throwing_Knife` | 50 | 0.2 |
| Sandwyrm Queen Lantern | `Sandwyrm_Lantern` | 1 | 0.25 |
| Scorpion Fishing Rod | `Scorpion_FishingRod` | 1 | 1.25 |
| Specialist Knife Vestige Attachment | `Knife_Attachment_VestigeChance_2` | 1 | 1.0 |
| Steel Axe | `Steel_Axe` | 1 | 0.5 |
| Steel Hammer | `Steel_Hammer` | 1 | 2.0 |
| Steel Knife | `Steel_Knife` | 1 | 0.5 |
| Steel Pickaxe | `Steel_Pickaxe` | 1 | 0.5 |
| Steel Throwing Knife | `Steel_Throwing_Knife` | 50 | 0.2 |
| Stick | `Stick` | 100 | 0.01 |
| Stone Axe | `Stone_Axe` | 1 | 0.5 |
| Stone Knife | `Stone_Knife` | 1 | 0.5 |
| Stone Pickaxe | `Stone_Pickaxe` | 1 | 0.5 |
| Stone Throwing Knife | `Stone_Throwing_Knife` | 50 | 0.2 |
| Taxidermy Knife | `Taxidermy_Knife` | 1 | 0.5 |
| Titanium Axe | `Titanium_Axe` | 1 | 0.5 |
| Titanium Hammer | `Titanium_Hammer` | 1 | 2.0 |
| Titanium Knife | `Titanium_Knife` | 1 | 0.5 |
| Titanium Pickaxe | `Titanium_Pickaxe` | 1 | 0.5 |
| Titanium Shovel | `Titanium_Shovel` | 1 | 0.5 |
| Titanium Sickle | `Titanium_Sickle` | 1 | 0.5 |
| Titanium Throwing Knife | `Titanium_Throwing_Knife` | 50 | 0.2 |
| Water Pipe Tool | `SplineTool_Water` | 1 | 0.1 |
| Wood Hammer | `Building_RepairTool` | 1 | 1.0 |
| Wood Rag Torch | `Wood_Rag_Torch` | 1 | 0.5 |
| Wood Torch | `Wood_Flare` | 1 | 0.5 |
| Wooden Fishing Rod | `Wooden_Fishing_Rod` | 1 | 1.0 |
| Wooden Shovel | `Stone_Shovel` | 1 | 0.5 |

## Armaduras e Roupas (164 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Advanced Aerodynamic Attachment | `Feet_Legs_Attachment_Movement_Bonus_2` | 1 | 1.0 |
| Advanced Calibrated Grip Attachment | `Arms_Attachment_Tool_Use_2` | 1 | 1.0 |
| Advanced Noise Suppression Attachment | `Feet_Body_Legs_Attachment_Stealth_Movement_2` | 1 | 1.0 |
| Advanced Nutrition Attachment | `Chest_Attachment_StomachCapacity_2` | 1 | 1.0 |
| Advanced Plating Attachment | `Body_Legs_Attachment_Regen_Resistance_2` | 1 | 1.0 |
| Advanced Pockets Attachment | `Body_Legs_Arms_Attachment_Carrying_Bonus_2` | 1 | 1.0 |
| Advanced Rubberized Attachment | `Feet_Arms_Attachment_Fall_Resistance_2` | 1 | 1.0 |
| Advanced Storm Visor Attachment | `Helmet_Attachment_Storm_Resistance_2` | 1 | 1.0 |
| Advanced Supplemental Filtration Attachment | `Helmet_Attachment_Poison_Water_2` | 1 | 1.0 |
| Advanced Supplemental Respiration Attachment | `Helmet_Attachment_Cave_Resistance_2` | 1 | 1.0 |
| Aerodynamic Attachment | `Feet_Legs_Attachment_Movement_Bonus_1` | 1 | 1.0 |
| Arctic Arm Armor | `Polarbear_Arms` | 1 | 1.0 |
| Arctic Chest Armor | `Polarbear_Chest` | 1 | 4.0 |
| Arctic Feet Armor | `Polarbear_Feet` | 1 | 1.0 |
| Arctic Head Armor | `PolarBear_Armor_Head` | 1 | 2.0 |
| Arctic Head Armor (Frostfoot) | `Polarbear_Head_Armor_Yeti` | 1 | 2.0 |
| Arctic Leg Armor | `Polarbear_Legs` | 1 | 4.0 |
| Arctic Survival Arms Armor | `ArcticArmor_Arms` | 1 | 1.0 |
| Arctic Survival Chest Armor | `ArcticArmor_Chest` | 1 | 2.0 |
| Arctic Survival Feet Armor | `ArcticArmor_Feet` | 1 | 2.0 |
| Arctic Survival Head Armor | `ArcticArmor_Head` | 1 | 1.0 |
| Arctic Survival Legs Armor | `ArcticArmor_Legs` | 1 | 2.0 |
| Bastion Armor Arms | `Alloy_Armor_Arms` | 1 | 2.0 |
| Bastion Armor Chest | `Alloy_Armor_Chest` | 1 | 2.0 |
| Bastion Armor Feet | `Alloy_Armor_Feet` | 1 | 2.0 |
| Bastion Armor Head | `Alloy_Armor_Head` | 1 | 2.0 |
| Bastion Armor Legs | `Alloy_Armor_Legs` | 1 | 2.0 |
| Black Wolf Arm Armor | `Black_Wolf_Arms` | 1 | 1.0 |
| Black Wolf Chest Armor | `Black_Wolf_Chest` | 1 | 1.5 |
| Black Wolf Feet Armor | `Black_Wolf_Feet` | 1 | 0.5 |
| Black Wolf Head Armor | `Black_Wolf_Head` | 1 | 0.5 |
| Black Wolf Legs Armor | `Black_Wolf_Legs` | 1 | 1.5 |
| Bone Arm Armor | `Bone_Arms` | 1 | 1.0 |
| Bone Chest Armor | `Bone_Chest` | 1 | 2.0 |
| Bone Feet Armor | `Bone_Feet` | 1 | 1.0 |
| Bone Head Armor | `Bone_Head` | 1 | 1.0 |
| Bone Leg Armor | `Bone_Legs` | 1 | 2.0 |
| Brown Bear Arm Armor | `Brownbear_Arms` | 1 | 1.0 |
| Brown Bear Chest Armor | `Brownbear_Chest` | 1 | 4.0 |
| Brown Bear Feet Armor | `Brownbear_Feet` | 1 | 1.0 |
| Brown Bear Head Armor | `BrownBear_Armor_Head` | 1 | 2.0 |
| Brown Bear Leg Armor | `Brownbear_Legs` | 1 | 4.0 |
| Calibrated Grip Attachment | `Arms_Attachment_Tool_Use_1` | 1 | 1.0 |
| Carbonweave Arms Armor | `SandArmor_Arms` | 1 | 1.0 |
| Carbonweave Chest Armor | `SandArmor_Chest` | 1 | 1.0 |
| Carbonweave Feet Armor | `SandArmor_Feet` | 1 | 1.0 |
| Carbonweave Head Armor | `SandArmor_Head` | 1 | 1.0 |
| Carbonweave Legs Armor | `SandArmor_Legs` | 1 | 1.0 |
| Caveworm Arms Armor | `CavewormScale_Arms` | 1 | 0.38 |
| Caveworm Chest Armor | `CavewormScale_Chest` | 1 | 1.0 |
| Caveworm Feet Armor | `CavewormScale_Feet` | 1 | 0.38 |
| Caveworm Head Armor | `CavewormScale_Head` | 1 | 0.75 |
| Caveworm Leg Armor | `CavewormScale_Legs` | 1 | 1.0 |
| Cloth Arm Armor | `Cloth_Arms` | 1 | 0.5 |
| Cloth Chest Armor | `Cloth_Chest` | 1 | 0.75 |
| Cloth Feet Armor | `Cloth_Feet` | 1 | 0.5 |
| Cloth Head Armor | `Cloth_Head` | 1 | 0.5 |
| Cloth Leg Armor | `Cloth_Legs` | 1 | 0.75 |
| Comfort Attachment | `Armor_Attachment_Comfort_1` | 1 | 1.0 |
| Composite Arms Armor | `Composite_Arms` | 1 | 0.75 |
| Composite Chest Armor | `Composite_Chest` | 1 | 2.5 |
| Composite Feet Armor | `Composite_Feet` | 1 | 0.75 |
| Composite Head Armor | `Composite_Head` | 1 | 1.5 |
| Composite Legs Armor | `Composite_Legs` | 1 | 2.5 |
| Containment Arm Armor | `Radiation_Protection_Armor_Arms` | 1 | 2.0 |
| Containment Chest Armor | `Radiation_Protection_Armor_Chest` | 1 | 2.0 |
| Containment Feet Armor | `Radiation_Protection_Armor_Feet` | 1 | 2.0 |
| Containment Head Armor | `Radiation_Protection_Armor_Head` | 1 | 2.0 |
| Containment Leg Armor | `Radiation_Protection_Armor_Legs` | 1 | 2.0 |
| Cured Leather Arms Armor | `Hard_Leather_Arms` | 1 | 1.0 |
| Cured Leather Chest Armor | `Hard_Leather_Chest` | 1 | 2.0 |
| Cured Leather Feet Armor | `Hard_Leather_Feet` | 1 | 1.0 |
| Cured Leather Head Armor | `Hard_Leather_Head` | 1 | 1.0 |
| Cured Leather Leg Armor | `Hard_Leather_Legs` | 1 | 2.0 |
| Dusty Miner Arms Armor | `MinerArmor_Arms` | 1 | 1.0 |
| Dusty Miner Chest Armor | `MinerArmor_Chest` | 1 | 2.0 |
| Dusty Miner Feet Armor | `MinerArmor_Feet` | 1 | 1.0 |
| Dusty Miner Head Armor | `MinerArmor_Head` | 1 | 1.5 |
| Dusty Miner Legs Armor | `MinerArmor_Legs` | 1 | 2.0 |
| Fur Arm Armor | `Fur_Arms` | 1 | 1.0 |
| Fur Chest Armor | `Fur_Chest` | 1 | 4.0 |
| Fur Feet Armor | `Fur_Feet` | 1 | 1.0 |
| Fur Head Armor | `Fur_Head` | 1 | 2.0 |
| Fur Leg Armor | `Fur_Legs` | 1 | 4.0 |
| Garganutan Arms Armor | `Ape_Armor_Arms` | 1 | 0.5 |
| Garganutan Chest Armor | `Ape_Armor_Chest` | 1 | 0.5 |
| Garganutan Feet Armor | `Ape_Armor_Feet` | 1 | 0.5 |
| Garganutan Head Armor | `Ape_Armor_Head` | 1 | 0.5 |
| Garganutan Legs Armor | `Ape_Armor_Legs` | 1 | 0.5 |
| Ghillie Arms Armor | `Ghillie_Arms` | 1 | 0.25 |
| Ghillie Chest Armor | `Ghillie_Chest` | 1 | 0.75 |
| Ghillie Feet Armor | `Ghillie_Feet` | 1 | 0.25 |
| Ghillie Head Armor | `Ghillie_Head` | 1 | 0.5 |
| Ghillie Leg Armor | `Ghillie_Legs` | 1 | 0.75 |
| Hazmat Arm Armor | `Hazmat_Arms` | 1 | 0.75 |
| Hazmat Chest Armor | `Hazmat_Chest` | 1 | 0.75 |
| Hazmat Feet Armor | `Hazmat_Feet` | 1 | 0.75 |
| Hazmat Head Armor | `Hazmat_Head` | 1 | 0.75 |
| Hazmat Leg Armor | `Hazmat_Legs` | 1 | 0.75 |
| Heavy Obsidian Arm Armor | `Heavy_Obsidian_Arms` | 1 | 2.0 |
| Heavy Obsidian Chest Armor | `Heavy_Obsidian_Chest` | 1 | 2.0 |
| Heavy Obsidian Feet Armor | `Heavy_Obsidian_Feet` | 1 | 2.0 |
| Heavy Obsidian Head Armor | `Heavy_Obsidian_Head` | 1 | 2.0 |
| Heavy Obsidian Leg Armor | `Heavy_Obsidian_Legs` | 1 | 2.0 |
| Hunter Arms Armor | `Hunter_Arms` | 1 | 0.38 |
| Hunter Chest Armor | `Hunter_Chest` | 1 | 1.0 |
| Hunter Feet Armor | `Hunter_Feet` | 1 | 0.38 |
| Hunter Head Armor | `Hunter_Head` | 1 | 0.75 |
| Hunter Leg Armor | `Hunter_Legs` | 1 | 1.0 |
| Jump Attachment | `Legs_Attachment_Jump_1` | 1 | 1.0 |
| Leather Arms Armor | `Leather_Arms` | 1 | 1.0 |
| Leather Chest Armor | `Leather_Chest` | 1 | 2.0 |
| Leather Feet Armor | `Leather_Feet` | 1 | 1.0 |
| Leather Head Armor | `Leather_Head` | 1 | 1.0 |
| Leather Leg Armor | `Leather_Legs` | 1 | 2.0 |
| Noise Suppression Attachment | `Feet_Body_Legs_Attachment_Stealth_Movement_1` | 1 | 1.0 |
| Nutrition Attachment | `Body_Attachment_Stomach_Capacity` | 1 | 1.0 |
| Obsidian Arm Armor | `Obsidian_Arms` | 1 | 1.0 |
| Obsidian Chest Armor | `Obsidian_Chest` | 1 | 1.0 |
| Obsidian Feet Armor | `Obsidian_Feet` | 1 | 1.0 |
| Obsidian Head Armor | `Obsidian_Head` | 1 | 1.0 |
| Obsidian Leg Armor | `Obsidian_Legs` | 1 | 1.0 |
| Oxygen Attachment | `Chest_Attachment_Oxygen_1` | 1 | 1.0 |
| Plating Attachment | `Body_Legs_Attachment_Regen_Resistance_1` | 1 | 1.0 |
| Pockets Attachment | `Body_Legs_Arms_Attachment_Carrying_Bonus_1` | 1 | 1.0 |
| Punch Damage Attachment | `Arms_Attachment_FistDamage_1` | 1 | 1.0 |
| Quarrite Armor Attachment | `Rock_Golem_Attachment` | 1 | 0.5 |
| Recovery Attachment | `Body_Head_Attachment_Quick_Healing` | 1 | 1.0 |
| Resurgent Arm Armor  | `Synthetic_Armor_Arms` | 1 | 2.0 |
| Resurgent Chest Armor  | `Synthetic_Armor_Chest` | 1 | 2.0 |
| Resurgent Feet Armor | `Synthetic_Armor_Feet` | 1 | 2.0 |
| Resurgent Head Armor  | `Synthetic_Armor_Head` | 1 | 2.0 |
| Resurgent Leg Armor | `Synthetic_Armor_Legs` | 1 | 2.0 |
| Rimetusk Arms Armor | `IceMammoth_Armor_Arms` | 1 | 0.5 |
| Rimetusk Chest Armor | `IceMammoth_Armor_Chest` | 1 | 0.5 |
| Rimetusk Feet Armor | `IceMammoth_Armor_Feet` | 1 | 0.5 |
| Rimetusk Head Armor | `IceMammoth_Armor_Head` | 1 | 0.5 |
| Rimetusk Legs Armor | `IceMammoth_Armor_Legs` | 1 | 0.5 |
| Rubberized Attachment | `Feet_Arms_Attachment_Fall_Resistance_1` | 1 | 1.0 |
| Sandworm Arms Armor | `Scale_Arms` | 1 | 0.38 |
| Sandworm Chest Armor | `Scale_Chest` | 1 | 1.0 |
| Sandworm Feet Armor | `Scale_Feet` | 1 | 0.38 |
| Sandworm Head Armor | `Scale_Head` | 1 | 0.75 |
| Sandworm Leg Armor | `Scale_Legs` | 1 | 1.0 |
| Scorpion Arms Armor | `Scorpion_Arms_Armor` | 1 | 0.85 |
| Scorpion Chest Armor | `Scorpion_Chest_Armor` | 1 | 1.25 |
| Scorpion Feet Armor | `Scorpion_Feet_Armor` | 1 | 0.85 |
| Scorpion Head Armor | `Scorpion_Head_Armor` | 1 | 1.0 |
| Scorpion Legs Armor | `Scorpion_Legs_Armor` | 1 | 1.25 |
| Specialist Comfort Attachment | `Armor_Attachment_Comfort_2` | 1 | 1.0 |
| Specialist Jump Attachment | `Legs_Attachment_Jump_2` | 1 | 1.0 |
| Specialist Oxygen Attachment | `Chest_Attachment_Oxygen_2` | 1 | 1.0 |
| Specialist Punch Damage Attachment | `Arms_Attachment_FistDamage_2` | 1 | 1.0 |
| Specialist Throw Accuracy Attachment | `Arms_Attachment_ThrowAccuracy_2` | 1 | 1.0 |
| Storm Visor Attachment | `Helmet_Attachment_Storm_Resistance_1` | 1 | 1.0 |
| Supplemental Filtration Attachment | `Helmet_Attachment_Poison_Water_1` | 1 | 1.0 |
| Supplemental Respiration Attachment | `Helmet_Attachment_Cave_Resistance_1` | 1 | 1.0 |
| Throw Accuracy Attachment | `Arms_Attachment_ThrowAccuracy_1` | 1 | 1.0 |
| Tracking Attachment | `Head_Attachment_Boss_Tracker` | 1 | 1.0 |
| Wayfarer Arms Armor | `Advanced_Cloth_Arms` | 1 | 1.0 |
| Wayfarer Chest Armor | `Advanced_Cloth_Chest` | 1 | 2.0 |
| Wayfarer Feet Armor | `Advanced_Cloth_Feet` | 1 | 1.0 |
| Wayfarer Head Armor | `Advanced_Cloth_Head` | 1 | 1.0 |
| Wayfarer Leg Armor | `Advanced_Cloth_Legs` | 1 | 2.0 |

## Mochilas e Equipamentos (17 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| C0NT4CT Radio | `Mission_Radio` | 1 | 1.0 |
| Cave Scanner | `Scanner_Cave` | 1 | 1.0 |
| Deep Mining Ore Scanner | `Scanner_DeepOre` | 1 | 1.0 |
| ECHO Device | `Recovery_Beacon_Tracker` | 1 | 1.0 |
| Farmers Satchel | `Seed_Pouch_T2` | 1 | 0.5 |
| HEAL Device | `Mission_Medical_Device` | 1 | 1.0 |
| Leather Backpack | `Basic_Backpack` | 1 | 0.5 |
| Sandwyrm Queen Backpack | `Sandwyrm_Backpack` | 1 | 0.5 |
| Seed Pouch | `Seed_Pouch` | 1 | 0.5 |
| Small Blue Pouch | `Pouch_Generic_Blue` | 1 | 0.5 |
| Small Green Pouch | `Pouch_Generic_Green` | 1 | 0.5 |
| Small Pouch | `Pouch_Generic` | 1 | 0.5 |
| Small Red Pouch | `Pouch_Generic_Red` | 1 | 0.5 |
| Tackle Box | `Tackle_Box` | 1 | 5.0 |
| Uranium Locator | `Radiation_Tracker` | 1 | 1.0 |
| Water Can | `Jerry_Can_Water` | 1 | 3.0 |
| Water Container | `Any_Water_Container` | 1 | 0.0 |

## Montarias (itens relacionados) (20 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Arctic Explorer Saddle | `Saddle_Explorer` | 1 | 1.5 |
| Arctic Riding Saddle | `Saddle_Basic_Arctic` | 1 | 1.5 |
| Arctic Survival Saddle | `Saddle_Advanced_Arctic` | 1 | 2.0 |
| Armored Saddle | `Saddle_Armored` | 1 | 1.5 |
| Basic Riding Saddle | `Saddle_Standard` | 1 | 1.5 |
| Bearhide Saddle | `Saddle_BearHide` | 1 | 1.5 |
| Bovine Pack Harness | `Saddle_Standard_Bag` | 1 | 1.5 |
| Crocodile Skin Saddle | `Saddle_CrocSkin` | 1 | 1.5 |
| Deluxe Leather Saddle | `Saddle_DeluxeLeather` | 1 | 1.5 |
| Desert Riding Saddle | `Saddle_Basic_Desert` | 1 | 1.5 |
| Desert Tracker Saddle | `Saddle_Desert` | 1 | 1.5 |
| Harvesting Cart | `Saddle_Cart_Harvest` | 1 | 80.0 |
| Laika\'s Jumpsuit | `Dog_Accessory_D` | 1 | 0.5 |
| Racing Saddle | `Saddle_Racing` | 1 | 1.5 |
| Sandworm Scale Saddle | `Saddle_Sandworm` | 1 | 1.5 |
| Seeding Cart | `Saddle_Cart_Plough` | 1 | 80.0 |
| Specialised Raptor Saddle | `Saddle_Raptor` | 1 | 1.5 |
| Watering Cart | `Saddle_Cart_Water` | 1 | 80.0 |
| Wooden Cart | `Saddle_Cart` | 1 | 80.0 |
| Woolly Mammoth Saddle | `Saddle_Mammoth_Standard` | 1 | 1.5 |

## Caça — Carcaças de Animais (116 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Alpha Cougar Carcass | `AnimalCarcass_Cougar_Alpha` | 1 | 8.0 |
| Alpha Hyena Carcass | `AnimalCarcass_Alpha_Desert_Wolf` | 1 | 12.0 |
| Alpha Snow Leopard Carcass | `AnimalCarcass_SnowLeopard_Alpha` | 1 | 12.0 |
| Antelope Carcass | `AnimalCarcass_DeerDesert` | 1 | 10.0 |
| Arctic Moa Carcass | `AnimalCarcass_Arctic_Moa` | 1 | 5.0 |
| Arctic Quarrite Carcass | `AnimalCarcass_RockGolem_Juvie_Arctic` | 1 | 10.0 |
| Arctic Scorpion Carcass | `AnimalCarcass_Scorpion_Arctic` | 1 | 8.0 |
| Arid Striker Carcass | `AnimalCarcass_Desert_Striker` | 1 | 8.0 |
| Armored Scorpion Carcass | `AnimalCarcass_Scorpion_Armored` | 1 | 8.0 |
| Ashen Drake Carcass | `AnimalCarcass_Lava_Komodo` | 1 | 3.5 |
| Bear Carcass | `AnimalCarcass_Bear` | 1 | 10.0 |
| Bear Cub Carcass | `AnimalCarcass_BearCub` | 1 | 2.5 |
| Black Jaguar Carcass | `AnimalCarcass_Jaguar_Black` | 1 | 15.0 |
| Black Wolf Carcass | `AnimalCarcass_Alpha_Wolf` | 1 | 12.0 |
| Blueback Carcass | `AnimalCarcass_BlueBack` | 1 | 10.0 |
| Buffalo Carcass | `AnimalCarcass_Buffalo` | 1 | 10.0 |
| Bull Carcass | `AnimalCarcass_Bull` | 1 | 10.0 |
| Calf Carcass | `AnimalCarcass_Calf` | 1 | 7.5 |
| Chala Carcass | `AnimalCarcass_Chamois_Var` | 1 | 8.0 |
| Chamois Carcass | `AnimalCarcass_Chamois_M` | 1 | 8.0 |
| Chick Carcass | `AnimalCarcass_Chick` | 1 | 5.0 |
| Chicken Carcass | `AnimalCarcass_Chicken` | 1 | 5.0 |
| Clicker Carcass | `AnimalCarcass_Giant_Roach` | 1 | 8.0 |
| Columbian Mammoth Carcass | `AnimalCarcass_MammothDesert` | 1 | 10.0 |
| Cougar Carcass | `AnimalCarcass_Lion_F` | 1 | 8.0 |
| Cow Carcass | `AnimalCarcass_Cow` | 1 | 10.0 |
| Crocodile Carcass | `AnimalCarcass_Crocodile` | 1 | 5.0 |
| Deer Carcass | `AnimalCarcass_Deer` | 1 | 10.0 |
| Destroyed Hoverframe | `AnimalCarcass_SpeederBike` | 1 | 10.0 |
| Drac Carcass | `AnimalCarcass_BatDog` | 1 | 8.0 |
| Draven Carcass | `AnimalCarcass_Chew` | 1 | 10.0 |
| Dreadwing Carcass | `AnimalCarcass_PredatorBird` | 1 | 1.25 |
| Dribbo Carcass | `AnimalCarcass_MiniHippo` | 1 | 6.0 |
| Drosik Carcass | `AnimalCarcass_Tundra_Deer` | 1 | 10.0 |
| Dune Raptor Carcass | `AnimalCarcass_Raptor_Desert` | 1 | 8.0 |
| Elephant Carcass | `AnimalCarcass_Elephant` | 1 | 10.0 |
| Fire Needler Carcass | `AnimalCarcass_Needler_Fire` | 1 | 5.0 |
| Frostfoot Carcass | `AnimalCarcass_Yeti` | 1 | 4.0 |
| Garganutan Carcass | `AnimalCarcass_Ape_Juvenile` | 1 | 5.0 |
| Geothermal Spider Carcass | `AnimalCarcass_GeothermalSpider` | 1 | 8.0 |
| Gribbler Carcass | `AnimalCarcass_Tundra_Monkey` | 1 | 15.0 |
| Hammerhead Carcass | `AnimalCarcass_Hammerhead_Slug_Small` | 1 | 20.0 |
| Hopper Carcass | `AnimalCarcass_HoppingCreature` | 1 | 10.0 |
| Hyena Carcass | `AnimalCarcass_Desert_Wolf` | 1 | 8.0 |
| Ignari Carcass | `AnimalCarcass_Lava_Slug` | 1 | 20.0 |
| Jaguar Carcass | `AnimalCarcass_Jaguar` | 1 | 12.0 |
| Juvenile Shaggy Zebra Carcass | `AnimalCarcass_Wooly_Zebra_Juvenile` | 1 | 10.0 |
| Juvenile Snow Wolf Carcass | `AnimalCarcass_Snow_Wolf_Juvenile` | 1 | 3.5 |
| Juvenile Terrenus Carcass | `AnimalCarcass_JuvieHorse` | 1 | 5.0 |
| Juvenile Wolf Carcass | `AnimalCarcass_Conifer_Wolf_Juvenile` | 1 | 3.5 |
| Kea Carcass | `AnimalCarcass_Kea` | 1 | 1.25 |
| Kiwi Carcass | `AnimalCarcass_Kiwi` | 1 | 0.2 |
| Komodo Carcass | `AnimalCarcass_Komodo` | 1 | 3.5 |
| Korrin Carcass | `AnimalCarcass_Bounder_Desert` | 1 | 10.0 |
| Large Antelope Carcass | `AnimalCarcass_DeerDesertLarge` | 1 | 13.0 |
| Large Deer Carcass | `AnimalCarcass_DeerLarge` | 1 | 13.0 |
| Lava Bomber Carcass | `AnimalCarcass_LavaBomber` | 1 | 5.0 |
| Lava Broodling Carcass | `AnimalCarcass_Broodling` | 1 | 10.0 |
| Lava Roat Carcass | `AnimalCarcass_Roat_Lava` | 1 | 1.0 |
| Moa Carcass | `AnimalCarcass_Moa` | 1 | 5.0 |
| Needler Carcass | `AnimalCarcass_Needler` | 1 | 5.0 |
| Pack Wolf Carcass | `AnimalCarcass_Pack_Wolf` | 1 | 8.0 |
| Pig Carcass | `AnimalCarcass_Pig` | 1 | 6.0 |
| Plains Equix Carcass | `AnimalCarcass_Deer_Variant` | 1 | 10.0 |
| Polar Bear Carcass | `AnimalCarcass_PolarBear` | 1 | 10.0 |
| Polar Bear Cub Carcass | `AnimalCarcass_PolarBearCub` | 1 | 10.0 |
| Pronghorn Carcass | `AnimalCarcass_Pronghorn` | 1 | 9.0 |
| Pygmy Lop Carcass | `AnimalCarcass_Rabbit_Variant` | 1 | 1.0 |
| Quarrite Carcass | `AnimalCarcass_RockGolem_Juvie` | 1 | 10.0 |
| Rabbit Carcass | `AnimalCarcass_Rabbit` | 1 | 1.0 |
| Ram Carcass | `AnimalCarcass_Ram` | 1 | 5.0 |
| Raptor Carcass | `AnimalCarcass_Raptor` | 1 | 8.0 |
| Ravager Carcass | `AnimalCarcass_Flying_Tank` | 1 | 8.0 |
| Reaver Carcass | `AnimalCarcass_Reaver` | 1 | 8.0 |
| Redback Carcass | `AnimalCarcass_BlueBack_Lava` | 1 | 10.0 |
| Revenant Carcass | `AnimalCarcass_Irradiated_Abomination` | 1 | 8.0 |
| Rimetusk Carcass | `AnimalCarcass_Mammoth_Icy` | 1 | 10.0 |
| Rooster Carcass | `AnimalCarcass_Rooster` | 1 | 5.0 |
| Sandhorn Carcass | `AnimalCarcass_Flightless_Tank` | 1 | 8.0 |
| Sandwyrm Queen Carcass | `AnimalCarcass_Sandwyrm_Queen` | 1 | 8.0 |
| Scorpion Carcass | `AnimalCarcass_Scorpion` | 1 | 8.0 |
| Scuttler Carcass | `AnimalCarcass_SandScuttle` | 1 | 1.0 |
| Shaggy Zebra Carcass | `AnimalCarcass_Wooly_Zebra` | 1 | 10.0 |
| Sheep Carcass | `AnimalCarcass_Sheep` | 1 | 5.0 |
| Skulk Carcass | `AnimalCarcass_Orka_Arctic` | 1 | 10.0 |
| Skulmutt Carcass | `AnimalCarcass_Mange_Wolf` | 1 | 8.0 |
| Skulmutt Prime Carcass | `AnimalCarcass_Mange_Wolf_Alpha` | 1 | 16.0 |
| Slinker Carcass | `AnimalCarcass_Slinker` | 1 | 8.0 |
| Small Deer Carcass | `AnimalCarcass_BabyDeer` | 1 | 3.0 |
| Snow Leopard Carcass | `AnimalCarcass_SnowLeopard` | 1 | 12.0 |
| Snow Pygmy Lop Carcass | `AnimalCarcass_Rabbit_Variant_Snow` | 1 | 1.0 |
| Snow Rabbit Carcass | `AnimalCarcass_Snow_Rabbit` | 1 | 1.0 |
| Snow Stalker Carcass | `AnimalCarcass_Snow_Striker` | 1 | 8.0 |
| Snow Wolf Carcass | `AnimalCarcass_Snow_Wolf` | 1 | 8.0 |
| Spectre Carcass | `AnimalCarcass_Irradiated_Prospector` | 1 | 8.0 |
| Spider Carcass | `AnimalCarcass_Spider` | 1 | 8.0 |
| Spliced Viscid Carcass | `AnimalCarcass_Swamp_Slug_Enzyme` | 1 | 20.0 |
| Stomper Carcass | `AnimalCarcass_Stomper` | 1 | 5.0 |
| Stomper Matriarch Carcass | `AnimalCarcass_Stomper_Matriarch` | 1 | 5.0 |
| Stonejaw Carcass | `AnimalCarcass_RockDog` | 1 | 10.0 |
| Storca Carcass | `AnimalCarcass_Storca` | 1 | 8.0 |
| Stryder Carcass | `AnimalCarcass_Swamp_Quad` | 1 | 10.0 |
| Swamp Hopper Carcass | `AnimalCarcass_HoppingCreature_Swamp` | 1 | 10.0 |
| Swamp Roat Carcass | `AnimalCarcass_Roat_Swamp` | 1 | 1.0 |
| Terrenus Carcass | `AnimalCarcass_Horse` | 1 | 10.0 |
| Trapjaw Carcass | `AnimalCarcass_Ghost_Crocodile` | 1 | 5.0 |
| Tusker Carcass | `AnimalCarcass_Tusker` | 1 | 10.0 |
| Ubis Carcass | `AnimalCarcass_SwampBird` | 1 | 10.0 |
| Venomfly Carcass | `AnimalCarcass_DragonFly` | 1 | 8.0 |
| Viscid Carcass | `AnimalCarcass_Swamp_Slug` | 1 | 20.0 |
| Wild Boar Carcass | `AnimalCarcass_WildBoar` | 1 | 6.0 |
| Wolf Carcass | `AnimalCarcass_Conifer_Wolf` | 1 | 8.0 |
| Woolly Mammoth Carcass | `AnimalCarcass_Mammoth` | 1 | 10.0 |
| Woolly Mammoth Carcass | `AnimalCarcass_WoollyMammoth_Mount` | 1 | 10.0 |
| Wraith Carcass | `AnimalCarcass_Irradiated_Mutation` | 1 | 8.0 |
| Zebra Carcass | `AnimalCarcass_Zebra` | 1 | 10.0 |

## Bancadas e Estações (85 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Advanced Alteration Bench | `Advanced_Alteration_Bench` | 1 | 20.0 |
| Advanced Masonry Bench | `Masonry_Bench_T3` | 1 | 25.0 |
| Advanced Textiles Bench | `Advanced_Armor_Bench` | 1 | 20.0 |
| Alteration Bench | `Alteration_Bench` | 1 | 20.0 |
| Anvil Bench | `Anvil_Bench` | 1 | 20.0 |
| Art Deco Fireplace | `Gold_Fireplace` | 1 | 5.0 |
| Basic Fishing Bench | `Fishing_Bench` | 1 | 20.0 |
| Biofuel Bio-Cleaner | `T3_Cleaning_Device` | 1 | 2.5 |
| Biofuel Composter | `Composter` | 1 | 30.0 |
| Biofuel Fireplace | `Gas_Fireplace` | 1 | 30.0 |
| Biofuel Generator | `Kit_Generator` | 1 | 40.0 |
| Biofuel Oxite Dissolver | `Metal_Oxite_Dissolver` | 1 | 8.0 |
| Biofuel Stove | `Kitchen_Stove` | 1 | 20.0 |
| Butchery Bench | `Butchery_Bench` | 1 | 20.0 |
| Campfire | `Campfire` | 1 | 10.0 |
| Carpentry Bench | `Carpentry_Bench` | 1 | 20.0 |
| Cement Mixer | `Cement_Mixer` | 1 | 2.0 |
| Character Crafting | `FieldGuide_Character` | 1 | 0.1 |
| Chemistry Bench | `Chemistry_Bench` | 1 | 20.0 |
| Concrete Furnace | `Concrete_Furnace_V2` | 1 | 40.0 |
| Cooking Station | `Cooking_Station_V2` | 1 | 2.0 |
| Crafting Bench | `Crafting_Bench` | 1 | 20.0 |
| Crude Oil Generator | `Oil_Power_Generator` | 1 | 40.0 |
| Decoration Bench | `Rustic_Decoration_Bench` | 1 | 20.0 |
| Deep Freeze | `Deep_Freeze` | 1 | 25.0 |
| Drying Rack | `Drying_Rack` | 1 | 1.0 |
| Electric Carpentry Bench | `Carpentry_Bench_T4` | 1 | 20.0 |
| Electric Composter | `Composter_Electric` | 1 | 30.0 |
| Electric Composter | `Faction_MIssion_Analyzer` | 1 | 30.0 |
| Electric Fireplace | `Electric_Fireplace` | 1 | 30.0 |
| Electric Furnace | `Electric_Furnace_Large` | 1 | 50.0 |
| Electric Masonry Bench | `Masonry_Bench_T4` | 1 | 35.0 |
| Electric Stove | `Electric_Stove` | 1 | 20.0 |
| Electric Textiles Bench | `Electric_Armor_Bench` | 1 | 20.0 |
| Electrolytic Oxygen Synthesizer | `Electric_Oxite_Dissolver` | 1 | 8.0 |
| Fabricator | `Fabricator` | 1 | 30.0 |
| Firepit | `FirePit` | 1 | 20.0 |
| Fireplace | `Fireplace` | 1 | 30.0 |
| Forge | `Anvil_Bench_T3` | 1 | 30.0 |
| Foundry | `Anvil_Bench_T4` | 1 | 100.0 |
| Glassworking Bench | `Glassworking_Bench_V2` | 1 | 25.0 |
| Herbalism Bench | `Herbalism_Bench` | 1 | 20.0 |
| Homestead Butchery Bench | `Homestead_Kitchen_Butchery` | 1 | 20.0 |
| Homestead Fireplace | `Homestead_Fireplace` | 1 | 5.0 |
| Homestead Iron Stove | `Homestead_Iron_Stove` | 1 | 20.0 |
| Homestead Kitchen Bench | `Homestead_Kitchen_Bench` | 1 | 20.0 |
| Homestead Kitchen Stove | `Homestead_Kitchen_Stove` | 1 | 20.0 |
| Homestead Medicine Bench | `Homestead_Kitchen_Herbalism` | 1 | 1.0 |
| Homestead Refrigerator | `Homestead_Refrigerator` | 1 | 20.0 |
| Homestead Sewing Machine | `Homestead_Sewing_Machine` | 1 | 30.0 |
| Homestead Well | `Homestead_Well` | 1 | 2.0 |
| Kitchen Bench | `Kitchen_Bench` | 1 | 20.0 |
| Machining Bench | `Kit_Machining_Bench` | 1 | 25.0 |
| Manufacturer | `Manufacturer` | 1 | 40.0 |
| Marble Kitchen Bench | `Advanced_Kitchen_Bench` | 1 | 20.0 |
| Masonry Bench | `Masonry_Bench` | 1 | 20.0 |
| Material Processor | `Material_Processor` | 1 | 30.0 |
| Medicine Bench | `Medicine_Bench` | 1 | 1.0 |
| Metal Rain Reservoir | `Rain_Reservoir_T3` | 1 | 20.0 |
| Mortar and Pestle | `Kit_Mortar_And_Pestle` | 1 | 5.0 |
| Nuclear Centrifuge | `Uranium_Converter` | 1 | 50.0 |
| Nuclear Reactor | `Uranium_Generator` | 1 | 40.0 |
| Organic Extractor | `Organic_Extractor` | 1 | 10.0 |
| Organic Residue Cleanser | `Exotic_Processor` | 1 | 2.5 |
| Oxidizer | `Basic_Oxite_Dissolver` | 1 | 2.0 |
| Oxite Dissolver | `Kit_Oxite_Dissolver` | 1 | 10.0 |
| Polymerizer | `Polymerizer` | 1 | 10.0 |
| Portable Biofuel Generator | `Portable_Generator` | 1 | 2.0 |
| Potbelly Stove | `PotBellyStove` | 1 | 4.0 |
| Rain Reservoir | `Rain_Reservoir` | 1 | 2.0 |
| Ranching Station | `Animal_Bench` | 1 | 20.0 |
| Refrigerator | `Refrigerator` | 1 | 20.0 |
| Repair Bench | `Repair_Bench` | 1 | 20.0 |
| Salting Station | `Salting_Station` | 1 | 20.0 |
| Seed Extractor | `Seed_Extractor` | 1 | 5.0 |
| Skinning Bench | `Kit_Skinning_Bench` | 1 | 20.0 |
| Smoker | `Smoker_T3` | 1 | 1.75 |
| Stone Brick Fireplace | `StoneBrick_Fireplace` | 1 | 25.0 |
| Stone Furnace | `Kit_Stone_Furnace` | 1 | 30.0 |
| Textiles Bench | `Armor_Bench` | 1 | 20.0 |
| Trophy Bench | `Trophy_Bench` | 1 | 20.0 |
| Water Wheel | `WaterWheel_Generator` | 1 | 15.0 |
| Windmill | `Windmill` | 1 | 20.0 |
| Wood Burner | `Wood_Burner` | 1 | 10.0 |
| Wood Composter | `Composter_Wood` | 1 | 2.0 |

## Itens Implantáveis (Deployables) (104 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Animal Bed | `Animal_Bed` | 1 | 1.5 |
| Animal Nesting Bed | `Animal_Bed_Nesting` | 1 | 1.5 |
| Art Deco Bed | `Gold_Bed` | 1 | 10.0 |
| Art Deco Bookshelf | `Gold_Bookshelf` | 1 | 10.0 |
| Art Deco Dresser | `Gold_Dresser` | 1 | 5.0 |
| Art Deco Nightstand | `Gold_Nightstand` | 1 | 5.0 |
| Art Deco Safe | `Gold_Safe` | 1 | 5.0 |
| Art Deco Vault | `Gold_Vault` | 1 | 5.0 |
| Art Deco Wardrobe | `Gold_Wardrobe` | 1 | 5.0 |
| Basic Rainwater Purifier | `Water_Purifier_T1_Ground` | 1 | 1.0 |
| Basic Water Purifier | `Water_Purifier_T1_Water` | 1 | 1.0 |
| Bedroll | `Bed_Bedroll` | 1 | 1.0 |
| Black Tusker Animal Bed | `Animal_Bed_Tusker` | 1 | 1.5 |
| Black Wolf Claw Trap | `Black_Wolf_Trap` | 1 | 0.1 |
| Broken Pottery | `AlienFossil_Pottery` | 10 | 1.0 |
| Brutalist Bed | `Brutalist_Bed` | 1 | 10.0 |
| Brutalist Bookshelf | `Brutalist_Bookshelf` | 1 | 15.0 |
| Brutalist Display Cabinet | `Brutalist_Cabinet` | 1 | 10.0 |
| Brutalist Dresser | `Brutalist_Dresser` | 1 | 10.0 |
| Brutalist Nightstand  | `Brutalist_Nightstand` | 1 | 7.0 |
| Brutalist Wardrobe | `Brutalist_Wardrobe` | 1 | 15.0 |
| Bunk Bed | `Bunker_BunkBed` | 1 | 10.0 |
| Burlap Animal Bed | `Animal_Bed_Burlap` | 1 | 1.5 |
| Carved Wood Bed | `Carved_Bed` | 1 | 10.0 |
| Carved Wood Bookshelf | `Carved_Bookshelf` | 1 | 1.0 |
| Carved Wood Cabinet | `Carved_Display_Cabinet` | 1 | 1.0 |
| Carved Wood Dresser | `Carved_Dresser` | 1 | 1.0 |
| Carved Wood Narrow Wardrobe | `Carved_Narrow_Wardrobe` | 1 | 1.0 |
| Carved Wood Nightstand | `Carved_Nightstand` | 1 | 1.0 |
| Carved Wood Wardrobe | `Carved_Wardrobe` | 1 | 1.0 |
| Cat Water Bowl | `Cat_Bowl_Water` | 1 | 0.5 |
| Dog Water Bowl | `Dog_Bowl_Water` | 1 | 0.5 |
| Elegant Curtain Door | `SilkWeave_Curtain_Door` | 20 | 1.0 |
| Equipment Locker | `Bunker_Locker` | 1 | 3.0 |
| Filtered Water Trough | `Water_Trough_T4` | 1 | 3.0 |
| Flow Meter | `Flow_Meter` | 1 | 1.0 |
| Fur Curtain Door | `Fur_Curtain_Door` | 20 | 1.0 |
| Heated Animal Bed | `Animal_Bed_Heated` | 1 | 1.5 |
| Homestead Cabinet | `Homestead_Cabinet` | 1 | 10.0 |
| Homestead Kitchen Corner Bench | `Homestead_Kitchen_Corner` | 1 | 1.0 |
| Homestead Kitchen Sink | `Homestead_Kitchen_Sink` | 1 | 20.0 |
| Homestead Kitchen Storage Block | `Homestead_Kitchen_Storage` | 1 | 10.0 |
| Homestead Quilted Bed | `Homestead_Quilted_Bed` | 1 | 30.0 |
| Homestead Silo | `Homestead_Food_Silo` | 1 | 50.0 |
| Ice Box | `IceBox` | 1 | 8.0 |
| Industrial Bed | `Metal_Bed` | 1 | 10.0 |
| Industrial Bookshelf | `Metal_Bookshelf` | 1 | 10.0 |
| Industrial Display Cabinet | `Metal_Display_Cabinet` | 1 | 10.0 |
| Industrial Dresser | `Metal_Dresser` | 1 | 10.0 |
| Industrial Nightstand | `Metal_Nightstand` | 1 | 10.0 |
| Industrial Wardrobe | `Metal_Wardrobe` | 1 | 10.0 |
| Interior Wood Cupboard | `Interior_Wood_Cupboard` | 1 | 8.0 |
| Iron Cupboard | `Kit_Metal_Cupboard` | 1 | 12.0 |
| Jaguar Buffalo Animal Bed | `Animal_Bed_Leopard` | 1 | 1.5 |
| Kitchen Corner Bench | `Kitchen_Corner_Bench` | 1 | 1.0 |
| Kitchen Storage Block | `Kitchen_Storage` | 1 | 10.0 |
| Large Homestead Cabinet | `Homestead_Cabinet_LRG` | 1 | 15.0 |
| Large Water Trough | `Water_Trough_Large` | 1 | 3.0 |
| Leather Curtain Door | `Leather_Curtain_Door` | 20 | 1.0 |
| Lightning Rod | `LightningRod_Basic` | 1 | 2.0 |
| Luxury Chicken Coop | `Chicken_Coop_Red` | 1 | 15.0 |
| Marble Kitchen Corner Bench | `Advanced_Kitchen_Corner_Bench` | 1 | 1.0 |
| Marble Kitchen Storage | `Advanced_Kitchen_Storage` | 1 | 20.0 |
| Marble Plumbed Sink | `Advanced_Kitchen_Sink` | 1 | 20.0 |
| Medic Cabinet | `Medic_Cabinet` | 1 | 2.0 |
| Medium Interior Wood Crate | `Interior_Wood_Crate_Medium` | 1 | 4.0 |
| Medium Iron Crate | `Metal_Crate_Medium` | 1 | 6.0 |
| Medium Wood Crate | `Wood_Crate_Medium` | 1 | 4.0 |
| Medium Wood Hedgehog | `Wood_Hedgehog_Medium` | 20 | 2.0 |
| Metal Water Trough | `Water_Trough_Metal` | 1 | 3.0 |
| MXC "Preservation" Crate | `Mission_Prototype_Printed_Crate` | 1 | 2.0 |
| Oil Deep-Mining Drill | `Deep_Mining_Drill_Oil` | 1 | 15.0 |
| Ornate Water Trough | `Water_Trough_Fountain` | 1 | 3.0 |
| Platinum Lightning Rod | `LightningRod_Platinum` | 1 | 2.0 |
| Plumbed Sink | `Kitchen_Sink` | 1 | 20.0 |
| Regent Animal Bed | `Animal_Bed_Emperor` | 1 | 1.5 |
| Reinforced Curtain Door | `PlatinumWeave_Curtain_Door` | 20 | 1.0 |
| Rimetusk Snap Trap | `IceMammoth_Trap` | 1 | 0.1 |
| Royal Animal Bed | `Animal_Bed_Royal` | 1 | 1.5 |
| Rustic Bed | `Rustic_Bed` | 1 | 10.0 |
| Rustic Bookshelf | `Rustic_Bookshelf` | 1 | 15.0 |
| Rustic Cabinet | `Rustic_Cabinet` | 1 | 15.0 |
| Rustic Chicken Coop | `Chicken_Coop` | 1 | 15.0 |
| Rustic Dresser | `Rustic_Dresser` | 1 | 20.0 |
| Rustic Narrow Wardrobe | `Rustic_WardrobeNarrow` | 1 | 10.0 |
| Rustic Nightstand | `Rustic_NightStand` | 1 | 5.0 |
| Rustic Wardrobe | `Rustic_Wardrobe` | 1 | 15.0 |
| Scorpion Hedgehog | `Scorpion_Hedgehog_Medium` | 20 | 2.0 |
| Scorpion Pincer Trap | `Scorpion_Trap_Medium` | 20 | 1.5 |
| Small Interior Wood Crate | `Interior_Wood_Crate_Small` | 1 | 2.0 |
| Small Interior Wood Cupboard | `Interior_Wood_Cupboard_Small` | 1 | 2.0 |
| Small Iron Crate | `Metal_Crate_Small` | 1 | 3.0 |
| Small Iron Cupboard | `Metal_Cupboard_Small` | 1 | 3.0 |
| Small Wood Crate | `Wood_Crate_Small` | 1 | 2.0 |
| Small Wood Cupboard | `Wood_Cupboard_Small` | 1 | 2.0 |
| Snow Leopard Skin Animal Bed | `Animal_Bed_SnowLeopardSkin` | 1 | 1.5 |
| Stone Water Trough | `Water_Trough_Stone` | 1 | 3.0 |
| Striker Terrenus Animal Bed | `Animal_Bed_Striker` | 1 | 1.5 |
| Water Trough | `Water_Trough` | 1 | 3.0 |
| Wolfskin Animal Bed | `Animal_Bed_WolfSkin` | 1 | 1.5 |
| Wood Bed | `Bed_Wood` | 1 | 10.0 |
| Wood Cupboard | `Kit_Wood_Cupboard` | 1 | 8.0 |
| Wooden Bed | `Bed_Interior_Wood` | 1 | 10.0 |
| Zebra Animal Bed | `Animal_Bed_Zebra` | 1 | 1.5 |

## Construção (293 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Advanced Orbital Exchange Interface | `Advanced_Exotic_Delivery_Interface` | 1 | 25.0 |
| Aluminium Beam | `Iron_Beam` | 20 | 0.1 |
| Aluminium Door | `Iron_Door` | 20 | 0.1 |
| Aluminium Floor | `Iron_Floor` | 20 | 0.1 |
| Aluminium Halfpieces | `Iron_Halfpiece` | 20 | 0.1 |
| Aluminium Halfpitches | `Iron_Half_Pitch` | 20 | 0.1 |
| Aluminium Ladder | `Metal_Ladder` | 20 | 0.1 |
| Aluminium Railing | `Iron_Railing` | 20 | 0.1 |
| Aluminium Railing Gate | `Iron_Railing_Gate` | 20 | 0.1 |
| Aluminium Roof Corner | `Iron_Roof_Corner` | 20 | 0.1 |
| Aluminium Roof/Ramp | `Iron_Ramp` | 20 | 0.1 |
| Aluminium Trapdoor | `Iron_TrapDoor` | 20 | 0.1 |
| Aluminium Wall | `Iron_Wall` | 20 | 0.1 |
| Aluminium Wall Angled | `Iron_Wall_Angle` | 20 | 0.1 |
| Aluminium Window | `Iron_Window` | 20 | 0.1 |
| Beehive | `Beehive` | 1 | 5.0 |
| Beehive Breeding Center | `Beehive_BreedingCenter` | 1 | 5.0 |
| Beehive Extractor | `Beehive_Extractor` | 1 | 5.0 |
| Beeswax Wood Beam | `ReinforcedWood_Beam` | 20 | 0.5 |
| Beeswax Wood Floor | `ReinforcedWood_Floor` | 20 | 0.5 |
| Beeswax Wood Halfpieces | `ReinforcedWood_Halfpiece` | 20 | 0.5 |
| Beeswax Wood Halfpitches | `ReinforcedWood_Half_Pitch` | 20 | 0.5 |
| Beeswax Wood Roof Corner | `ReinforcedWood_Roof_Corner` | 20 | 0.5 |
| Beeswax Wood Roof/Ramp | `ReinforcedWood_Ramp` | 20 | 0.5 |
| Beeswax Wood Wall | `ReinforcedWood_Wall` | 20 | 0.5 |
| Beeswax Wood Wall Angled | `ReinforcedWood_Wall_Angle` | 20 | 0.5 |
| Biofuel Extractor | `Extractor_Biofuel` | 1 | 2.0 |
| Biofuel Radar | `Radar_Biofuel` | 1 | 2.0 |
| Brazier | `Brazier` | 1 | 1.75 |
| Classic Rustic Sign | `Raw_Wood_Sign` | 20 | 0.5 |
| Clay Brick Advanced Beams | `ClayBrick_Advanced_Beam_Set` | 20 | 5.0 |
| Clay Brick Beam | `Clay_Brick_Beam` | 20 | 2.5 |
| Clay Brick Curved Buildings | `ClayBrick_Curved_Set` | 20 | 5.0 |
| Clay Brick Curved Wall Angles | `ClayBrick_Diagonal_Curved_Wall_Angles` | 20 | 5.0 |
| Clay Brick Diagonal Buildings | `ClayBrick_Diagonal_Set` | 20 | 5.0 |
| Clay Brick Floor | `Clay_Brick_Floor` | 20 | 2.5 |
| Clay Brick Halfpieces | `Clay_Brick_Halfpiece` | 20 | 2.5 |
| Clay Brick Halfpitches | `Clay_Brick_Roof_Half_Pitch` | 20 | 2.5 |
| Clay Brick Ramp | `Clay_Brick_Ramp` | 20 | 2.5 |
| Clay Brick Roof Corner | `Clay_Brick_Roof_Corner` | 20 | 2.5 |
| Clay Brick Roof Curved Angle | `ClayBrick_Roof_CurvedAngles` | 20 | 5.0 |
| Clay Brick Wall | `Clay_Brick_Wall` | 20 | 2.5 |
| Clay Brick Wall Angle | `Clay_Brick_Wall_Angle` | 20 | 2.5 |
| Clay Brick Wall/Roof Curved | `ClayBrick_Wall_Curved` | 20 | 5.0 |
| Concrete Advanced Beams | `Concrete_Advanced_Beam_Set` | 20 | 5.0 |
| Concrete Beam | `Concrete_Beam` | 20 | 2.5 |
| Concrete Curved Buildings | `Concrete_Curved_Set` | 20 | 5.0 |
| Concrete Curved Wall Angles | `Concrete_Diagonal_Curved_Wall_Angles` | 20 | 5.0 |
| Concrete Diagonal Buildings | `Concrete_Diagonal_Set` | 20 | 5.0 |
| Concrete Door | `Concrete_Door` | 20 | 1.0 |
| Concrete Floor | `Concrete_Floor` | 20 | 5.0 |
| Concrete Frame | `Concrete_Frame` | 20 | 5.0 |
| Concrete Halfpieces | `Concrete_Halfpiece` | 20 | 2.5 |
| Concrete Halfpitches | `Concrete_Half_Pitch` | 20 | 2.5 |
| Concrete Railing | `Concrete_Railing` | 20 | 1.0 |
| Concrete Railing Gate | `Concrete_Railing_Gate` | 20 | 1.0 |
| Concrete Ramp/Stairs | `Concrete_Ramp` | 20 | 5.0 |
| Concrete Roof Curved Angle | `Concrete_Roof_CurvedAngles` | 20 | 5.0 |
| Concrete Wall | `Concrete_Wall` | 20 | 5.0 |
| Concrete Wall Angled | `Concrete_Wall_Angle` | 20 | 5.0 |
| Concrete Wall/Roof Curved | `Concrete_Wall_Curved` | 20 | 5.0 |
| Dirt Corner | `Dirt_Corner` | 20 | 2.5 |
| Dirt Foundation | `Dirt_Frame` | 20 | 2.5 |
| Dirt Ramp | `Dirt_Ramp` | 20 | 2.5 |
| Dropship Landing Pad | `Landing_Pad_Player` | 1 | 25.0 |
| Electric Extractor | `Extractor_Electric` | 1 | 2.0 |
| Electric Radar | `Radar_Electric` | 1 | 2.0 |
| Elegant Curtain Window | `SilkWeave_Curtain_Window` | 20 | 1.0 |
| Examination Table | `Mission_Examination_Table` | 1 | 10.0 |
| Exotic Harvester | `Exotic_Harvester` | 1 | 3.0 |
| Experimental Sandworm Thumper | `Thumper_Sandworm` | 1 | 50.0 |
| Flag Pole | `National_Flag` | 1 | 5.0 |
| Floor Torch | `Kit_Floor_Torch` | 20 | 0.5 |
| Fur Curtain Window | `Fur_Curtain_Window` | 20 | 1.0 |
| Glass Advanced Beams | `Glass_Advanced_Beam_Set` | 20 | 5.0 |
| Glass Beam | `Glass_Beam` | 20 | 0.1 |
| Glass Curved Buildings | `Glass_Curved_Set` | 20 | 5.0 |
| Glass Curved Wall Angles | `Glass_Diagonal_Curved_Wall_Angles` | 20 | 5.0 |
| Glass Diagonal Buildings | `Glass_Diagonal_Set` | 20 | 5.0 |
| Glass Door | `Glass_Door` | 20 | 1.0 |
| Glass Floor | `Glass_Floor` | 20 | 0.1 |
| Glass Halfpieces | `Glass_Halfpiece` | 20 | 0.1 |
| Glass Halfpitches | `Glass_Half_Pitch` | 20 | 0.1 |
| Glass Roof | `Glass_Ramp` | 20 | 0.1 |
| Glass Roof Corner | `Glass_Roof_Corner` | 20 | 0.1 |
| Glass Roof Curved Angle | `Glass_Roof_CurvedAngles` | 20 | 5.0 |
| Glass Wall | `Glass_Wall` | 20 | 0.1 |
| Glass Wall Angled | `Glass_Wall_Angle` | 20 | 0.1 |
| Glass Wall/Roof Curved | `Glass_Wall_Curved` | 20 | 5.0 |
| Glass Window | `Glass_Window` | 20 | 1.0 |
| Heavy Glass Window | `Concrete_Window` | 20 | 1.0 |
| Heavy Trapdoor | `Concrete_TrapDoor` | 20 | 1.0 |
| Homestead Fireplace Cap | `Homestead_Fireplace_Cap` | 1 | 5.0 |
| Homestead Fireplace Extension | `Homestead_Fireplace_Ext` | 1 | 5.0 |
| Hydroponic Crop Plot | `Farming_CropPlot_T4_v2` | 10 | 2.0 |
| Ice Advanced Beams | `Ice_Advanced_Beam_Set` | 20 | 5.0 |
| Ice Beam | `Ice_Beam` | 20 | 0.5 |
| Ice Curved Buildings | `Ice_Curved_Set` | 20 | 5.0 |
| Ice Curved Roof Angles | `Ice_Roof_CurvedAngles` | 20 | 5.0 |
| Ice Curved Wall Angles | `Ice_Diagonal_Curved_Wall_Angles` | 20 | 5.0 |
| Ice Diagonal Buildings | `Ice_Diagonal_Set` | 20 | 5.0 |
| Ice Floor | `Ice_Floor` | 20 | 0.5 |
| Ice Halfpieces | `Ice_Halfpiece` | 20 | 0.5 |
| Ice Halfpitches | `Ice_Half_Pitch` | 20 | 0.5 |
| Ice Roof Corner | `Ice_Roof_Corner` | 20 | 0.5 |
| Ice Roof/Ramp | `Ice_Ramp` | 20 | 0.5 |
| Ice Wall | `Ice_Wall` | 20 | 0.5 |
| Ice Wall Angled | `Ice_Wall_Angle` | 20 | 0.5 |
| Ice Wall/Roof Curved | `Ice_Wall_Curved` | 20 | 5.0 |
| Industrial Floor | `Metal_Grate_Floor` | 20 | 1.0 |
| Industrial Stairs | `Metal_Grate_Stairs` | 20 | 1.0 |
| Interior Wood Beam | `Interior_Wood_Beam` | 20 | 0.5 |
| Interior Wood Door | `Wood_Door_Refined` | 20 | 1.0 |
| Interior Wood Floor | `Wood_Floor_Refined` | 20 | 0.5 |
| Interior Wood Halfpieces | `Refined_Halfpiece` | 20 | 0.25 |
| Interior Wood Halfpitches | `Refined_Half_Pitch` | 20 | 0.25 |
| Interior Wood Ladder | `Interior_Wood_Ladder` | 20 | 0.5 |
| Interior Wood Railing | `Wood_Railing_Refined` | 20 | 1.0 |
| Interior Wood Railing Gate | `Wood_Railing_Gate_Refined_V2` | 20 | 1.0 |
| Interior Wood Ramp | `Wood_Ramp_Refined` | 20 | 0.5 |
| Interior Wood Trapdoor | `Wood_TrapDoor_Refined` | 20 | 1.0 |
| Interior Wood Wall | `Wood_Wall_Refined` | 20 | 0.5 |
| Interior Wood Wall Angled | `Wood_Wall_Angle_Refined` | 20 | 0.5 |
| Iron Crop Plot | `Farming_CropPlot_T3_v2` | 10 | 2.0 |
| Large Beehive Expansion | `Beehive_Expansion2` | 1 | 5.0 |
| Lava Hunter Throne | `Lava_Hunter_Chair` | 1 | 0.5 |
| Leather Curtain Window | `Leather_Curtain_Window` | 20 | 1.0 |
| Leather Curtain Window | `Curtain_PlatinumWeave` | 20 | 1.0 |
| Limestone Advanced Beams | `Limestone_Advanced_Beam_Set` | 20 | 5.0 |
| Limestone Beam | `Limestone_Beam` | 20 | 5.0 |
| Limestone Curved Buildings | `Limestone_Curved_Set` | 20 | 5.0 |
| Limestone Curved Wall Angles | `Limestone_Diagonal_Curved_Wall_Angles` | 20 | 5.0 |
| Limestone Diagonal Buildings | `Limestone_Diagonal_Set` | 20 | 5.0 |
| Limestone Floor | `Limestone_Floor` | 20 | 5.0 |
| Limestone Frame | `Limestone_Frame` | 20 | 5.0 |
| Limestone Halfpieces | `Limestone_Halfpiece` | 20 | 5.0 |
| Limestone Halfpitches | `Limestone_Half_Pitch` | 20 | 5.0 |
| Limestone Ramp | `Limestone_Ramp` | 20 | 5.0 |
| Limestone Roof Corner | `Limestone_Roof_Corner` | 20 | 5.0 |
| Limestone Roof Curved Angle | `Limestone_Roof_CurvedAngles` | 20 | 5.0 |
| Limestone Wall | `Limestone_Wall` | 20 | 5.0 |
| Limestone Wall Angled | `Limestone_Wall_Angle` | 20 | 5.0 |
| Limestone Wall/Roof Curved | `Limestone_Wall_Curved` | 20 | 5.0 |
| Mug | `Prop_Mug` | 5 | 1.0 |
| Natural Rustic Sign | `Raw_Wood_Sign_Trunk_A` | 20 | 0.5 |
| Prototype Mini Thumper | `Thumper_Mini` | 1 | 50.0 |
| Prototype Thumper | `Thumper` | 1 | 90.0 |
| Quarrite Throne | `Rock_Golem_Chair` | 1 | 0.1 |
| Radar | `Kit_Radar` | 1 | 2.0 |
| Radar | `Faction_Mission_Radar` | 1 | 2.0 |
| Reinforced Curtain Window | `PlatinumWeave_Curtain_Window` | 20 | 1.0 |
| Reinforced Door | `Reinforced_Door` | 20 | 1.0 |
| Reinforced Glass Advanced Beams | `Glass_Advanced_Beam_Set_Tempered` | 20 | 5.0 |
| Reinforced Glass Beam | `Glass_Beam_Tempered` | 20 | 0.1 |
| Reinforced Glass Curved Buildings | `Glass_Curved_Set_Tempered` | 20 | 5.0 |
| Reinforced Glass Curved Wall Angles | `Glass_Diagonal_Curved_Wall_Angles_Tempered` | 20 | 5.0 |
| Reinforced Glass Diagonal Buildings | `Glass_Diagonal_Set_Tempered` | 20 | 5.0 |
| Reinforced Glass Door | `Glass_Door_Reinforced` | 20 | 1.0 |
| Reinforced Glass Floor | `Glass_Floor_Tempered` | 20 | 0.1 |
| Reinforced Glass Halfpieces | `Glass_Halfpiece_Tempered` | 20 | 0.1 |
| Reinforced Glass Halfpitches | `Glass_Half_Pitch_Tempered` | 20 | 0.1 |
| Reinforced Glass Roof | `Glass_Ramp_Tempered` | 20 | 0.1 |
| Reinforced Glass Roof Corner | `Glass_Roof_Corner_Tempered` | 20 | 0.1 |
| Reinforced Glass Roof Curved Angle | `Glass_Roof_CurvedAngles_Tempered` | 20 | 5.0 |
| Reinforced Glass Wall | `Glass_Wall_Tempered` | 20 | 0.1 |
| Reinforced Glass Wall Angled | `Glass_Wall_Angle_Tempered` | 20 | 0.1 |
| Reinforced Glass Wall/Roof Curved | `Glass_Wall_Curved_Tempered` | 20 | 5.0 |
| Reinforced Glass Window | `Glass_Window_Reinforced` | 20 | 1.0 |
| Reinforced Ladder | `Reinforced_Ladder` | 20 | 0.1 |
| Reinforced Railing | `Reinforced_Railing` | 20 | 1.0 |
| Reinforced Railing Gate | `Reinforced_Railing_Gate` | 20 | 1.0 |
| Reinforced Trapdoor | `Reinforced_TrapDoor` | 20 | 1.0 |
| Reinforced Window | `Reinforced_Window` | 20 | 1.0 |
| Resonance Surveyor | `Mission_Seismic_Probe` | 1 | 2.0 |
| Round Rustic Sign | `Raw_Wood_Sign_Trunk_B` | 20 | 0.5 |
| Sandworm Beam | `Sandworm_Beam` | 20 | 0.5 |
| Sandworm Floor | `Sandworm_Floor` | 20 | 0.5 |
| Sandworm Halfpieces | `Sandworm_Halfpiece` | 20 | 0.5 |
| Sandworm Halfpitches | `Sandworm_Half_Pitch` | 20 | 0.5 |
| Sandworm Roof Corner | `Sandworm_Roof_Corner` | 20 | 0.5 |
| Sandworm Roof/Ramp | `Sandworm_Ramp` | 20 | 0.5 |
| Sandworm Wall | `Sandworm_Wall` | 20 | 0.5 |
| Sandworm Wall Angled | `Sandworm_Wall_Angle` | 20 | 0.5 |
| Scoria Advanced Beams | `Scoria_Advanced_Beam_Set` | 20 | 5.0 |
| Scoria Beam | `Scoria_Beam` | 20 | 2.5 |
| Scoria Brick Advanced Beams | `ScoriaBrick_Advanced_Beam_Set` | 20 | 5.0 |
| Scoria Brick Beam | `Scoria_Brick_Beam` | 20 | 3.0 |
| Scoria Brick Curved Buildings | `ScoriaBrick_Curved_Set` | 20 | 5.0 |
| Scoria Brick Curved Wall Angles | `ScoriaBrick_Diagonal_Curved_Wall_Angles` | 20 | 5.0 |
| Scoria Brick Diagonal Buildings | `ScoriaBrick_Diagonal_Set` | 20 | 5.0 |
| Scoria Brick Floor | `Scoria_Brick_Floor` | 20 | 3.0 |
| Scoria Brick Halfpieces | `Scoria_Brick_Halfpiece` | 20 | 3.0 |
| Scoria Brick Halfpitches | `Scoria_Brick_Roof_Half_Pitch` | 20 | 3.0 |
| Scoria Brick Ramp | `Scoria_Brick_Ramp` | 20 | 3.0 |
| Scoria Brick Roof Corner | `Scoria_Brick_Roof_Corner` | 20 | 3.0 |
| Scoria Brick Roof Curved Angle | `ScoriaBrick_Roof_CurvedAngles` | 20 | 5.0 |
| Scoria Brick Wall | `Scoria_Brick_Wall` | 20 | 3.0 |
| Scoria Brick Wall Angle | `Scoria_Brick_Wall_Angle` | 20 | 3.0 |
| Scoria Brick Wall/Roof Curved | `ScoriaBrick_Wall_Curved` | 20 | 5.0 |
| Scoria Curved Buildings | `Scoria_Curved_Set` | 20 | 5.0 |
| Scoria Curved Wall Angles | `Scoria_Diagonal_Curved_Wall_Angles` | 20 | 5.0 |
| Scoria Diagonal Buildings | `Scoria_Diagonal_Set` | 20 | 5.0 |
| Scoria Floor | `Scoria_Floor` | 20 | 5.0 |
| Scoria Frame | `Scoria_Frame` | 20 | 5.0 |
| Scoria Halfpieces | `Scoria_Halfpiece` | 20 | 2.5 |
| Scoria Halfpitches | `Scoria_Half_Pitch` | 20 | 2.5 |
| Scoria Roof Corner | `Scoria_Roof_Corner` | 20 | 5.0 |
| Scoria Roof Curved Angle | `Scoria_Roof_CurvedAngles` | 20 | 5.0 |
| Scoria Roof/Ramp | `Scoria_Ramp` | 20 | 5.0 |
| Scoria Wall | `Scoria_Wall` | 20 | 5.0 |
| Scoria Wall Angled | `Scoria_Wall_Angle` | 20 | 5.0 |
| Scoria Wall/Roof Curved | `Scoria_Wall_Curved` | 20 | 5.0 |
| Scorpion Seat | `Scorpion_Boss_Trophy_Chair` | 1 | 2.0 |
| Small Beehive Expansion | `Beehive_Expansion` | 1 | 5.0 |
| Small Clay Brick Sign | `Brick_Sign_Small` | 20 | 1.0 |
| Small Composite Sign | `Composite_Sign_Small` | 20 | 1.0 |
| Small Iron Sign | `Iron_Sign_Small` | 20 | 1.0 |
| Small Stone Sign | `Stone_Sign_Small` | 20 | 1.0 |
| Small Wood Sign | `Wood_Sign_Small` | 20 | 0.5 |
| Steel Barred Door | `Clay_Brick_Door` | 20 | 1.0 |
| Steel Barred Railing | `Clay_Brick_Railing` | 20 | 1.0 |
| Steel Barred Railing Gate | `Clay_Brick_Railing_Gate` | 20 | 1.0 |
| Steel Barred Trapdoor Hatch | `Clay_Brick_TrapDoor` | 20 | 1.0 |
| Steel Barred Window | `Clay_Brick_Window` | 20 | 1.0 |
| Steel Roofing | `Concrete_Roof_Corner` | 20 | 5.0 |
| Stone Advanced Beams | `Stone_Advanced_Beam_Set` | 20 | 5.0 |
| Stone Beam | `Stone_Beam` | 20 | 2.5 |
| Stone Brick Advanced Beams | `StoneBrick_Advanced_Beam_Set` | 20 | 5.0 |
| Stone Brick Beam | `Stone_Brick_Beam` | 20 | 2.5 |
| Stone Brick Curved Buildings | `StoneBrick_Curved_Set` | 20 | 5.0 |
| Stone Brick Curved Wall Angles | `StoneBrick_Diagonal_Curved_Wall_Angles` | 20 | 5.0 |
| Stone Brick Diagonal Buildings | `StoneBrick_Diagonal_Set` | 20 | 5.0 |
| Stone Brick Fireplace Cap | `StoneBrick_Fireplace_Cap` | 1 | 5.0 |
| Stone Brick Fireplace Extension | `StoneBrick_Fireplace_Ext` | 1 | 5.0 |
| Stone Brick Floor | `Stone_Brick_Floor` | 20 | 2.5 |
| Stone Brick Halfpieces | `Stone_Brick_Halfpiece` | 20 | 2.5 |
| Stone Brick Halfpitches | `Stone_Brick_Roof_Half_Pitch` | 20 | 2.5 |
| Stone Brick Ramp | `Stone_Brick_Ramp` | 20 | 2.5 |
| Stone Brick Roof Corner | `Stone_Brick_Roof_Corner` | 20 | 2.5 |
| Stone Brick Roof Curved Angle | `StoneBrick_Roof_CurvedAngles` | 20 | 5.0 |
| Stone Brick Wall | `Stone_Brick_Wall` | 20 | 2.5 |
| Stone Brick Wall Angle | `Stone_Brick_Wall_Angle` | 20 | 2.5 |
| Stone Brick Wall/Roof Curved | `StoneBrick_Wall_Curved` | 20 | 5.0 |
| Stone Cairn | `Stone_Cairn` | 1 | 30.0 |
| Stone Curved Buildings | `Stone_Curved_Set` | 20 | 5.0 |
| Stone Curved Wall Angles | `Stone_Diagonal_Curved_Wall_Angles` | 20 | 5.0 |
| Stone Diagonal Buildings | `Stone_Diagonal_Set` | 20 | 5.0 |
| Stone Floor | `Stone_Floor` | 20 | 5.0 |
| Stone Frame | `Stone_Frame` | 20 | 5.0 |
| Stone Halfpieces | `Stone_Halfpiece` | 20 | 2.5 |
| Stone Halfpitches | `Stone_Half_Pitch` | 20 | 2.5 |
| Stone Pile | `ResourceStack_Stone` | 1 | 60.0 |
| Stone Roof Corner | `Stone_Roof_Corner` | 20 | 5.0 |
| Stone Roof Curved Angle | `Stone_Roof_CurvedAngles` | 20 | 5.0 |
| Stone Roof/Ramp | `Stone_Ramp` | 20 | 5.0 |
| Stone Wall | `Stone_Wall` | 20 | 5.0 |
| Stone Wall Angled | `Stone_Wall_Angle` | 20 | 5.0 |
| Stone Wall/Roof Curved | `Stone_Wall_Curved` | 20 | 5.0 |
| Thatch Beam | `Thatch_Beam` | 20 | 0.1 |
| Thatch Door | `Thatch_Door` | 20 | 1.0 |
| Thatch Floor | `Thatch_Floor` | 20 | 0.1 |
| Thatch Halfpieces | `Thatch_Halfpiece` | 20 | 0.1 |
| Thatch Halfpitches | `Thatch_Half_Pitch` | 20 | 0.1 |
| Thatch Ladder | `Thatch_Ladder` | 20 | 0.1 |
| Thatch Railing | `Thatch_Railing` | 20 | 1.0 |
| Thatch Railing Gate | `Thatch_Railing_Gate` | 20 | 1.0 |
| Thatch Roof Corner | `Thatch_Roof_Corner` | 20 | 0.1 |
| Thatch Roof/Ramp | `Thatch_Ramp` | 20 | 0.1 |
| Thatch Trapdoor | `Thatch_TrapDoor` | 20 | 1.0 |
| Thatch Wall | `Thatch_Wall` | 20 | 0.1 |
| Thatch Wall Angled | `Thatch_Wall_Angle` | 20 | 0.1 |
| Thatch Window | `Thatch_Window` | 20 | 1.0 |
| TPS Landing Pad | `Landing_Pad_Prop` | 1 | 25.0 |
| UDA Dropship | `Prop_Dropship` | 1 | 1.0 |
| Uranium Extraction Unit | `Exotic_Uranium_Collector` | 1 | 8.0 |
| Wall Torch | `Kit_Wall_Torch` | 20 | 0.5 |
| Wood Beam | `Wood_Beam` | 20 | 0.5 |
| Wood Crop Plot | `Farming_CropPlot_T2_v2` | 10 | 2.0 |
| Wood Door | `Wood_Door` | 20 | 1.0 |
| Wood Floor | `Wood_Floor` | 20 | 0.5 |
| Wood Halfpieces | `Wood_Halfpiece` | 20 | 0.5 |
| Wood Halfpitches | `Wood_Half_Pitch` | 20 | 0.1 |
| Wood Ladder | `Wood_Ladder` | 20 | 0.1 |
| Wood Pile | `ResourceStack_Wood` | 1 | 60.0 |
| Wood Railing | `Wood_Railing` | 20 | 1.0 |
| Wood Railing Gate | `Wood_Railing_Gate` | 20 | 1.0 |
| Wood Roof Corner | `Wood_Roof_Corner` | 20 | 0.5 |
| Wood Roof/Ramp | `Wood_Ramp` | 20 | 0.5 |
| Wood Trapdoor | `Wood_TrapDoor` | 20 | 1.0 |
| Wood Wall | `Wood_Wall` | 20 | 0.5 |
| Wood Wall Angled | `Wood_Wall_Angle` | 20 | 0.5 |
| Wood Window | `Wood_Window` | 20 | 1.0 |
| Wooden Chair | `Wood_Chair` | 1 | 0.5 |

## Decoração (415 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Antelope Trophy | `Desert_Deer_Trophy` | 1 | 2.0 |
| Arctic Scorpion Trophy | `Arctic_Scorpion_Trophy` | 1 | 2.0 |
| Arctic Skulk Trophy | `Orka_Arctic_Trophy` | 1 | 4.0 |
| Arctic Vesper Trophy | `Arctic_Bat_Trophy` | 1 | 1.0 |
| Arid Striker Trophy | `Desert_Striker_Trophy` | 1 | 2.0 |
| Art Deco 10-Seater Table | `Gold_Table_10Seater` | 1 | 5.0 |
| Art Deco 2-Seater Couch | `Gold_Living_Chair2` | 1 | 5.0 |
| Art Deco 3-Seater Couch | `Gold_Living_Chair3` | 1 | 5.0 |
| Art Deco 6-Seater Table | `Gold_Table_6Seater` | 1 | 5.0 |
| Art Deco Candlestick | `Gold_Candle` | 1 | 0.1 |
| Art Deco Chandelier | `Gold_Chandelier` | 1 | 5.0 |
| Art Deco Dining Chair | `Gold_Dining_Chair` | 1 | 5.0 |
| Art Deco Fireplace Cap | `Gold_Fireplace_Cap` | 1 | 5.0 |
| Art Deco Fireplace Extension | `Gold_Fireplace_Ext` | 1 | 5.0 |
| Art Deco Floor Lamp | `Gold_Standing_Lamp` | 1 | 5.0 |
| Art Deco Lounge Chair  | `Gold_Living_Chair` | 1 | 5.0 |
| Art Deco Partition | `Gold_Partition` | 1 | 5.0 |
| Art Deco Round Table | `Gold_Table_Round` | 1 | 5.0 |
| Art Deco Rug | `Gold_Rug` | 1 | 5.0 |
| Art Deco Sitting Bench | `Gold_Sitting_Bench` | 1 | 5.0 |
| Art Deco Vase | `Gold_Vase` | 1 | 5.0 |
| Art Deco Wall Light | `Gold_Wall_Light` | 1 | 5.0 |
| Art Deco Wall Shelf | `Gold_Shelf_Wall` | 1 | 5.0 |
| Art Deco Wall Sign | `Gold_Wall_Sign` | 1 | 5.0 |
| Ashen Drake Trophy | `Ashen_Drake_Trophy` | 1 | 2.0 |
| Barbed Wire Fence | `Homestead_Barbed_Wire_Fence` | 20 | 1.0 |
| Barn Door | `Homestead_BarnDoor` | 20 | 1.0 |
| Base Sign | `Bunker_Base_Sign` | 5 | 5.0 |
| Battered Stool | `Lab_Stool` | 1 | 1.5 |
| Bear Rug | `Rug_Bear` | 1 | 1.0 |
| Bear Trophy | `Bear_Trophy` | 1 | 4.0 |
| Biofuel Chimney Cap | `Gas_Fireplace_Cap` | 1 | 2.0 |
| Biofuel Chimney Extension | `Gas_Fireplace_Ext` | 1 | 6.5 |
| Black Cat Trophy | `Cat_Trophy_A3` | 1 | 2.5 |
| Black Chicken Trophy | `Chicken_Trophy_A2` | 1 | 1.0 |
| Black Horse Trophy | `Horse_Trophy_A2` | 1 | 2.5 |
| Black Jaguar Trophy | `Jaguar_Black_Trophy` | 1 | 2.0 |
| Black Wolf Trophy | `Alphawolf_Trophy` | 1 | 2.0 |
| Black Wolf Trophy | `Black_Wolf_Trophy_Sit` | 1 | 5.0 |
| Blueback Trophy | `Blueback_Trophy` | 1 | 2.0 |
| Boardgame | `Prop_Boardgame` | 20 | 1.0 |
| Book | `Prop_Book` | 20 | 0.5 |
| Bookstack | `Prop_Bookstack` | 20 | 1.0 |
| Bronze Alpha Sandworm Statue | `Alpha_Sandworm_Statue_Bronze` | 1 | 1.0 |
| Bronze Bear Statue | `Bear_Statue_Bronze` | 1 | 1.0 |
| Bronze Cougar Statue | `Cougar_Statue_Bronze` | 1 | 1.0 |
| Bronze Elephant Statue | `Elephant_Statue_Bronze` | 1 | 1.0 |
| Bronze Hyena Statue | `Hyena_Statue_Bronze` | 1 | 1.0 |
| Bronze Jaguar Statue | `Jaguar_Statue_Bronze` | 1 | 1.0 |
| Bronze Polar Bear Statue | `PolarBear_Statue_Bronze` | 1 | 1.0 |
| Bronze Scorpion Statue | `Scorpion_Statue_Bronze` | 1 | 1.0 |
| Bronze Snow Leopard Statue | `SnowLeopard_Statue_Bronze` | 1 | 1.0 |
| Brown Horse Trophy | `Horse_Trophy_A1` | 1 | 2.5 |
| Brown Laika Jumpsuit Trophy | `Dog_Trophy_D2_2` | 1 | 2.5 |
| Brown Laika Trophy | `Dog_Trophy_D2_1` | 1 | 2.5 |
| Brutalist 10-Seater Table | `Brutalist_Dining_Table_10` | 1 | 15.0 |
| Brutalist 2-Seater Couch | `Brutalist_Living_Couch_2` | 1 | 10.0 |
| Brutalist 3-Seater Couch | `Brutalist_Living_Couch_3` | 1 | 12.0 |
| Brutalist 6-Seater Table | `Brutalist_Dining_Table_6` | 1 | 10.0 |
| Brutalist Candlestick | `Brutalist_Candle` | 1 | 1.0 |
| Brutalist Coffee Table | `Brutalist_CoffeeTable` | 1 | 5.0 |
| Brutalist Dining Chair | `Brutalist_Dining_Chair` | 1 | 7.0 |
| Brutalist Lamp | `Brutalist_Lamp` | 1 | 1.0 |
| Brutalist Lounge Chair | `Brutalist_Living_Chair` | 1 | 7.0 |
| Brutalist Octagonal Table | `Brutalist_Dining_Table_Round` | 1 | 10.0 |
| Brutalist Sitting Bench | `Brutalist_Bench_Sitting` | 1 | 8.0 |
| Brutalist Square Lamp | `Brutalist_Lamp_Square` | 1 | 1.0 |
| Brutalist Stool | `Brutalist_Stool` | 1 | 5.0 |
| Brutalist Wall Shelf | `Brutalist_Shelf_Wall` | 1 | 5.0 |
| Buffalo Rug | `Rug_Buffalo` | 1 | 1.0 |
| Buffalo Trophy | `Buffalo_Trophy` | 1 | 2.0 |
| Bull Trophy | `Bull_Trophy` | 1 | 2.0 |
| Burlap Sack | `Prop_Burlap_Sack` | 20 | 1.0 |
| Calf Trophy | `Calf_Trophy` | 1 | 2.0 |
| Cards | `Prop_Cards` | 20 | 0.25 |
| Carved Wood 2-Seater Couch | `Carved_Chair_Living_2Seater` | 1 | 1.0 |
| Carved Wood 3-Seater Couch | `Carved_Chair_Living_3Seater` | 1 | 1.0 |
| Carved Wood Armchair | `Carved_Chair_Living` | 1 | 1.0 |
| Carved Wood Candlestick | `Carved_Candle` | 1 | 1.0 |
| Carved Wood Chair | `Carved_Chair_Dining` | 1 | 1.0 |
| Carved Wood Coffee Table | `Carved_Coffee_Table` | 1 | 1.0 |
| Carved Wood Desk Lamp | `Carved_Desk_Lamp` | 1 | 1.0 |
| Carved Wood Large Table | `Carved_Table_10Seater` | 1 | 1.0 |
| Carved Wood Round Table | `Carved_Table_Round` | 1 | 1.0 |
| Carved Wood Sitting Bench | `Carved_Sitting_Bench` | 1 | 1.0 |
| Carved Wood Stool | `Carved_Stool` | 1 | 1.0 |
| Carved Wood Table | `Carved_Table_6Seater` | 1 | 1.0 |
| Carved Wood Wall Shelf | `Carved_Wall_Shelf` | 1 | 1.0 |
| Caveworm Trophy | `Caveworm_Trophy` | 1 | 2.0 |
| Centrifuge | `Prop_Centrifuge` | 10 | 2.0 |
| Chala Trophy | `Chala_Trophy` | 1 | 2.0 |
| Chamois Trophy | `Chamios_Trophy` | 1 | 2.0 |
| Charcoal Framed Painting | `Painting_Dark` | 1 | 2.0 |
| Chemicals | `Prop_Chemicals` | 30 | 1.0 |
| Chick Trophy | `Chick_Trophy` | 1 | 2.0 |
| Chimney Cap | `Fireplace_Chimney_Cap` | 1 | 2.0 |
| Chimney Cap Half | `Fireplace_Chimney_Cap_Half` | 1 | 2.0 |
| Chimney Extension | `Fireplace_Chimney_Ext` | 1 | 6.5 |
| Chocolate Labrador Trophy | `Dog_Trophy_A2` | 1 | 2.5 |
| Cleaning Supplies | `Prop_CleaningSupplies` | 10 | 1.0 |
| Clicker Trophy | `Giant_Roach_Trophy` | 1 | 4.0 |
| Clipboard | `Prop_Clipboard` | 20 | 0.5 |
| Columbian Mammoth Trophy | `Desert_Mammoth_Trophy` | 1 | 2.0 |
| Container | `Prop_Container` | 1 | 0.5 |
| Copper Cluster Lamp | `Geode_Lamp_Burst_Copper` | 1 | 1.5 |
| Copper Geode Lamp | `Geode_Lamp_Cut_Copper` | 1 | 1.5 |
| Copper Monolith Lamp | `Geode_Lamp_Monolith_Copper` | 1 | 1.5 |
| Corkboard | `Prop_Eden_Corkboard` | 20 | 1.5 |
| Cougar Rug | `Rug_Cougar` | 1 | 1.0 |
| Cougar Trophy | `Cougar_Trophy` | 1 | 2.0 |
| Cow Trophy | `Cow_Trophy` | 1 | 2.0 |
| Crocodile Trophy | `Crocodile_Trophy` | 1 | 2.0 |
| Cryogenic Sample Storage | `Prop_Cryogenic_Sample_Storage` | 20 | 0.25 |
| Damaged Air Conditioning Unit | `Bunker_Aircon` | 1 | 5.0 |
| Damaged Communication Antenna | `Bunker_Antenna` | 1 | 5.0 |
| Damaged Electrical Equipment | `Bunker_Prop` | 5 | 5.0 |
| Damaged Solar Panel | `Bunker_SolarPanel` | 1 | 5.0 |
| Dark Wall Pipes | `Prop_Pipe2` | 10 | 2.0 |
| Decorative shell | `AlienFossil_Conch` | 5 | 1.0 |
| Deer Rug | `Rug_Deer` | 1 | 1.0 |
| Deer Trophy | `Deer_Trophy` | 1 | 2.0 |
| Dissected Creature | `Prop_Dissected_Roach` | 5 | 2.0 |
| Dossier | `Prop_NPC_File` | 10 | 0.5 |
| Drac Trophy | `Drac_Trophy` | 1 | 2.0 |
| Draven Trophy | `Chew_Trophy` | 1 | 4.0 |
| Dreadwing Trophy | `Dreadwing_Trophy` | 1 | 2.0 |
| Dribbo Trophy | `Mini_Hippo_Trophy` | 1 | 1.0 |
| Drosik Trophy | `Tundra_Deer_Trophy` | 1 | 4.0 |
| Dune Raptor Trophy | `Raptor_Desert_Trophy` | 1 | 4.0 |
| Electric Chimney Cap | `Electric_Fireplace_Cap` | 1 | 2.0 |
| Electric Chimney Extension | `Electric_Fireplace_Ext` | 1 | 6.5 |
| Elephant Trophy | `Elephant_Trophy` | 1 | 2.0 |
| Elysium Magazine | `Prop_Magazine_Eden` | 20 | 0.2 |
| Enzyme Vat | `Prop_Enzyme_Vat` | 10 | 5.0 |
| Enzyme Vat (Empty) | `Prop_Enzyme_Vat_Empty` | 10 | 5.0 |
| Equix Trophy | `Equix_Trophy` | 1 | 2.0 |
| Eye Wash Station | `Prop_Eye_Wash_Station` | 10 | 5.0 |
| Farm Fence | `Homestead_Farm_Railing` | 20 | 1.0 |
| Farm Fence Gate | `Homestead_Farm_Railing_Gate` | 20 | 1.0 |
| Filing Cabinet | `Prop_Filing_Cabinet` | 5 | 10.0 |
| Fire Extinguisher Wall Mount | `Bunker_ExtinguisherWallMount` | 1 | 1.0 |
| Fish Poster | `Prop_Poster_Fishing` | 20 | 0.25 |
| Fish Trophy Mount | `Fish_Wall_Mount` | 1 | 1.0 |
| Flasks | `Prop_Flask` | 20 | 0.5 |
| Flower Pot Classic | `Homestead_Flower_Pot_A` | 1 | 1.5 |
| Flower Pot Round | `Homestead_Flower_Pot_E` | 1 | 1.5 |
| Flower Pot Round Large | `Homestead_Flower_Pot_C` | 1 | 1.5 |
| Flower Pot Short | `Homestead_Flower_Pot_B` | 1 | 1.5 |
| Flower Pot Tall | `Homestead_Flower_Pot_D` | 1 | 1.5 |
| Frostfoot Trophy | `Yeti_Trophy` | 1 | 4.0 |
| Full Sandworm Brazier | `Sandworm_Trophy_Brazier_Large` | 1 | 5.0 |
| Full Sandworm Trophy | `Sandworm_Trophy` | 1 | 5.0 |
| Garganutan Fishing trap | `Ape_Fishing_Trap` | 5 | 1.0 |
| Garganutan Rug | `Ape_Rug` | 5 | 1.0 |
| Garganutan Trophy | `Ape_Trophy` | 1 | 1.0 |
| Garganutan Trophy | `Juvenile_Ape_Trophy` | 1 | 4.0 |
| Geothermal Spider Trophy | `Geothermal_Spider_Trophy` | 1 | 4.0 |
| German Shepherd Trophy | `Dog_Trophy_B1` | 1 | 2.5 |
| Giant Scorpion Trophy | `Scorpion_Boss_Trophy` | 1 | 2.0 |
| Gilded Framed Painting | `Painting_Gold_Wood` | 1 | 2.0 |
| Glaci Trophy | `Snow_Slug_Trophy` | 1 | 2.0 |
| Gold Cluster Lamp | `Geode_Lamp_Burst_Gold` | 1 | 1.5 |
| Gold Geode Lamp | `Geode_Lamp_Cut_Gold` | 1 | 1.5 |
| Gold Monolith Lamp | `Geode_Lamp_Monolith_Gold` | 1 | 1.5 |
| Golden Framed Painting | `Painting_Gold` | 1 | 2.0 |
| Golden Labrador Trophy | `Dog_Trophy_A1` | 1 | 2.5 |
| Grey Tabby Cat Trophy | `Cat_Trophy_A1` | 1 | 2.5 |
| Gribbler Trophy | `Tundra_Monkey_Trophy` | 1 | 3.5 |
| Group 15 Sign | `Prop_UDA_Sign` | 20 | 2.0 |
| Group 15 Sign (Defaced) | `Prop_UDA_Sign_Defaced` | 20 | 2.0 |
| Hammerhead Trophy Coil | `Slug_Trophy_Coil` | 1 | 0.5 |
| Hammerhead Trophy Habitat | `Slug_Trophy_Habitat` | 1 | 0.5 |
| Hammerhead Vial Trophy | `Slug_Trophy_Vial` | 1 | 0.5 |
| Hanging Scorpion Trophy | `Scorpion_Boss_Trophy_Hanging` | 1 | 2.0 |
| Hay Bale | `Hay_Bale` | 10 | 0.5 |
| Helpful UDA Sign | `Prop_Propaganda_Sign` | 20 | 2.0 |
| Homestead Aged Cheese | `Homestead_Cheese` | 10 | 0.2 |
| Homestead Barrel Butter Churn | `Homestead_Butter_Churn` | 10 | 2.0 |
| Homestead Bird Feeder | `Homestead_BirdFeeder` | 5 | 5.0 |
| Homestead Coffee Grinder | `Homestead_Coffee_Grinder` | 10 | 2.0 |
| Homestead Copper Pot | `Homestead_Copper_Pot` | 10 | 0.5 |
| Homestead Cuckcoo Clock | `Homestead_Cuckcoo_Clock` | 10 | 0.5 |
| Homestead Curtain | `Homestead_Curtain` | 20 | 1.0 |
| Homestead Dash Butter Churn | `Homestead_Butter_Churn_Large` | 10 | 2.0 |
| Homestead Double Rocking Chair | `Homestead_Rocking_Chair_Double` | 1 | 10.0 |
| Homestead Fireplace Bellows | `Homestead_Fireplace_Bellows` | 10 | 0.5 |
| Homestead Fireplace Screen | `Homestead_Fireplace_Screen` | 10 | 0.5 |
| Homestead Fireplace Tools | `Homestead_Fireplace_Tools` | 10 | 0.5 |
| Homestead Gold Bird Bath | `Homestead_BirdBath_Gold` | 5 | 1.5 |
| Homestead Hanging Meat | `Homestead_Hanging_Meat` | 10 | 0.5 |
| Homestead Hard Cushion | `Homestead_Cushion_B` | 10 | 0.5 |
| Homestead Honey Pot | `Homestead_Honey_Pot` | 25 | 1.0 |
| Homestead Iron Bird Bath | `Homestead_BirdBath_Iron` | 5 | 1.5 |
| Homestead Knitting Decor | `Homestead_Knitting_Decor` | 20 | 0.25 |
| Homestead Lamp Post | `Homestead_Lamp_Ground` | 5 | 5.0 |
| Homestead Picnic Table | `Homestead_Picnic_Table` | 1 | 10.0 |
| Homestead Planter Box | `Homestead_PlanterBox_SML` | 10 | 2.0 |
| Homestead Rocking Chair | `Homestead_Rocking_Chair_Single` | 1 | 5.0 |
| Homestead Rustic Lamp | `Homestead_Lantern` | 5 | 1.0 |
| Homestead Saloon Door | `Homestead_Saloon_Door` | 20 | 1.0 |
| Homestead Scarecrow | `Homestead_Spawn_Blocker_Scarecrow` | 1 | 5.0 |
| Homestead Shutter | `Homestead_Shutter` | 20 | 1.0 |
| Homestead Soft Armchair | `Homestead_Soft_Sofa_Single` | 1 | 20.0 |
| Homestead Soft Cushion | `Homestead_Cushion_A` | 10 | 0.5 |
| Homestead Soft Sofa | `Homestead_Soft_Sofa_Double` | 1 | 40.0 |
| Homestead Spinning Wheel | `Homestead_Spinning_Wheel` | 10 | 0.5 |
| Homestead Swing Chair | `Homestead_Swing_Chair` | 1 | 20.0 |
| Homestead Vintage Jar | `Homestead_Vintage_Jar` | 25 | 0.5 |
| Homestead Wall Candle | `Homestead_Wall_Candle` | 5 | 1.0 |
| Homestead Wall Lamp | `Homestead_Lamp_Wall` | 5 | 2.0 |
| Homestead Weather Vane | `Homestead_Weather_Vane` | 10 | 0.5 |
| Hopper Trophy | `Hopping_Creature_Trophy` | 1 | 4.0 |
| Howling Black Wolf Trophy | `Black_Wolf_Trophy_Howl` | 1 | 5.0 |
| Hyena Rug | `Rug_Desert_Wolf` | 1 | 1.0 |
| Hyena Trophy | `DesertWolf_Trophy` | 1 | 2.0 |
| Ignari Trophy | `Lava_Viscid_Trophy` | 1 | 2.0 |
| Industrial 2-Seater Couch | `Metal_Chair_Living_2Seater` | 1 | 10.0 |
| Industrial Candlestick | `Metal_Candle` | 1 | 10.0 |
| Industrial Chair | `Metal_Chair_Living` | 1 | 10.0 |
| Industrial Coffee Table | `Metal_Coffeetable` | 1 | 10.0 |
| Industrial Dining Chair | `Metal_Chair_Dining` | 1 | 10.0 |
| Industrial Lamp | `Metal_Lamp` | 1 | 10.0 |
| Industrial Large Table | `Metal_Table_Dining10` | 1 | 10.0 |
| Industrial Round Table | `Metal_Table_Round` | 1 | 10.0 |
| Industrial Sign - Diamond | `Prop_Industrial_Sign_Diamond` | 20 | 2.0 |
| Industrial Sign - Square | `Prop_Industrial_Sign_Square` | 20 | 2.0 |
| Industrial Sign - Triangle | `Prop_Industrial_Sign_Triangle` | 20 | 2.0 |
| Industrial Sitting Bench | `Metal_Chair_Sitting` | 1 | 10.0 |
| Industrial Stool | `Metal_Stool` | 1 | 10.0 |
| Industrial Table | `Metal_Table_Dining6` | 1 | 10.0 |
| Industrial Wall Shelf | `Metal_Shelf_Wall` | 1 | 10.0 |
| Jaguar Rug | `Rug_Jaguar` | 1 | 1.0 |
| Jaguar Trophy | `Jaguar_Trophy` | 1 | 2.0 |
| Kea Trophy | `Kea_Trophy` | 1 | 2.0 |
| Keyboard | `Prop_Keyboard` | 5 | 1.0 |
| Kiwi Trophy | `Kiwi_Trophy` | 1 | 2.0 |
| Komodo Trophy | `Komodo_Trophy` | 1 | 2.0 |
| Korrin Trophy | `Bounder_Trophy` | 1 | 4.0 |
| Lab Info Poster | `Prop_Lab_Poster` | 20 | 0.25 |
| Lab Stand | `Prop_Lab_Stand` | 20 | 0.5 |
| Lab Table | `Prop_Lab_Table` | 20 | 2.0 |
| Labcoats | `Prop_Labcoats` | 10 | 0.5 |
| Lamb Trophy | `Lamb_Trophy` | 1 | 2.0 |
| Landshark Trophy | `Landshark_Trophy` | 1 | 2.0 |
| Laptop | `Prop_Laptop` | 20 | 0.5 |
| Large Cork board | `Prop_Corkboard_Large` | 20 | 1.5 |
| Large Flask | `Prop_Large_Flask` | 10 | 0.5 |
| Large Specimen Sample | `Prop_Specimen_Large` | 10 | 5.0 |
| Lava Broodling Trophy | `Lava_Hunter_Broodling_Trophy` | 1 | 2.0 |
| Lava Hunter Display | `Lava_Hunter_Feature` | 1 | 0.5 |
| Lava Hunter Trophy | `Lava_Hunter_Trophy` | 1 | 2.0 |
| Magazine | `Prop_Magazine` | 20 | 0.2 |
| Medical Trolley | `Prop_Medical_Trolly` | 5 | 5.0 |
| Metallic Framed Painting | `Painting_Metal` | 1 | 2.0 |
| Microscope | `Prop_Microscope` | 20 | 2.0 |
| Mining Cart | `Prop_Mining_Cart` | 5 | 2.0 |
| Mining Cart Rail | `Prop_Mining_Rail` | 100 | 1.0 |
| Mining Machinery | `Prop_Mining_Equipment` | 5 | 50.0 |
| Moa Trophy | `Moa_Trophy` | 1 | 2.0 |
| Moisture Analyzer | `Prop_Moisture_Analyzer` | 20 | 2.0 |
| Molecules | `Prop_Molecule` | 20 | 0.25 |
| Monitor | `Prop_Monitor` | 10 | 1.0 |
| Mouse | `Prop_Mouse` | 5 | 0.5 |
| Needler Trophy | `Needler_Trophy` | 1 | 2.0 |
| Orange Tabby Cat Trophy | `Cat_Trophy_A2` | 1 | 2.5 |
| Orbital Laser Controls | `Prop_LaserControls` | 20 | 10.0 |
| Oxite Cluster Lamp | `Geode_Lamp_Burst_Oxite` | 1 | 1.5 |
| Oxite Geode Lamp | `Geode_Lamp_Cut_Oxite` | 1 | 1.5 |
| Oxite Monolith Lamp | `Geode_Lamp_Monolith_Oxite` | 1 | 1.5 |
| Panda German Shepherd Trophy | `Dog_Trophy_B2` | 1 | 2.5 |
| Paper Towels | `Prop_PaperTowls` | 10 | 0.25 |
| Photo Frame | `Prop_Photo_Frame_Standing` | 20 | 0.25 |
| Pig Trophy | `Pig_Trophy` | 5 | 0.5 |
| Piglet Trophy | `Piglet_Trophy` | 5 | 0.5 |
| Plastic Crate | `Prop_Plastic_Crate` | 10 | 1.5 |
| Polar Bear Rug | `Rug_PolarBear` | 1 | 1.0 |
| Polar Bear Trophy | `PolarBear_Trophy` | 1 | 4.0 |
| Posters | `Bunker_Poster` | 5 | 5.0 |
| Pronghorn Trophy | `Pronghorn_Trophy` | 1 | 2.0 |
| Pug Trophy | `Dog_Trophy_C1` | 1 | 2.5 |
| Pygmy Lop Trophy | `Pygmy_Lop_Trophy` | 1 | 2.0 |
| Quarrite Lamp | `Rock_Golem_Trophy_Lamp` | 1 | 1.0 |
| Quarrite Trophy | `Rock_Golem_Trophy` | 1 | 1.0 |
| Quarrite Trophy | `Juvenile_Rock_Golem_Trophy` | 1 | 4.0 |
| Rabbit Trophy | `Rabbit_Trophy` | 1 | 2.0 |
| Radio | `Prop_Radio` | 10 | 1.0 |
| Ram Trophy | `Ram_Trophy` | 1 | 2.0 |
| Ranch Gate Sign | `Homestead_Ranch_Gate_Sign` | 1 | 20.0 |
| Ranch Sign | `Homestead_Ranch_Sign` | 1 | 20.0 |
| Raptor Trophy | `Raptor_Trophy` | 1 | 4.0 |
| Ravager Trophy | `Flying_Tank_Trophy` | 1 | 4.0 |
| Raw Copper Lamp | `Geode_Lamp_Rock_Copper` | 1 | 1.5 |
| Raw Gold Lamp | `Geode_Lamp_Rock_Gold` | 1 | 1.5 |
| Raw Oxite Lamp | `Geode_Lamp_Rock_Oxite` | 1 | 1.5 |
| Reaver Trophy | `Reaver_Trophy` | 1 | 4.0 |
| Record Player | `Prop_Record_Player` | 10 | 2.5 |
| Red Chicken Trophy | `Chicken_Trophy` | 1 | 1.0 |
| Redback Trophy | `Redback_Trophy` | 1 | 2.0 |
| Retaining Wall | `Homestead_Retaining_Wall` | 20 | 2.0 |
| Rimetusk Chandelier | `IceMammoth_Trophy_Chandelier` | 1 | 2.0 |
| Rimetusk Display Trophy | `IceMammoth_Trophy_Feature` | 1 | 2.0 |
| Rimetusk Head Trophy | `IceMammoth_Trophy_Head` | 1 | 2.0 |
| Rimetusk Trophy | `Snow_Mammoth_Trophy` | 1 | 2.0 |
| Road Cone | `Prop_Cone` | 100 | 0.05 |
| Roat Trophy | `Roat_Trophy` | 1 | 2.0 |
| Rooster Trophy | `Rooster_Trophy` | 1 | 2.0 |
| Ruaumoko Base Sign | `Bunker_Sign` | 5 | 5.0 |
| Running Black Wolf Trophy | `Black_Wolf_Trophy` | 1 | 5.0 |
| Rusted Bear Trap | `Prop_Bear_Trap` | 10 | 3.0 |
| Rustic 2-Seater Couch | `Rustic_CouchMedium` | 1 | 15.0 |
| Rustic 3-Seater Couch | `Rustic_CouchLarge` | 1 | 20.0 |
| Rustic Armchair | `Rustic_LivingChair` | 1 | 5.0 |
| Rustic Candles | `Rustic_Candles` | 1 | 0.5 |
| Rustic Coffee Table | `Rustic_CoffeeTable` | 1 | 10.0 |
| Rustic Dining Chair | `Rustic_DiningChair` | 1 | 5.0 |
| Rustic Icarus Statue | `Rustic_Statue` | 1 | 0.5 |
| Rustic Lamp | `Raw_Wood_Lamp` | 1 | 1.0 |
| Rustic Large Table | `Rustic_TableLarge` | 1 | 15.0 |
| Rustic Pot | `Rustic_Pot` | 1 | 0.5 |
| Rustic Round Table | `Rustic_TableRound` | 1 | 10.0 |
| Rustic Sitting Bench | `Rustic_Bench` | 1 | 20.0 |
| Rustic Stool | `Rustic_Stool` | 1 | 1.0 |
| Rustic Table | `Rustic_Table` | 1 | 10.0 |
| Rustic Wall Shelf | `Rustic_Wood_Shelf` | 1 | 1.0 |
| Saddle Bag | `Prop_Saddle_Bag` | 20 | 0.5 |
| Safety Goggles | `Prop_Goggles` | 30 | 0.5 |
| Safety Poster | `Prop_Poster` | 20 | 0.25 |
| Sandhorn Trophy | `Flightless_Tank_Trophy` | 1 | 4.0 |
| Sandworm Brazier | `Sandworm_Trophy_Brazier` | 1 | 5.0 |
| Sandworm Lifecycle Poster | `Prop_Sandworm_Poster` | 10 | 0.5 |
| Sandworm Trophy | `Sandworm_Trophy_Head` | 1 | 5.0 |
| Scales | `Prop_Scales` | 20 | 1.0 |
| Science Tray | `Prop_Science_Tray` | 10 | 0.5 |
| Scorpion Tail Trophy | `Scorpion_Boss_Trophy_Tail` | 1 | 2.0 |
| Scorpion Trophy | `Scorpion_Trophy` | 1 | 2.0 |
| Scroll Painting | `Painting_Scroll` | 1 | 2.0 |
| Scuttler Trophy | `Sandscuttle_Trophy` | 1 | 3.5 |
| Security Camera | `Prop_Camera` | 5 | 1.0 |
| Shaggy Zebra Trophy | `Wooly_Zebra_Trophy` | 1 | 2.0 |
| Sheep Trophy | `Sheep_Trophy` | 1 | 2.5 |
| Skeleton Stand | `Prop_Skeleton` | 10 | 5.0 |
| Skulmutt Prime Trophy | `Mange_Wolf_Alpha_Trophy` | 1 | 3.5 |
| Skulmutt Trophy | `Mange_Wolf_Trophy` | 1 | 3.5 |
| Sled | `Prop_Sled` | 1 | 20.0 |
| Slinker Trophy | `Slinker_Trophy` | 1 | 4.0 |
| Small Cork board | `Prop_Corkboard_Small` | 20 | 1.0 |
| Small Specimen Sample | `Prop_Specimen_Small` | 10 | 0.5 |
| Snow Leopard Rug | `Rug_SnowLeopard` | 1 | 1.0 |
| Snow Leopard Trophy | `SnowLeopard_Trophy` | 1 | 2.0 |
| Snow Pygmy Lop Trophy | `Rabbit_Variant_Snow_Trophy` | 1 | 4.0 |
| Snow Rabbit Trophy | `Arctic_Rabbit_Trophy` | 1 | 2.0 |
| Snow Stalker Trophy | `Snow_Stalker_Trophy` | 1 | 2.0 |
| Snow Wolf Rug | `Rug_Snow_Wolf` | 1 | 1.0 |
| Snow Wolf Trophy | `SnowWolf_Trophy` | 1 | 2.0 |
| Soap Dispensers | `Prop_Soap` | 10 | 2.0 |
| Specimen Sample | `Prop_Specimen` | 10 | 0.5 |
| Spider Trophy | `Spider_Trophy` | 1 | 4.0 |
| Stationeers BobbleHead | `Stationeers_Bobblehead` | 1 | 1.0 |
| Sterile Mortar & Pestle | `Prop_Mortar_And_Pestle` | 20 | 0.5 |
| Stirrer | `Prop_Stirrer` | 20 | 1.0 |
| Stomper Matriarch Trophy | `Stomper_Matriarch_Trophy` | 1 | 4.0 |
| Stomper Trophy | `Stomper_Trophy` | 1 | 4.0 |
| Stone Buffalo Statue | `Buffalo_Statue_Stone` | 1 | 1.0 |
| Stone Caveworm Statue | `Caveworm_Statue_Stone` | 1 | 1.0 |
| Stone Deer Statue | `Deer_Statue_Stone` | 1 | 1.0 |
| Stone Elephant Statue | `Elephant_Statue_Stone` | 1 | 1.0 |
| Stone Komodo Statue | `Komodo_Statue_Stone` | 1 | 1.0 |
| Stone Piranha Statue | `Piranha_Statue_Stone` | 1 | 1.0 |
| Stone Rabbit Statue | `Rabbit_Statue_Stone` | 1 | 1.0 |
| Stonejaw Trophy | `Stonejaw_Trophy` | 1 | 2.0 |
| Stool | `Prop_Stool` | 10 | 2.0 |
| Storca Trophy | `Storca_Trophy` | 1 | 2.5 |
| Stryder Trophy | `Stryder_Trophy` | 1 | 2.0 |
| Sulfur Worm Trophy | `SulfurWorm_Trophy` | 1 | 2.0 |
| Surgical Equipment | `Prop_Surgical_Equipment` | 20 | 1.0 |
| Surgical Masks | `Prop_Surgical_Masks` | 20 | 0.5 |
| Swamp Hopper Trophy | `Hopping_Creature_Swamp_Trophy` | 1 | 4.0 |
| Tan Laika Jumpsuit Trophy | `Dog_Trophy_D1_2` | 1 | 2.5 |
| Tan Laika Trophy | `Dog_Trophy_D1_1` | 1 | 2.5 |
| Teddy Bear | `Teddy_Bear` | 20 | 0.5 |
| Teenage Caveworm Trophy | `Teenage_Caveworm_Trophy` | 1 | 2.0 |
| Terrenus Trophy | `Terrenus_Trophy` | 1 | 2.0 |
| Test Tubes | `Prop_Test_Tube_Rack` | 20 | 0.5 |
| Thick Woven Rug | `Rug_Weave_Thick` | 1 | 1.0 |
| Thin Woven Rug | `Rug_Weave_Thin` | 1 | 1.0 |
| Toilet | `Toilet` | 5 | 10.0 |
| Trapjaw Trophy | `Ghost_Crocodile_Trophy` | 1 | 3.5 |
| Tusker Trophy | `Tusker_Trophy` | 1 | 2.0 |
| Ubis Trophy | `Ubis_Trophy` | 1 | 2.0 |
| Venomfly Trophy | `DragonFly_Trophy` | 1 | 4.0 |
| Vinyl Record | `Prop_Record` | 25 | 0.5 |
| Viscid Trophy | `Viscid_Trophy` | 1 | 2.0 |
| Wall Pipes | `Prop_Pipe1` | 10 | 2.0 |
| White Board | `Bunker_Whiteboard` | 1 | 5.0 |
| White Board (Subspecies 1341) | `Prop_Eden_Whiteboard` | 1 | 5.0 |
| White Chicken Trophy | `Chicken_Trophy_A3` | 1 | 1.0 |
| White Horse Trophy | `Horse_Trophy_A3` | 1 | 2.5 |
| Wild Boar Trophy | `Wild_Boar_Trophy` | 1 | 2.0 |
| Wildflower (Bluebell) | `Homestead_Wildflower_Bluebell` | 50 | 0.01 |
| Wildflower (Daisy) | `Homestead_Wildflower_Daisy` | 50 | 0.01 |
| Wildflower (Lavender) | `Homestead_Wildflower_Lavender` | 50 | 0.01 |
| Wildflower (Poppy) | `Homestead_Wildflower_Poppy` | 50 | 0.01 |
| Wildflower (Strawflower) | `Homestead_Wildflower_Strawflower` | 50 | 0.01 |
| Wolf Rug | `Rug_Conifer_Wolf` | 1 | 1.0 |
| Wolf Trophy | `ConiferWolf_Trophy` | 1 | 2.0 |
| Wood Buffalo Statue | `Buffalo_Statue_Wood` | 1 | 1.0 |
| Wood Deer Statue | `Deer_Statue_Wood` | 1 | 1.0 |
| Wood Painting | `Painting_Wood` | 1 | 2.0 |
| Wood Piranha Statue | `Piranha_Statue_Wood` | 1 | 1.0 |
| Wood Rabbit Statue | `Rabbit_Statue_Wood` | 1 | 1.0 |
| Wood Table | `Wood_Table` | 1 | 2.0 |
| Wooden Weapon Rack (Double) | `Homestead_Weapon_Rack` | 5 | 2.0 |
| Wooden Weapon Rack (Single) | `Homestead_Weapon_Rack_Single` | 5 | 2.0 |
| Woolly Mammoth Trophy | `Mammoth_Trophy` | 1 | 2.0 |
| Zebra Trophy | `Zebra_Trophy` | 1 | 2.0 |

## Acessórios / Anexos (102 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Advanced Attack Speed Attachment | `Tool_Attachment_Attack_Speed_2` | 1 | 1.0 |
| Advanced Copper Attachment | `Pickaxe_Attachment_Copper_Yield_2` | 1 | 1.0 |
| Advanced Economic Attachment | `Ranged_Weapon_Attachment_Economic_2` | 1 | 1.0 |
| Advanced Felling Damage Attachment | `Axe_Attachment_FellingDamage_2` | 1 | 1.0 |
| Advanced Flexible Frame Attachment | `Ranged_Weapon_Attachment_Lightweight_2` | 1 | 1.0 |
| Advanced Gold Attachment | `Pickaxe_Attachment_Gold_Yield_2` | 1 | 1.0 |
| Advanced Handcannon Attachment | `Ranged_Weapon_Attachment_Damage_2` | 1 | 1.0 |
| Advanced Iron Lure | `Advanced_Iron_Lure` | 1 | 0.25 |
| Advanced Lightweight Frame Attachment | `Ranged_Weapon_Attachment_Speed_2` | 1 | 1.0 |
| Advanced Melee Damage Attachment | `Tool_Attachment_Melee_Damage_2` | 1 | 1.0 |
| Advanced Narrow Barrel Attachment | `Ranged_Weapon_Attachment_Decreased_Spread_2` | 1 | 1.0 |
| Advanced Platinum Attachment | `Pickaxe_Attachment_Platnium_Yield_2` | 1 | 1.0 |
| Advanced Reaping Attachment | `Sickle_Attachment_Reaping_Yield_2` | 1 | 1.0 |
| Advanced Repair Speed Attachment | `Hammer_Attachment_Repair_2` | 1 | 1.0 |
| Advanced Scope Attachment | `Ranged_Weapon_Attachment_ADS_Upgrade_2` | 1 | 1.0 |
| Advanced Silencer Attachment | `Ranged_Weapon_Attachment_Stealth_2` | 1 | 1.0 |
| Advanced Sniper Scope Attachment | `Ranged_Weapon_Attachment_Sniper_2` | 1 | 1.0 |
| Advanced Strengthened Strings Attachment | `Ranged_Weapon_Attachment_Wear_2` | 1 | 1.0 |
| Advanced Titanium Attachment | `Pickaxe_Attachment_Titanium_2` | 1 | 1.0 |
| Advanced Trajectory Module Attachment | `Ranged_Weapon_Attachment_Ammo_Highlight_2` | 1 | 1.0 |
| Advanced Wood Yield Attachment | `Axe_Attachment_Felling_Yield_2` | 1 | 1.0 |
| Aluminum Attachment | `Pickaxe_Attachment_BauxiteYield_1` | 1 | 1.0 |
| Attack Speed Attachment | `Tool_Attachment_Attack_Speed_1` | 1 | 1.0 |
| Bark Lure | `Bark_Lure` | 1 | 0.25 |
| Barrel Widening Attachment | `Ranged_Weapon_Attachment_Increased_Spread` | 1 | 1.0 |
| Basic Scope Attachment | `Ranged_Weapon_Attachment_ADS_Upgrade_1` | 1 | 1.0 |
| Black Wolf Lure | `Black_Wolf_Lure` | 1 | 0.25 |
| Bleed Attachment | `Tool_Attachment_Bleed` | 1 | 1.0 |
| Blue Reed Lure | `Blue_Reed_Lure` | 1 | 0.25 |
| Bone Lure | `Bone_Lure` | 1 | 0.25 |
| Clay Attachment | `Sledgehammer_Attachment_ClayYield_1` | 1 | 1.0 |
| Copper Attachment | `Pickaxe_Attachment_Copper_Yield_1` | 1 | 1.0 |
| Cured Leather Lure | `Cured_Leather_Lure` | 1 | 0.25 |
| Dogtags Lure | `Dogtags_Lure` | 1 | 0.25 |
| Economic Attachment | `Ranged_Weapon_Attachment_Economic_1` | 1 | 1.0 |
| Electric Conversion Attachment | `Laser_Attachment_Electric` | 1 | 1.0 |
| Electroshock Attachment | `Tool_Attachment_Electroshock` | 1 | 1.0 |
| Extended Ammo Attachment | `Guns_Attachment_ExtendedAmmo_1` | 1 | 1.0 |
| Extended Chamber Attachment | `Ranged_Weapon_Attachment_Extended_Mag` | 1 | 1.0 |
| Felling Damage Attachment | `Axe_Attachment_FellingDamage_1` | 1 | 1.0 |
| Fiber Lure | `Fiber_Lure` | 1 | 0.25 |
| Fire Conversion Attachment | `Laser_Attachment_Fire` | 1 | 1.0 |
| Flexible Frame Attachment | `Ranged_Weapon_Attachment_Lightweight_1` | 1 | 1.0 |
| Frost Conversion Attachment | `Laser_Attachment_Frost` | 1 | 1.0 |
| Gold Attachment | `Pickaxe_Attachment_Gold_Yield_1` | 1 | 1.0 |
| Gold Ore Lure | `Gold_Ore_Lure` | 1 | 0.25 |
| Gorse Flower Lure | `Gorse_Flower_Lure` | 1 | 0.25 |
| Handcannon Attachment | `Ranged_Weapon_Attachment_Damage_1` | 1 | 1.0 |
| Hunting Scope Attachment | `Ranged_Weapon_Attachment_Animal_Highlight` | 1 | 1.0 |
| Iron Lure | `Iron_Lure` | 1 | 0.25 |
| Lightweight Frame Attachment | `Ranged_Weapon_Attachment_Speed_1` | 1 | 1.0 |
| Melee Damage Attachment | `Tool_Attachment_Melee_Damage_1` | 1 | 1.0 |
| Mining Radius Attachment | `Pickaxe_Attachment_MiningRadius_1` | 1 | 1.0 |
| Narrow Barrel Attachment | `Ranged_Weapon_Attachment_Decreased_Spread_1` | 1 | 1.0 |
| Obsidian Attachment | `Sledgehammer_Attachment_ObsidianYield_1` | 1 | 1.0 |
| Pistol Accuracy Attachment | `Pistol_Attachment_Accuracy_1` | 1 | 1.0 |
| Platinum Attachment | `Pickaxe_Attachment_Platnium_Yield_1` | 1 | 1.0 |
| Poison Attachment | `Tool_Attachment_Poison` | 1 | 1.0 |
| Poison Conversion Attachment | `Laser_Attachment_Poison` | 1 | 1.0 |
| Poison Sac Lure | `Poison_Sack_Lure` | 1 | 0.25 |
| Projectile Damage Attachment | `Guns_Attachment_Damage_1` | 1 | 1.0 |
| Prototype Notch Attachment | `Ranged_Weapon_Attachment_Additional_Projectiles` | 1 | 1.0 |
| Rapid Fire Attachment | `Ranged_Weapon_Attachment_Rapid_Fire` | 1 | 1.0 |
| Reaping Attachment | `Sickle_Attachment_Reaping_Yield_1` | 1 | 1.0 |
| Reed Flower Lure | `Reed_Flower_Lure` | 1 | 0.25 |
| Refined Wooden Lure | `Refined_Wood_Lure` | 1 | 0.25 |
| Repair Speed Attachment | `Hammer_Attachment_Repair_1` | 1 | 1.0 |
| Rifle Accuracy Attachment | `Rifle_Attachment_Accuracy_1` | 1 | 1.0 |
| Rotten Meat Lure | `Rotten_Meat_Lure` | 1 | 0.25 |
| Rubber Lure | `Rubber_Lure` | 1 | 0.25 |
| Scoria Attachment | `Sledgehammer_Attachment_ScoriaYield_1` | 1 | 1.0 |
| Scorpion Tail Lure | `Scorpion_Lure` | 1 | 0.25 |
| Seed Harvesting Attachment | `Seed_Harvester` | 1 | 15.0 |
| Seeding Cart Platinum Plow | `Plough_Platinum` | 1 | 15.0 |
| Seeding Cart Steel Plow | `Plough_Steel` | 1 | 15.0 |
| Seeding Cart Titanium Plow | `Plough_Titanium` | 1 | 15.0 |
| Silencer Attachment | `Ranged_Weapon_Attachment_Stealth_1` | 1 | 1.0 |
| Slow Attachment | `Sledgehammer_Attachment_Slow_1` | 1 | 1.0 |
| Sniper Scope Attachment | `Ranged_Weapon_Attachment_Sniper_1` | 1 | 1.0 |
| Specialist Aluminum Attachment | `Pickaxe_Attachment_BauxiteYield_2` | 1 | 1.0 |
| Specialist Clay Attachment | `Sledgehammer_Attachment_ClayYield_2` | 1 | 1.0 |
| Specialist Extended Ammo Attachment | `Guns_Attachment_ExtendedAmmo_2` | 1 | 1.0 |
| Specialist Mining Radius Attachment | `Pickaxe_Attachment_MiningRadius_2` | 1 | 1.0 |
| Specialist Obsidian Attachment | `Sledgehammer_Attachment_ObsidianYield_2` | 1 | 1.0 |
| Specialist Pistol Accuracy Attachment | `Pistol_Attachment_Accuracy_2` | 1 | 1.0 |
| Specialist Projectile Damage Attachment | `Guns_Attachment_Damage_2` | 1 | 1.0 |
| Specialist Rifle Accuracy Attachment | `Rifle_Attachment_Accuracy_2` | 1 | 1.0 |
| Specialist Scoria Attachment | `Sledgehammer_Attachment_ScoriaYield_2` | 1 | 1.0 |
| Specialist Slow Attachment | `Sledgehammer_Attachment_Slow_2` | 1 | 1.0 |
| Specialist Tool Durability Attachment | `Tool_Attachment_Durability_2` | 1 | 1.0 |
| Specialist Tool Stamina Attachment | `Tool_Attachment_StaminaCost_2` | 1 | 1.0 |
| Strengthened Strings Attachment | `Ranged_Weapon_Attachment_Wear_1` | 1 | 1.0 |
| Threshing Attachment | `Sickle_Attachment_Harvest_Seeds` | 1 | 1.0 |
| Titanium Attachment | `Pickaxe_Attachment_Titanium_1` | 1 | 1.0 |
| Tool Durability Attachment | `Tool_Attachment_Durability_1` | 1 | 1.0 |
| Tool Stamina Attachment | `Tool_Attachment_StaminaCost_1` | 1 | 1.0 |
| Trajectory Module Attachment | `Ranged_Weapon_Attachment_Ammo_Highlight_1` | 1 | 1.0 |
| White Jelly Lure | `White_Jelly_Lure` | 1 | 0.25 |
| Wolf Lure | `Wolf_Lure` | 1 | 0.25 |
| Wood Yield Attachment | `Axe_Attachment_Felling_Yield_1` | 1 | 1.0 |
| Wooden Lure  | `Wood_Lure` | 1 | 0.25 |
| Yeast Lure | `Yeast_Lure` | 1 | 0.25 |

## Vestígios e Troféus (122 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Antelope Vestige | `Desert_Deer_Head` | 5 | 2.0 |
| Arctic Scorpion Vestige | `Arctic_Scorpion_Head` | 5 | 2.0 |
| Arctic Skulk Vestige | `Orka_Arctic_Head` | 5 | 2.0 |
| Arctic Vesper Vestige | `Arctic_Bat_Head` | 5 | 1.0 |
| Arid Striker Vestige | `Desert_Striker_Head` | 5 | 1.0 |
| Ashen Drake Vestige | `Ashen_Drake_Head` | 5 | 1.0 |
| Bear Vestige | `Bear_Head` | 5 | 2.0 |
| Black Cat Vestige | `Cat_Head_A3` | 5 | 1.0 |
| Black Chicken Vestige | `Chicken_Head_A2` | 5 | 0.5 |
| Black Horse Vestige | `Horse_Head_A2` | 5 | 1.0 |
| Black Jaguar Vestige | `Jaguar_Black_Head` | 5 | 1.0 |
| Black Wolf Vestige | `Alphawolf_Head` | 5 | 1.0 |
| Blueback Vestige | `Blueback_Head` | 5 | 2.0 |
| Brown Horse Vestige | `Horse_Head_A1` | 5 | 1.0 |
| Brown Laika Vestige | `Dog_Head_D2` | 5 | 0.5 |
| Buffalo Vestige | `Buffalo_Head` | 5 | 1.5 |
| Bull Vestige | `Bull_Head` | 5 | 1.5 |
| Calf Vestige | `Calf_Head` | 5 | 1.5 |
| Cave Vesper Vestige | `Cave_Bat_Head` | 5 | 1.0 |
| Caveworm Vestige | `Caveworm_Head` | 5 | 1.0 |
| Chala Vestige | `Chala_Head` | 5 | 1.0 |
| Chamois Vestige | `Chamios_Head` | 5 | 1.0 |
| Chick Vestige | `Chick_Head` | 5 | 0.5 |
| Chocolate Labrador Vestige | `Dog_Head_A2` | 5 | 1.0 |
| Clicker Vestige | `Giant_Roach_Head` | 5 | 1.0 |
| Columbian Mammoth Vestige | `Desert_Mammoth_Head` | 5 | 2.0 |
| Cougar Vestige | `Cougar_Head` | 5 | 1.0 |
| Cow Vestige | `Cow_Head` | 5 | 1.5 |
| Crocodile Vestige | `Crocodile_Head` | 5 | 2.0 |
| Deer Vestige | `Deer_Head` | 5 | 1.0 |
| Drac Vestige | `Drac_Head` | 5 | 1.0 |
| Draven Vestige | `Chew_Head` | 5 | 1.0 |
| Dreadwing Vestige | `Dreadwing_Head` | 5 | 0.5 |
| Dribbo Vestige | `Mini_Hippo_Head` | 5 | 1.0 |
| Drosik Vestige | `Tundra_Deer_Head` | 5 | 1.0 |
| Dune Raptor Vestige | `Raptor_Desert_Head` | 5 | 1.0 |
| Elephant Vestige | `Elephant_Head` | 5 | 2.0 |
| Equix Vestige | `Equix_Head` | 5 | 1.0 |
| Frostfoot Vestige | `Yeti_Head` | 5 | 1.0 |
| Garganutan Prime Vestige | `Ape_Head` | 5 | 1.0 |
| Garganutan Vestige | `Juvenile_Ape_Head` | 5 | 1.0 |
| Geothermal Spider Vestige | `Geothermal_Spider_Head` | 5 | 1.0 |
| German Shepherd Vestige | `Dog_Head_B1` | 5 | 1.0 |
| Giant Scorpion Vestige | `Scorpion_Boss_Head` | 5 | 5.0 |
| Glaci Vestige | `Snow_Slug_Head` | 5 | 1.0 |
| Golden Labrador Vestige | `Dog_Head_A1` | 5 | 1.0 |
| Grey Tabby Cat Vestige | `Cat_Head_A1` | 5 | 1.0 |
| Gribbler Vestige | `Tundra_Monkey_Head` | 5 | 1.0 |
| Hammerhead Vestige | `Slug_Head` | 5 | 1.0 |
| Hopper Vestige | `Hopping_Creature_Head` | 5 | 1.0 |
| Hyena Vestige | `DesertWolf_Head` | 5 | 1.0 |
| Ignari Vestige | `Lava_Viscid_Head` | 5 | 1.0 |
| Jaguar Vestige | `Jaguar_Head` | 5 | 1.0 |
| Kea Vestige | `Kea_Head` | 5 | 0.5 |
| Kiwi Vestige | `Kiwi_Head` | 5 | 1.0 |
| Komodo Vestige | `Komodo_Head` | 5 | 1.0 |
| Korrin Vestige | `Bounder_Head` | 5 | 1.0 |
| Lamb Vestige | `Lamb_Head` | 5 | 0.5 |
| Landshark Vestige | `Land_Shark_Head` | 5 | 5.0 |
| Lava Broodling Vestige | `Lava_Broodling_Head` | 5 | 1.0 |
| Lava Hunter Vestige | `Lava_Hunter_Head` | 5 | 5.0 |
| Moa Vestige | `Moa_Head` | 5 | 1.0 |
| Needler Vestige | `Needler_Head` | 5 | 2.0 |
| Orange Tabby Cat Vestige | `Cat_Head_A2` | 5 | 1.0 |
| Panda German Shepherd Vestige | `Dog_Head_B2` | 5 | 1.0 |
| Pig Vestige | `Pig_Head` | 5 | 0.5 |
| Piglet Vestige | `Piglet_Head` | 5 | 0.5 |
| Polar Bear Vestige | `PolarBear_Head` | 5 | 2.0 |
| Pronghorn Vestige | `Pronghorn_Head` | 5 | 1.0 |
| Pug Vestige | `Dog_Head_C1` | 5 | 0.5 |
| Pygmy Lop Vestige | `Rabbit_Varient_Head` | 5 | 0.5 |
| Quarrite Vestige | `Rock_Golem_Juvenile_Head` | 5 | 1.0 |
| Rabbit Vestige | `Rabbit_Head` | 5 | 0.5 |
| Ram Vestige | `Ram_Head` | 5 | 1.5 |
| Raptor Vestige | `Raptor_Head` | 5 | 1.0 |
| Ravager Vestige | `Flying_Tank_Head` | 5 | 1.0 |
| Reaver Vestige | `Reaver_Head` | 5 | 2.0 |
| Red Chicken Vestige | `Chicken_Head` | 5 | 0.5 |
| Redback Vestige | `Redback_Head` | 5 | 2.0 |
| Rimetusk Matriarch Vestige | `IceMammoth_Head` | 5 | 2.0 |
| Rimetusk Vestige | `Snow_Mammoth_Head` | 5 | 1.0 |
| Roat Vestige | `Roat_Head` | 5 | 0.5 |
| Rooster Vestige | `Rooster_Head` | 5 | 1.5 |
| Sandhorn Vestige | `Flightless_Tank_Head` | 5 | 1.0 |
| Sandworm Vestige | `Sandworm_Head` | 5 | 1.0 |
| Sandwyrm Queen Vestige | `Sandwyrm_Queen_Head` | 5 | 2.0 |
| Scorpion Vestige | `Scorpion_Head` | 5 | 2.0 |
| Scuttler Vestige | `Sandscuttle_Head` | 5 | 1.0 |
| Shaggy Zebra Vestige | `Wooly_Zebra_Head` | 5 | 2.0 |
| Sheep Vestige | `Sheep_Head` | 5 | 1.0 |
| Skulmutt Prime Vestige | `Mange_Wolf_Alpha_Head` | 5 | 1.0 |
| Skulmutt Vestige | `Mange_Wolf_Head` | 5 | 1.0 |
| Slinker Vestige | `Slinker_Head` | 5 | 1.0 |
| Snow Leopard Vestige | `SnowLeopard_Head` | 5 | 1.0 |
| Snow Pygmy Lop Vestige | `Rabbit_Variant_Snow_Head` | 5 | 1.0 |
| Snow Rabbit Vestige | `Snow_Rabbit_Head` | 5 | 0.5 |
| Snow Stalker Vestige | `Snow_Stalker_Head` | 5 | 1.0 |
| Snow Wolf Vestige | `SnowWolf_Head` | 5 | 1.0 |
| Spider Vestige | `Spider_Head` | 5 | 1.0 |
| Stomper Matriarch Vestige | `Stomper_Matriarch_Head` | 5 | 1.0 |
| Stomper Vestige | `Stomper_Head` | 5 | 1.0 |
| Stonejaw Vestige | `Stonejaw_Head` | 5 | 2.0 |
| Storca Vestige | `Storca_Head` | 5 | 1.0 |
| Stryder Vestige | `Stryder_Head` | 5 | 1.0 |
| Sulfur Vesper Vestige | `Geothermal_Bat_Head` | 5 | 1.0 |
| Sulfur Worm Vestige | `SulfurWorm_Head` | 5 | 1.0 |
| Swamp Hopper Vestige | `Hopping_Creature_Swamp_Head` | 5 | 1.0 |
| Tan Laika Vestige | `Dog_Head_D1` | 5 | 0.5 |
| Teenage Caveworm Vestige | `Teenage_Caveworm_Head` | 5 | 2.0 |
| Terrenus Vestige | `Terrenus_Head` | 5 | 2.0 |
| Trapjaw Vestige | `Ghost_Crocodile_Head` | 5 | 1.0 |
| Tusker Vestige | `Tusker_Head` | 5 | 2.0 |
| Ubis Vestige | `Ubis_Head` | 5 | 1.0 |
| Unstable Quarrite Vestige | `Rock_Golem_Head` | 5 | 1.0 |
| Venomfly Vestige | `DragonFly_Head` | 5 | 1.0 |
| Viscid Vestige | `Swamp_Viscid_Head` | 5 | 1.0 |
| White Chicken Vestige | `Chicken_Head_A3` | 5 | 0.5 |
| White Horse Vestige | `Horse_Head_A3` | 5 | 1.0 |
| Wild Boar Vestige | `WildBoar_Head` | 5 | 2.0 |
| Wolf Vestige | `ConiferWolf_Head` | 5 | 1.0 |
| Woolly Mammoth Vestige | `Mammoth_Head` | 5 | 2.0 |
| Zebra Vestige | `Zebra_Head` | 5 | 2.0 |

## Energia e Utilidades (26 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Advanced Battery Rack | `Battery_Shelf_T4` | 1 | 60.0 |
| Basic Battery Rack | `Battery_Shelf_T3` | 1 | 15.0 |
| Battery Cavelight | `CaveLight` | 1 | 2.0 |
| Battery Spotlight | `CaveSpotLight` | 1 | 5.0 |
| Biofuel | `FieldGuide_Biofuel` | 1 | 0.1 |
| Biofuel Water Pump | `Biofuel_Water_Pump` | 1 | 20.0 |
| Carbonweave Backpack | `SandArmor_Backpack` | 1 | 1.0 |
| Crude Oil | `FieldGuide_CrudeOil` | 1 | 0.1 |
| Crude Oil Refiner | `Crude_Oil_Refiner` | 1 | 10.0 |
| Electric Water Pump | `Water_Pump` | 1 | 10.0 |
| Electric Water Purifier | `Water_Purifier_T4` | 1 | 5.0 |
| Electricity | `FieldGuide_Electricity` | 1 | 0.1 |
| Homestead Water Tank | `Homestead_Water_Tank` | 1 | 50.0 |
| Lava Hunter Heated Backpack | `Lava_Hunter_Backpack` | 1 | 0.5 |
| Lithium Shield | `Lithium_Shield` | 1 | 2.0 |
| Localized Terraforming Device | `Enzyme_Cannon_Hub` | 1 | 30.0 |
| Milk | `FieldGuide_Milk` | 1 | 0.1 |
| Natural Oil Refiner | `Natural_Oil_Refiner` | 1 | 40.0 |
| Oxygen | `FieldGuide_Oxygen` | 1 | 0.1 |
| Portable Icebox Backpack | `Icebox_Backpack` | 1 | 0.5 |
| Pump Jack | `Pump_Jack` | 1 | 20.0 |
| Refined Oil | `FieldGuide_RefinedOil` | 1 | 0.1 |
| Water | `FieldGuide_Water` | 1 | 0.1 |
| Water Barrel | `Water_Barrel` | 1 | 10.0 |
| Water Borer | `Water_Borer` | 1 | 20.0 |
| Water Purifier | `Water_Purifier_T2` | 1 | 2.5 |

## Itens de Missão (28 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Aerosol Emitter | `Mission_Aerosol_Emitter` | 1 | 5.0 |
| Alternator | `Mission_Alternator` | 1 | 50.0 |
| Biological Containment Power Source | `Mission_Power_Source` | 1 | 1.0 |
| Ethanol | `Mission_Ethanol` | 30 | 1.0 |
| Experimental Goop | `ExperimentalGoop` | 10 | 2.5 |
| Full Enzyme Containment Unit | `Mission_Full_Enzyme_Container` | 1 | 5.0 |
| Layered Plating | `Layered_Plating` | 1 | 90.0 |
| Liquid Solution | `Mission_Liquid_Deployment` | 1 | 0.25 |
| Makeshift Kiwi Nest | `Kiwi_Nest` | 1 | 1.0 |
| Mammoth Bio-Sample | `Mission_MammothBioSample` | 1 | 5.0 |
| MK-200 Weaponized Laser (Repaired) | `Mission_Prototype_Laser` | 1 | 2.0 |
| Monitoring Pylon | `Mission_Monitoring_Pylon` | 1 | 2.0 |
| Neurotoxic Aerosol | `Mission_Neurotoxic_Aerosol` | 1 | 1.5 |
| Partially Digested Enzymes | `Digested_Enzymes` | 20 | 0.2 |
| Prototype Portable Beacon | `Dynamic_Mission_Beacon` | 1 | 10.0 |
| Prototype Threat Tracker | `Prototype_Boss_Tracker` | 1 | 10.0 |
| Radiator | `Mission_Radiator` | 1 | 50.0 |
| Stasis Bag | `Mission_Stasis_Bag` | 5 | 1.0 |
| Stasis Bag (Agent Bob) | `Stasis_Bag_Full_ELY4_NPC1` | 1 | 75.0 |
| Stasis Bag (Associate Researcher Felix) | `Mission_Stasis_Bag_Full_IM_Researcher2` | 1 | 75.0 |
| Stasis Bag (Drill Chief Biggs) | `Mission_Stasis_Bag_Full_RG_NPC3` | 1 | 75.0 |
| Stasis Bag (Excavator Wedge) | `Mission_Stasis_Bag_Full_RG_NPC4` | 1 | 75.0 |
| Stasis Bag (Foreman Voss) | `Mission_Stasis_Bag_Full_RG_NPC1` | 1 | 75.0 |
| Stasis Bag (Iris) | `Mission_Stasis_Bag_Full_Iris` | 1 | 75.0 |
| Stasis Bag (Lieutenant Washington) | `Mission_Stasis_Bag_Full_NPC_5` | 1 | 75.0 |
| Stasis Bag (Private Simmons) | `Mission_Stasis_Bag_Full_NPC_4` | 1 | 75.0 |
| Stasis Bag (Technician Harken) | `Mission_Stasis_Bag_Full_RG_NPC2` | 1 | 75.0 |
| Tris-EDTA Buffer  | `Mission_Buffer` | 30 | 1.0 |

## Outros (231 itens)

| Nome (em jogo) | Nome interno | Pilha máx. | Peso (kg) |
|---|---|---|---|
| Abandoned Audio Log | `Mission_AudioLog_Prometheus_3` | 1 | 0.5 |
| Abyssal Oxite | `Mission_STYX_D_Research2_Abyssal_Oxite` | 50 | 0.4 |
| Acoustic Cavitation Cannon | `Mission_Sonic_Disrupter` | 1 | 1.0 |
| Advanced Aquarium | `Advanced_Aquarium` | 1 | 2.5 |
| Advanced Creature Deterrent | `Spawn_Blocker_T3` | 1 | 8.0 |
| Advanced Fishing Trap | `Advanced_Fishing_Trap` | 1 | 1.0 |
| Animal Fish Gruel | `Animal_Gruel_Fish` | 25 | 0.05 |
| Animal Fruit Gruel | `Animal_Gruel_Fruit` | 25 | 0.05 |
| Animal Meat Gruel | `Animal_Gruel_Meat` | 25 | 0.05 |
| Animal Vegetable Gruel | `Animal_Gruel_Vegetable` | 25 | 0.05 |
| Aquarium | `Aquarium` | 1 | 1.0 |
| Arctic Animal Feed | `Food_Animal_Feed_Pumpkin` | 100 | 0.5 |
| Automated Defense System: Flamethrower | `Turret_Flamethrower` | 1 | 20.0 |
| Automated Defense System: Pistol | `Turret_Pistol` | 1 | 20.0 |
| Automated Defense System: Tesla Coil | `Tesla_Coil` | 1 | 20.0 |
| Basic Fishing Trap | `Basic_Fishing_Trap` | 1 | 1.0 |
| Bio-Warhead | `Bio_Needle` | 1 | 1.0 |
| Biochip (Experiment 002) | `Mission_Biochip_A` | 1 | 0.2 |
| Biochip (Experiment 003) | `Mission_Biochip_B` | 1 | 0.2 |
| Biochip (Experiment 004) | `Mission_Biochip_C` | 1 | 0.2 |
| Biofuel Deep-Mining Drill | `Deep_Mining_Drill_Biofuel` | 1 | 10.0 |
| Biofuel Drill | `Faction_Mission_Drill` | 1 | 2.0 |
| Biotag | `Mission_Biotag` | 50 | 0.2 |
| Black Wolf Forest Module | `Black_Wolf_Module` | 1 | 0.1 |
| Black Wolf Shield | `Black_Wolf_Shield` | 1 | 1.0 |
| Blackmarket Automative Defence Turret (Flamethrower) | `Enemy_Turret_Flamethrower` | 1 | 20.0 |
| Blackmarket Automative Defence Turret (Pistol) | `Enemy_Turret_Pistol` | 1 | 20.0 |
| Bone Shield | `Shield_Bone` | 1 | 1.5 |
| Bramble Bush | `Bramble` | 20 | 1.0 |
| Broken MK-200 Laser Parts | `Mission_Broken_Prototype_Laser` | 1 | 2.0 |
| Broken Solar Panel | `Mission_Broken_Solar_Panel` | 1 | 2.0 |
| Buffalo Fertility Serum | `Fertility_Serum_Buffalo` | 10 | 0.05 |
| Bull Fertility Serum | `Fertility_Serum_Cow` | 10 | 0.05 |
| Bullseye Target | `Target_Bullseye` | 1 | 12.5 |
| Bunker Light | `Basic_Ceiling_Light` | 10 | 0.75 |
| C0NT4CT Device | `Mission_Device` | 1 | 10.0 |
| Caged Light | `Single_Ceiling_Light` | 10 | 0.5 |
| Carbon Fiber Round Shield | `Shield_Carbon` | 1 | 1.5 |
| Charging Station | `Charging_Device` | 1 | 10.0 |
| Composite Dropship Recall Beacon | `Dropship_Grenade_T4` | 1 | 0.5 |
| Composite Tactical Shield | `Shield_Composites` | 1 | 1.5 |
| Concrete Gate Fortification | `Fortification_Concrete_Gate` | 20 | 4.0 |
| Concrete Spikes Fortification | `Fortification_Concrete_Spikes` | 20 | 4.0 |
| Concrete Walkway Fortification | `Fortification_Concrete_Walkway` | 20 | 4.0 |
| Concrete Walkway Fortification | `Fortification_Concrete_Platform` | 20 | 4.0 |
| Concrete Wall Fortification | `Fortification_Concrete_Wall` | 20 | 4.0 |
| Containment Unit | `Mission_STYX_D_Research2_Containment` | 1 | 1.0 |
| Cryo Landmine | `Landmine_Freeze` | 1 | 1.0 |
| Crystallised Ruby | `Ruby_Ore` | 100 | 0.25 |
| Damaged Audio Log | `Mission_AudioLog_Prometheus_1` | 1 | 0.5 |
| Damaged Audio Log | `Mission_AudioLog_Prometheus_2` | 1 | 0.5 |
| Damaged Bio-weapon Sample | `Mission_Damaged_Bioweapon_Sample` | 100 | 0.25 |
| Damaged Guidance System Part | `Mission_Ship_Navigation_Part` | 1 | 0.01 |
| Damaged Gyroscope | `Mission_Ship_Gyro_Broken` | 1 | 0.01 |
| Damaged Thruster Part | `Mission_Ship_Thruster_Part` | 1 | 0.01 |
| Dehumidifier | `Dehumidifier` | 1 | 20.0 |
| Desert Animal Feed | `Food_Animal_Feed_Squash` | 100 | 0.5 |
| Device Component | `FactionMission_Tech1` | 1 | 1.0 |
| Device Component | `FactionMission_Tech2` | 1 | 1.0 |
| Device Component | `FactionMission_Tech3` | 1 | 1.0 |
| Digested Biomatter Sample | `Mission_Digested_Biomatter_Sample` | 100 | 0.25 |
| Dirt Mound | `Dirt_Mound` | 10 | 0.25 |
| DNA Pellet Solution | `Mission_DNA_Pellet` | 1 | 0.01 |
| DNA Supernatant Solution | `Mission_DNA_Supernatant` | 1 | 0.01 |
| Eden Orbital Exchange Interface | `EdenStation_OEI` | 1 | 10.0 |
| Electric Deep-Mining Drill | `Deep_Mining_Drill_Electric` | 1 | 10.0 |
| Electric Dehumidifier | `Electric_Dehumidifier_V2` | 1 | 20.0 |
| Empty Enzyme Containment Unit | `Mission_Empty_Enzyme_Container` | 1 | 1.0 |
| Encrypted Satellite Upgrade | `Mission_Communication_Device_T4` | 1 | 10.0 |
| Endurance Animal Feed | `Food_Animal_Feed_Corn` | 100 | 0.5 |
| Environmental Monitoring Station | `Mission_STYX_D_Research2_Bomb` | 1 | 1.0 |
| Enzyme Propagation Hub | `Mission_Enzyme_Propogation_Hub` | 1 | 2.0 |
| Enzyme Propagation Unit | `Mission_Enzyme_Propogation_Unit` | 1 | 2.0 |
| Enzyme Propagation Unit | `Mission_Enzyme_Propogation_Unit_Craftable` | 1 | 2.0 |
| Enzyme Virus | `Mission_Enzyme_Virus` | 100 | 0.2 |
| Experimental Sonic Device | `SonicDevice` | 1 | 10.0 |
| Exposed Light | `Exposed_Ceiling_Light` | 10 | 0.25 |
| Flat Solar Panel | `Flat_Solar_Panel` | 5 | 10.0 |
| Flora Biomatter Sample | `Mission_Flora_Biomatter_Sample` | 100 | 0.25 |
| Frosted Light | `Exposed_Ceiling_Light_Foggy` | 10 | 0.25 |
| Frozen Mammoth Sample | `Faction_Mission_Frozen_Mammoth_Sample` | 100 | 0.25 |
| Garganutan Damage Module | `Ape_Module` | 1 | 0.5 |
| Garganutan Sonic Attractor | `Ape_Attractor` | 1 | 5.0 |
| Garganutan Tissue Sample | `Mission_DNA_TissueSample` | 1 | 0.01 |
| Geneticially Modified Kiwi Egg | `Mission_Kiwi_Egg` | 1 | 0.5 |
| Geo-Crystal | `Mission_Delivery_Crystal` | 100 | 0.4 |
| Geo-Station | `Survey_Radar` | 1 | 2.0 |
| Giant Scorpion Thorn Module | `Scorpion_Module` | 1 | 0.1 |
| Glass Milk Bottle | `Milk_Bottle_Glass` | 1 | 0.5 |
| Gribbler Bait | `CreatureBait_Tundra_Monkey` | 10 | 0.2 |
| Ground Penetrating Vapor Laser | `Faction_Mission_DownLaser` | 1 | 2.0 |
| Hammerhead Swamp Module | `Slug_Module` | 1 | 0.5 |
| Heated Lysate Solution | `Mission_DNA_Heated_Lysate` | 1 | 0.01 |
| Heating Device Arm | `Mission_Laser_Part_2` | 1 | 1.0 |
| Heating Device Base | `Mission_Laser_Part_1` | 1 | 1.0 |
| Heating Device Laser | `Mission_Laser_Part_3` | 1 | 1.0 |
| Heavy Air Conditioner | `Cooler_Large` | 1 | 20.0 |
| Heavy Heater  | `Heater_Large` | 1 | 20.0 |
| Hitching Post | `Hitching_Post` | 5 | 0.5 |
| Hitching Rope | `Hitching_Rope` | 10 | 0.15 |
| Homogenized Sample | `Mission_DNA_HomogenizedSample` | 1 | 0.01 |
| Hydro-scanner | `Faction_Mission_AquaScanner` | 1 | 8.0 |
| Hyena Bait | `CreatureBait_Hyena` | 10 | 0.2 |
| Ice Armor Fragment | `IceMammoth_Fractured_Ice` | 25 | 1.0 |
| Ice Borer | `Ice_Borer` | 1 | 10.0 |
| Incendiary Landmine | `Landmine_Burn` | 1 | 1.0 |
| Infrasonic Relay Upgrade | `Mission_Communication_Device_T3` | 1 | 10.0 |
| Ionic Dust | `Terraforming_Dust` | 500 | 0.01 |
| Iron Bucket | `Iron_Bucket` | 1 | 1.5 |
| Large Advanced Aquarium | `Large_Advanced_Aquarium` | 1 | 5.0 |
| Larkwell Martinez Device | `FactionMission_TechRecombined` | 1 | 1.0 |
| Lava Hunter Bomber Mine | `Lava_Hunter_Mine` | 1 | 1.0 |
| Lava Hunter Volcanic Module | `Lava_Hunter_Module` | 1 | 0.5 |
| Lithium Ore | `Lithium_Ore` | 100 | 0.4 |
| Lysate Solution | `Mission_DNA_Lysate` | 1 | 0.01 |
| Makeshift Landmine | `Landmine` | 20 | 1.0 |
| Makeshift Radio | `MakeshiftRadio` | 1 | 10.0 |
| Makeshift Radio Amplifier | `Mission_Makeshift_Beacon` | 1 | 10.0 |
| Mammoth Sample | `Faction_Mission_Mammoth_Sample` | 100 | 0.25 |
| Milk Pail | `Milk_Bucket` | 1 | 0.5 |
| Mixed Buffer Solution | `Mission_DNA_MixedBufferSolution` | 1 | 0.01 |
| Moa Fertility Serum | `Fertility_Serum_Moa` | 10 | 0.05 |
| Monitoring Device | `Mission_STYX_D_Research2_Scanner` | 1 | 1.0 |
| Monitoring Station Components | `Mission_STYX_D_Research2_BombParts` | 1 | 1.0 |
| Mountaineering Animal Feed | `Food_Animal_Feed_Mushroom` | 100 | 0.5 |
| MXC Gyroscope MK-IV (Repaired) | `Mission_Ship_Gyro` | 1 | 0.01 |
| MXC Navigation MK-I (Repaired) | `Mission_Ship_Navigation` | 1 | 0.01 |
| MXC Thruster MK-I (Repaired) | `Mission_Ship_Thruster` | 1 | 0.01 |
| MXC Thruster MK-I (Salvaged) | `Mission_Ship_Thruster_Salvaged` | 1 | 0.01 |
| NOREX Boss Tracker Upgrade | `Great_Hunt_Device` | 1 | 10.0 |
| Noxious Crust (Various Ores) | `FieldGuide_PyriticCrust` | 50 | 0.25 |
| Omni Animal Feed | `Food_Animal_Feed_High_Quality` | 25 | 0.05 |
| Orbital Exchange Interface | `Exotic_Delivery_Interface` | 1 | 10.0 |
| Organic Analyzer | `Mission_Organic_Analyzer` | 1 | 10.0 |
| Organic Matter Analyzer | `Mission_Analyzer_Egg` | 1 | 2.0 |
| Partially Frozen Audio Log | `Mission_AudioLog_Prometheus_4` | 1 | 0.5 |
| Pig Fertility Serum | `Fertility_Serum_Pig` | 10 | 0.05 |
| Platinum Shield | `Shield_Platinum` | 1 | 2.0 |
| Poison Gas Landmine | `Landmine_Poison` | 1 | 1.0 |
| Poison Lair Sample | `Mission_Poison_Lair_Sample` | 1 | 0.01 |
| Portable Beacon | `Portable_Beacon` | 1 | 10.0 |
| Powered Creature Deterrent | `Spawn_Blocker_T4` | 1 | 10.0 |
| Precipitated DNA Solution | `Mission_DNA_Precipitated` | 1 | 0.01 |
| Prototype Battery | `Mission_Prototype_Battery` | 1 | 10.0 |
| Prototype Hoverframe | `Speeder_Kit` | 1 | 50.0 |
| Prototype Trail Beacon | `Trail_Beacon` | 100 | 0.5 |
| Prototype Trail Beacon Tool | `Beacon_Tool` | 1 | 1.0 |
| Prototype UDA Communication Upgrade | `Mission_Communication_Blueprint_T2` | 1 | 0.25 |
| Quarrite Armor Fragment (Coal) | `Rock_Golem_Juvenile_Armor_Coal` | 5 | 1.0 |
| Quarrite Armor Fragment (Copper) | `Rock_Golem_Juvenile_Armor_Copper` | 5 | 1.0 |
| Quarrite Armor Fragment (Exotic) | `Rock_Golem_Juvenile_Armor_Exotic` | 5 | 1.0 |
| Quarrite Armor Fragment (Gold) | `Rock_Golem_Juvenile_Armor_Gold` | 5 | 1.0 |
| Quarrite Armor Fragment (Iron) | `Rock_Golem_Juvenile_Armor_Iron` | 5 | 1.0 |
| Quarrite Armor Fragment (Oxite) | `Rock_Golem_Juvenile_Armor_Oxite` | 5 | 1.0 |
| Quarrite Caltrops | `Rock_Golem_Grenade_Caltrops` | 1 | 0.05 |
| Quarrite Mining Module | `Rock_Golem_Module` | 1 | 0.5 |
| Radioactive Waste | `Radioactive_Waste` | 100 | 0.5 |
| Ram Fertility Serum | `Fertility_Serum_Sheep` | 10 | 0.05 |
| Raptor Fertility Serum | `Fertility_Serum_Raptor` | 10 | 0.05 |
| Refined Wood Platform Fortification | `Fortification_Stone_Platform` | 20 | 3.0 |
| Refined Wood Spikes Fortification | `Fortification_Stone_Spikes` | 20 | 3.0 |
| Refined Wood Walkway Fortification | `Fortification_Stone_Walkway` | 20 | 3.0 |
| Research Incubator | `Mission_Incubator` | 1 | 10.0 |
| Rimetusk Arctic Module | `IceMammoth_Module` | 1 | 0.5 |
| Rimetusk Shield | `IceMammoth_Shield` | 1 | 1.5 |
| Rooster Fertility Serum | `Fertility_Serum_Chicken` | 10 | 0.05 |
| Ruined DNA Sample | `Mission_DNA_Ruined` | 100 | 0.01 |
| Sandworm Desert Module | `Sandworm_Module` | 1 | 0.1 |
| Scalpel | `Mission_DNA_Scalpel` | 1 | 0.01 |
| Scorpion Pincer | `Scorpion_Pincer` | 10 | 1.0 |
| Scorpion Tail | `Scorpion_Tail` | 10 | 1.0 |
| Seed Animal Feed | `Food_Animal_Feed` | 100 | 0.05 |
| Seed Animal Feed | `Food_Animal_Feed_Speed` | 100 | 0.05 |
| Seed Animal Feed | `Food_Animal_Feed_CarryWeight` | 100 | 0.05 |
| Shackles | `Mission_Shackles` | 10 | 2.0 |
| Shrouded Light | `Shroud_Light` | 10 | 2.5 |
| Silage | `Animal_Silage` | 50 | 0.05 |
| Simple Creature Deterrent | `Spawn_Blocker_T2` | 1 | 5.0 |
| Skulk Bait | `CreatureBait_Orka` | 10 | 0.2 |
| Slinker Fertility Serum | `Fertility_Serum_Slinker` | 10 | 0.05 |
| Snare Trap | `Snare_Trap` | 1 | 2.5 |
| Solar Panel | `Solar_Panel` | 1 | 10.0 |
| Spotlight | `Spotlight` | 10 | 3.0 |
| Sprinters Animal Feed | `Food_Animal_Feed_Carrot` | 100 | 0.5 |
| Stabilization Catalyst | `Mission_STYX_D_Research2_Catalyst` | 1 | 1.0 |
| Stable Garganutan DNA Sample | `Mission_DNA_Sample` | 1 | 0.01 |
| Stale Animal Gruel | `Animal_Gruel_Rotten` | 25 | 0.05 |
| Steel Heater Shield | `Shield_Steel` | 1 | 2.5 |
| Stone Gate Fortification | `Fortification_Stone_Gate` | 20 | 3.0 |
| Stone Wall Fortification | `Fortification_Stone_Wall` | 20 | 3.0 |
| Storca Bait | `CreatureBait_Storca` | 10 | 0.2 |
| Strange Device | `Mission_Ship_Cargo` | 1 | 0.01 |
| Strange Egg? | `MiniHippo_Egg` | 1 | 2.0 |
| Survival Animal Feed | `Food_Animal_Feed_Bean` | 100 | 0.5 |
| Target Dummy | `Target_Dummy` | 1 | 12.5 |
| Terraforming Flechette | `Delivery_Object` | 100 | 0.25 |
| Titanium Tower Shield | `Shield_Titanium` | 1 | 2.0 |
| TPS Communication Tower | `Mission_TPS_Communication_Tower` | 1 | 2.0 |
| Triangulation Beacon | `TriangulationBeacon` | 5 | 2.0 |
| Truffle Spiced Vodka | `Truffle_Vodka` | 10 | 0.1 |
| Tunnelling Drill | `Faction_Mission_WallDrill` | 1 | 3.0 |
| Unknown component | `Mission_HighTech_1` | 1 | 0.01 |
| Unknown component | `Mission_HighTech_2` | 1 | 0.01 |
| Unknown component | `Mission_HighTech_3` | 1 | 0.01 |
| Unknown Device | `Mission_HighTech_Assembled` | 1 | 0.05 |
| Unstable Prototype Explosive | `Mission_Explosive` | 1 | 0.5 |
| Unstable Prototype Explosive | `Mission_Explosive_Crafted` | 1 | 0.5 |
| Unstable Terraforming Flechette | `Delivery_Object_Temperature` | 1 | 0.25 |
| Uplink Transmitter | `Survey_Transmitter` | 1 | 2.0 |
| Uplink Transmitter | `SurveyTransmitter_NoSnap` | 1 | 2.0 |
| Vapor Condenser | `Vapour_Condenser` | 1 | 5.0 |
| Vapor Laser | `Faction_Mission_Laser` | 1 | 2.0 |
| Vesper Cage | `Mission_Vesper_Cage` | 1 | 5.0 |
| Vodka | `Vodka` | 10 | 0.1 |
| Volcanic Animal Feed | `Food_Animal_Feed_Potato` | 100 | 0.5 |
| Volt Landmine | `Landmine_Shock` | 1 | 1.0 |
| Wall Charging Station | `Charging_Device_Wall` | 1 | 10.0 |
| Water Bomb | `WaterBomb` | 25 | 0.05 |
| Water Sprinkler | `Water_Sprinkler` | 1 | 0.5 |
| Watering Can | `Watering_Can` | 1 | 0.5 |
| Wild Boar Bait | `CreatureBait_Boar` | 10 | 0.2 |
| Wind Turbine | `Wind_Turbine` | 1 | 10.0 |
| Wolf Bait | `CreatureBait_Wolf` | 10 | 0.2 |
| Wolf Fertility Serum | `Fertility_Serum_Wolf` | 10 | 0.05 |
| Wood Gate Fortification | `Fortification_Wood_Gate` | 20 | 2.0 |
| Wood Shield | `Wooden_Shield` | 1 | 1.5 |
| Wood Spikes Fortification | `Fortification_Wood_Spikes` | 20 | 2.0 |
| Wood Walkway Fortification | `Fortification_Wood_Walkway` | 20 | 2.0 |
| Wood Wall Fortification | `Fortification_Wood_Wall` | 20 | 2.0 |
| Wooden Armor Stand | `Armour_Stand` | 1 | 15.0 |
| Worklamp | `Light_Worklamp_Omnidirectional` | 10 | 2.0 |
