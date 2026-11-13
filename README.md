# PGA Prüfungstrainer

Web-App-Version **3.4**. Der Regelfragenpool enthält 364 Fragen: 289 Regel- und Änderungsfragen sowie 75 Definitionsfragen. Der Bereich PGA/Golftechnik enthält 167 Fragen einschließlich GOSSIP.

Die App zeigt beim Öffnen eine Passwortabfrage. Sie blendet die Oberfläche aus; die Dateien im öffentlichen Repository bleiben abrufbar.

Die App wird über [GitHub Pages](https://borisbannwitz.github.io/pga-pruefungstrainer/) bereitgestellt.

## Regelabdeckung

- [Vollständige Abdeckungsmatrix (595 Einträge)](docs/Regelabdeckungsmatrix_2023.md)
- [Matrix der 185 nummerierten Regelunterpunkte](docs/Nummerierte_Regelunterpunkte_Matrix.md)
- [Fortsetzungsstand und nächste Schritte](docs/Fortsetzungsstand_Regelfragen.md)

Alle 185 nummerierten Unterpunkte sind jetzt direkt mit mindestens einer Frage verknüpft. Keiner bleibt nur über einen verwandten Regelzweig abgedeckt oder ohne Regelverweis.

## Änderungen in Version 3.4

- Prüfungssimulationen wählen in jedem Bereich höchstens 45 Fragen aus; Regelfragenprüfungen verwenden nicht mehr den vollständigen Fragenpool auf einmal.
- Neue und falsch beantwortete Fragen werden bei der Auswahl weiterhin bevorzugt.

## Änderungen in Version 3.3

- In allen neun Grobform-/Feinform-Paaren der Golftechnik steht die richtige Antwort der jeweils anderen Form als plausible falsche Auswahl bereit.
- Die korrekten Antwortmarkierungen und die Gesamtzahl von 167 Golftechnikfragen bleiben unverändert.

## Änderungen in Version 3.2

- 43 direkte Fragen zu Unterpunkten ergänzt (R322–R364), um die vollständige direkte Abdeckung der nummerierten Absätze zu erreichen.
- Antwortoptionen aller 75 Definitionsfragen und der älteren Regelabschnittsfragen R143–R202 fachlich passender formuliert.
- Mehrere frühe Kernfragen zu Suchzeit, Reihenfolge, Naturkräften, Penalty Areas und Berichtigungsfristen präzisiert.
- Golftechnik, darunter die 167 PGA-Fragen, unverändert gelassen.
- Die wesentlichen Regeländerungen 2023 auf den gedruckten Buchseiten 18–19 sind in der Matrix orange hervorgehoben.

Kurztests und Prüfungssimulationen priorisieren noch nicht gestellte und falsch beantwortete Fragen; der Testverlauf bleibt lokal im Browser. Die Regelfragenquelle `rules.json` ist die einzige Datenquelle; die Anzahl wird dynamisch angezeigt.
