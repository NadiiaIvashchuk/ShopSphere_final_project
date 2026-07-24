# ShopSphere Marketplace Performance Analyse
#
## ShopSphere-Marktplatzanalyse  
Analyse der globalen Online-Marktplatzdaten des ShopSphere Marketplace sowie Erstellung datenbasierter Berichte und Dashboards für das Management

## Datenquelle

Die Analyse basiert auf dem E-Commerce-Datensatz ShopSphere Marketplace, der Informationen zu Bestellungen, Kunden, Produkten, Marketingkanälen und Retouren enthält.

## Verwendete Technologien

- SQL(SQLite)
- Tableau Public
- GitHub (Dokumentation)

## Ziel des Projekts

Ziel des Projekts war die Entwicklung eines interaktiven Management-Dashboards zur Analyse der Performance eines Online-Marktplatzes. Das Dashboard unterstützt Führungskräfte bei datenbasierten Entscheidungen in den Bereichen Umsatzentwicklung, Marketingeffizienz, Kundenverhalten und Produktperformance.

Durch die Kombination verschiedener KPIs und Visualisierungen ermöglicht das Dashboard sowohl einen schnellen Überblick über die Geschäftsentwicklung als auch eine detaillierte Analyse der wichtigsten Einflussfaktoren.

---

## Projektvorgehen

1. Datenaufbereitung (SQL)
   - Zusammenführung der Tabellen mittels JOINs
   - Filterung abgeschlossener Bestellungen
   - Berechnung von KPIs und aggregierten Kennzahlen
   - Erstellung der Datengrundlage für Tableau

2. Datenvisualisierung (Tableau)
   - Entwicklung interaktiver Dashboards
   - Visualisierung zentraler KPIs
   - Analyse von Marketing, Kunden, Produkten und Umsatzentwicklung
   - Implementierung interaktiver Filter und Drill-down-Funktionen

3. Business-Analyse
   - Interpretation der Ergebnisse
   - Ableitung strategischer Handlungsempfehlungen
   - Erstellung des Management Reports

## Dashboard

Link für Tableau Public: (https://public.tableau.com/views/ShopSphereanalyse/Dashboard1?:language=de-DE&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link). 
Diagramm-Screenshots - ShopShere_project/Tableau/Diagramm_screenshots.md.

## Wichtigste  Erkenntnisse

- Organic Marketing erzielt den höchsten ROI (8,02), während Influencer-Kampagnen den höchsten Customer Lifetime Value (1,77 Tsd. €) generieren. Eine ausgewogene Kombination beider Kanäle bietet das größte Wachstumspotenzial.

- Obwohl Electronics den höchsten Umsatz erzielt, weisen die Kategorie eine vergleichsweise niedrige Gewinnmarge und die höchste Retourenquote auf. Beauty und Home & Kitchen zeigen dagegen ein deutlich attraktiveres Profitabilitätsprofil.

- Die TOP-5-% der Kunden erwirtschaften 34,6 % des Gesamtumsatzes und generieren pro Kunde rund das Zehnfache des Umsatzes gegenüber allen übrigen Kunden. Eine gezielte Bindungsstrategie für diese Kundengruppe verspricht einen hohen geschäftlichen Nutzen.

- Hohe Rabatte gehen mit einer deutlich geringeren Bestellhäufigkeit einher. Rabattaktionen sollten daher gezielt eingesetzt und nicht als langfristiges Instrument der Kundenbindung betrachtet werden.

- Die Ergebnisse des A/B-Tests zeigen, dass Variante B vor allem bei Neukunden einen deutlichen Mehrwert liefert (+19 %), während sich für Bestandskunden kaum Unterschiede ergeben. Ein segmentierter Rollout erscheint daher sinnvoller als eine vollständige Einführung.

## Strategische Empfehlungen

- Marketingbudget zugunsten der Kanäle Organic, Influencer und Referral umverteilen

- Beauty und Home & Kitchen stärker fördern, da diese Kategorien hohe Margen erzielen

- Rabattaktionen gezielt einsetzen und nicht als allgemeines Wachstumsinstrument verwenden

- VIP- und Loyalty-Programme für die umsatzstärksten 5 % der Kunden ausbauen

- Mobile Customer Experience sowie die Vorbereitung auf das Weihnachtsgeschäft priorisieren

  
## Repository-Strukewsatur

```
data/       hochgeladene CSV
sql/        queries.sql, SQL_Ergebnisse.md
tableau/    Diagramm-Screenshots, ShopSphere analyse.twb
Management Report.md
README.md
```

## Reproduzierbarkeit

So kann das Projekt reproduziert werden:

1. Repository klonen.
2. Die SQL-Datenbank in SQLite öffnen.
3. Die SQL-Skripte zur Erstellung der Analyse-Datensätze ausführen.
4. Die erzeugten CSV-Dateien in Tableau Public importieren.
5. Die Arbeitsmappen öffnen oder das Dashboard anhand der bereitgestellten Visualisierungen nachbauen.
