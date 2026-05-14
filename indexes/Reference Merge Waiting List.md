---
tags:
  - campaign/shadows-over-rome
  - migration
  - index
status: active
---

# Reference Merge Waiting List

Reference repo: `Wazard/Shadows-over-Rome@main`

This report compares the current Obsidian vault against the reference repo tree. It tracks what still needs a usable merge, not just whether a filename exists somewhere.

## Summary

- Reference files scanned: 118
- Waiting / needs review: 40
- Merged, usable, or downloaded: 64
- Intentionally skipped: 14

## Highest Priority

1. Split `CSVs/Encounters/Routines/day1-7_Secondary_characters_routine.csv`; it exists on `main` and is not represented by the current split encounter notes.
2. Convert the four `CSVs/Market` files from raw tables into usable market/shop/item notes, then link item images.
3. Reconcile `CSVs/Quests/Il_Veliero_quest_board.csv` against the daily quest notes and the Il Veliero board.
4. Review raw/partial Act 2 and Act 3 sources for playable notes, especially dynamic NPC and guide material.
5. Link downloaded images/audio from the relevant NPC, location, item, and handout notes.

## missing split migration

| Reference file | Current state / action |
| --- | --- |
| `CSVs/Encounters/Routines/day1-7_Secondary_characters_routine.csv` | This main-branch routine CSV is not represented by the split encounter/routine notes. |

## raw table only

| Reference file | Current state / action |
| --- | --- |
| `CSVs/Market/Cleric_services.csv` | CSV source is present as a table, but still needs usable market/shop/item notes and image links. |
| `CSVs/Market/Day1-7_Central_market_stocks.csv` | CSV source is present as a table, but still needs usable market/shop/item notes and image links. |
| `CSVs/Market/Day5-10_Black_market_stocks.csv` | CSV source is present as a table, but still needs usable market/shop/item notes and image links. |
| `CSVs/Market/Day5-10_Inner_black_market.csv` | CSV source is present as a table, but still needs usable market/shop/item notes and image links. |

## reconcile quest board

| Reference file | Current state / action |
| --- | --- |
| `CSVs/Quests/Il_Veliero_quest_board.csv` | Quest-board CSV exists, but should be reconciled with daily quest notes and Il Veliero board. |

## raw or partial merge

