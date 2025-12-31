# Tetris JS – Gioco web in HTML/CSS/JavaScript

Un semplice ma completo clone realizzato con **HTML**, **CSS** e **JavaScript** puro, senza framework. Il gioco è colorato, supporta più velocità e include tutti i classici tetramini.[1][2]

## Caratteristiche

- 7 pezzi classici (I, O, T, S, Z, J, L), ciascuno con un colore differente.[3]
- Diverse velocità di gioco selezionabili (livelli di difficoltà crescenti).[4]
- Punteggio, linee completate e livello visualizzati in tempo reale.[1]
- Anteprima del prossimo pezzo.[2]
- Pausa e ripresa della partita.[2]
- Interfaccia responsive, giocabile anche da browser mobile moderni.[1]

## Controlli

- **Freccia sinistra**: muovi il pezzo a sinistra.[2]
- **Freccia destra**: muovi il pezzo a destra.[2]
- **Freccia giù**: discesa veloce del pezzo.[2]
- **Freccia su**: ruota il pezzo.[2]
- **Barra spaziatrice**: caduta immediata (hard drop).[5]
- **P**: pausa/ripresa del gioco.[5]

Puoi modificare i controlli nella parte JavaScript del file index se desideri usare una diversa mappatura dei tasti.[2]

## Struttura del progetto

- `index.html`   – Contiene il markup della griglia di gioco, HUD (score/level/lines) e controlli UI.[1]
                 - Nella parte css iniziale gestisce layout, colori dei pezzi, effetti glow e stile generale della pagina.[6]
                 – Nella parte <script> tramite js implementa logica di gioco, gestione input, collisioni, rimozione linee e avanzamento livello.[2]

## Come eseguire il gioco in locale

1. Clona il repository:
   ```bash
   git clone https://github.com/<tu-username>/<nome-repo>.git
   cd <nome-repo>
   ```
2. Apri `index.html` con il tuo browser preferito (Chrome, Firefox, Edge, ecc.).[1]
3. Inizia a giocare e regola la velocità dal selettore/controllo dedicato nell’interfaccia.[1]

Per uno sviluppo più comodo, puoi usare un semplice server statico (es. `npx serve`, `live-server` o l’estensione Live Server di VS Code).[7]

## Personalizzazione

- Modifica i **colori dei pezzi** nel CSS (classi associate ai singoli tetramini).[6]
- Cambia le **velocità per livello** nel file JavaScript, regolando l’intervallo del timer di discesa.[4]
- Aggiungi **suoni** per rotazione, caduta e eliminazione righe collegando eventi di gioco a file audio.[8]
- Integra un sistema di **high score** salvando il punteggio su `localStorage`.[7]

## Licenza

Questo progetto è rilasciato sotto licenza **MIT**; puoi utilizzare, modificare e ridistribuire il codice liberamente mantenendo l’avviso di copyright e la licenza.[5]

