
# Storytime Roleplay – Regelwerk (GitHub Pages Template)

Dies ist eine sofort nutzbare Vorlage, um euer Regelwerk als GitHub Pages Webseite zu veröffentlichen.

## Schnellanleitung (ohne Vorwissen)

1. **Neues Repository erstellen** auf GitHub, z. B. `storytime-regelwerk`.
2. Die Inhalte dieses Ordners **hochladen** (entweder als ZIP entpacken und pushen, oder im GitHub Web-UI).
3. In den Repository-Einstellungen: **Settings → Pages**
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` (oder `master`) und **Folder:** `/docs`
   - Speichern. Nach 1–2 Minuten ist die Seite live.
4. **Link zur Seite** steht oben in **Settings → Pages**.

## Aufbau

- `docs/_config.yml` – Konfiguration & Theme
- `docs/index.md` – Startseite mit Übersicht & Inhaltsverzeichnis
- `docs/regeln/*.md` – Einzelne Regel-Seiten (einfach erweiterbar)
- `docs/assets/style.css` – kleine Style-Anpassungen

## Bearbeiten

- Die meisten Inhalte sind **Markdown** (`.md`). Das ist super einfach: `# Überschrift`, `**fett**`, `*kursiv*`, Listen `-` usw.
- Fügt einfach neue Dateien in `docs/regeln/` hinzu und verlinkt sie in der `index.md`.
- Änderungen committen/pushen – GitHub Pages baut automatisch neu.

Viel Erfolg und happy roleplay! 🎮
