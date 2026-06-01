---
tags:
  - campaign/shadows-over-rome
  - context
  - log
status: active
---
# Log dei Lavori

Registro cronologico delle modifiche fatte all'archivio.

## 2026-06-01

- **Riformattazione prep Sessione 3** ([[Session 03 - Day 02 Festival Pressure]]) secondo `context/quest_markdown_rules.md`: aggiunti i callout obbligatori (motive / summary / success), la tabella dei campi, le CD colorate per caratteristica, i colori di dialogo per PNG e la tabella indizi a 7 colonne. Tutto in italiano.
- **Riassunto Sessione 3 (in corso)**: creato [[Session 03 - Day 02 Recap]] con piazza del mercato, [[Marcia]], il suono fallito di Apollodoro che ha imitato i fuochi d'artificio e attirato le guardie, i sospetti alla forgia di [[Borin Martelferro]] e la testimonianza di [[Lippo]] sulle due figure notturne ("non erano pagate per far casino"). Marcato `status: in-progress`.
- **Nuovo NPC [[Lippo]]**: creata la scheda del bambino dei vicoli che parla con gli animali, primo testimone del furto alla forgia; impostato come informatore ricorrente.
- **Rinominato il mercante [[Lippo Gualdo]] → [[Lappo Gualdo]]** per liberare il nome "Lippo" per il bambino. Aggiornati i backlink in [[NPC Index]], [[Missing Cargo from the Docks]], [[Promised Flour Missing Flour]] e [[Act 1 Clue Escalation Table]]; corretta una riga di tabella malformata nell'indice NPC; vecchio nome mantenuto come alias. (I CSV sorgente in `10 - GM Reference` restano col nome originale.)
- **Git**: commit e push sul branch `session-03-quest-rules-rewrite` (commit `6ce5886` per la riformattazione, `60f8ef8` per recap + Lippo + rename). PR non aperta automaticamente perché `gh` non è installato sulla macchina; fornito il link manuale per crearla.
- **Fabbri umani (NPC nuovi)**: verificato che nel canone non esisteva alcun fabbro umano nominato (l'unico umano con "mani da fabbro" è [[Decimus Varian]], ma è mercante d'armi della rete Varro). Creati due stub provvisori in `05 - NPCs/Merchant NPCs`: [[Tullio Spaccaferro]] e [[Macra Carbonera]], fabbri della forgia rivale di [[Borin Martelferro]], sospetti plausibili ma non colpevoli nella quest [[Forge Theft]]. Aggiunti al [[NPC Index]] sotto "Mercanti indipendenti" e linkati nel recap della Sessione 3. Nomi da confermare/rinominare se al tavolo erano usciti nomi diversi.
