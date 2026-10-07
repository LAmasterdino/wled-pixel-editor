# WLED Pixel Art Studio

Statische Pixel-Art-Webapp für GitHub Pages.

## Enthalten
- frei einstellbare Matrixgröße
- Stift, Radierer, Füllen, Pipette, Linie, Rechteck
- Brush-Größe, Zoom, Raster/Transparenz
- Undo/Redo
- mehrere Animationsframes, Duplizieren/Löschen
- FPS-Vorschau
- PNG-Export
- WLED-JSON-Export mit Row / Serpentine / Column Mapping
- animiertes GIF
- Projekt-JSON speichern/laden
- läuft clientseitig

## GitHub Pages
1. Dateien dieses Ordners in ein Repository laden.
2. GitHub → Settings → Pages → Deploy from branch → `main` / `/root`.
3. Die Seite wird anschließend über die GitHub-Pages-URL erreichbar.

Hinweis: Der GIF-Export nutzt `gif.js` per CDN. Für komplett offline Betrieb können `gif.js` und `gif.worker.js` lokal eingebunden werden.
