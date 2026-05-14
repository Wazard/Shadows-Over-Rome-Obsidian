# Campaign Bible

## Repositories

- Editable vault: `Wazard/Shadows-Over-Rome-Obsidian`
- Read-only reference repo: `Wazard/Shadows-over-Rome`
- Use the reference repo only as source material.
- Apply changes only inside this Obsidian vault.
- The useful stripped reference branch is `main`.

## Naming And Structure Rules

- Use **Act** in campaign-facing Obsidian notes, not **Phase**.
- Raw source imports may preserve original source filenames containing `Phase` or `Fase`.
- All index files belong in the `indexes` folder.
- Index files must stay in `indexes` because that folder is excluded from the graph.
- Do not reintroduce old python-derived quest migration.
- Old python generator/source files are intentionally excluded unless the user explicitly asks otherwise.

## Current Vault Structure

- `00 - Campaign Hub`: campaign entry notes.
- `01 - World`: city/world material.
- `02 - Story Arcs`: Act 1, Act 2, Act 3 story structure.
- `03 - Sessions and Timeline`: day notes and timeline material.
- `04 - Quests`: quest notes by act/day.
- `05 - NPCs`: NPC notes grouped by role/faction.
- `06 - Factions`: faction notes.
- `07 - Locations`: districts, hubs, government/temple, underworld.
- `08 - Systems and Tables`: rules, CSV-derived tables, systems.
- `09 - Items, Props, and Handouts`: props, handouts, assets.
- `10 - GM Reference`: raw source imports.
- `indexes`: all indexes and migration review notes.
- `context`: future-session handoff files.

## Core Campaign Premise

**Shadows over Rome** is a Pathfinder 1e urban campaign in a Roman-inspired coastal city.

The campaign uses a living-city structure: every day changes the board, prices, shortages, NPC behavior, and political pressure.

## Campaign Calendar

- [[Day 01]] is Desnus 1, 3608.
- Day 30 is Desnus 30, 3608.
- Desnus opens with the Breaching Festival: public preparation, city-wide markets, music, visiting caravans, special tavern dinners, and harbor fireworks.
- The month also carries Remembrance Moon rites: candles, vigils, names of the dead, sea-offerings, family memory, and public mourning.
- The cult chose this span deliberately. The black moon on Desnus 30 gives the final ritual both lunar timing and emotional cover.
- Quest material should be staged through the festival calendar whenever possible: crowds, temporary markets, music, festival logistics, remembrance rites, caravans, fireworks, and public grief.

## Main Acts

### Act 1 - Varro's Merchant Conspiracy

Main antagonist: [[Gaius Varro]]

Theme: manufactured scarcity, merchant pressure, political capture.

Varro does not want to destroy Rome. He wants to destabilize the city enough that people accept him as the only stabilizing force.

### Act 2 - Marcia's Rebellion

Main figure: [[Marcia]]

Theme: public anger, civic grief, class conflict, unstable justice.

Marcia is not Varro's puppet. Act 2 is being reframed so her "rebellion" grows first as songs, vigils, mutual aid, public testimony, and disciplined civic pressure during Remembrance Moon rather than as immediate festival violence.

### Act 3 - Aelius and the Cult of Eternal Night

Main hidden antagonist: [[Aelius Nuurglaag]]

Theme: sea, darkness, ritual, apocalypse.

The cult should be seeded early as strange background noise, not revealed too soon as a full plot.

## Important NPC Notes

- [[Gaius Varro]]: Act 1 antagonist, noble merchant, wants control through scarcity.
- [[Marcia]]: bard and future rebellion leader, public voice of anger.
- [[Aelius Nuurglaag]]: hidden cult leader.
- [[Diego]]: unreliable but often pattern-sensitive clue source.
- [[Arach-Sul]]: black market leader.
- [[Cassian Rulfo]]: Varro-linked official. CSV source also calls him Cassian Rulfo.
- Aelia Polvere and Sorella Elenia are different people. Aelia Polvere is a Varro-linked hidden guard; Sorella Elenia is a Temple of Sarenrae support NPC.

## Migration Quality Rules

When migrating future material:

- Prefer usable Obsidian notes over raw dumps.
- Keep raw source imports in `10 - GM Reference/Source Imports` if they are archival.
- Link assets from relevant notes after downloading them.
- Keep NPC source tags:
  - `source/npc-primari-csv`
  - `source/npc-secondari-csv`
  - `source/npc-terziari-csv`
- Do not add `Day`, `appearing day`, `first appear`, or `First Appears` fields to NPC notes.
- Quest notes should have `Day` and `NPCs` properties when possible.

## Known Source Categories

Useful reference categories:

- `CSVs/NPCs`: current NPC CSVs.
- `CSVs/Market`: market tables.
- `CSVs/Encounters`: encounter/routine tables.
- `CSVs/Quests`: quest-board CSV.
- `phase 1/quests`: Act 1 quest documents/text.
- `phase 2/quests`: Act 2 quest documents.
- `phase 3`: Act 3 quest/endgame documents.
- `images`: campaign, market item, player, and location images.
- root `.docx` and `.txt`: campaign systems, handouts, dossiers, and general source docs.

Intentionally excluded unless requested:

- `python` files;
- app executables;
- temporary Office lock files;
- repo metadata.
