# Trust-Layer Improvement Brief — Issue #4

## Ziel

Der Quellenstatus im Lean Dashboard soll für Nutzer sichtbarer und verständlicher werden, ohne bestehende Fachlogik oder Dashboard-Funktionen zu verändern.

## Ausgangslage

Issue #4 fordert: „Quellenstatus im Dashboard sichtbarer machen“.

Da die konkrete Dashboard-Datei vor der Umsetzung eindeutig identifiziert werden muss, ist der erste technische Schritt eine Analyse der vorhandenen Projektstruktur.

## Arbeitsauftrag für Codex

### Schritt 1: Relevante Dateien finden

Identifiziere zuerst die Dateien, in denen das Dashboard oder die Lean-Module definiert sind.

Typische Kandidaten können sein:

- `index.html`
- `dashboard.html`
- `src/App.jsx`
- `src/App.tsx`
- `app/page.tsx`
- Komponenten unter `components/`
- Daten-/Konfigurationsdateien unter `data/`, `content/` oder `docs/`

Wenn keine Dashboard-Datei vorhanden ist, bitte keine technische UI-Änderung vornehmen, sondern einen Befund im Issue kommentieren.

### Schritt 2: Quellenstatus-Logik finden

Suche nach Begriffen wie:

- `trust`
- `source`
- `sources`
- `documented`
- `partly_documented`
- `needs_source`
- `quality`
- `evidence`
- `review`

Beschreibe kurz:

1. Wo der Status gespeichert ist.
2. Wie er aktuell angezeigt wird.
3. Ob es bereits eine Legende oder Erklärung gibt.
4. Welche Statuswerte existieren.

### Schritt 3: Kleine Verbesserung umsetzen

Nur wenn die bestehende Logik klar ist, eine minimale Verbesserung umsetzen.

Geeignete kleine Änderungen:

- Legende für Statuswerte ergänzen.
- Tooltip oder kurze Erklärung hinzufügen.
- Statuslabels konsistenter benennen.
- `partly_documented` und `needs_source` visuell oder textlich klarer unterscheiden.
- Keine Aussage fachlich aufwerten.

## Empfohlene Status-Erklärungen

| Status | Nutzerverständliche Erklärung |
| --- | --- |
| `documented` | Durch Quelle oder Review gut gestützt. |
| `partly_documented` | Plausibel, aber nur teilweise belegt. |
| `needs_source` | Aussage benötigt noch eine belastbare Quelle. |
| `opinion_or_design_choice` | Projektentscheidung, kein externer Fachfakt. |
| `risky_or_overstated` | Aussage könnte stärker klingen, als die Quellen tragen. |

## Akzeptanzkriterien

- [ ] Relevante Dashboard-Datei wurde identifiziert.
- [ ] Bestehende Quellenstatus-Logik wurde kurz dokumentiert.
- [ ] Bestehende Statuswerte bleiben erhalten.
- [ ] Keine fachliche Aussage wurde ohne Beleg aufgewertet.
- [ ] Änderung ist klein und reviewbar.
- [ ] README oder Kommentar verweist bei Bedarf auf den Trust-Layer.

## Nicht-Ziele

- Kein kompletter UI-Umbau.
- Keine neue Bibliothek.
- Keine Entfernung bestehender Funktionen.
- Keine pauschale Quellenbewertung ohne Recherche.
- Keine Umbenennung von Statuswerten, wenn dadurch bestehende Logik bricht.

## Risikoabschätzung

**Risiko: Mittel**

Der Trust-Layer kann fachliche Sicherheit suggerieren. Deshalb müssen Formulierungen vorsichtig bleiben und Unsicherheiten sichtbar machen.

## Definition of Done

Issue #4 ist bereit für Review, wenn Codex im Pull Request klar beschreibt:

1. Welche Datei geändert wurde.
2. Wie der Quellenstatus vorher dargestellt wurde.
3. Was genau verbessert wurde.
4. Welche Statuswerte unverändert geblieben sind.
5. Welche offenen Quellen- oder Review-Fragen bleiben.
