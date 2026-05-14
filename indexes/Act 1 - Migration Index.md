---
tags:
  - campaign/shadows-over-rome
  - migration/index
  - act/1
status: in-review
source: "Wazard/Shadows-over-Rome@gpt-main"
---

# Act 1 - Migration Index

This note tracks the migration from the reference repository into the Obsidian vault.

Reference repo: `Wazard/Shadows-over-Rome`  
Editable vault: `Wazard/Shadows-Over-Rome-Obsidian`  
Current review status: **incomplete, needs another pass**

## Current Migration State

The vault now has the main Act 1 structure, NPC import, quest migration, source imports, and indexes in place, but the migration should not be considered complete yet. Some files were missed during the broad audit and need a focused follow-up pass.

## Completed So Far

### Folder Structure

The vault was reorganized into campaign-facing folders:

- `00 - Campaign Hub`
- `01 - World`
- `02 - Story Arcs`
- `03 - Sessions and Timeline`
- `04 - Quests`
- `05 - NPCs`
- `06 - Factions`
- `07 - Locations`
- `08 - Systems and Tables`
- `09 - Items, Props, and Handouts`
- `10 - GM Reference`
- `indexes`

All index files should live under `indexes` from now on.

### Story Terminology

Campaign-facing structure now uses **Act** instead of **Phase**:

- [[Act 1 - Varro's Merchant Conspiracy]]
- [[Act 2 - Marcia's Rebellion]]
- [[Act 3 - Aelius and the Cult of Eternal Night]]

Some imported raw source notes may still preserve original source titles containing “Phase” because those are archival imports.

### NPCs

NPCs were imported from the updated `gpt-main` CSVs:

| Source CSV | Imported Count | Source Tag |
| --- | ---: | --- |
| `NPC_primari.csv` | 13 | `source/npc-primari-csv` |
| `NPC_secondari.csv` | 64 | `source/npc-secondari-csv` |
| `NPC_terziari.csv` | 83 | `source/npc-terziari-csv` |

Total NPC CSV import: **160 NPCs**.

Additional NPC cleanup:

- [[Aelius Nuurglaag]] was merged with the imported `Aelius` entry.
- [[Diego]] was filled from the Diego dossier source.
- NPC appearance timing properties/rows were removed as requested.
- Empty NPC notes were cleaned up.

### Quests

Current quest migration counts:

| Act | Migrated Quest Notes | Notes |
| --- | ---: | --- |
| Act 1 | 30 | Non-python Day 1-7 quest docs/text files |
| Act 2 | 9 | Act 2 quest docs and Diego-related scenes |
| Act 3 | 4 | Siege, final confrontation, Diego Quest 3 material |

Old python-derived quest migration was removed:

- `phase 1/quests/python`
- `## Source Script Migration`
- `source/phase-1-quest-script`

### Source Imports And Assets

Imported as raw source notes or assets:

- player backgrounds;
- player handout;
- campaign endings;
- food and drink rules;
- sea/failure feedback system;
- sigil documentation;
- Il Veliero source text;
- Diego and Er Trace reference material;
- GM source documents for Acts 1-3;
- encounter, market, NPC, and quest-board CSVs;
- image/audio assets from the reference repo.

## Known Problems

This section is the important part for the next pass.

### 1. Broad Audit Was Too Coarse

The last “missing files” check treated source references as coverage. That means a file could be counted as covered if it was archived as a raw source import, even if it was not transformed into a useful Obsidian campaign note.

Tomorrow’s pass should distinguish:

- **archived source imported**;
- **usable Obsidian note created**;
- **linked into campaign navigation**;
- **asset downloaded but not linked**.

### 2. Some Files Are Still Only Raw Imports

Several important documents are present as raw source imports but still need proper playable/usable Obsidian notes. Likely candidates:

- market and black market material;
- item documents and market item images;
- routine/encounter CSVs;
- player handouts/backgrounds;
- Act 2 and Act 3 documents;
- campaign systems documents.

### 3. Images And Assets Need Linking

Assets were downloaded, but many are not yet linked from the relevant notes.

Examples to review:

- sigils;
- Rome map;
- Il Veliero images;
- market item images;
- player images;
- Borin Martelferro image;
- Lost Ledger image;
- Er Trace audio.

### 4. Index Duplication Needs Cleanup

There are currently two migration-related files:

- `indexes/Act 1 - Migration Index.md`
- `indexes/Migration Index.md`

This should be consolidated once you decide the preferred name/location. This file is the one currently being updated because the other migration file was placed incorrectly for your workflow.

### 5. Raw Encoding Artifacts Remain

Some imported source text contains encoding artifacts inherited from the source conversion, such as broken apostrophes/accented characters. These should be cleaned after the content structure is stable.

## Intentionally Not Migrated

These categories should remain out unless explicitly requested:

- old python generator/source files;
- app executables;
- temporary Office lock files;
- reference repo metadata like `.gitignore`.

## Next Recommended Pass

Tomorrow, do a targeted file-by-file review of the updated reference repo and classify every file into one of these statuses:

| Status | Meaning |
| --- | --- |
| Migrated as usable note | Converted into an Obsidian note meant for play/reference |
| Archived source only | Preserved as raw import, not yet cleaned |
| Asset downloaded | File exists locally but may need note links |
| Intentionally skipped | Python/exe/temp/metadata or explicitly unwanted |
| Missing | Not yet represented in the vault |

Then update this index with an exact checklist rather than a broad summary.
