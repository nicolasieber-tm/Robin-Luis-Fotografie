# Robin Luis Fotografie – Website Redesign

Statischer One-Pager mit Buchungs-Overlay (Kennenlern-Gespräch).

## Lokal starten

```
npm install
npm start
```

## Railway

Railway erkennt das `package.json` automatisch (Nixpacks) und startet `npm start`.
Der Server (`serve`) liefert `index.html` auf dem von Railway gesetzten `$PORT` aus.

## Offene Punkte für den Livegang

- Bilder sind aktuell von robinluisfotografie.ch verlinkt – für Produktion lokal hosten.
- Buchungsanfrage wird noch nicht versendet (kein Backend). Payload liegt fertig als JSON in `submitBooking()` in `index.html` – dort Endpoint (Formspree, CRM, o.ä.) einhängen.
- Preise stehen als «auf Anfrage».
