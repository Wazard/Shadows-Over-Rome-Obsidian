---
tags:
  - linker-exclude
---
# Migration State

Last updated after expanding the player hub to all four repo-confirmed players from `main/players`.

## User Preference

The user wants future migration sessions to rely on:

- `context/campaign_bible.md`
- `context/migration_state.md`
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
- Later added very subtle cult traces to each Day 02 quest. These are intentionally non-conclusive background details: salt, moon phrases, blue/gray candle wax, sea smell, strange glass, children's drawings, and other motifs that can be ignored now but recognized later.

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
- `Marcia's Song in the Square` is the Day 01 Marcia quest only. A separate Day 02 quest now exists as `Marcia's Song in the Square 2`, with stronger festival texture, short recurring lyrics, random square encounters, crowd lines, guard behavior, possible payout, and a very subtle "la luna beve" cult echo that Marcia does not understand as occult.
- `Wolves Outside the Walls` was expanded with detailed points of interest outside the walls, travel encounters, sensory cues, advanced preparations, and wolf behavior.
- `04 - Quests/Act 1 - Days 01-10/Quest Board.md` now has a Day 2 board section linking `Marcia's Song in the Square 2` and the other Day 2 Session 03 quests.
- `indexes/Act 1 Quest Index.md` now lists `Marcia's Song in the Square 2` under Day 02 and no longer includes the stale broken `Merchant Official Escort` row.

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

- `Marcia's Song in the Square 2`
- `Delayed Shipment Mediation Needed`
- `Forge Theft`
- `Lantern in the Crooked Alley`
- `Shop Dispute`
- `Wolves Outside the Walls`

The prep includes rollable d4 encounter tables with 4 encounters per zone for Il Veliero, Harbor District, Warehouse District, Market Square, artisan/shop district, poor residential alleys, city gates/outside walls, and roads toward the noble district.

Session 03 prep now points the Marcia option toward the separate Day 02 quest `Marcia's Song in the Square 2`.

### Player Hub And Player Dossiers

Filled `00 - Campaign Hub/Players.md` in Italian and created individual player notes under `00 - Campaign Hub/Players`.

After user correction, the player roster was rechecked against `Wazard/Shadows-over-Rome@main/players` rather than only local imported background notes.

Confirmed player-character notes created:

- `Auris Mantopietra`
- `Apollodoro`
- `Massimiliano`
- `Filippo`

Confirmed from existing background/session notes:

- Auris Mantopietra is a halfling stregone livello 2, raised by dwarves in the Lombard Alps, with innate earth/metal affinity and a hammer-shaped birthmark interpreted as a possible sign of Torag.
- Auris' current Session 02 hook is the six gold-looking false-coin prototypes taken from `Cassian Rulfo`; Auris failed Valutare/Appraise and believes they are pure gold.
- Apollodoro is the public/stage identity of Aurelio, originally from Naples, whose family, home and face were destroyed by fire.
- Apollodoro's background confirms exhibition combat, bardic arts, Tiberius as mentor, the gladiator helmet as a central identity object, class as guerriero with one bard level, and scizore as preferred weapon.
- Apollodoro was wounded by `Naso Rotto` during Session 02, creating a direct hostile/rival contact.
- Massimiliano is a noble human from Pienza, trained first in Desna's church, then drawn to Sarenrae, and later transformed by the nine-bells village massacre into a paladin-like protector. His source confirms paladino and spadalunga.
- Filippo, also called Pippo, comes from a large family, fears discovery of his fae/sorcerous blood, and is a ladro/stregone described in source as a "mago che fa furtivi con magie".

Repo files confirmed/read from `main/players`:

- `Background Auris.txt`
- `Background Apollodoro.txt`
- `Background Massimiliano.txt`
- `Background Filippo.txt`
- `Auris.pdf`
- `Apollodoro.pdf`
- `Fabio.pdf` - this is Massimiliano's character sheet; the name stayed Fabio because in Session 01 the player/character switched to Massimiliano and the repo file was not renamed.
- `Filippo.pdf`

Massimiliano's PDF should be treated as `players/Fabio.pdf`, not as `players/Massimiliano.pdf`.

Previously tested non-canonical paths that were not found:

