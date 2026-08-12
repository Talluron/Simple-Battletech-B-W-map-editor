# Simple B&W Hex Map Editor

Version: 0.12.1

A standalone browser-based black-and-white hex map editor/generator for tabletop wargame maps. It creates deterministic maps from a seed, supports several biomes, exports the full map as PNG, and exports tiled A4 PDFs.

The editor is available in German and English and intentionally remains a single local HTML app. Open `index.html` with a double click; no web server, build step, package manager, CDN, or internet connection is required.

## English

### Run locally

1. Open `index.html` in a modern browser.
2. Choose the language in the top right.
3. Generate a map, copy the seed or map URL, or export PNG/PDF files.

### Suggested GitHub setup

Recommended repository title:

`simple-bw-hex-map-editor`

Good short description:

`Standalone black-and-white hex map editor/generator for printable tabletop wargame maps. Runs directly from index.html without a web server.`

Alternative titles:

- `simple-tabletop-hex-map-editor`
- `bw-hex-map-generator`
- `printable-hex-map-editor`

I would avoid using `BattleTech` in the repository name unless you explicitly want to handle trademark wording and disclaimers. A safer description is "for hex-based tabletop wargames" or "for printable tabletop wargame maps".

### Notes for GitHub publishing

- Keep the `assets/` folder next to `index.html`; the editor loads these files with relative paths so double-click usage keeps working.
- Do not replace the inline JavaScript with module imports or fetched translation files unless you also accept losing some `file://` compatibility.
- The copied map URL stores the complete map code and selected language in the query string.

### License

The project uses the Apache License 2.0. It is still permissive and practical for a small open-source browser tool, but it is clearer than MIT about attribution in modified versions: redistributed modified files must carry prominent change notices, existing attribution notices must be retained, and the `NOTICE` file must be carried forward where applicable.

Important asset check before publishing: only publish the PNG files in `assets/` under Apache-2.0 if you created them yourself or have permission to relicense them. If any asset came from a third party, add its original license and attribution before making the repository public.

## Deutsch

### Lokal starten

1. `index.html` in einem modernen Browser öffnen.
2. Oben rechts Deutsch oder Englisch auswählen.
3. Karte erzeugen, Seed oder Karten-URL kopieren oder PNG/PDF exportieren.

### Vorschlag für GitHub

Empfohlener Repository-Titel:

`simple-bw-hex-map-editor`

Gute Kurzbeschreibung:

`Standalone black-and-white hex map editor/generator for printable tabletop wargame maps. Runs directly from index.html without a web server.`

Alternative Titel:

- `simple-tabletop-hex-map-editor`
- `bw-hex-map-generator`
- `printable-hex-map-editor`

Ich würde `BattleTech` nicht in den Repository-Namen setzen, solange du keinen expliziten Markenhinweis/Disclaimer verwenden möchtest. Sicherer ist eine Formulierung wie "for hex-based tabletop wargames" oder "for printable tabletop wargame maps".

### Hinweise für GitHub

- Der Ordner `assets/` muss neben `index.html` bleiben; die Bilder werden relativ geladen, damit der Doppelklick-Start erhalten bleibt.
- Keine Modul-Imports, CDN-Dateien oder per `fetch` geladene Übersetzungen einbauen, wenn die `file://`-Kompatibilität wichtig bleibt.
- Die kopierte Karten-URL enthält den vollständigen Karten-Code und die gewählte Sprache als Query-Parameter.

### Lizenz

Das Projekt steht unter der Apache License 2.0. Sie bleibt permissiv und gut für Open Source geeignet, ist aber bei Namensnennung und Änderungen klarer als MIT: verteilte geänderte Dateien müssen erkennbare Änderungshinweise tragen, bestehende Attributionen bleiben erhalten, und die `NOTICE`-Datei muss, soweit anwendbar, mitgeführt werden.

Wichtiger Asset-Check vor der Veröffentlichung: Die PNG-Dateien in `assets/` sollten nur dann unter Apache-2.0 veröffentlicht werden, wenn du sie selbst erstellt hast oder die Rechte zur Weiterlizenzierung besitzt. Falls ein Asset von Dritten stammt, ergänze vor dem öffentlichen GitHub-Release dessen Originallizenz und Attribution.
