# Report Statistico 2026 — U.O. San Lorenzo

Report statistico standalone: singolo file HTML con CSS e JavaScript inline, nessuna dipendenza da installare.

## Uso

Pubblicato su GitHub Pages: apri l'URL del sito e usa direttamente dal browser.
In alternativa, scarica `index.html` e aprilo con un doppio clic.

## Note tecniche

- Il file sorgente è `index.html` (rinominato da `report_statistico_2026.html` perché GitHub Pages serve `index.html` come pagina principale).
- I dati caricati (Excel/PDF) restano nel browser tramite `localStorage`: non vengono inviati a nessun server.
- Il file carica da CDN esterne le librerie SheetJS (xlsx) e pdf.js, e i font da Google Fonts: serve una connessione a Internet.
- La schermata di login è un controllo lato client: utili per separare i ruoli in ufficio, non è una misura di sicurezza.