- `Massimiliano.pdf`
- `massimiliano.pdf`
- `Massimilliano.pdf`
- `Padre_Massimiliano.pdf`
- `Padre Massimiliano.pdf`
- `Padre-Massimiliano.pdf`
- `Aldebarand.pdf`

The player hub now tracks:

- party state after Session 02;
- individual player links;
- session action log;
- NPC relationship snapshot;
- player-specific fears/levers;
- open inputs still needed.

Important unresolved player inputs:

- Whether Massimiliano and Filippo had individual Session 01-02 actions not captured by the session prep recap.
- Full character sheet details beyond the repo background's class/weapon lines.
- Auris' bloodline, spell list and current combat role.
- Whether `Er Trace` is still active in current play or only a backstory bridge.
- Any full Massimiliano sheet details not visible from the PDF filename/background summary.

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

### Pulizia Accenti Italiani

Eseguita una revisione degli accenti nei file markdown italiani attivi del vault.

- Normalizzate forme frequenti senza accento, tra cui `perché`, `città`, `più`, `può`, `già`, `ciò`, `però`, `finché`, `attività`, `identità`, `possibilità`, `curiosità`, `schiavitù`, `furtività`, `criminalità`, `stabilità`, `comodità`, `personalità`, `avidità`, `vulnerabilità`, `affinità`, `adattabilità` e `mobilità`.
- Corretti i file giocatore e il player hub con accenti mancanti e alcuni falsi positivi `e/è`.
- Correzioni specifiche applicate a [[Auris Mantopietra]], [[Apollodoro]], [[Massimiliano]], [[Filippo]] e [[Players]].
- Verifica finale: nessuna occorrenza residua trovata per le forme non accentate cercate nei file `.md` fuori da `.obsidian`.

Nota operativa: da ora in avanti, ogni contenuto italiano scritto nel vault deve usare gli accenti corretti.

### Vaeltharuun, Paure dei PG e Numero Nove

Aggiornata la progressione della serie di Vaeltharuun per usare in modo crescente le paure di [[Massimiliano]] e [[Filippo]], con richiami anche a [[Auris Mantopietra]] e [[Apollodoro]].

- In [[Candles for the Old Chapel]], giorno 7, Madre Elenia prepara **nove candele** vicino all'altare: una per ciascun giorno di sofferenza della defunta della veglia. Il dettaglio deve sembrare umano e religioso, non ancora minaccioso.
- Nella stessa quest sono state aggiunte tracce fatate deboli nella cera e nel passaggio di Vaeltharuun, perché Vaeltharuun è uno stregone di stirpe fatata e ha usato magia fatata per non essere notato.
- In [[Day 11 - Corpi mancanti dalle fosse comuni]], i corpi mancanti sono **esattamente nove**. La selezione è pratica per gli esperimenti di Vaeltharuun, ma al tavolo deve richiamare il trauma del numero nove di Massimiliano.
- In quella quest, controlli alti di Perception/Investigation/Sapienza Magica o Knowledge Nature possono rivelare che le tracce non sono state cancellate fisicamente: sono state rese facili da ignorare tramite magia fatata.
- In [[Day 13 - 14 Arthemol Coro di Carne Quest]] e nella nota parallela [[Day 13 - 14 Bestia nei bassifondi]], Arthemol ha **nove facce**: otto secondarie in dolore e paura, e una primaria completamente mutilata.
- Arthemol può percepire paure e identità ferite tramite memoria necromantica contaminata da magia fatata. Non è lettura del pensiero pulita.
- Frasi mirate confermate:
  - Massimiliano: "Nove campane, nove rintocchi, nove vittime, un solo sopravvissuto codardo."
  - Filippo, primo colpo: "Padrone, ne abbiamo trovato un altro."
  - Filippo, secondo colpo o magia: "Amico fatato, non senti la nostra sofferenza? Perché nascondi la tua identità?"
- Arthemol ora ha anche risposte per le paure di Auris e Apollodoro: identità nanica/oro falso per Auris, elmo/volto bruciato/buio per Apollodoro.
- Il combattimento contro Arthemol deve essere molto difficile ma non arbitrario: con preparazione è vincibile e costoso; senza preparazione è probabile almeno una morte NPC, e con approccio frontale anche un PG può realisticamente morire.

