# Aries Fashion — Boutique-Website

Statische Single-Page-Website für **Aries Fashion GmbH**, Berger Straße 63, 60316 Frankfurt am Main
(inhabergeführte Damenmode-Boutique im Nordend, 5,0★ bei Google).

**Live:** https://adamanm780-dotcom.github.io/aries-fashion-website/

## Aufbau

| Pfad | Inhalt |
|---|---|
| `index.html` | komplette Seite (HTML + CSS + JS inline) |
| `assets/` | Fotos, Logos, freigestellte Blüten (WebP), OG-Bild |
| `frames/` | 80 Frames für die Scroll-Bildsequenz |
| `flowers/` | Frame-Sequenzen der animierten Blüten (peony, rose) |
| `favicon.svg` | Favicon |

Alle Asset-Pfade sind **relativ** (`assets/…`, `frames/…`, `flowers/…`), damit die Seite
unter dem GitHub-Pages-Unterpfad `/aries-fashion-website/` funktioniert.

## Deployment

GitHub Pages, Branch `main`, Ordner `/` (root). Push auf `main` → Pages baut automatisch neu.
`.nojekyll` verhindert die Jekyll-Verarbeitung.

## Lokale Vorschau

```bash
npx http-server . -p 8195
```

---
FlowState · Webdesign
