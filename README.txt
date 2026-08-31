# Karteikarten Pro – installierbare Web-App

Die App ist als Progressive Web App (PWA) vorbereitet.

## Installation auf Android
1. Die Dateien auf einen HTTPS-Webserver hochladen (z. B. GitHub Pages oder einen anderen statischen Webhost).
2. Die Adresse der App in Chrome öffnen.
3. Chrome-Menü ⋮ → „App installieren“ bzw. „Zum Startbildschirm hinzufügen“.
4. Danach startet die App wie eine normale App im Vollbild.

Wichtig: Ein Service Worker funktioniert aus Sicherheitsgründen nicht direkt über `file://`. Deshalb muss die PWA über HTTPS oder einen lokalen Entwicklungsserver bereitgestellt werden.

Die Karteikarten werden weiterhin im Browser des Geräts gespeichert.