### Regole Markdown Quest

Create regole di formattazione quest in [[quest_markdown_rules]].

- Ogni quest deve aprire con callout `> [!motive]`, `> [!summary]` e `> [!success]`.
- Subito dopo l'apertura deve esserci una tabella con giorno, luogo, PNG coinvolti, tipi di CD, combattimento e ricompensa.
- Readaloud, descrizioni, note e avvertimenti devono usare callout evidenti, per esempio `> [!readaloud]`, `> [!description]`, `> [!note]`, `> [!warning]`, `> [!danger]`, `> [!clue]`.
- I dialoghi devono essere colorati per PNG con colore coerente dentro la quest.
- Le CD devono essere colorate per caratteristica: FOR rosso, DES arancione, COS verde, INT azzurro, SAG viola, CAR giallo.
- Le quest investigative devono includere una tabella indizi con CD colorate.
- Tutto il materiale di campagna in italiano deve mantenere accenti corretti.

Applicazione di prova completata:

- [[Day 13 - 14 Bestia nei bassifondi]] è ora la versione play-facing unica della quest, riformattata secondo le nuove regole.
- [[Day 13 - 14 Arthemol Coro di Carne Quest]] è stato accorpato e trasformato in nota-puntatore verso [[Day 13 - 14 Bestia nei bassifondi]], per evitare doppioni e contraddizioni.

### Formattazione Quest Fase 1

Applicate le regole di [[quest_markdown_rules]] alle quest giornaliere già scritte della Fase 1.

- Aggiornate 30 note quest sotto `04 - Quests/Act 1 - Days 01-10`, giorni 1-7.
- Aggiornata anche [[Day 11 - Corpi mancanti dalle fosse comuni]], come richiesto, con apertura specifica, tabella indizi colorata, dialoghi colorati e maggiore coerenza con la serie di Vaeltharuun.
- Ogni quest aggiornata ora ha apertura con `> [!motive]`, `> [!summary]`, `> [!success]`, tabella gestionale iniziale e sezione `## PNG e Colori`.
- Promossi readaloud, descrizioni, note, avvertimenti e indizi principali a callout evidenti.
- Colorate le CD ricorrenti secondo caratteristica quando riconosciute nel testo.
- Puliti accenti italiani frequenti nei file toccati.

Nota: `Quest Board.md` e `Varro's Plan - Act 1.md` non sono stati trattati come singole quest giocabili, quindi non sono stati riformattati in questo passaggio.

### Riscrittura Completa Quest Giorno 2

Corretto il passaggio precedente sulle quest di [[Day 02]]: la prima formattazione aveva aggiornato soprattutto apertura e struttura, ma non abbastanza il corpo giocabile.

Riscritti in modo sostanziale i corpi delle sei quest del giorno 2, seguendo il modello play-facing di [[Day 13 - 14 Bestia nei bassifondi]]:

