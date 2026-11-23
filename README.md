# cs-kostenstellen

Liste der laufenden Kostenstellen für die Formular-App (Tagesbericht, LKW-Rapport, Taglohn).

- `kostenstellen.json` wird **automatisch** von der Lieferscheinapp erzeugt und hochgeladen.
  Bitte nicht von Hand ändern – die nächste Änderung dort überschreibt die Datei.
- Enthalten sind nur laufende Baustellen (`aktiv = ja`, laufende Nummer unter 900),
  und nur Kostenstelle und Kurzname.
- Das Repository ist **öffentlich lesbar**. Keine Kunden, Adressen oder Personen eintragen.

Format:

```json
{ "stand": "2026-11-23T14:05",
  "kostenstellen": [ { "ks": "26014", "name": "Kindergarten Aach" } ] }
```
