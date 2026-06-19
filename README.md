# zonesnap-legal

Statische Rechts-/Support-Seiten für die iOS-App **ZoneSnap**, gehostet über
GitHub Pages (analog zu `showup-legal`).

| Datei | Zweck | App-Store-Connect-Feld |
|-------|-------|------------------------|
| `privacy.html` | Datenschutzerklärung (DE + EN) | **Datenschutz-URL** (Pflicht) |
| `support.html` | Support & Kontakt | **Support-URL** (Pflicht) |
| `impressum.html` | Impressum nach § 5 DDG | — |
| `index.html` | Startseite mit Links | Marketing-URL (optional) |

## Veröffentlichen (GitHub Pages)

1. Repo auf GitHub anlegen: `zonesnap-legal` (public).
2. Diesen Ordner pushen:
   ```bash
   git remote add origin https://github.com/MisterLG/zonesnap-legal.git
   git push -u origin main
   ```
3. Auf GitHub: **Settings → Pages → Branch: `main` / `root`** → Save.
4. Nach ein paar Minuten erreichbar unter:
   - Datenschutz: `https://misterlg.github.io/zonesnap-legal/privacy.html`
   - Support: `https://misterlg.github.io/zonesnap-legal/support.html`

Diese beiden URLs in App Store Connect eintragen.