| Reference file | Current state / action |
| --- | --- |
| `Diego_Dossier_PNG.docx` | Source exists, but should be folded into usable NPC/world/handout notes or cleaned. |
| `Er Trace Description.txt` | Source exists, but should be folded into usable NPC/world/handout notes or cleaned. |
| `Lista_NPC_Campagna.docx` | Source exists, but should be folded into usable NPC/world/handout notes or cleaned. |
| `Lista_NPC_Campagna_Riorganizzata.docx` | Source exists, but should be folded into usable NPC/world/handout notes or cleaned. |
| `Sigils.docx` | Source exists, but should be folded into usable NPC/world/handout notes or cleaned. |
| `introduzione_roma.docx` | Source exists, but should be folded into usable NPC/world/handout notes or cleaned. |
| `phase 1/Major events/Cult_plan_phase_1.docx` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 1/Major events/Marcia_plan_phase_1.docx` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 1/Major events/Varro_Plan_and_Endings.docx` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 1/Marcia_s_story_Varro.docx` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 1/Routine_NPC_Fase_1_Giorni_1_7.docx` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 1/Sessione1_Scaletta.docx` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 1/Sessione2_Scaletta.docx` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 1/Shadows_Over_Rome_Phase1_DM_Guide.docx` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 1/Varro_s_plan.txt` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 1/varro_background_narrativo.docx` | Act 1 source exists, but needs review against playable Act/day notes. |
| `phase 2/Diego Quest 2.txt` | Act 2 source exists, but needs conversion/review for playability. |
| `phase 2/Diego_Kidnapping_Scene_Day16.docx` | Act 2 source exists, but needs conversion/review for playability. |
| `phase 2/Diego_Quest_2_COMPLETE.docx` | Act 2 source exists, but needs conversion/review for playability. |
| `phase 2/Dynamic_NPC_Phase2.docx` | Act 2 source exists, but needs conversion/review for playability. |
| `phase 2/Shadows_Over_Rome_Phase2_DM_Guide.docx` | Act 2 source exists, but needs conversion/review for playability. |
| `phase 3/Aelius_Final_Confrontation.docx` | Act 3 source exists, but needs conversion/review for playability. |
| `phase 3/Diego Quest 3.txt` | Act 3 source exists, but needs conversion/review for playability. |
| `phase 3/Diego_Quest_3_COMPLETE.docx` | Act 3 source exists, but needs conversion/review for playability. |
| `phase 3/Dynamic_NPC_Phase3.docx` | Act 3 source exists, but needs conversion/review for playability. |
| `phase 3/Shadows_Over_Rome_Phase3_DM_Guide.docx` | Act 3 source exists, but needs conversion/review for playability. |
| `phase 3/Siege_of_Rome_Quest.docx` | Act 3 source exists, but needs conversion/review for playability. |

## verify playable quest

| Reference file | Current state / action |
| --- | --- |
| `phase 1/quests/Day3/Day3_Escort_Merchant_Official.docx` | Quest source may have a playable note, but no exact source reference was found by this scan. |

## verify handout merge

| Reference file | Current state / action |
| --- | --- |
| `players/Background Apollodoro.txt` | Player background source should be checked against player handout notes. |
| `players/Background Auris.txt` | Player background source should be checked against player handout notes. |
| `players/Background Filippo.txt` | Player background source should be checked against player handout notes. |
| `players/Background Massimiliano.txt` | Player background source should be checked against player handout notes. |

## confirm renamed asset

| Reference file | Current state / action |
| --- | --- |
| `images/Rome Large Map final.png` | Likely downloaded as Rome map.png, but source linkage/name should be confirmed. |

## missing asset

| Reference file | Current state / action |
| --- | --- |
| `images/a132d1ce-b083-4848-b907-d47fd46b84be.png` | No obvious local asset with this filename. |

## Done Or Present

These files appear to be merged, usable, or downloaded. Some may still need polish, but they are not the immediate waiting list.

| Reference file | Status |
| --- | --- |
| `CSVs/Encounters/Day1-7_random_encounters.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/Encounters/Day8-9_random_encounters.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/Encounters/Routines/Day1-7_Main_characters_routine.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/Encounters/Routines/day1-7_Against_merchants_routine.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/Encounters/Routines/day1-7_Aulus_bandits_routine.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/Encounters/Routines/day1-7_Cassian_men_routine.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/Encounters/Routines/day1-7_Independent_merchants_routine.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/Encounters/day1-7_Guard_Rounds.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/NPCs/NPC_primari.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/NPCs/NPC_secondari.csv` | Merged or usable: Exact source reference found in vault. |
| `CSVs/NPCs/NPC_terziari.csv` | Merged or usable: Exact source reference found in vault. |
| `Campaign_Endings_Shadows_Over_Rome.docx` | Merged or usable: Exact source reference found in vault. |
| `Il Veliero.txt` | Merged or usable: Exact source reference found in vault. |
| `Player_Handout.docx` | Merged or usable: Exact source reference found in vault. |
| `Sea_and_Failure_Feedback_System.docx` | Merged or usable: Exact source reference found in vault. |
| `images/Cult_sigil.png` | Merged or usable: Exact source reference found in vault. |
| `images/Cult_sigil_10.png` | Merged or usable: Exact source reference found in vault. |
| `images/Cult_sigil_20.png` | Merged or usable: Exact source reference found in vault. |
| `images/Er_trace.png` | Merged or usable: Exact source reference found in vault. |
| `images/Government_sigil.png` | Merged or usable: Exact source reference found in vault. |
| `images/Il_Veliero_Bar.png` | Merged or usable: Exact source reference found in vault. |
| `images/Il_Veliero_Esterno.png` | Merged or usable: Exact source reference found in vault. |
| `images/Il_Veliero_Sala_da_pranzo.png` | Merged or usable: Exact source reference found in vault. |
| `images/Il_Veliero_Stanza.png` | Merged or usable: Exact source reference found in vault. |
| `images/La bestia cucita.png` | Merged or usable: Exact source reference found in vault. |
| `images/Merchant_sigil.png` | Merged or usable: Exact source reference found in vault. |
| `images/Varro_sigil.png` | Merged or usable: Exact source reference found in vault. |
| `phase 1/Diego Quest 1.txt` | Merged or usable: Exact source reference found in vault. |
| `phase 1/Er Trace re del Veliero.mp3` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day1/Day1_Lost_Ledger.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day1/Day1_Marcia_Canto_Piazza.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day1/Day1_Missing_Cargo.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day1/Day1_Rumore_Fetch_Pacco_Spezieria.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day1/Day1_Rumore_Lupi_fuori_dalle_mura.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day2/Day2_Rumore_Consegna_contesa_al_mercato.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day2/Day2_Rumore_Disputa_Bottega.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day2/Day2_Rumore_Lanterna_del_vicolo_storto.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day2/Day2_Varro_Delayed_Shipment_Mediation_Needed.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day2/Day2_Varro_Furto_alla_forgia.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day3/Day3_Controllo_su_consegna_non_registrata.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day3/Day3_Escort_Required_Official_Transport.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day3/Day3_Mercante_rifiuta_consegna.txt` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day3/Day3_Pane_prima_del_tramonto.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day3/Day3_Verifica_discreta_su_doppia_registrazione.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day4/Day4_Disputa_sui_prezzi.txt` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day4/Day4_Farina_promessa_farina_sparita.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day4/Day4_Guardie_richieste_per_trasporto_breve.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day4/Day4_Ricevute_sporche_Quest_Ramificata.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day5_Diego_Quest_1_Tutto_Strano.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day5_Mercanti rifiutano consegne.txt` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day5_Una_stanza_per_chi_non_puo_tornare.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day5_pane comprato due volte.txt` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day6_Confronto pubblico sui registri di grano.txt` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day6_Disputa consegna cargo numeri errati.txt` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day6_Workers_Missing_Quest.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day7_Candele_per_la_cappella_vecchia.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day7_Carovana mancante strada sud.txt` | Merged or usable: Exact source reference found in vault. |
| `phase 1/quests/Day7_Tax_Collector_Quest.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 2/quests/Day11_Corpi_mancanti_dalle_fosse_comuni.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 2/quests/Day13_14_Arthemol_Coro_di_Carne_Quest.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 2/quests/Day13_14_Bestia_nei_bassifondi.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 2/quests/Day13_Drowned_Shrine_Quest.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 2/quests/Day15_Caravan_Escalation.docx` | Merged or usable: Exact source reference found in vault. |
| `phase 2/quests/Day16_Persone_scomparse_dopo_la_veglia.docx` | Merged or usable: Exact source reference found in vault. |

## Intentionally Skipped

Skipped files are app executables, Python tooling, repo metadata, or files excluded by campaign rules unless explicitly requested.

| Reference file | Reason |
| --- | --- |
| `.gitignore` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `Apps/EncountersReader.exe` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `Apps/MarketViewer.exe` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `Apps/QuestBoard.exe` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `Apps/python/EncounterViewerApp.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `Apps/python/NPCViewerApp.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `Apps/python/QuestApp.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `Apps/python/StockMarketApp.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `phase 1/quests/Day4/Day4_Una_Stanza_per_chi_non.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `phase 3/python/Diego_quest.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `phase 3/python/Last_battle.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `phase 3/python/NPCs.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `phase 3/python/phase_3.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
| `phase 3/python/siege_quest.py` | Repo/app/python/support file excluded by campaign bible unless explicitly requested. |
