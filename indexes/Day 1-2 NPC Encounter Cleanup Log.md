---
tags:
  - campaign/shadows-over-rome
  - cleanup
  - index
status: active
---

# Day 1-2 NPC And Encounter Cleanup Log

## Scope

Cleaned Day 1 and Day 2 quest/encounter material so NPC references follow the authoritative NPC notes. Also applied the global Cassian name correction requested by the user.

## Canon Name Correction

- Renamed the old Cassian NPC note to `05 - NPCs/Varro Network/Cassian Rulfo.md`.
- Replaced every old Cassian text/link occurrence with `Cassian Rulfo` across the vault.
- Renamed all encounter/routine files that had the old Cassian spelling in the filename.
- Verification: no remaining text occurrences or filenames containing the old Cassian spelling.

## NPC Link Corrections

Corrected old/source aliases to the authoritative NPC-note titles:

| Old use | Correct use |
| --- | --- |
| `Mauro tersi` | `[[Mauro Tersi]]` |
| `Vibius "Panciotto" Ennio` | `[[Vibius Panciotto Ennio]]` |
| `Pinna d?Argento` | `[[Pinna d’Argento]]` |
| `Maro Silanus\` | `[[Maro Silanus]]` |
| `Titus Falco\` | `[[Titus Falco]]` |
| `Sorella Aelia` | corrected to `[[Sorella Elenia]]` and renamed at table to Sorella Elenia |
| `Fratello Iovian` | `[[Frate Caldus]]` |
| `Matria Sabina` | `[[Sabina]]` |
| `Taverniere Lupo` | `[[Lupo]]` |
| `Facchino cieco Tito / Custode cieco Tito` | `[[Tito Senzasuola]]` |
| `Capitano Remus` | `[[Remus Aurelianus]]` |
| `Uomo di Aulus / Uomini di Aulus` | `[[Man of Aulus]]` |
| `Venditore Afer / Mercante Afer` | `[[Aferio Lento]]` |
| `Mercante Rufa / Venditrice Rufa` | `[[Rufina Sale]]` |
| `Guardiano Muto` | `[[Muto]]` |
| `Scaricatore Tiber` | `[[Tired Dockworker]]` |
| `Apprendista Numa` | `[[Numa Campanasecca]]` |
| `Terenzio delle chiavi` | `[[Terenzia Acquabassa]]` |
| `Publius` | `[[Publius - Apprentice]]` |

## Phantom NPC Link Cleanup

Removed wiki-links from one-off incidental encounter figures that do not currently have authoritative NPC notes. Their names remain as plain encounter text so the scenes still run normally without creating false NPC nodes.

Examples include street witnesses, animals, temporary crowds, unnamed guards, unnamed merchants, minor workers, children, and similar single-scene color figures in Day 1-2 random encounters.

## Location Alias Cleanup

After the NPC pass, several Day 1-2 broken links were actually place aliases. These were normalized to existing broad location notes:

| Old place link | New linked target |
| --- | --- |
| `Studio contrattuale` | `[[Merchant District|...]]` |
| `Spezieria / Spezieria di Flavius` | `[[Merchant District|...]]` |
| `Zona carovane` | `[[Outside the Walls|...]]` |
| `Vicolo della lanterna rotta` | `[[Slums|...]]` |
| `Casa privata di Brutus / Casa privata o studio` | `[[Noble District|...]]` |
| `Zone di scarico secondarie` | `[[Harbor District|...]]` |
| `Quartiere mercantile` | `[[Merchant District|...]]` |

## Verification

- Day 1-2 quest, random encounter, and NPC routine notes now have 0 broken wiki links.
- The old Cassian spelling has 0 remaining text occurrences.
- The old Cassian spelling has 0 remaining filenames.

## Files With Visible Renames Or Normalized References

The cleanup touched Day 1-2 quest/encounter files and renamed consistency files where needed. Key affected files include:

- `04 - Quests\Act 1 - Days 01-10\Day 01\Lost Ledger near the Harbor.md`
- `04 - Quests\Act 1 - Days 01-10\Day 01\Missing Cargo from the Docks.md`
- `04 - Quests\Act 1 - Days 01-10\Day 02\Delayed Shipment Mediation Needed.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Mattina - Anti-Merchant - Aferio Lento.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Mattina - Aulus Bandit - Muto.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Mattina - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Mattina - Independent Merchant - Vibius Panciotto Ennio.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Mattina - Varro's Merchant - Flavius Corvin.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Mattina - Varro's Merchant - Titus Falco.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Pomeriggio - Anti-Merchant - Aferio Lento.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Pomeriggio - Aulus Bandit - Muto.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Pomeriggio - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Pomeriggio - Independent Merchant - Vibius Panciotto Ennio.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Pomeriggio - Varro's Merchant - Titus Falco.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Anti-Merchant - Aferio Lento.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Anti-Merchant - Livia Cornelia Frizzapunto.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Anti-Merchant - Sergerro Atranus.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Aulus Bandit - Muto.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Independent Merchant - Vibius Panciotto Ennio.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Varro's Merchant - Decimus Varian.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Varro's Merchant - Titus Falco.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Mattina - Anti-Merchant - Aferio Lento.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Mattina - Anti-Merchant - Livia Cornelia Frizzapunto.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Mattina - Aulus Bandit - Muto.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Mattina - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Mattina - Independent Merchant - Vibius Panciotto Ennio.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Mattina - Varro's Merchant - Titus Falco.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Pomeriggio - Anti-Merchant - Aferio Lento.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Pomeriggio - Aulus Bandit - Muto.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Pomeriggio - Common Bandit - Pezza; Cencio.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Pomeriggio - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Pomeriggio - Independent Merchant - Vibius Panciotto Ennio.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Pomeriggio - Varro's Merchant - Flavius Corvin.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Pomeriggio - Varro's Merchant - Titus Falco.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Sera - Anti-Merchant - Aferio Lento.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Sera - Anti-Merchant - Brutus Verro.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Sera - Aulus Bandit - Muto.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Sera - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Sera - Independent Merchant - Vibius Panciotto Ennio.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Sera - Varro's Merchant - Titus Falco.md`

