# Coqvia Legal Pages → GitHub Pages

## Setup (einmalig, ~5 Minuten)

### Schritt 1: Neues GitHub Repository anlegen
1. github.com → „New repository"
2. Name: `coqvia-legal` (oder beliebig)
3. **Public** auswählen (Pflicht für GitHub Pages)
4. „Create repository"

### Schritt 2: Dateien hochladen
1. Im neuen Repo auf „Add file → Upload files"
2. Alle 3 HTML-Dateien aus diesem Ordner hochladen:
   - `index.html`
   - `privacy-policy.html`
   - `terms-of-service.html`
3. „Commit changes"

### Schritt 3: GitHub Pages aktivieren
1. Im Repo: **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / Ordner: **/ (root)**
4. „Save"
5. Nach ~1 Minute ist die Seite live unter:
   `https://DEIN-USERNAME.github.io/coqvia-legal/`

---

## Deine URLs für App Store Connect

| Zweck | URL |
|---|---|
| **Datenschutzerklärung** | `https://DEIN-USERNAME.github.io/coqvia-legal/privacy-policy.html` |
| **Nutzungsbedingungen** | `https://DEIN-USERNAME.github.io/coqvia-legal/terms-of-service.html` |

---

## Bevor du veröffentlichst – prüfe:
- [ ] E-Mail `support@coqvia.app` existiert und wird gelesen
- [ ] Datum in beiden HTML-Dateien aktualisieren
- [ ] Supabase-Serverstandort prüfen (EU oder US?) → ggf. in Datenschutzerklärung ergänzen
