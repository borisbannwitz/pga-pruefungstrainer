# PGA Prüfungstrainer

Web-App-Version **2.2**. Der Regelfragenpool enthält 234 Fragen; der Bereich PGA/Golftechnik enthält 167 Fragen einschließlich GOSSIP.

Die App zeigt beim Öffnen eine Passwortabfrage. Sie blendet nur die Oberfläche aus; Dateien im öffentlichen Repository bleiben abrufbar.

Die App wird über [GitHub Pages](https://borisbannwitz.github.io/pga-pruefungstrainer/) bereitgestellt.

## Regelabdeckung

- [Vollständige Abdeckungsmatrix (595 Einträge)](docs/Regelabdeckungsmatrix_2023.md)
- [Matrix der 185 nummerierten Regelunterpunkte](docs/Nummerierte_Regelunterpunkte_Matrix.md)
- [Fortsetzungsstand und nächste Schritte](docs/Fortsetzungsstand_Regelfragen.md)

Kurztests und Prüfungssimulationen priorisieren noch nicht gestellte und falsch beantwortete Fragen; der Testverlauf bleibt lokal im Browser.

Die Regelfragenquelle `rules.json` ist die einzige Datenquelle; die Anzahl wird dynamisch angezeigt. Die Regelfragen liegen in `rules.json`, die PGA-Golftechnikfragen in `questions.json` und `questions.js`.