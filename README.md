# Ventaglio

Synth virtual analog ritmico per browser (Web Audio API, nessuna dipendenza), suonabile con la tastiera del Mac.
Apri `index.html` in Chrome, Safari o Firefox, premi ACCENDI (o un tasto nota) e suona.

## Tastiera
- `A S D F G H J K L ò à` tasti bianchi, `W E T Y U O P` tasti neri
- `Z` / `X` ottava giù/su, `C` / `V` velocità
- `Q` arpeggiatore, `R` trance gate, `spazio` hold, `N` / `M` suono precedente/successivo, `esc` silenzia tutto

## Touch (telefono e tablet)
- Tastiera piatta a sfioramento, multitouch: tocca più in basso per suonare più forte, scorri verso l'alto sul tasto per aprire il filtro (aftertouch)
- Striscia PITCH (±2 semitoni, torna al centro) e striscia MOD (apre il filtro)
- Su schermo stretto la tastiera resta fissa in basso; i pulsanti sopra fanno ottava, hold, arp, gate, REC e play
- Su iPhone togli il silenzioso, altrimenti il Web Audio non suona

## Registratore di pattern
- `B` REC (parte anche il loop se è fermo), `invio` play/stop, `⌫` annulla l'ultima ripresa
- Loop di 1, 2 o 4 battute in sedicesimi, quantizzazione, metronomo, sovraincisione; registra anche l'uscita dell'arpeggiatore
- Il pattern resta salvato nel browser e non cambia quando cambi suono

## MIDI
Premi "Attiva MIDI" (funziona in Chrome/Edge sulla pagina pubblicata come file o su hosting; nell'anteprima Artifact il browser lo blocca).
CC74 o CC1 = cutoff, CC71 = risonanza, CC64 = hold con arpeggiatore attivo.

## Pubblicarlo online
Carica `index.html` su GitHub Pages, Netlify Drop o Cloudflare Pages: basta un hosting statico.
