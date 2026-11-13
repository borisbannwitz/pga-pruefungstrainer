# Fortsetzungsstand – PGA-Prüfungstrainer

Stand: 13.11.2026 · veröffentlichte App-Version 3.4

## Gesicherter Stand

- Die Regelfragen-Daten umfassen 364 Fragen: 289 Regel- und Änderungsfragen sowie 75 Definitionsfragen (74 Begriffe plus die 2023 geänderte Definition „Erleichterungsbereich“).
- Die PGA-Golftechnik enthält 167 Fragen einschließlich GOSSIP.
- Die Regelabdeckungsmatrix zur DGV-Ausgabe „Offizielle Golfregeln 2023“ enthält 595 Einträge: 107 Überschriften x.y, 229 Buchstaben-Unterabschnitte, 185 nummerierte Absätze und 74 Definitionen.
- Alle 185 nummerierten Absätze sind direkt mit mindestens einer Regelfrage verknüpft. Die Änderungen von 2023 auf den gedruckten Seiten 18–19 sind in der Matrix hervorgehoben.
- In Version 3.3 erhielten alle neun Grobform-/Feinform-Paare eine Gegenform-Antwort als falsche Auswahl: Spieleröffnung 236/237, Transportschlag 240/241, Recovery 243/244, Schlag ins Grün 246/247, Pitchen 250/251, Lob 255/256, Bunkerschlag 261/262, Chippen 266/267 und Putten 269/270.
- In Version 3.4 zieht jede Prüfungssimulation höchstens 45 Fragen. Auch eine Regelfragen-Simulation nimmt jetzt 45 adaptive Fragen aus dem 364-Fragen-Pool statt den gesamten Pool. Neue und falsch beantwortete Fragen werden bevorzugt.
- Die gemeinsame Passwortabfrage bleibt aktiv. Das Passwort ist nicht als Klartext in dieser Notiz gespeichert.

## Gesicherte Dateien und Veröffentlichung

- GitHub-Repository: `borisbannwitz/pga-pruefungstrainer`, Branch `main`.
- Letzter App-Commit: `98b4928adf27cb037e665627cd1b9039ffb22e11` (Version 3.4, Regelsimulation auf 45 Fragen begrenzt).
- Vorheriger App-Commit: `fbbb836d99c5e2d73a7d2464170295a9b6f5f2f1` (Version 3.3, Gegenform-Antworten in der Golftechnik).
- Live-Seite: https://borisbannwitz.github.io/pga-pruefungstrainer/?v=3.4
- Vollständige App-Dateien liegen im Repository-Root; lokal in `outputs/PGA-Pruefungstrainer-Web/`.
- Die App lädt Golftechnik aus `questions.js` (mit synchronisierter `questions.json`) und Regeln aus `rules.json`.
- Die Abdeckungsmatrix, die Matrix der 185 nummerierten Regelunterpunkte und der ausführliche Regel-Fortsetzungsstand liegen unter `docs/` im Repository. Lokale Kopien liegen in `outputs/`.
- Das Quelldokument `offizielle_golfregeln_2023.pdf` bleibt unter `C:\Users\runte\Downloads\` lokal und wurde nicht ins Repository hochgeladen.

## Sinnvolle nächste Schritte

Bei weiterer Arbeit können die verbleibenden Regelüberschriften und Buchstaben-Unterabschnitte ohne direkte Frage priorisiert werden. Danach können Verständlichkeit und Schwierigkeit der Regelfragen weiter verbessert werden. Golftechnik bleibt grundsätzlich unangetastet, außer bei ausdrücklich gewünschten Änderungen wie den neun Gegenform-Auswahlen.

