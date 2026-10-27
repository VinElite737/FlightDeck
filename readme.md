# FlightDeck - Pilot Toolkit

FlightDeck ist ein kompaktes, modernes und mobiles Tool-Package für Pilotinnen und Piloten. Die Anwendung vereint alle wichtigen Pre-Flight- und In-Flight-Werkzeuge – von Echtzeit-Flugplatzdaten und Wetterberichten bis hin zu Performance-Rechnern und Lizenz-Erinnerungen – in einer schnellen, installierbaren Progressive Web App (PWA).

## Features

* **Airport Information & Weather (METAR / TAF)**

  * Abruf von Flugplatz-Stammdaten über ICAO-Codes.

  * Automatische Anzeige von Start- und Landebahnen (Runways) inklusive Belag, Längen und Breiten.

  * Funkfrequenzen (Tower, Ground, ATIS, Approach u. a.).

  * Echtzeit-METAR mit automatischer Klartext-Dekodierung (Wind, Sicht, Wetterphänomene, Bewölkung, QNH/Altimeter).

  * TAF-Vorhersagen und direkte Links zu offiziellen NOTAM-Quellen (FAA, DFS AIS, EAD).

* **Aviation Calculator**

  * **Pressure & Density Altitude:** Druck- und Dichtehöhenberechnung basierend auf Platzhöhe, QNH und OAT.

  * **Wind Components & Heading:** Gegenwind-, Rückenwind- und Seitenwindkomponenten, Windkorrekturwinkel (WCA) sowie True & Magnetic Heading (inkl. Variation).

  * **Unit Converter:** Schnellumrechnung von Distanzen, Geschwindigkeiten, Massen, Volumina, Temperaturen und Fuel-Gewichten (Jet A-1 / Avgas / benutzerdefinierte Dichte).

* **Time Zone Converter**

  * Präzise Umrechnung von UTC in lokale Zeitzonen unter Berücksichtigung von Sommer-/Winterzeit.

* **Licence & Document Reminder**

  * Lokale Speicherung von Ablaufdaten (Class 1/2 Medical, SEP/MEP Ratings, IR, Sprachprüfungen, Reisepass).

  * Übersichtliche Anzeige der verbleibenden Tage mit Warnanzeige bei bevorstehendem Ablauf.

* **Mobile & PWA Ready**

  * Optimiertes Cockpit-Design mit Cockpit-Uhr (UTC).

  * Mobilfreundliche Bottom-Navigation im Taxiway-Sign-Look.

  * Kann direkt auf dem Smartphone oder Tablet als App (PWA) installiert werden.

## Technologie-Stack

* **HTML5 & Pure CSS3:** Keine schweren Frameworks – maximale Performance und schnelle Ladezeiten.

* **Vanilla JavaScript (ES6+):** Leichtgewichtig und ohne Abhängigkeiten.

* **Service Worker & Web App Manifest:** PWA-Funktionalität für die Nutzung als App.

* **APIs & Datenquellen:**

  * [AviationWeather.gov (NOAA)](https://aviationweather.gov/) für METAR-, TAF- und Airport-Informationen.

  * Open-Data-Sätze für Runways und Frequenzen.

## Installation & Lokale Entwicklung

Kein komplexes Build-System erforderlich!

1. **Repository klonen:**

   ```bash
   git clone https://github.com/DEIN-USERNAME/flightdeck.git
   cd flightdeck
   ```

2. **Starten:**
   Öffne einfach die `index.html` direkt in deinem Browser oder nutze einen lokalen Server (z. B. VS Code *Live Server* oder `python -m http.server`).

## Operational Disclaimer

> **Wichtiger Hinweis:**
>
> FlightDeck dient ausschließlich zu Informations- und Trainingszwecken sowie zur Flugvorbereitung als Unterstützung. Alle berechneten Werte, Daten und Wetterberichte müssen vor der betrieblichen Nutzung im Flugbetrieb stets mit den offiziellen Quellen (z. B. NOTAMs, AIP, DWD/NOAA) abgeglichen werden.

## Lizenz

Dieses Projekt ist unter der [MIT License](LICENSE) lizenziert.