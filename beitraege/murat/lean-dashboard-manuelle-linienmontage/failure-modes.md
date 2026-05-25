# Failure Modes und Grenzen

## Grundsatz

Das Dashboard liefert Hypothesen und Struktur. Es ersetzt keine Vor-Ort-Beobachtung, keine Zeitaufnahme nach methodischem Standard, keine Qualitaetsfreigabe, keine Arbeitssicherheitsbewertung und keine Entscheidung durch Prozessverantwortliche.

## Moegliche Fehlanwendungen

### 1. Personenbezogene Leistungsbewertung

Risiko: Stations- oder Mitarbeitendendaten werden zur Bewertung einzelner Personen genutzt.

Gegenmassnahme: Keine Namen oder personenbezogenen Leistungsdaten eingeben. Ergebnisse nur auf Prozess- und Stationsniveau diskutieren.

### 2. Falsche Datengrundlage

Risiko: Ungenaue, erfundene oder nicht repraesentative Zeiten fuehren zu falschen Engpasshypothesen.

Gegenmassnahme: Daten als Hypothese markieren und am Shopfloor validieren.

### 3. Automatische Ursachenannahme

Risiko: Ein hoher NVA-Anteil wird direkt als Ursache interpretiert.

Gegenmassnahme: NVA-Cluster nur als Hinweis nutzen. Ursache erst durch Beobachtung, Gespraech und PDCA-Test pruefen.

### 4. Qualitaets- oder Sicherheitsrisiko durch zu schnelle Umsetzung

Risiko: Eine Massnahme reduziert Zeit, erhoeht aber Nacharbeit, Fehler oder Belastung.

Gegenmassnahme: Review durch Qualitaet, Arbeitssicherheit und Ergonomie vor Umsetzung.

### 5. Zu grobes Modell

Risiko: Das Dashboard bildet Sondervarianten, Materialstoerungen oder Schichtunterschiede nicht ab.

Gegenmassnahme: Scope klar begrenzen und offene Annahmen dokumentieren.

### 6. Ueberstandardisierung

Risiko: Ein noch nicht validierter PDCA-Test wird zu frueh als Standard festgelegt.

Gegenmassnahme: Erst beobachten, dann testen, messen und erst danach standardisieren.

### 7. Vertrauliche Daten im Export

Risiko: Bericht, JSON-Export oder One-Pager enthalten sensible Informationen.

Gegenmassnahme: Export vor Weitergabe menschlich pruefen und vertrauliche Details entfernen.

## Nicht geeignet fuer

- HR-Entscheidungen
- Leistungsbewertung einzelner Mitarbeitender
- rechtliche oder arbeitsrechtliche Beurteilungen
- sicherheitskritische Freigaben ohne Fachreview
- vollautomatische Prozessentscheidung
- Einsatz mit echten sensiblen Daten ohne Schutzkonzept

## Restliches Risiko

`yellow`

Das fachliche Risiko ist beherrschbar, wenn nur synthetische/anonymisierte Daten genutzt werden und menschliche Review verpflichtend bleibt.
