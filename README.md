# Sito vetrina base

Sito statico in HTML e CSS, senza librerie esterne e senza passaggi di compilazione. È un punto di partenza neutro da adattare a un'attività reale. Tutti i contenuti sono segnaposto fittizi.

## Struttura

- `index.html` contiene la pagina unica con le sezioni Servizi, Chi siamo, Orari, Contatti.
- `privacy.html` è una pagina segnaposto da sostituire con un'informativa corretta.
- `assets/style.css` contiene tutti gli stili. I colori e il raggio degli angoli si cambiano dalle variabili in cima al file.
- `assets/script.js` gestisce solo il menu su telefono e l'anno nel footer.

## Provarlo in locale

Apri `index.html` nel browser. Per una prova più fedele alla pubblicazione, dalla cartella del progetto esegui `python -m http.server 8000` e vai su `http://localhost:8000`.

## Pubblicarlo con GitHub Pages

1. Crea un repository su GitHub e carica questi file nella radice.
2. Vai in Settings, poi Pages.
3. In Source scegli il ramo `main` e la cartella `/ (root)`.
4. Dopo qualche minuto il sito è raggiungibile all'indirizzo che GitHub mostra nella stessa pagina.

Le condizioni del servizio gratuito possono cambiare, quindi controlla la documentazione ufficiale di GitHub Pages.

## Adattarlo a un cliente

1. Sostituisci titolo, descrizione e tutti i testi, e togli `noindex` dal tag `meta robots` quando il sito è pronto per comparire sui motori di ricerca.
2. Inserisci foto reali del cliente, con testo alternativo e dimensioni ottimizzate.
3. Aggiorna telefono, email, indirizzo e orari. I dati presenti sono fittizi.
4. Sostituisci `privacy.html` con un'informativa corretta.
5. Se serve un modulo di contatto, serve un servizio che riceva i messaggi, perché un sito statico da solo non può inviare email. Valuta le opzioni e le implicazioni privacy prima di aggiungerlo.
6. Se incorpori mappe, video o statistiche di terze parti, ricordati che possono richiedere il consenso ai cookie.

## Scelte fatte di proposito

- Nessun font o script da servizi esterni, per avere un sito veloce e meno problemi di privacy.
- Colori scuri e chiari automatici in base alle impostazioni del dispositivo.
- Struttura semantica, link di salto al contenuto e focus visibile per la tastiera.
