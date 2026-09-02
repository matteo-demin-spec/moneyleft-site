# moneyleft-site

Pagine pubbliche di **MoneyLeft** (app iOS di finanze personali), usate come
URL di assistenza e di informativa privacy su App Store Connect.

- `index.html` &mdash; pagina di presentazione dell'app
- `assistenza.html` &mdash; assistenza e domande frequenti
- `img/` &mdash; schermate dell'app, ricavate da quelle di App Store
- `privacy.html` &mdash; informativa privacy
- `termini.html` &mdash; termini di servizio

I testi di privacy e termini sono gli stessi mostrati dentro l'app
(`Schermate/Impostazioni/PaginaLegale.swift`): se cambiano l&igrave;, vanno
aggiornati anche qui.

Pubblicate con GitHub Pages. Nessuna dipendenza esterna: HTML e CSS in un
solo file per pagina.

L'URL di assistenza su App Store Connect deve puntare a `assistenza.html`,
non pi&ugrave; alla radice: alla radice ora c'&egrave; la presentazione.
