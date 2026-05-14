# Migration State

Last updated after applying the Breaching Festival and Remembrance Moon calendar premise to quests and Act 2 guidance.

## User Preference

The user wants future sessions to rely on:

- `context/campaign_bible.md`
- `context/state.md`
- the current task

Keep future responses focused on the vault work, not re-explaining old context.

## Current Important Correction

The file `indexes/Act 1 - Migration Index.md` was empty, so it has been rewritten with an honest migration review.

There is also an older `indexes/Migration Index.md`. The user said the migration index was placed in the wrong folder and moved. Do not assume the duplicate is desired. Tomorrow's cleanup should ask or consolidate carefully.

## What Was Done

### Breaching Festival And Remembrance Moon Calendar

New canon calendar premise:

- `Day 01` is Desnus 1, 3608.
- `Day 30` is Desnus 30, 3608.
- Desnus opens with the Breaching Festival: city-wide preparation, public markets, music, visiting caravans, special dinners, and harbor fireworks.
- Remembrance Moon adds vigils, candles, mourning rites, names of the dead, sea-offerings, and public grief.
- The cult chose this month deliberately because the black moon on Desnus 30 aligns with the city's mourning rites and sea symbolism.

Applied the premise to all quest notes under `04 - Quests` by adding a `Festival Calendar Context` section to each one. Also updated Day 1-10 daily timeline notes with their Desnus dates and festival frame, and updated Session 02 prep so Day 01 afternoon/evening runs through festival preparation, Il Veliero's special dinner, and harbor fireworks.

Updated `02 - Story Arcs/Act 2 - Marcia's Rebellion/Act 2 - Marcia's Rebellion.md` with suggestions to reframe Act 2 away from an immediate festival riot and toward Marcia turning songs, vigils, mutual aid, and Remembrance Moon grief into civic pressure.

Refined that Act 2 guidance after user feedback:

- Act 2 must branch based on Act 1's Varro outcome, especially if the players dealt with Varro and earned a good ending.
- A good Varro ending should matter: Marcia shifts from anti-Varro resistance to civic watchdog, reparations advocate, and missing-person organizer while the cult exploits the city's relief.
- Every Act 2 thread should involve the players passively and actively. Passive involvement means unavoidable public memory, rumors, vigils, and NPC pressure. Active involvement means concrete choices around protecting vigils, verifying missing names, controlling aid, stopping hotheads, challenging the "Varro is solved" narrative, and giving or withholding public testimony.
- Ignoring Marcia should not stop Act 2, but it should let officials, Varro remnants, hotheads, or the cult define public events without the players.

### Act 1 Clue Expansion

Created `02 - Story Arcs/Act 1 - Varro's Merchant Conspiracy/Act 1 Clue Escalation Table.md` and linked it from the Act 1 overview.

The new clue table makes Act 1 investigations more playable:

- Days 1-3 keep mostly surface evidence inside existing quests.
- Days 4-6 add slum rumors, black market information purchases, private Merchants' Guild investigation, and interrogatable common bandits.
- Day 5 black market access can buy names, locations, NPC routines, guard uniforms, delivery tokens, and route information.
- Days 7-9 introduce active resistance by guards, bandits, and Aulus' men.
- Players can learn Varro's name as a beneficiary/political force before they have proof.
- Cassian remains hidden behind seals, offices, or indirect paperwork unless the players take higher-risk evidence.
- Direct proof against Varro requires multiple evidence categories, not one lucky roll.

Later embedded these clue options directly into the dated Act 1 quest notes:

- Every dated Act 1 quest under `04 - Quests/Act 1 - Days 01-10/Day XX` now has a `Deeper Investigation Clues` section.
- Clues that do not cleanly belong inside an existing quest remain highlighted in `Act 1 Clue Escalation Table.md` under `Highlighted Floating Clues`.
- Generic quest NPC placeholders were replaced with existing named support NPCs where possible:
  - Missing Cargo now uses `Grumo Bracciodiragno`, `Tilla Tresecchi`, `Lippo Gualdo`, `Sajan Qadir`, `Captain Linh Sura`, `Bao Yiren`, and `Naso Rotto`.
  - Marcia's Day 1 song now uses `Pietro Dueprezzi` instead of a generic protester.
  - Shop Dispute now uses `Asterio Falena` and `Caius Rutilo`.
  - Tax Enforcement now uses `Cassian Rulfo`, `Nerva Censore`, `Pietro Dueprezzi`, and `Larto Vero`.

Expanded `Crew of the Chimera di Giada`:

