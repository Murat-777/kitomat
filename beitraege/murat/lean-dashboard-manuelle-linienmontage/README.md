# Lean-Dashboard fuer manuelle Linienmontage

## Kurzbeschreibung

Dieses KI-Tomat-Artefakt beschreibt ein Lean-Dashboard fuer bestehende manuelle Montage- und Produktionslinien. Das Dashboard hilft, Taktzeit, Stationslast, wertschoepfende Zeit, nicht wertschoepfende Restzeit, NVA-Verlustcluster, Engpasskandidaten und PDCA-Arbeitspakete strukturiert zu analysieren.

Das Artefakt ist kein fertiges Beratungsurteil. Es ist ein reviewfaehiger Arbeitsbaustein fuer Shopfloor-Reviews, KVP-Workshops und PDCA-Vorbereitung.

## Artefakttyp

KMU-/Branchenmodell

## Zielgruppe

- Produktionsleiter
- Betriebsingenieure und Industrial Engineering
- Prozessingenieure
- Lean Management und KVP-Verantwortliche
- Operational Excellence Manager
- Werkleiter mit Bedarf an Management-Sicht und Umsetzungsstatus

## Kernnutzen

- Engpaesse und Stationslasten sichtbar machen
- Taktabweichungen nachvollziehbar berechnen
- NVA-Anteile in konkrete Verlustcluster uebersetzen
- Lean-Prinzipien wie 5S, Standard Work, Yamazumi, Kanban oder Jidoka an konkrete Stationsdaten koppeln
- PDCA-Tests und To-Dos vorbereiten
- Ergebnisse fuer Shopfloor- und Management-Review dokumentieren

## Bestandteile

- `model.md` - fachliches Modell und Logik des Lean-Dashboards
- `application-guide.md` - Anwendungsschritte und Review-Ablauf
- `metadata.yml` - KI-Tomat-Metadaten und Trust-Layer
- `sources.md` - Quellenstatus und fachliche Grundlage
- `failure-modes.md` - Grenzen, Fehlanwendungen und Risiken
- `examples/example-01.md` - synthetisches Beispiel
- `examples/scenario-01-positive.md` - positives Szenario
- `examples/scenario-02-nachbearbeitbar.md` - nachbearbeitbares Szenario
- `examples/scenario-03-negativ.md` - negatives Szenario
- `worksheet/lean-dashboard-review-canvas.md` - Review-Canvas fuer Workshop oder Dozentenpruefung

## Verknuepfte Quelldateien

Die funktionierende Webapp und der Reproduktionsprompt liegen im lokalen vorbereiteten Paket:

- `lean-dashboard-quellcode.html`
- `masterprompt_reproduktion_lean_dashboard.txt`
- `Ziel_Verwendung.pdf`
- `README-quelldatei.md`

Diese Dateien sind fachliche Referenzen. Fuer eine Weiterentwicklung der Webapp soll die HTML-Quelldatei als verbindliche Basis genutzt werden.

## Daten- und Sicherheitsgrenze

Nur synthetische, anonymisierte oder unkritische Produktionsdaten verwenden. Keine echten Namen, personenbezogenen Leistungsdaten, vertraulichen Kunden-, Produkt- oder Betriebsdaten eingeben.

## Statusvorschlag

`bronze_candidate`

Dieser Status bedeutet: Das Paket ist formal vorbereitet und kann menschlich geprueft werden. Es ist noch keine finale Freigabe, kein Audit und keine produktive Empfehlung.
