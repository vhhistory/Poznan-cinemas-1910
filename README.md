# Kinos in Posen vor dem Ersten Weltkrieg


[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![License: MIT](https://img.shields.io/badge/Code_License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Über das Projekt

Dieses Repository enthält den Workflow und die Skripte zur Extraktion, Aufbereitung und Georeferenzierung historischer Ortsdaten.

---

## Methodik & Data Provenance

Die Datenverarbeitung gliedert sich in folgende Schritte:

1. **Historische Georeferenzierung:**
   - Manuelle und automatisierte Recherche historischer Ortsbezeichnungen und Toponyme.
   - Zuordnung von Geokoordinaten (Breiten- und Längengrade).
2. **GIS-Verarbeitung & Harmonisierung (R):**
   - OCR-gestützte Extraktion der Daten aus Adressbuch der Residenzstadt Posen. 1914, Posen 1914 sowie Hendrykowska, Małgorzata: Święty Marcin – ulica kinematografów, in: Kronika Miasta Poznania (1), 2006, S. 182–191.
   - Georeferenzierung über mapwarper des Pharus-Plan der Stadt Posen 1910, in: http://maps.mapywig.org/m/City_plans/Central_Europe/PHARUS-PLAN_POSEN_10K_1910_APP_Sygn._Pl.m.Poz._11a.jpg (20.08.2026).
3. **Interaktive Visualisierung (Leaflet):** Aufbereitung der harmonisierten Geodaten für eine interaktive Kartendarstellung im Web mittels des R-Pakets `leaflet` (bzw. JavaScript Leaflet.js).
4. **Code-Generierung & AI Transparency:** Der Code für die Datenverarbeitung in R sowie die Erstellung der Leaflet-Karte wurde unter Einsatz von KI-Assistenz generiert, angepasst und validiert.