- The crew now comes from eastern sea routes and trades spices, gunpowder, jade, diamonds, eastern weaponry, and shady homebrew spell scrolls with side effects.
- Added crew NPCs `Sajan Qadir`, `Captain Linh Sura`, and `Bao Yiren`.
- `Sajan Qadir` is the always-available harbor contact for questions and commissions.
- Created `08 - Systems and Tables/Encounter Tables/NPC Routines/Chimera di Giada/Chimera di Giada Harbor Routine.md`.

### Folder And Index Rules

- Created project folders for campaign hub, world, acts, sessions, quests, NPCs, factions, locations, systems, props/assets, GM reference, indexes, and context.
- All index files should live in `indexes`.
- Created/updated:
  - `indexes/Act 1 - Migration Index.md`
  - `indexes/Act 1 Quest Index.md`
  - `indexes/Act 2 Quest Index.md`
  - `indexes/Act 3 Quest Index.md`
  - `indexes/NPC Index.md`
  - `indexes/Source Import Index.md`
  - `indexes/Asset Index.md`
  - `indexes/Reference Repo - Shadows-over-Rome.md`

### NPCs

Imported NPCs from `Wazard/Shadows-over-Rome@gpt-main/CSVs/NPCs`:

- `NPC_primari.csv`: 13 NPCs.
- `NPC_secondari.csv`: 64 NPCs.
- `NPC_terziari.csv`: 83 NPCs.

Total CSV NPC import: 160.

Important cleanup:

- Removed NPC appearance timing properties/rows.
- Merged imported `Aelius` into `05 - NPCs/Main NPCs/Aelius Nuurglaag.md`.
- Filled `05 - NPCs/Supporting NPCs/Diego.md` from Diego dossier material.
- No empty NPC notes remained after the last check.

NPC note expansion and Italian cleanup:

- Rewrote all 186 notes under `05 - NPCs` into a consistent Italian play-facing structure.
- Each NPC now has expanded sections for:
  - `Dati NPC`
  - `Descrizione Estesa`
  - `Personalita`
  - `Uso in Campagna`
  - `Impressione per i Giocatori`
  - `Spunti di Scena`
  - `Segreti, Pressione e Reazioni`
  - `Battute Rapide`
- Preserved frontmatter, source tags, factions, race/stirpe, role, and important canon relationships.
- Cleaned old mojibake and translated old English section headings in NPC notes.
- Verification after cleanup: 186 NPC notes, 0 broken wiki links inside NPC notes, no old English NPC section headings left.

### Quests

Old python-derived quest migration was removed.

Current migrated quest counts:

- Act 1: 30 quest notes from non-python docs/text files.
- Act 2: 9 quest notes from non-python docs/text files.
- Act 3: 4 quest/endgame notes from non-python docs/text files.

No remaining quest note should contain:

- `phase 1/quests/python`
- `## Source Script Migration`
- `source/phase-1-quest-script`

Day 02 Act 1 quest expansion:

- Rewrote and expanded all five Day 02 quest notes in Italian:
  - `Delayed Shipment Mediation Needed`
  - `Disputed Market Delivery`
  - `Forge Theft`
  - `Lantern in the Crooked Alley`
  - `Shop Dispute`
- Each now includes festival/remembrance context, a public bacheca hook, DM summary, opening boxed-style scene, named NPC handling, staged investigation, deeper clues, complications, possible outcomes, rewards, and future hooks toward Varro's network where appropriate.
- The notes are substantially expanded for table use, but exact "page" length depends on Obsidian layout and export settings.
- Later added dedicated `Punti di Interesse` sections to every Day 02 quest, with table-ready descriptions and interaction hooks for the relevant locations:
  - warehouse courtyard, record desk, priority cargo lane, and merchant waiting wall;
  - market food stall, delivery cart, green-tarp stall, and small fountain;
  - forge hall, custom tool bench, coal yard, and old warehouse well;
  - crooked alley entrance, fallen lantern point, Daria's window, Oriolo's stall, and dark alley end;
  - Asterio's workbench, old sample shelf, Caius' crate, street window, and apprentice corner.
- Cleaned lingering encoding artifacts in Day 02 quest text after the point-of-interest pass.

Day 01 Act 1 quest expansion:

- Rewrote and expanded all five Day 01 quest notes in Italian:
  - `Lost Ledger near the Harbor`
  - `Marcia's Song in the Square`
  - `Missing Cargo from the Docks`
  - `Parcel to the Apothecary`
  - `Wolves Outside the Walls`
- Each now includes festival/remembrance context, a bacheca hook, DM summary, scene flow, named NPC handling, investigation options, complications, outcomes, rewards, and table notes.
- `Parcel to the Apothecary` canon changed: the apothecary is not seen by the players. The true hidden figure is `Veska Sottolingua`, a vishkanya from the black market. `Tamira Velofalso` is the legal face of the activity, selling perfumes, ordinary remedies, oils, soaps, and other normal apothecary goods.
- Renamed/normalized the Tamira NPC note to `Tamira Velofalso`; `Market Apothecary` is now only a legacy placeholder pointing to Tamira and Veska.