- [[Mediazione per Carico in Ritardo]]
- [[Consegna Contesa al Mercato]]
- [[Furto alla Forgia]]
- [[La Lanterna del Vicolo Storto]]
- [[Marcia's Song in the Square 2]]
- [[Disputa alla Bottega]]

Modifiche applicate:

- aperture specifiche con motivo, riassunto ed esiti non generici;
- tabelle iniziali con luogo, PNG, tipi di CD, combattimento e ricompensa;
- sezioni `PNG e Colori` con dialoghi colorati coerenti;
- scene di apertura e punti di interesse riscritti come materiale direttamente giocabile;
- fasi di gestione al tavolo, complicazioni, indizi e ricompense rese esplicite;
- tabelle indizi con CD colorate secondo [[quest_markdown_rules]];
- tracce cultuali mantenute molto sottili e non risolutive;
- accenti italiani verificati nei file del giorno 2.

Nota operativa: questo è il livello minimo desiderato per le prossime riformattazioni quest. La sola aggiunta di blocchi iniziali non è sufficiente.

### Riscrittura Completa Quest Giorno 3 e Veltharuun

Applicato lo stesso standard play-facing usato per [[Day 13 - 14 Bestia nei bassifondi]] e per le quest del [[Day 02]] alle quest del [[Day 03]] e alle tappe principali ancora non riscritte della sottotrama di Veltharuun.

Quest del giorno 3 riscritte:

- [[Bread Before Sunset|Pane Prima del Tramonto]]
- [[Discreet Double Registration Check|Verifica Discreta su Doppia Registrazione]]
- [[Merchant Refuses Delivery|Mercante Rifiuta Consegna]]
- [[Official Transport Escort|Scorta a Trasporto Ufficiale]]
- [[Unregistered Delivery Check|Controllo su Consegna Non Registrata]]

Quest di Veltharuun riscritte:

- [[Candles for the Old Chapel|Candele per la Cappella Vecchia]]
- [[Day 16 - Persone scomparse dopo la veglia]]

Decisioni e note canoniche:

- [[Bread Before Sunset|Pane Prima del Tramonto]] resta una quest senza vera paga monetaria: il premio è fiducia di [[Marcia]] e riconoscimento nei bassifondi.
- [[Official Transport Escort|Scorta a Trasporto Ufficiale]] è confermata come prima apparizione diretta di [[Gaius Varro]]: deve sembrare ordinato, potente e quasi ragionevole.
- Le quest documentali del giorno 3 rafforzano la falsa pista di [[Brutus Verro]] senza rivelare ancora la rete completa di Varro.
- [[Merchant Refuses Delivery|Mercante Rifiuta Consegna]] era quasi uno stub: è stata resa giocabile mantenendo il nucleo canonico, cioè il sospetto di [[Naevius Prisco]] sui materiali illegali e sulla paura dei controlli.
- [[Candles for the Old Chapel|Candele per la Cappella Vecchia]] è ora la prima tappa chiara della serie di Veltharuun: introduce la cappella, [[Serena Valeria]], le nove candele, il numero 9 come lutto plausibile e una traccia fatata per [[Filippo]], senza mostrare il necromante.
- [[Day 16 - Persone scomparse dopo la veglia]] è ora la conclusione play-facing della sottotrama: quattro volontari, scelta morale, possibile rituale completato, scontro difficile con timer e ricompense sporche.
- Le note usano [[Veltharuun|Vaeltharuun]] quando serve mantenere il nome narrativo usato nei testi e il link al file PNG esistente.

Verifiche eseguite:

- blocchi iniziali obbligatori presenti nei 7 file;
- sezioni `PNG e Colori` presenti;
- nessun placeholder `$c`;
- nessuna CD grezza non colorata trovata con il controllo usato;
- nessuna occorrenza residua trovata per i termini inglesi operativi cercati (`fight`, `Feeling`, `Ritual`, `Quest Board`, `Source Migration`, ecc.);
- accenti italiani comuni verificati nei file toccati.

### Sessioni 04 / 04.5 / 05, Rework Quest e Stato Vivo (giu 2026)

Lavoro di sessione e quest successivo all'ultima riscrittura del Giorno 3. Dettaglio cronologico completo in [[log|context/log.md]].

**Stato vivo della campagna**

- Creato [[campaign_state|context/campaign_state.md]]: istantanea per ripartire in qualsiasi momento (tempo di gioco, quest aperte/chiuse, fili caldi, PNG chiave, semi dell'Atto 3). Da aggiornare a fine sessione insieme a [[log|context/log.md]] e a **questo file**.

**Recap e prep di sessione**

- [[Session 04 - Day 02 Recap]]: Disputa alla Bottega mediata ([[Asterio Falena]]/[[Caius Rutilo]]); sospetto di fondo "carta pulita, sostanza peggiore" tenuto sottile.
- [[Session 04.5 - Day 02 Evening Wolves]] (prep): scontro lupi con orologio di preparazione, **Alpha-osservatore che non combatte**, Lupo Mutilato col marchio cultuale; aggiunti due beat di roster (ingresso [[Hillara]], morte opzionale di Apollodoro).
- [[Session 04.5 - Day 02 Recap]] (giocata): lupi **respinti** (1 ucciso, 1 in fuga; una pecora sventrata); **Apollodoro caduto ma SOPRAVVISSUTO** (ha protetto Massimiliano); [[Massimiliano]] spezza il branco con un colpo "benedetto da Iomedae"; Lupo Mutilato **fuggito monco** (marchio non recuperato sul campo); [[Hillara]] entra alla fattoria di [[Faustus]].
- [[Session 05 - Day 03 Morning]] (prep): mezza giornata di [[Day 03]] (alba→mezzogiorno); false piste su [[Brutus Verro]], pane di [[Marcia]], prima **sparizione** (seme cultuale), gancio della Scorta al Trasporto per il pomeriggio.

**Riconciliazione "Apollodoro vivo"** (decisione utente: Apollodoro resta in gioco, [[Hillara]] = quinta PG, non sostituta): allineati [[campaign_state|context/campaign_state.md]] (stato avanzato post-4.5, quest lupi chiusa, roster) e [[Session 05 - Day 03 Morning]] (rimosso il funerale; Fase 1 → "Alba - Rientro e Medicazione").

**Quest Giorno 3 — rework per più azione** (oltre alla prima riscrittura play-facing): [[Discreet Double Registration Check]] (rompicapo a incrocio + heist/controspionaggio), [[Unregistered Delivery Check]] (orologio dell'allarme + caccia notturna), [[Official Transport Escort]] (diversivo, spionaggio bidirezionale, assalto non lineare), [[Bread Before Sunset]] (motivo politico, bassifondi ostili, puzzle dei segni, 4 tappe).

**Nuove quest**

- Tangente "I corrieri che non tornano" (port dal docx sorgente, Giorni 2-3): [[The Note in the Mud]], [[The Orphan Network]]. Restano i Giorni 4-9. Workflow: l'utente metterà i docx sorgente nella cartella quests per i prossimi port.
- Giorno 4: [[Attention - Report counterfeit coins]] (le 6 monete false di Auris diventano contrabbando), [[The Unsigned List]] (infiltrazione, Indicatore di Sospetto).

**PG e GM reference**

- Nuova PG [[Hillara]] (scheda backstory; stirpe/classe ancora da fissare).
- `10 - GM Reference/Merchant Inventories.csv`: inventari PF1e per venditore (~31 venditori: mercato/porto, rete di Varro, nave Chimera di Giada).

**Nota operativa:** da ora ogni modifica al vault va registrata in [[log|context/log.md]] **e** [[campaign_state|context/campaign_state.md]] **e** in **questo file** (`migration_state.md`). Push / PR / backup restano gestiti dall'utente.

### Espansione Quest "Verifica Doppia Registrazione" (giu 2026)

Su richiesta dell'utente, [[Discreet Double Registration Check|Verifica Doppia Registrazione]] (Giorno 3) è passata da semplice investigazione documentale a quest a più strati:

- **Descrizioni giocabili** in Fase 3 e 4 (ambienti, abiti, gesti dei PNG) con liste esplicite di "Cosa potete fare qui", così i giocatori vedono cosa **possono** fare.
- **Rumore e false piste:** nuova sezione con testimonianze discordanti, un depistaggio interessato e una **bugia pagata** (l'orario di attracco) che attacca l'indizio-chiave; distinguere segnale da rumore è ora parte dell'indagine.
- **Indizi sulle monete false:** la mancia "in moneta nuova" di Sergerro e la sacca nello scrigno sono **falsi dello stesso conio** delle 6 di Auris → aggancio esplicito a [[Attention - Report counterfeit coins]] (mostrare la parentela, non la fonte).
- **Infiltrazione notturna come dungeon:** Orologio dell'Allarme (0→6), ingresso multiplo, **armature animate** (Oggetto Animato PF1e) disattivabili via sigillo o aggirabili col gettone d'ottone, corridoio **trappolato** (campanella, glifo d'allarme, ago avvelenato, scaffale instabile), stanzino della **ricerca** dove non sanno cosa cercano, scrigno con ricevuta + monete false.
- **Lettura di trama:** trappole e armature animate segnalano che "Brutus protegge troppo per un truffatore di grano" senza rivelare Cassian/Aulus/Varro; falsa pista intatta.

Stesso standard estendibile alle altre quest del Giorno 3 se richiesto.

### Fix Timing Bread + Rework "Scorta al Trasporto Ufficiale" (giu 2026)

- **[[Session 05 - Day 03 Morning]]:** corretto un errore di slotting — [[Bread Before Sunset|Pane Prima del Tramonto]] è **pomeriggio→tramonto** (quattro tappe, non rapida), quindi **non** è una quest del mattino. Ora è un **gancio del pomeriggio** (Marcia la offre al mattino, la corsa si gioca dopo, accanto alla Scorta).
- **[[Official Transport Escort|Scorta al Trasporto Ufficiale]] (Giorno 3):** rework per renderla "puzzolente" e far sentire i PG **complici**:
  - più **descrizioni**/gesti dei PNG; **landmark mnemonico** della magione di Varro (fontana-prua di marmo nero **sempre asciutta**, salita silenziosa, cipressi gemelli, battente a occhio chiuso) come **seme di memoria** per ritrovarla;
  - sezione **"Voci Discordanti"** con false piste e una narrativa-banditi piazzata in anticipo;
  - **Fase 9** come bivio decisivo: non seguire il carico "perso" = **biasimo + niente paga**; seguirlo porta a un deposito leggibile come **banditi che rivendono** (superficie, errato) **o messinscena** (profondità), con indizi distinti;
  - **Conclusione** con la **dichiarazione da firmare** = i PG diventano **testimoni dei banditi** (complici), con logica di paga esplicita;
  - falsa pista intatta: il filo punta ad **Aulus** come mano, mai a Varro come testa.

### Nuovi PNG e Archi Personali Atto 2 (Elira, Dario, Tommaso) (giu 2026)

Aggiunti due archi personali "alla Veltharuun" (5 tappe: indizi sottili → nome → confronto salvare/combattere), tarati sull'Atto 2, più i relativi PNG.

- **PNG creati** (template NPC standard, italiano con accenti): [[Elira]] (`05 - NPCs/Supporting NPCs` — mentore cantante di [[Hillara]], imprigionata), [[Dario]] (`05 - NPCs/Criminal Underworld` — ex capo-banda tradito da [[Filippo]], cacciatore libero con banda; nome reale **Dario**, alias "Ruggin"), [[Tommaso]] (`05 - NPCs/Supporting NPCs` — fratello di Filippo, leva e specchio).
- **File d'arco** (uno per arco) in `04 - Quests/Act 2 - Days 11-20/Personal Arcs/`:
  - [[Elira Arc - The Caged Song]]: Elira incolpata di un delitto del **[[Cult of Eternal Night|culto]]**; **falsa pista deliberata su [[Veltharuun]]** (non è lui); finale salvare/scagionare o perdere (martire). Tell = una **melodia**.
  - [[Dario Arc - The Debt Comes to Rome]]: Dario caccia [[Filippo]] con una banda e usa [[Tommaso]] come leva; finale combattere o risolvere (debito + riconciliazione). Tell = le **monete cadute**.
- Ogni file ha tabella sintesi con **giorni possibili, sender, combattimento, ricompensa** per tappa. Aggiunti i pointer nel roster PG di campaign_state (Hillara→Elira, Filippo→Dario).
- **Nota di continuità:** il background di Filippo nomina il capo sia "Ruggin" sia "Dario" → fissato **Dario** come nome reale.

### Tracker Relazioni PG (giu 2026)

Aggiunta a [[campaign_state|context/campaign_state.md]] una sezione **"Rapporti con i PG (punteggio)"**: tally numerico del rapporto dei PNG importanti verso il gruppo, da aggiornare quando le azioni dei PG lo spostano. Valori iniziali (utente): Marcia +2, Borin +1, Faustus +1, Asterio Falena -1, Cassian Rulfo -1. Aggiornata la checklist "Come aggiornare" del file di stato. **Discrepanza da confermare:** Asterio era "riconoscente" nel recap Sess. 4 (forse l'utente intendeva [[Caius Rutilo]]).

### Asterio -1 confermato + Gancio "Damigiane" (giu 2026)

- **[[Asterio Falena]] confermato a -1:** l'esito della [[Shop Dispute|Disputa alla Bottega]] è slittato alla 4.5 e i PG non l'hanno aiutato oltre un piccolo sconto (non il "contatto riconoscente" del recap Sess. 4). Aggiornati: tracker relazioni (tolto il ⚠️) e voce PNG Chiave in campaign_state; nota correttiva nel [[Session 04 - Day 02 Recap]]; scheda Asterio.
- **Gancio "Le Damigiane di Asterio"** in [[Session 05 - Day 03 Morning]] (sez. 6.5): i PG trovano le damigiane d'olio rubate di Asterio (marchio a falena), vuote o riempite d'**acqua ferma + sale nero** → vindica la sua denuncia (aggancio per risalire da -1) e semina il **buio organizzato** del [[Cult of Eternal Night|culto]] (luce sottratta alla città), coerente coi semi della sparizione e del marchio del lupo.

### File Tracker Relazioni Dedicato (giu 2026)

Creato **[[npc_relations|05 - NPCs/npc_relations.md]]**, file canonico per i rapporti PNG → PG: scala (+3…-3), tabella attuale (Marcia +2, Borin +1, Faustus +1, Asterio -1, Cassian -1), istruzioni d'aggiornamento, e nota di aggiungere [[Elira]]/[[Dario]]/[[Tommaso]] quando partono i loro archi. La sezione "Rapporti con i PG" in [[campaign_state|context/campaign_state.md]] è stata ridotta a **puntatore + snapshot** per evitare duplicazione/divergenza.

### Espansione Arco di Elira a Cavallo dei Due Atti (giu 2026)

Su richiesta dell'utente, l'[[Elira Arc - The Caged Song|Arco di Elira]] **non** deve iniziare e finire nell'Atto 1: rifatto sul modello a lungo respiro di [[Veltharuun]] (**inizio ~Giorno 5, climax Giorno 16-18, flessibile fino al 20**) e progettato per girare **in parallelo** all'[[Dario Arc - The Debt Comes to Rome|Arco di Dario]], così i giocatori vivono i due archi personali insieme.

- **Da 5 a 6 tappe, a cavallo Atto 1→Atto 2:** Q1 *La melodia in città* (G5-7) e Q2 *La stanza vuota* (G8-10) come **semi silenziosi dell'Atto 1**, agganciabili a quest già in corso ([[A Room for Those Who Cannot Return]], [[Bread Bought Twice]], [[Candles for the Old Chapel]]); Q3 *Una veglia andata storta* (G11-12), Q4 *Il nome: Elira* (G13), Q5 *Il delitto che non ha commesso* — colloquio in cella + indagine (G14-15), Q6 *Prima che canti* — climax salvare/martire (G16-18).
- **Motore emotivo (Hillara):** agganciato alle sue due paure canoniche dal background (paura media = essere abbandonata/dimenticata — Elira l'ha già lasciata una volta; paura grave = essere responsabile della morte di qualcuno — leva del finale se Elira muore martire), più l'**eco di Roderik** (fiducia tradita / Elira non perfetta) come twist opzionale.
- **Parallelo con Dario:** nuova sezione con **tabella giorno-per-giorno** (riflettore alternato Hillara/Filippo), nota di pacing sui due climax (**scaglionare** vs **collidere** in una notte di crisi doppia) e **intersezioni opzionali** (stesso fence/[[Spago]], stessa prigione/secondini) tenendo gli antagonisti separati — un arco **non** risolve l'altro.
- **Canone invariato:** falsa pista su [[Veltharuun]] (è il **[[Cult of Eternal Night|culto]]**, non lui; [[Aelius Nuurglaag]] mai nominato); rima con i beat Veltharuun ([[Day 11 - Corpi mancanti dalle fosse comuni|G11]], [[Day 16 - Persone scomparse dopo la veglia|G16]]) per sfruttare la memoria recente dei PG; mano "legale" [[Nerva Censore]] che silenzia le veglie. Aggiornati i tag frontmatter (`act/1`+`act/2`). `campaign_state` invariato (stato di gioco vivo fermo al Day 02).
- **Workflow:** da ora lavoro **nel vault vivo** (non nel worktree): il vault è sotto auto-sync e avanza di continuo, quindi il worktree restava indietro e i file `context/*` divergevano. Lavorando nel vault vivo l'auto-commit raccoglie tutto senza conflitti; push/PR restano dell'utente.
- **Aperto:** spacchettare Q1-Q6 in file quest play-facing singoli (`quest_markdown_rules`) quando richiesto; eventuale anticipo dei beat Q1-Q2 di Dario per un avvio davvero simultaneo dei due archi.
