# Operating Model — Rollenverbund Lean Dashboard KI-Tomat

## Zielbild

Das Projekt wird nicht als eine einzige Allzweck-KI betrieben, sondern als Rollenverbund:

1. ChatGPT Project: Konzept, Fachlogik, Review
2. Codex: GitHub, Code, Pull Requests
3. Recherche-/Qualitätsagent: Quellen, Belege, Trust-Level

## Arbeitsfluss

### Schritt 1: Fachliche Idee im ChatGPT Project klären
Output:
- Nutzen
- Lean-Bezug
- Nicht-Ziele
- Risiken
- Codex-Auftrag
- Akzeptanzkriterien

### Schritt 2: Kleine GitHub-Aufgabe für Codex formulieren
Output:
- Issue oder Task
- betroffene Dateien
- klare Grenzen
- Definition of Done

### Schritt 3: Codex setzt technische Änderung um
Output:
- Branch
- Pull Request
- Änderungsbeschreibung
- Testhinweise
- Risikoabschätzung

### Schritt 4: Review im ChatGPT Project
Output:
- fachliche Prüfung
- UI-/Logikprüfung
- Quellenstatus
- nächste kleine Aufgabe

### Schritt 5: Quellenagent verbessert Belege
Output:
- Quellenliste
- Statusänderungsvorschläge
- vorsichtigere Formulierungen
- offene Quellenlücken

## Entscheidungsregel

Wenn eine Aufgabe fachlich unklar ist, geht sie zuerst ins ChatGPT Project.
Wenn eine Aufgabe technisch klar ist, geht sie zu Codex.
Wenn eine Aussage belegt werden muss, geht sie zum Quellenagenten.

## Qualitätsprinzip

Keine Codeänderung ohne fachlichen Zweck.
Keine fachliche Aussage ohne sichtbaren Sicherheitsgrad.
Keine KI-Empfehlung ohne Review-Möglichkeit.