### Source Imports And Assets

Imported many non-python reference docs/text/CSVs as raw source notes.

Downloaded 49 media/audio assets into:

`09 - Items, Props, and Handouts/Assets`

Important: many assets are downloaded but not yet linked from the relevant notes.

### Encounters And NPC Routines

The reference repo branch to use is now `main`, not `gpt-main`; the user said `main` has been stripped of useless information.

Migrated `Wazard/Shadows-over-Rome@main/CSVs/Encounters` into one-note-per-row play-facing encounter/routine notes under:

- `08 - Systems and Tables/Encounter Tables/Random Encounters`
- `08 - Systems and Tables/Encounter Tables/NPC Routines`

Created `indexes/Encounter Tables Index.md`.

Created source index notes in `indexes`:

- `Day 01-07 Random Encounters.md`
- `Day 08-09 Outcome Random Encounters.md`
- `Day 01-07 Main Character Routines.md`
- `Day 01-07 Guard Rounds.md`
- `Day 01-07 Anti-Merchant Routines.md`
- `Day 01-07 Aulus Bandit Routines.md`
- `Day 01-07 Cassian Men Routines.md`
- `Day 01-07 Common Bandit Routines.md`
- `Day 01-07 Independent Merchant Routines.md`
- `Day 01-07 Varro's Merchant Routines.md`

Split counts:

- Random encounter notes: 672.
- NPC routine notes: 815.
- Total split encounter/routine notes: 1,487.

Each split note links its day, broad location, and involved NPC/group entry where the CSV identifies them. The source index notes are now lightweight link indexes, not reproduced CSV tables. The old direct CSV dump notes were preserved in `08 - Systems and Tables/Encounter Tables/Legacy CSV Dumps` as source cache only.

Each individual split encounter/routine note also has graph/filter tags for:

- `day/NN`
- `location/<linked-location-slug>`
- `daytime/<period-slug>`

Last verification found 1,487 split encounter/routine notes and 0 missing day/location/daytime tags.

Important indexing rule update:

- All index files must live in `indexes`, because that folder is excluded from the graph.
- Encounter/routine index files have been moved into `indexes`; split encounter/routine notes remain in `08 - Systems and Tables/Encounter Tables`.

Reference merge audit:

- Created `indexes/Reference Merge Waiting List.md`.
- Compared the vault against `Wazard/Shadows-over-Rome@main`.
- Scanned 118 reference files.
- Current report counts: 40 waiting/needs review, 64 merged/usable/downloaded, 14 intentionally skipped.
- Highest-priority waiting item: `CSVs/Encounters/Routines/day1-7_Secondary_characters_routine.csv`, which exists on `main` and still needs split migration.

### Session 02 Prep

Prepared `03 - Sessions and Timeline/Session Prep/Session 02 - Close Day 01.md`.

Canon start state for Session 02:

