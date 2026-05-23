# KI-Tomat — Lean Dashboard

Dieses Repository enthält das Lean Dashboard „KI-Tomat“ für die manuelle Linienmontage.

Ziel ist ein praxisnahes Lean-/KI-Dashboard, das Fachlogik, Anwendungsszenarien, Quellenstatus und Review-Möglichkeiten sichtbar verbindet.

## Agenten-Workflow

Das Projekt wird bewusst nicht als eine einzige Allzweck-KI betrieben, sondern als Rollenverbund.

### 1. ChatGPT Project: Konzept, Fachlogik und Review

Das ChatGPT Project dient als fachlicher Arbeitsraum für:

- Lean-Konzept und Modulpriorisierung
- Review-Fragen und Szenarien
- Anforderungen für Codex
- fachliche Risiken und Nicht-Ziele
- Dozenten-, Community- und Praxisfeedback

Die Projektanweisungen liegen in:

- `docs/chatgpt-project-instructions.md`

### 2. Codex: GitHub, Code und Pull Requests

Codex wird als technischer GitHub-Agent eingesetzt. Er soll kleine, klare Aufgaben umsetzen, ohne bestehende Funktionen zu entfernen oder das Dashboard neu zu bauen.

Die Codex-Regeln liegen in:

- `AGENTS.md`
- `docs/codex-task-template.md`

### 3. Quellen- und Qualitätsagent

Der Quellenagent prüft fachliche Aussagen, ordnet Quellenstatus ein und markiert unsichere oder überstarke Aussagen.

Die Arbeitsanweisung liegt in:

- `docs/source-quality-agent.md`

## Review- und Qualitätsdokumente

- `docs/review-canvas-template.md`
- `docs/operating-model.md`
- `docs/github-start-issues.md`

## Arbeitsprinzipien

- Erst verstehen, dann ändern.
- Kleine, reviewbare Schritte bevorzugen.
- Keine bestehenden Funktionen ohne Auftrag entfernen.
- Fachliche Lean-Aussagen nicht stärker darstellen, als Quellen und Review es tragen.
- Quellenstatus und Trust-Level sichtbar halten.

## Empfohlener nächster Schritt

1. Eine kleine GitHub-Issue aus `docs/github-start-issues.md` auswählen.
2. Daraus eine konkrete Codex-Aufgabe formulieren.
3. Änderung als Pull Request prüfen.
4. Fachliches Review mit `docs/review-canvas-template.md` durchführen.
