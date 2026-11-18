Pagina pubblicata: https://mattiabaldinazzo.github.io/generatore_dati_azienda/

# Generatore dati azienda

Pagina che genera dati di fantasia per testare la maschera "Crea nuova azienda".

## Lettore QR

In fondo alla pagina c'e' un lettore QR: incolli uno screenshot con Ctrl+V, oppure trascini o scegli dal PC una o piu' immagini insieme. La lettura avviene nel browser con zxing-wasm, copiato nella cartella `vendor/`: nessuna immagine esce dal PC.

## Come aggiornarlo

1. Sostituisci `index.html` con la nuova versione (e la cartella `vendor/` se cambia).
2. Fai il commit: `git add index.html vendor && git commit -m "Aggiorna generatore"`
3. Fai il push: `git push origin main`

GitHub Pages pubblica la nuova versione in circa un minuto.

## Nota

Tutti i dati generati sono inventati e non corrispondono ad aziende o persone reali.
