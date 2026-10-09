# Uhren-Profi – Uhrzeit lernen

Lernspiel für Grundschulkinder, läuft komplett im Browser (eine einzige `index.html`, keine Abhängigkeiten).

## Spielmodi
- **Uhr lesen:** Analoge Uhr wird angezeigt, das Kind schreibt beide möglichen Uhrzeiten auf (z. B. 3:45 und 15:45).
- **Uhr stellen:** Uhrzeit wird digital genannt, das Kind stellt Stunden- und Minutenzeiger auf der leeren Uhr ein.
- **Gemischt:** Beides im Wechsel.

## Einstellungen (⚙️ im Menü)
- Minuten: nur volle Stunden, Viertelstunden (Standard), 5-Minuten-Schritte oder alle Minuten
- Stundenbereich (Standard 1–23)
- Genauigkeit beim Zeiger-Stellen: **Leicht** (Stundenzeiger irgendwo im richtigen Stundenbereich), **Mittel**, **Genau**
- Aufgaben pro Runde

Einstellungen und Bestwerte werden im Browser (localStorage) gespeichert.

## Auf GitHub Pages veröffentlichen
1. Neues Repository auf GitHub anlegen und `index.html` + `README.md` hochladen.
2. Im Repository: **Settings → Pages**.
3. Unter *Build and deployment* → *Source*: **Deploy from a branch**, Branch `main`, Ordner `/ (root)`, speichern.
4. Nach ca. 1 Minute erreichbar unter `https://<dein-name>.github.io/<repo-name>/`.
