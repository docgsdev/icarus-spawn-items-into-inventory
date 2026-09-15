A guide and reference for adding items to your own Icarus save file, written specifically for players running the game on Linux via Proton/Steam Play (most existing guides assume Windows).

This edits your own local save file. Icarus has no anti-cheat, so there's no ban risk — but it does directly modify game data, so back up your save before touching anything (the manual covers this first).

Use case: this is meant for finishing missions that have already run well past a reasonable amount of time — for example, a required crop or resource that just isn't spawning enough in your world. It's not meant as a way to skip the game's normal progression, and it isn't recommended for that.

What's in this repo
File	What it is
index.html	Full item reference — 2,453 items with icon, internal name, max stack size, weight, category, and an unofficial Portuguese/Spanish translation for each. Searchable, works offline once downloaded. Live version → (add your GitHub Pages link here once enabled)
manual-editar-inventario-icarus-linux.md	Step-by-step walkthrough: locating your save under Proton, backing it up, and using a small Python script to list, add, edit, or remove inventory items.
tabela-completa-itens-icarus.md	The same 2,453-item list as plain Markdown, no icons/translations — lighter to read in a text editor.
Quick start
Read manual-editar-inventario-icarus-linux.md from the top — it explains where your save lives under Proton, how to back it up, and how to run the editing script.
Use index.html (or the plain Markdown table) to look up the internal name of the item you want, plus its max stack size.
Follow the script template in the manual to add, edit, or remove that item in your save.
Notes on accuracy
Item data (names, max stack, weight) is extracted directly from the game's own data files, not copied from a wiki — see the "Provenance" section inside tabela-completa-itens-icarus.md for exactly how and how current that data is.
The Portuguese and Spanish item names in index.html are unofficial, approximate translations generated for this project — not the game's real localized text. They're there to help recognize an item, not as an authoritative source.
Wiki links in index.html are built from a URL pattern and aren't individually verified — some, especially for decoration/building-trim items, may not resolve.
Credits

Built on top of two open-source community projects:

N30Z/icarus-save-editor — the save-editing toolkit and the extracted game data tables this reference is built from.
AgentKush/Icarus-Save-file-Toolkit — extracted item icons used in index.html.

Not affiliated with RocketWerkz or the official Icarus team.
