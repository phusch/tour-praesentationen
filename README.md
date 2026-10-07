# Huschels Tour-Präsentationen V1.3.3d

Basis: V1.3.3c mit dunkelblauer Kartenlinie aus V1.3.3b und den realen Bieranker-Bildern aus V1.3.3a.

## Neu: GitHub-Bilderpaket für eigene Highlightbilder

Auf der Seite **Highlights der Tour** kannst du weiterhin pro Kachel `Bild wählen` verwenden.

Zusätzlich gibt es jetzt unten den Button **GitHub-Bilderpaket erstellen**.

Die App erzeugt ein ZIP mit:
- den ausgewählten Bildern unter `projects/<projekt>/assets/user-highlights/`
- `data/user-images.js` mit der fertigen Bildzuordnung
- `highlight-manifest.json`
- einer kurzen Anleitung

### Dauerhaft übernehmen
1. Bilder in der App auswählen und prüfen.
2. `GitHub-Bilderpaket erstellen` drücken.
3. ZIP auf dem Mac entpacken.
4. Die enthaltenen Ordner `projects` und `data` in den Hauptordner des GitHub-Repositories kopieren und zusammenführen.
5. `data/user-images.js` ersetzen.
6. In GitHub Desktop committen und pushen.

Danach werden diese Bilder von der Präsentations-App automatisch als dauerhafte Highlightbilder verwendet und erscheinen auf allen Geräten.
