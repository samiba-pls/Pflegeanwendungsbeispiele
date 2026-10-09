# KI in der Pflege – 3D-Würfel

- `index.html` – die Grafik (lädt `data.json`)
- `data.json` – Daten, wird automatisch aus der Excel erzeugt
- `KI_Pflege_Anwendungsbeispiele.xlsx` – Quelle der Wahrheit
- `tools/excel_to_json.py` – Konvertierung (lokal: `python tools/excel_to_json.py`)
- `.github/workflows/update-data.yml` – erzeugt `data.json` neu, sobald die Excel hochgeladen wird

Aktualisieren: Excel im Repository ersetzen (Upload) -> nach ca. 1-2 Minuten ist die Seite aktuell.
Lokaler Test: `python -m http.server` und http://localhost:8000 öffnen.
