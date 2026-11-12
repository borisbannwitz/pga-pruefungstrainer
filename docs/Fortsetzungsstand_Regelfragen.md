# Fortsetzungsstand – Regelfragen PGA-Prüfungstrainer

Stand: 12.11.2026

## Aktueller Stand

- Die Abdeckungsmatrix zur DGV-Ausgabe „Offizielle Golfregeln 2023“ ist erstellt.
- Sie enthält 595 Einträge: 107 Überschriften im Format x.y, 229 Buchstaben-Unterabschnitte, 185 nummerierte Absätze wie 1.3b(1) sowie 74 Definitionen.
- Mit der Fragenliste der App-Version 1.6 wurden 202 Fragen abgeglichen: 127 Regel-/Änderungsfragen, 74 einzelne Definitionsfragen und eine zusätzliche Frage zur geänderten Definition „Erleichterungsbereich“.
- Bei den 185 nummerierten Absätzen sind 15 direkt mit einer Frage verknüpft, 138 nur über einen verwandten Regelzweig und 32 ohne zugeordneten Regelverweis. Diese Einordnung basiert auf Kennungen und Quellen in der Fragenliste; sie bewertet nicht die fachliche Vollständigkeit jeder Antwort.
- Für das Ziel „jeder nummerierte Absatz bekommt eine eigene, direkt zugeordnete Frage“ wären somit 170 neue direkte Zuordnungen zu bearbeiten.
- Noch keine dieser zusätzlichen Fragen wurde erstellt oder in die App eingefügt.
- Die Änderungen 2023 auf den gedruckten Seiten 18–19 sind in den Matrizen orange hervorgehoben; Seite 20 erläutert die Fallprüfung.

## Dateien

- Vollständige Matrix: `outputs/Regelabdeckungsmatrix_2023.md`
- Matrix der 185 nummerierten Absätze: `outputs/Nummerierte_Regelunterpunkte_Matrix.md`
- App-Dateien: `outputs/PGA-Pruefungstrainer-Web/`
- PDF-Quelle: lokal bereitgestellte DGV-PDF `offizielle_golfregeln_2023.pdf` (die PDF selbst wird nicht ins Repository kopiert).
- Extrahierte Abschnittsdaten: `work/rule_sections_detailed.json`
- Erstellungsskript für die vollständige Matrix: `work/build_detailed_matrix.py`

## Nächster Schritt

Vor dem Erstellen der Fragen festlegen, ob alle 170 nicht direkt zugeordneten Absätze eine eigene Frage erhalten sollen oder zunächst nur die 32 Absätze ohne Regelzweig-Verweis. Danach Fragen ausarbeiten, in `rules.json` einfügen, Versionsnummer anpassen und die aktualisierte App veröffentlichen.

## Zeitabschätzung

- Für alle 170 direkten Unterpunkt-Fragen einschließlich Abgleich und App-Aktualisierung: etwa 4–5 Stunden.
- Nur die 32 Absätze ohne zugeordneten Regelverweis: etwa 45–75 Minuten.
