# PGA Prüfungstrainer

Web-App-Version **3.1**. Der Regelfragenpool enthält 321 Fragen: 246 Regel- und Änderungsfragen sowie 75 Definitionsfragen. Der Bereich PGA/Golftechnik enthält 167 Fragen einschließlich GOSSIP.

Die App zeigt beim Öffnen eine Passwortabfrage. Sie blendet die Oberfläche aus; die Dateien im öffentlichen Repository bleiben abrufbar.

Die App wird über [GitHub Pages](https://borisbannwitz.github.io/pga-pruefungstrainer/) bereitgestellt.

## Regelabdeckung

- [Vollständige Abdeckungsmatrix (595 Einträge)](docs/Regelabdeckungsmatrix_2023.md)
- [Matrix der 185 nummerierten Regelunterpunkte](docs/Nummerierte_Regelunterpunkte_Matrix.md)
- [Fortsetzungsstand und nächste Schritte](docs/Fortsetzungsstand_Regelfragen.md)

Die Matrix verknüpft 142 von 185 nummerierten Unterpunkten direkt. 43 sind nur über einen verwandten Regelzweig abgedeckt; keiner bleibt ohne zugeordneten Regelverweis.

## Änderungen in Version 3.1

- Antwortoptionen aller 75 Definitionsfragen und der älteren Regelabschnittsfragen R143–R202 fachlich passender formuliert.
- Zwölf direkte Fragen für nummerierte Regelunterpunkte ergänzt (R310–R321).
- Frühe Kernfragen zu Suchzeit, Reihenfolge, Naturkräften, Penalty Areas und Berichtigungsfristen präzisiert.
- Golftechnik, darunter die 167 PGA-Fragen, unverändert gelassen.
- Die wesentlichen Regeländerungen 2023 auf den gedruckten Buchseiten 18–19 sind in der Matrix orange hervorgehoben.

Kurztests und Prüfungssimulationen priorisieren noch nicht gestellte und falsch beantwortete Fragen; der Testverlauf bleibt lokal im Browser. Die Regelfragenquelle `rules.json` ist die einzige Datenquelle; die Anzahl wird dynamisch angezeigt.
