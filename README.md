# Supply-Chain-Bottleneck-Analytics
Lieferketten Engpass- und Umsatzanalyse
Ueberblick
Dieses Projekt bietet eine durchgehende Lieferkettenanalyse eines Datensatzes mit einem Gesamtumsatz von 577 Tsd. USD, um betriebliche Engpaesse zu identifizieren, die Zuverlaessigkeit von Lieferanten zu bewerten und Umsatzbeitraege nach Produktkategorien zu analysieren.

Um Hosting-Einschraenkungen im Web zu umgehen und gleichzeitig technische Tiefe sowie eine interaktive Bereitstellung zu gewaehrleisten, nutzt das Projekt eine Dual-Plattform-Architektur:

Power BI Desktop: Kerndatenmodellierung, Sternschema-Architektur, Power Query Transformationen und Entwurf von DAX-Kennzahlen.

Tableau Public: Rekonstruierte interaktive Visualisierungen fuer dynamisches Cross-Filtering im Web.

Technischer Stack und Architektur

Business Intelligence: Power BI Desktop, Tableau Public

Datenmodellierung und Abfragen: DAX (Data Analysis Expressions), Power Query / M

Entwickelte Hauptkennzahlen:
Avg Lead Time = AVERAGE(supply_chain_data[Lead times])
Defect Rate % = AVERAGE(supply_chain_data[Defect rates])
Revenue Contribution = SUM(supply_chain_data[Revenue generated])

Wichtige Erkenntnisse

Lieferantenleistung: Identifizierung spezifischer Lieferanten mit erhoehten Lieferzeiten, was gezielte Nachverhandlungen von Service Level Agreements ermoeglicht.

Konzentration der Ausschussrate: Erkennung von Qualitaetsschwankungen in Verbindung mit langen Lieferzeiten zur Identifizierung betrieblicher Risiken.

Umsatzverteilung: Auswertung der Kategorienbeitraege, wobei Hautpflege und Haarpflege zusammen ueber 70 Prozent des Gesamtumsatzes ausmachen.

Inhalt des Repositories

Supply_Chain_Analysis.pbix: Vollstaendiges Power BI Desktop Modell inklusive Abfragen und DAX-Kennzahlen.

supply_chain_data.csv: Ursprungssatensatz.

PowerBI_Walkthrough.mp4: Videodemonstration der Modellbeziehungen, DAX-Formeln und Filterfunktionen.
