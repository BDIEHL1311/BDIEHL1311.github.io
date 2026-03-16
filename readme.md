# Wellness Tracker – Offline + PWA (ohne Backend)

Perfekt, ist jetzt als **PWA-Variante** vorbereitet und um deine gewünschten Features erweitert.

## Neu in diesem Update
- ✅ **Datum pro Eintrag manuell wählbar** (direkt im Check-in-Flow)
  - Damit kannst du z. B. morgens noch einen Eintrag für den Vortag anlegen.
- ✅ **Reminder morgens/abends einstellbar** (in der App unter `Tools`)
  - Uhrzeit für Morgen und Abend frei konfigurierbar
  - Ein/Aus-Schalter für Reminder
  - Benachrichtigungsberechtigung direkt per Button anfragbar

## Was du bekommst
- Läuft weiterhin als einfache lokale Datei (`index.html`)
- Zusätzlich: PWA-Dateien (`manifest.webmanifest`, `sw.js`, `icon.svg`) für „Als App installieren“
- Kein Server-Backend, kein Account, kein Cloud-Zwang
- Daten lokal im Browser-Speicher

## Super-kurz: "Datei aufs Handy und go"
1. `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg` aufs Hosting (z. B. GitHub Pages) legen.
2. URL am Handy öffnen.
3. In der App unter `Tools` → **Als App installieren** (oder Browser-Menü „Zum Startbildschirm hinzufügen“).

## GitHub Pages (dein gewünschter Weg)
1. Lege die 4 Dateien ins Repo-Root.
2. Aktiviere GitHub Pages für den Branch.
3. Öffne die Pages-URL auf dem Handy.
4. Installiere die App über Browser-Menü oder den Button in `Tools`.

## Reminder-Hinweis (wichtig)
Die App ist komplett serverlos/offline. Reminder werden daher browserseitig ausgelöst.
- Funktioniert gut, wenn die App regelmäßig genutzt/geöffnet wird.
- Ohne externen Push-Server gibt es je nach Browser/OS Grenzen für harte Hintergrund-Zustellung.

## Dateien
- `index.html` – komplette App
- `manifest.webmanifest` – PWA-Metadaten
- `sw.js` – Offline-Cache
- `icon.svg` – App-Icon

## Features
- Morgen-/Abend-Check-in (Kartenflow)
- Manuelle Datumswahl pro Beitrag
- Alarm-System (Gelb/Rot + Kombinationsalarm)
- Interventionsvorschläge
- Verlauf
- Offline-Dashboard (Canvas)
- CSV-Export
- Beispieldaten-Generator
- Einstellbare Reminder

## Hinweis
Spracheingabe/NLP bleiben entfernt, damit die App robust und komplett offlinefähig bleibt.
