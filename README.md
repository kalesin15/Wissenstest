# Wissenstest 2026 – Übungsquiz

Übungsfragen zum Wissenstest der Jugendfeuerwehren Bayern 2026:
„Umgang mit Schläuchen, Armaturen & Leinen“.

**Inoffiziell** – keine Original-Prüfungsfragen. Grundlage: Unterlagen der
[Feuerwehr-Lernbar](https://www.feuerwehr-lernbar.bayern/topics/umgang-mit-schlaeuchen-armaturen-und-leinen).

## Veröffentlichen (GitHub Pages)
1. `index.html` ins Repo legen
2. Settings → Pages → Branch `main`, Ordner `/ (root)` → Save
3. Aufrufbar unter `https://<user>.github.io/<repo>/`

## Fragen bearbeiten
Alle Fragen stehen oben im `<script>` im Array `FRAGEN`:

```js
{b:"Leinen", s:1, f:"Frage?", o:["A","B","C","D"], r:2, e:"Erklärung"}
```
- `b` Bereich: `Schläuche` | `Armaturen` | `Leinen`
- `s` Schwierigkeit: `1` Basis, `2` Fortgeschritten
- `r` Index der richtigen Antwort (0-basiert)

Keine Abhängigkeiten, kein Build, kein Tracking.
