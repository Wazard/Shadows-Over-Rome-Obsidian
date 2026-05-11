---
tags:
  - campaign/shadows-over-rome
  - migration/index
status: reviewed
source: "Wazard/Shadows-over-Rome@gpt-main"
---

# Migration Index

This note reviews the migration from the read-only reference repository into the editable Obsidian vault.

Reference repository: `Wazard/Shadows-over-Rome`  
Reference branch audited: `gpt-main`  
Editable vault: `Wazard/Shadows-Over-Rome-Obsidian`

## Current Result

The migration now covers every usable non-skipped source file found in the updated reference branch.

Coverage audit:

| Status | Count | Meaning |
| --- | ---: | --- |
| Covered | 152 | Source file has a migrated note, source reference, or downloaded asset |
| Missing | 0 | No uncovered usable source files remain |
| Skipped | 72 | Intentionally not migrated |

Skipped files:

| Reason | Count |
| --- | ---: |
| Python source intentionally not migrated | 65 |
| Reference app executables | 3 |
| Temporary Office lock files | 3 |
| Reference repo metadata `.gitignore` | 1 |

## Important Rule

Python files from the old generator/application version are not considered campaign source for this vault. Any migration content previously derived from `phase 1/quests/python` was removed.

No quest note currently contains:

- `phase 1/quests/python`
- `## Source Script Migration`
- `source/phase-1-quest-script`

## Index Placement

All index files now live in the root `indexes` folder.

Current indexes:

- [[Migration Index]]
- [[Act 1 Quest Index]]
- [[Act 2 Quest Index]]
- [[Act 3 Quest Index]]
- [[NPC Index]]
- [[Source Import Index]]
- [[Asset Index]]
- [[Reference Repo - Shadows-over-Rome]]

## Quests

Quest migration is split by act and day.

| Act | Migrated Quest Notes | Notes |
| --- | ---: | --- |
| Act 1 | 30 | Non-python Day 1-7 quest docs/text files only |
| Act 2 | 9 | Act 2 quest docs plus Diego-related quest scenes |
| Act 3 | 4 | Siege, final confrontation, and Diego Quest 3 materials |

Act 1 notes from old python-only sources were removed. The stale `Unsorted` quest placeholders were also removed because they were not backed by the updated non-python reference sources.

## NPCs

NPC migration uses the three updated CSVs from `gpt-main/CSVs/NPCs`.

| Source CSV | Imported NPCs | Tag |
| --- | ---: | --- |
| `NPC_primari.csv` | 13 | `source/npc-primari-csv` |
| `NPC_secondari.csv` | 64 | `source/npc-secondari-csv` |
| `NPC_terziari.csv` | 83 | `source/npc-terziari-csv` |

Total imported NPCs: **160**.

NPC checks:

- No empty NPC notes remain.
- [[Aelius Nuurglaag]] was merged with the imported `Aelius` CSV entry.
- [[Diego]] was filled from the Diego dossier, since he is not part of the three NPC CSVs.
- The NPC appearance timing fields were removed as requested.

## Other Migrated Material

The updated branch also included material beyond quests and NPCs. These were migrated into the vault as source notes or assets.

Migrated source areas:

- player backgrounds;
- player handout;
- campaign endings;
- food and drink rules;
- sea/failure feedback system;
- sigils document;
- Il Veliero text source;
- Diego and Er Trace reference material;
- Act 1, Act 2, and Act 3 GM source documents;
- encounter, routine, market, NPC, and quest-board CSVs.

Migrated assets:

- sigils and map images;
- Il Veliero images;
- market item images;
- player images;
- Borin Martelferro image;
- Lost Ledger image;
- Er Trace audio file.

See [[Source Import Index]] and [[Asset Index]].

## Review Notes

The vault now has broad source coverage, but some imported documents are still raw source migrations rather than polished Obsidian-ready campaign notes. The most polished areas are:

- Day 1 Act 1 quests;
- NPC CSV imports;
- the main campaign/Act 1 structure;
- indexes and source tracking.

Areas that may deserve a future refinement pass:

- convert raw Act 2 and Act 3 source imports into cleaner playable notes;
- turn market CSVs into more usable shop/inventory pages;
- link downloaded images directly from item/location/NPC notes;
- clean any encoding artifacts inherited from original source documents;
- decide whether app executables should remain only in the reference repo, which is currently the cleaner choice.
