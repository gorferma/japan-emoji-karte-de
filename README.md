# Japan-Emoji-Karte 🇯🇵

Eine interaktive Karte mit Sehenswürdigkeiten in Japan: Emoji-Markierungen,
deutsche Beschreibungen, Kategorienfilter, Ortssuche, Hell-/Dunkelmodus und
teilbare Kartenausschnitte.

**App öffnen:** https://gorferma.github.io/japan-emoji-karte-de/

## Herkunft

Diese deutsche Version basiert auf
[gorferma/japan-emoji-karte](https://github.com/gorferma/japan-emoji-karte).
Sie wird als eigenständige Kopie mit der bisherigen Git-Historie gepflegt,
weil das Ursprungsprojekt bereits demselben GitHub-Konto gehört.

## Lokal starten

Im Projektordner einen statischen Webserver starten, zum Beispiel:

```sh
python -m http.server 8080
```

Anschließend `http://localhost:8080` im Browser öffnen. Es ist kein Build nötig.
Kartenkacheln, Ortssuche, Schriftarten und Bibliotheken werden aus dem Internet geladen.
Die Hintergrundkarte und Suchergebnisse verwenden deutsche Namen, soweit der jeweilige
Kartendienst sie bereitstellt. Japanische Eigennamen und Marken bleiben erhalten.

## GitHub Pages

Die Veröffentlichung erfolgt aus dem Stammverzeichnis des Branches `main`
über **Settings → Pages → Deploy from a branch**. Die Datei `.nojekyll`
sorgt dafür, dass GitHub die statischen Dateien unverändert ausliefert.

Die App nutzt Leaflet, OpenStreetMap, Nominatim und Twemoji.
