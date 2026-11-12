# Fortsetzungsstand – Regelfragen PGA-Prüfungstrainer

Stand: 12.11.2026

## Aktueller Stand

- Die Abdeckungsmatrix zur DGV-Ausgabe „Offizielle Golfregeln 2023“ ist erstellt.
- Sie enthält 595 Einträge: 107 Überschriften im Format x.y, 229 Buchstaben-Unterabschnitte, 185 nummerierte Absätze wie 1.3b(1) sowie 74 Definitionen.
- Mit der Fragenliste der App-Version 1.7 wurden 234 Fragen abgeglichen: 159 Regel-/Änderungsfragen, 74 einzelne Definitionsfragen und eine zusätzliche Frage zur geänderten Definition „Erleichterungsbereich“.
- Bei den 185 nummerierten Absätzen sind 47 direkt mit einer Frage verknüpft, 138 nur über einen verwandten Regelzweig und keiner ohne zugeordneten Regelverweis. Die 32 zuvor offenen Absätze sind als R203–R234 ergänzt. Diese Einordnung basiert auf Kennungen und Quellen in der Fragenliste; sie bewertet nicht die fachliche Vollständigkeit jeder Antwort.
- Für das Ziel „jeder nummerierte Absatz bekommt eine eigene, direkt zugeordnete Frage“ sind noch 138 Unterpunkte ohne direkte Einzelzuordnung.
- Die 32 ergänzten Fragen sind in `rules.json` enthalten; Version 1.7 ist auf GitHub main aktualisiert.
- Die Änderungen 2023 auf den gedruckten Seiten 18–19 sind in den Matrizen orange hervorgehoben; Seite 20 erläutert die Fallprüfung.

## Dateien

- Vollständige Matrix: `outputs/Regelabdeckungsmatrix_2023.md`
- Matrix der 185 nummerierten Absätze: `outputs/Nummerierte_Regelunterpunkte_Matrix.md`
- App-Dateien: `outputs/PGA-Pruefungstrainer-Web/`
- PDF-Quelle: lokal bereitgestellte DGV-PDF `offizielle_golfregeln_2023.pdf` (die PDF selbst wird nicht ins Repository kopiert).
- Extrahierte Abschnittsdaten: `work/rule_sections_detailed.json`
- Erstellungsskript für die vollständige Matrix: `work/build_detailed_matrix.py`

## Nächster Schritt

Optional können als nächster Schritt auch die 138 bislang nur über einen verwandten Regelzweig abgedeckten Unterpunkte eigene Fragen erhalten. Die 32 zuvor nicht zugeordneten Unterpunkte sind jetzt direkt ergänzt; Version 1.7 ist im GitHub-Repository aktualisiert.

## Zeitabschätzung

- Die vorherige Schätzung für alle 170 Ergänzungen lag bei etwa 4–5 Stunden. Die 32 Fragen wurden erstellt; für die verbleibenden 138 direkten Einzelzuordnungen wäre neu zu planen.
