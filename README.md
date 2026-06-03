# Daily OS – Persönlicher Tagesbegleiter

Ein persönlicher Tagesbegleiter mit Murmel-System, Routinen-Tracker, Morgen- und Abendritual, Glaubenssätzen und optionalen KI-Features.

## Features

- **⚡ Dashboard** – Tagesführer, Stimmungs-Check-in, Murmel-System, Routine-Fortschritt
- **📋 Heute** – Aktivitäten-Log (automatisch + manuell), Murmel-Momente mit Beschreibung
- **✓ Routinen** – Vollständig editierbar (hinzufügen, löschen, Zeitstempel: Morgens / Mittags / Abends / Flexibel)
- **💬 Glaubenssätze** – 5 Kategorien, KI-Generator, eigene Sätze speichern
- **🌙 Tagesritual** – Morgenritual (5 Min) + Abendritual (10 Min), zeitbasiert hervorgehoben
- **🤍 Murmel-System** – Selbstliebe tracken mit optionaler Beschreibung pro Moment
- **🌙 Dark Mode** – Warm & ruhiges Design
- **📱 Mobile-First** – Funktioniert auf iPhone, iPad und Desktop

## GitHub Pages einrichten

1. Dieses Repository forken oder die `daily-os.html` Datei hochladen
1. In Repository-Einstellungen → Pages → Branch: `main` → Ordner: `/ (root)`
1. Die App ist erreichbar unter: `https://[dein-username].github.io/[repository-name]/daily-os.html`

## KI-Features aktivieren

Die KI-Features (personalisierte Glaubenssätze, Tagesplanung, Coach-Feedback, Wochenanalyse) nutzen die Anthropic Claude API.

**API-Key holen:**

1. Gehe zu [console.anthropic.com](https://console.anthropic.com)
1. Erstelle einen Account und generiere einen API-Key
1. In der App: ⚙️ Symbol → API-Key eintragen → Speichern

**Wichtiger Hinweis zu CORS:**
Die KI-Features funktionieren am besten, wenn du die `daily-os.html` Datei **lokal** in deinem Browser öffnest (Doppelklick auf die Datei). Auf GitHub Pages können Browser-Sicherheitsrichtlinien (CORS) die Anfragen an die Anthropic API blockieren. Alle anderen Features (Routinen, Murmel-System, Reflexion etc.) funktionieren ohne API-Key und ohne Einschränkungen.

## Lokal nutzen

Einfach `daily-os.html` herunterladen und im Browser öffnen. Kein Server, kein Build-Schritt nötig.

## Daten

Alle Daten werden lokal im Browser (`localStorage`) gespeichert. Es werden keine Daten an externe Server übertragen (außer KI-Anfragen an Anthropic, wenn du einen API-Key einträgst).

Täglicher Reset: Stimmung, Marbles, Aktivitäten-Log und Reflexionen werden täglich zurückgesetzt. Routinen-Struktur, Glaubenssätze und Einstellungen bleiben erhalten.