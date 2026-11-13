# DealFinder — Web App installabile

## Contenuto
- `index.html`: interfaccia mobile e logica dell'app
- `manifest.webmanifest`: impostazioni PWA
- `sw.js`: cache offline di base
- `icons/icon.svg`: icona

## Anteprima e limiti
Questa versione è un prototipo funzionante: ricerca, categorie, ordinamento e preferiti locali. I prezzi e i prodotti sono **esempi fittizi**, chiaramente segnalati nell'interfaccia. Non ci sono ancora collegamenti a cataloghi o prezzi reali.

## Come installarla su iPhone
La PWA deve essere pubblicata su un indirizzo HTTPS. Dopo la pubblicazione:
1. Apri l'indirizzo in Safari su iPhone.
2. Tocca Condividi.
3. Scegli **Aggiungi alla schermata Home**.
4. Conferma.

Per la fase successiva servono una fonte lecita e aggiornata di prezzi/prodotti e la scelta di come gestire i link ai negozi. Non inserire credenziali o chiavi API nel codice pubblico.
