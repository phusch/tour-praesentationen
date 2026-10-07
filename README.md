# Huschels Tour-Präsentationen V1.2

Diese GitHub-/iPad-App ist eine kleine Präsentationsbibliothek für Reiseprojekte.

## Neu in V1.2
- alle Neuerungen aus V1.1 bleiben erhalten
- zusätzlicher eigener Bereich **„Highlights der Tour“**
- Highlight-Karten mit **Bild + Kurzinfo + Einordnung**, warum der Stopp in der Route wichtig ist
- integriert für:
  - Rothenburg ob der Tauber
  - Fränkische Schweiz / Pottenstein
  - Mariánské Lázně
  - Karlovy Vary
  - Boží Dar – Oberwiesenthal
  - Lübbenau / Spreewald
  - Stralsund Altstadt & Hafen
  - Tangermünde
  - Quedlinburg
  - Kyffhäuserdenkmal

## Bereits enthalten
- echte interaktive Karte direkt auf **Seite 1** der Präsentation
- alle ausgearbeiteten Routenpunkte aus der GPX werden auf der Karte angezeigt
- Marker sind anklickbar, die Karte ist zoombar und zusätzlich als **Großansicht** verfügbar
- eigener Bildbereich für die vier wichtigsten Bieranker
- GPX direkt im Projekt eingebunden

## Struktur
- `index.html` – komplette App
- `data/projects.js` – alle Projekte und Präsentationen
- `projects/.../files/` – GPX-Dateien
- `projects/.../assets/` – Icon und Bildmaterial je Projekt

## Bedienung
- Startseite: Projekt auswählen
- danach: Präsentationsversion auswählen
- unten rechts: `Zurück` / `Weiter`
- auf dem iPad funktionieren auch **Wischgesten**
- Button `Karte vergrößern` öffnet die Routenkarte in groß
- `Alle Projekte` führt zurück zur Übersicht

## Wichtig
Die Kartenansicht verwendet Leaflet mit OpenStreetMap-Kartenkacheln. Auf GitHub und iPad funktioniert das am besten mit aktiver Internetverbindung.