- In-game time is [[Day 01]], 13:00.
- The party is in [[Government Palace]].
- They have valid permits to re-enter Rome at night.
- During the morning, they completed [[Marcia's Song in the Square]] without fighting.
- During the morning, they completed [[Parcel to the Apothecary]] without opening the package and without uncovering who the apothecary is.
- Session target is 2h30m and should close the first in-game day.

Also updated `03 - Sessions and Timeline/Daily Timeline/Day 01.md` with this current play state.

Later expanded the same Session 02 prep with an optional random-encounter table for city travel and drift moments. Several entries point naturally toward `Missing Cargo from the Docks` or `Lost Ledger near the Harbor` without revealing a culprit.

### Session 03 Prep

Prepared `03 - Sessions and Timeline/Session Prep/Session 03 - Day 02 Festival Pressure.md`.

Canon recap from Session 02:

- The party learned about the Breaching Festival.
- They went to the Warehouse District.
- Auris saw/contacted `Cassian Rulfo` and `Gaius Varro` heading toward the noble district.
- Cassian's fake-coin prototype pouch had a hole; Auris took 6 gold-looking coins.
- Auris failed the appraisal/Valutare check and currently believes those coins are pure gold.
- Auris heard only Cassian's first name.
- The party took `Missing Cargo from the Docks` at Il Veliero and failed the main checks.
- They currently believe someone stole the cargo because it contained spices from the Chimera di Giada.
- They do not know the cargo was purposely disposed of.
- They took the black fabric fragment but failed to identify it.
- They met `Bobbins McTwist`, who pointed them toward warehouse 7 and had no documents for the missing package.
- They fought 3 drunkards and met `Naso Rotto`, who slashed Apollodoro and ended the combat with no deaths.
- The party slept 8 hours at Il Veliero, ate modest food, and took no malus.

Session 03 starts on `Day 02`, Desnus 2, 3608, at Il Veliero after rest. It should last one in-game day or less.

Available Session 03 quests:

- `Marcia's Song in the Square`
- `Delayed Shipment Mediation Needed`
- `Forge Theft`
- `Lantern in the Crooked Alley`
- `Shop Dispute`
- `Wolves Outside the Walls`

The prep includes rollable d4 encounter tables with 4 encounters per zone for Il Veliero, Harbor District, Warehouse District, Market Square, artisan/shop district, poor residential alleys, city gates/outside walls, and roads toward the noble district.

### Day 1-2 NPC Cleanup

Cleaned Day 1 and Day 2 quest/encounter NPC references against the authoritative NPC notes.

- Cassian's canonical name is now `Cassian Rulfo`.
- The old Cassian spelling has been removed from text and filenames.
- Renamed the Cassian NPC note to `05 - NPCs/Varro Network/Cassian Rulfo.md`.
- Normalized Day 1-2 quest/encounter NPC aliases such as Mauro Tersi, Vibius Panciotto Ennio, Aelia Polvere, Frate Caldus, Sabina, Lupo, Tito Senzasuola, Remus Aurelianus, Man of Aulus, Aferio Lento, Rufina Sale, Muto, Tired Dockworker, Numa Campanasecca, Terenzia Acquabassa, and Publius - Apprentice.
- Converted one-off incidental Day 1-2 encounter figures without authoritative NPC notes from wiki-links to plain text.
- Normalized the remaining broken Day 1-2 place aliases to broader existing location notes.
- Created `indexes/Day 1-2 NPC Encounter Cleanup Log.md`.
- Verification after cleanup: 0 broken wiki links in Day 1-2 quest, random encounter, and NPC routine notes.

Created broad encounter-location notes in `07 - Locations/Encounter Locations` for recurring places not already represented in the vault, including Residential District, Abandoned Chapel, Northeast Forest, Outside the Walls, Commercial Road, City Streets, Middle-Class District, Middle-Class Tavern, Noble Gate, North Gate, and South Gate.

### Temple NPC Correction

Corrected a major linking error:

- `Aelia Polvere` and `Sorella Elenia` are different NPCs.
- `Aelia Polvere` remains the Varro-linked hidden guard with the rare musket.
- The temple sister previously appearing in Sarenrae random encounters under the confusing source name has been renamed to `Sorella Elenia`.
- Active play-facing Temple of Sarenrae random encounter notes now link to `[[Sorella Elenia]]`, not to Aelia Polvere.
- Session 02 prep now borrows from the corrected Day 01 evening Sarenrae encounter.

Added Temple of Sarenrae NPC support:

- 2 secondary temple NPCs:
  - `Prior Lucanus Solari`
  - `Sorella Maura Vesta`
- 10 support temple NPCs:
  - `Sorella Elenia`
  - `Fratello Iovian`
  - `Novizia Clara`
  - `Accolito Marius`
  - `Padre Caldus Orante`
  - `Sorella Livia delle Bende`
  - `Fratello Nabor`
  - `Diacona Prisca`
  - `Custode Tullian`
  - `Eudocia la Lampadaria`

Created `indexes/Temple NPC and Sorella Elenia Correction Log.md`.

## Known Problems

The last broad audit was too coarse. It counted raw archived source imports as "covered", even when they are not yet usable Obsidian campaign notes.

This means some files are not truly "finished" even if they exist somewhere in the vault.

Known follow-up categories:

- Convert raw source imports into usable notes.
- Link downloaded images/audio from relevant notes.
- Clean encoding artifacts in imported raw source text.
- Consolidate duplicate migration index files.
- Review market item data and images.
- Review incidental one-off NPC names in split encounter/routine notes; many are linked from encounters but do not yet have full NPC notes.
- Review Act 2 and Act 3 quest/source notes for playability.

## Tomorrow's Recommended Task

Do a file-by-file migration review from `Wazard/Shadows-over-Rome@main`.

Classify every reference file as one of:

- usable Obsidian note;
- raw source import only;
- downloaded asset only;
- intentionally skipped;
- missing.

Then update `indexes/Act 1 - Migration Index.md` with an exact checklist.

## Important Cautions

- Do not restore old python quest/script migration unless explicitly requested.
- Do not add NPC day/first-appearance fields back.
- Do not assume raw source imports are sufficient; user is expecting actual migration quality.
- Do not push or create backups; the user handles that.
