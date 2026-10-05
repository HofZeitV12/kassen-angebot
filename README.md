# smartorder Studio

Kostenvergleich und Angebot für Kartenzahlung und Kassensysteme – eine einzige
HTML-Datei (`index.html`), mobilfreundlich, auf Deutsch, offline nutzbar.

## Live

- https://smartorder-studio.vercel.app
- https://smartoder.github.io/kassen-angebot/

## Funktionen

- Kundenverwaltung mit Suche, Bearbeiten, Löschen und JSON-Export/Import
- Dokumentation der aktuellen Situation (Kasse, Kartenanbieter, Anmerkungen, Foto)
- Kostenvergleich pro Position: links „Heute zahlt der Kunde", rechts „Bei uns zahlt der Kunde"
- Frei benennbare Positionen, Kategorien, ein-/ausblenden, hinzufügen
- Gebührentyp je Seite: Prozent, Fixbetrag €/Monat, Cent pro Transaktion, Prozent + Fixbetrag
- Monats-/Jahreskosten, Ersparnis in € und %, Balkendiagramm, Einmalkosten + Amortisation
- Angebotsseite zum Drucken als PDF, als Text kopieren oder teilen
- Eigene Firmendaten mit Logo und Gültigkeitsdatum

## Datenspeicherung

Alle Daten bleiben lokal im Browser (`localStorage`). Sicherung über
Firma → Export (JSON) und Import (JSON).

## Entwicklung

Kein Build nötig – `index.html` direkt öffnen oder ausliefern.
