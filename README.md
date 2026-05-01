# Ecommerce-Sorgentelefon (Static HTML)

Diese Website ist jetzt eine reine statische Seite (plain HTML + CSS) ohne Jekyll.

## Struktur

- `index.html` - komplette One-Page inklusive Impressum im Footer
- `assets/css/site.css` - Styles fuer die Seite
- `images/` - Bilder und Assets

## Lokal testen

Du kannst die Seite direkt im Browser oeffnen:

- `index.html` doppelklicken

oder einen kleinen lokalen Server starten:

```bash
python3 -m http.server 8080
```

Dann unter <http://localhost:8080> aufrufen.

## Deployment

GitHub Pages deployed als statische Seite:

- Workflow: `.github/workflows/jekyll-gh-pages.yml` (statisches Artifact, kein Jekyll-Build)
- `.nojekyll` ist gesetzt, damit GitHub Pages Jekyll nicht aktiviert.
