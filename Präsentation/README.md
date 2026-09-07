# The Whitelabels — Onboarding-Präsentation

Eine reveal.js-Präsentation (Single-File `index.html`) als 15-minütiges Onboarding-Overview.

## Starten

`index.html` im Browser öffnen — reveal.js und Fonts werden per CDN geladen, es ist kein Build nötig.

## Ordnerstruktur

```
.
├── index.html            # Die Präsentation (Markup, CSS, Slides)
├── assets/
│   ├── team/             # Portraitfotos der Teammitglieder (Slide "The people")
│   ├── brands/           # Screenshots der Whitelabel-Brands & Prototypen
│   ├── charts/           # Quell-Screenshots der Jira/Tableau-Kennzahlen
│   ├── logos/            # idealo-Logos (private label / whitelabel)
│   └── misc/             # Motto-Bilder (cash cow, paper jet)
├── data/                 # Rohdaten: Lead-ins / Clickouts 2025 (CSV)
└── docs/                 # Hintergrundmaterial (About Whitelabels)
```

## Assets pflegen

Bildpfade in `index.html` sind relativ (z. B. `assets/team/…`). Beim Austauschen
eines Bildes den Dateinamen beibehalten oder die `src`/`url()`-Referenz mit anpassen.
