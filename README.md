<div align="center">

# Icarus — Spawn Items Into Inventory

Add items to your own [Icarus](https://store.steampowered.com/app/1149460/Icarus/) save file — written specifically for players on **Linux via Proton/Steam Play**, since most existing guides assume Windows.

[![Platform](https://img.shields.io/badge/platform-Linux%20%2F%20Proton-3a3a3a?logo=linux&logoColor=white)](#)
[![Python](https://img.shields.io/badge/python-3.8%2B-3a3a3a?logo=python&logoColor=white)](#)
[![Anti-cheat](https://img.shields.io/badge/anti--cheat-none-3a3a3a)](#is-this-safe)
[![Items catalogued](https://img.shields.io/badge/items%20catalogued-2%2C453-3a3a3a)](./items.md)

**[→ Browse the full item list](./items.md)** · 2,453 items, internal names, max stack sizes, unofficial PT/ES names

</div>

<br>

> [!IMPORTANT]
> **Use case:** unblocking missions that have already run well past a reasonable amount of time to finish — e.g. a required crop or resource that just isn't spawning enough in your world. Not meant as a way to skip normal progression, and not recommended for that.

## Is this safe?

> [!TIP]
> Icarus has **no anti-cheat** (no VAC, no EAC) — there's no ban risk from editing your own local save. This only touches files on your machine, and only affects sessions where you're the host.

> [!WARNING]
> - Always close the game and **back up your save** before editing anything (Step 1 below).
> - If you play with friends: test in a solo/private session first, save properly by exiting to the menu, *then* open it for friends. Editing while others are connected can desync and corrupt items.

## What you need

Icarus via Proton/GE-Proton · a terminal · `git` · Python 3.8+ · `pip` (`sudo pacman -S python-pip` on Arch/CachyOS) · a terminal text editor like `nano`

---

## 1 · Find your save & back it up

Your save lives inside the Proton prefix, at the same relative path Windows uses. Icarus's Steam AppID is **1149460**.

```bash
# locate the compatdata folder
find ~/.steam ~/.local/share/Steam -maxdepth 4 -iname 'compatdata' 2>/dev/null

# with the game closed, back up everything before touching anything
cp -r ~/.local/share/Steam/steamapps/compatdata/1149460/pfx/drive_c/users/steamuser/AppData/Local/Icarus/Saved/PlayerData/<YOUR_STEAMID64> ~/icarus_backup_$(date +%Y%m%d)
```

Your prospect saves are `.json` files under `.../PlayerData/<YOUR_STEAMID64>/Prospects/`.

> [!TIP]
> Also disable Steam Cloud for Icarus temporarily (game Properties → Cloud), so it doesn't overwrite your edit on next launch.

## 2 · Set up the editing tool

The save's inventory data is a zlib-compressed, base64-encoded Unreal Engine binary blob inside the JSON — not something you can hand-edit in a text editor. We use the open-source [`icarus-save-editor`](https://github.com/N30Z/icarus-save-editor), which handles that for you.

```bash
cd ~ && git clone https://github.com/N30Z/icarus-save-editor && cd icarus-save-editor
pip install customtkinter --break-system-packages
cp ~/.local/share/Steam/steamapps/compatdata/1149460/pfx/drive_c/users/steamuser/AppData/Local/Icarus/Saved/PlayerData/<YOUR_STEAMID64>/Prospects/<PROSPECT_NAME>.json ~/icarus-save-editor/savegames/
```

Find your Steam ID and character slot (you'll need both next):

```bash
python3 gd_inventory_cli.py savegames/<PROSPECT_NAME>.json list
# → <YOUR_STEAMID64>  slot=2  [inv2:11, inv3:16, inv4:2, inv5:9, ...]
```

The number after `slot=` is your character slot — note it down.

| Inventory ID | What it is |
|:---:|---|
| `2` | Equipment / Hotbar |
| `3` | **Backpack** ← the one you usually want |
| `4` | Belt |
| `5` | Armor / Cosmetics |

## 3 · Edit your inventory

> [!WARNING]
> The tool's own CLI (`items`/`set`/`add`/`remove`/`clear` commands) always assumes character slot `0` and will error out or show empty results for any other slot. The script below works around that by calling the library directly.

```bash
nano my_editor.py
```

<details>
<summary><strong>Paste this into <code>my_editor.py</code></strong> (click to expand)</summary>

```python
from gd_inventory_editor import GdInventoryEditor

# ==== ADJUST THESE ====
SAVE_FILE  = "savegames/<PROSPECT_NAME>.json"
STEAM_ID   = "<YOUR_STEAMID64>"      # from 'list'
CHAR_SLOT  = 0                        # from 'list', the slot= field
INV_ID     = 3                        # 3 = Backpack
# =======================

editor = GdInventoryEditor(SAVE_FILE)
editor.load()   # required — without this the editor is empty


def list_items():
    items = editor.get_items(STEAM_ID, INV_ID, char_slot=CHAR_SLOT)
    for it in sorted(items, key=lambda x: x['location']):
        print(f"  slot {it['location']:>3}: {it['item']} x{it['count']}")


def add_item(internal_name, quantity):
    items = editor.get_items(STEAM_ID, INV_ID, char_slot=CHAR_SLOT)
    occupied = {it['location'] for it in items}
    slot = 0
    while slot in occupied:
        slot += 1
    editor.set_item(steam_id=STEAM_ID, inv_id=INV_ID, location=slot,
                     item_name=internal_name, count=quantity, durability=None, char_slot=CHAR_SLOT)
    print(f"Added: {internal_name} x{quantity} in slot {slot}")


def edit_item_in_slot(slot, internal_name, quantity):
    editor.set_item(steam_id=STEAM_ID, inv_id=INV_ID, location=slot,
                     item_name=internal_name, count=quantity, durability=None, char_slot=CHAR_SLOT)


def remove_item(slot):
    editor.remove_item(STEAM_ID, INV_ID, slot, char_slot=CHAR_SLOT)


list_items()

# add_item("Watermelon", 20)        # find internal names in items.md
# edit_item_in_slot(5, "Carrot", 50)
# remove_item(7)

editor.save(backup=True)
```

</details>

Uncomment/adjust the calls at the bottom for what you want, then:

```bash
python3 my_editor.py
```

> [!WARNING]
> **Respect each item's max stack size** (see [`items.md`](./items.md)) — going over it in one slot makes the game silently discard that item on load, no error shown. Need more? Call `add_item()` in a loop to spread it across several slots instead.

## 4 · Copy it back and test

```bash
cp ~/icarus-save-editor/savegames/<PROSPECT_NAME>.json ~/.local/share/Steam/steamapps/compatdata/1149460/pfx/drive_c/users/steamuser/AppData/Local/Icarus/Saved/PlayerData/<YOUR_STEAMID64>/Prospects/<PROSPECT_NAME>.json
```

Load that prospect in a **solo/private session first** and confirm everything looks right before playing with friends.

---

## Troubleshooting

<details>
<summary><code>KeyError: Player '...' slot 0 not found</code> — or "No items found" despite having items</summary>
<br>

You're hitting the CLI's slot-0 bug — use the script above instead of running `gd_inventory_cli.py` directly.
</details>

<details>
<summary><code>Players found: []</code></summary>
<br>

You forgot `editor.load()` right after creating `GdInventoryEditor(...)`.
</details>

<details>
<summary>An item I added vanished after loading the save</summary>
<br>

You likely exceeded that item's max stack size in one slot — check [`items.md`](./items.md) and split the quantity across multiple slots instead.
</details>

<details>
<summary>Terminal hangs after pasting a <code>&lt;&lt; 'EOF'</code> block</summary>
<br>

Known issue with heredocs in the `fish` shell — use `nano` instead.
</details>

---

<sub>Built on [N30Z/icarus-save-editor](https://github.com/N30Z/icarus-save-editor) (save-editing toolkit and extracted game data). Not affiliated with RocketWerkz or the official Icarus team.</sub>