## Renamed Routine Files Containing Corrected Names

- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Mattina - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Mattina - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Pomeriggio - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Pomeriggio - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 01\Day 01 - Sera - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Mattina - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Mattina - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Pomeriggio - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Pomeriggio - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Sera - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 02\Day 02 - Sera - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 03\Day 03 - Mattina - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 03\Day 03 - Mattina - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 03\Day 03 - Pomeriggio - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 03\Day 03 - Pomeriggio - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 03\Day 03 - Sera - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 03\Day 03 - Sera - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 04\Day 04 - Mattina - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 04\Day 04 - Mattina - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 04\Day 04 - Notte - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 04\Day 04 - Pomeriggio - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 04\Day 04 - Pomeriggio - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 04\Day 04 - Sera - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 04\Day 04 - Sera - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 05\Day 05 - Mattina - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 05\Day 05 - Mattina - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 05\Day 05 - Pomeriggio - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 05\Day 05 - Pomeriggio - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 05\Day 05 - Sera - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 05\Day 05 - Sera - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 06\Day 06 - Mattina - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 06\Day 06 - Mattina - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 06\Day 06 - Pomeriggio - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 06\Day 06 - Pomeriggio - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 06\Day 06 - Sera - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 06\Day 06 - Sera - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 07\Day 07 - Mattina - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 07\Day 07 - Mattina - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 07\Day 07 - Pomeriggio - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 07\Day 07 - Pomeriggio - Main Character - Cassian Rulfo.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 07\Day 07 - Sera - Independent Merchant - Mauro Tersi.md`
- `08 - Systems and Tables\Encounter Tables\NPC Routines\Day 07\Day 07 - Sera - Main Character - Cassian Rulfo.md`
