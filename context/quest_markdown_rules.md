---
tags:
  - campaign/shadows-over-rome
  - context
  - style-guide
status: active
---
# Regole Markdown per le Quest

Queste regole sono canone operativo per scrivere e riformattare le quest di Shadows Over Rome.

## Struttura obbligatoria iniziale

Ogni quest deve aprirsi con:

> [!motive] Motivo
> Perché i PG dovrebbero accettare la quest, cosa li spinge dentro la scena e quale pressione narrativa rende il lavoro rilevante.

> [!summary] Riassunto
> Versione breve giocabile: contesto, obiettivo, minaccia, tono e durata prevista.

> [!success] Esiti possibili
> Elenco sintetico degli esiti principali: successo pieno, successo parziale, fallimento, conseguenze sociali, conseguenze future.

Subito dopo deve esserci una tabella con:

| Campo | Dettaglio |
| --- | --- |
| Giorno | Link al giorno |
| Luogo | Link al luogo |
| PNG coinvolti | Link ai PNG |
| Tipi di CD principali | CD colorate per caratteristica |
| Combattimento | Nessuno / possibile / probabile / boss |
| Ricompensa | Monete, favori, oggetti, reputazione |

## Callout evidenti

Usare callout Obsidian per rendere il testo scansionabile:

- `> [!readaloud]` per testo da leggere ai giocatori.
- `> [!description]` per descrizioni ambientali non necessariamente lette parola per parola.
- `> [!summary]` per riassunti GM e liste.
- `> [!motive]` per motivazione della quest.
- `> [!success]` per esiti e ricompense positive.
- `> [!warning]` per rischi, complicazioni e gestione cauta.
- `> [!danger]` per pericoli mortali, bossfight e conseguenze pesanti.
- `> [!warning]` per chiarimenti di continuity o uso al tavolo.
- `> [!clue]` per indizi importanti.

## Dialoghi colorati per PNG

Ogni PNG con dialoghi ricorrenti nella quest deve avere un colore assegnato nella tabella iniziale o nella sezione "PNG e colori". Tutte le sue battute devono usare lo stesso colore. Il colore del png deve essere scritto: `<span style="color:#color">color #color</span>`

Formato consigliato:

`<span style="color:#3366cc"><strong>Nome PNG</strong></span>[[Nome PNG|link]]: "Battuta del PNG."`

Se il PNG non ha una nota:

`<span style="color:#3366cc"><strong>Nome PNG</strong></span>: "Battuta del PNG."`

Non cambiare colore allo stesso PNG dentro la stessa quest.

## CD colorate per caratteristica

Le prove devono essere colorate in base alla caratteristica dominante.

| Caratteristica | Colore | Uso |
| --- | --- | --- |
| FOR | Rosso `#d64545` | Forza, Atletica, prove fisiche brutali |
| DES | Arancione `#e68632` | Destrezza, Furtività, Disattivare Congegni, Acrobazia |
| COS | Verde `#3f8f4c` | Costituzione, resistenza, veleni, fatica |
| INT | Azzurro `#2f9ed8` | Conoscenze, Investigazione, Sapienza Magica, Artigianato tecnico |
| SAG | Viola `#8b5cf6` | Percezione, Guarire/Medicine, Sopravvivenza, Intuizione |
| CAR | Giallo `#d6a500` | Diplomazia, Raggirare, Intimidire, Intrattenere |

Formato consigliato:

`<span style="color:#8b5cf6"><strong>Perception CD 15</strong></span>`

Se una prova può usare più approcci, colorare ogni opzione in base alla caratteristica:

`<span style="color:#d64545"><strong>Athletics CD 15</strong></span> oppure <span style="color:#2f9ed8"><strong>Engineering CD 15</strong></span>`

## Tabelle di indizi

Ogni quest investigativa deve avere una tabella indizi con:

| Indizio | CD | Dove | PNG coinvolti | Cosa sembra | Cosa significa | Rischio |
| --- | --- | --- | --- | --- | --- | --- |

Le CD nella tabella devono usare il colore della caratteristica dominante.

## Lingua

Tutto il materiale di campagna scritto per Shadows Over Rome deve essere in italiano con accenti corretti.
