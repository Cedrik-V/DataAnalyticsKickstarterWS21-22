DataAnalyticsKickstarterWS21-22

Kurzbeschreibung
  Der ausgewählte Datensatz beinhaltet über 300000 Datensätze über Kickstarter Projekte. Der Datensatz stammt aus 2018. Ziel   der Analyse der Daten ist das Bestimmen von relevanten Faktoren, welche Den Erfolg einer Kampagne auf der Kickstarter         Webseite definieren. Grundlegende Zielsetzung ist es, ein Modell zu erstellen, welches Die Erfolgschancen eines Projektes     vor dem Release bestimmen kann. Die daraus erzielten Informationen könnne genutzt werden, um zum einen Gründer der Projekte   zu einem erfolgreicheren Projekt zu verhelfen. Gleichzeitig dient es potenziellen Unterstützern zu entscheiden, welche       Projekte am aussichtreichsten sind.
  
Bearbeiter (Namen, Abteilungen/Studiengänge)
  Niclas Selig, Master Digitale Prozesse & Technologien
  Cedrik Venier, Master Digitale Prozesse & Technologien
  
Welche Daten liegen vor?
  Der Datensatz besteht aus 375765 Werten:
  Attribute:
    1.	ID
    2.	Name
    3.	Category
    4.	Main_category
    5.	Currency
    6.	Deadline
    7.	Goal (Goal amount in project currency)
    8.	Launched
    9.	Pledged: Pledged Amount in the project currency
    10.	State: Failed/Sucessful/Other
    11.	usd pledged : Pledged amount in USD (conversion made by KS)
    12.	usd_pledged_real: Pledged amount in USD (conversion made by fixer.io api)
    13.	usd_goal_real: Goal amount in USD

•	Welche Daten fehlen? Wie sollen diese erhoben werden?
•	Ist eine Zielvariable erforderlich/liegt sie vor? (z.B. bei einer Klassifikation: sind Informationen über die positiven und negativen Klassenzugehörigkeiten vorhanden? Gibt es ausreichend Beispielen zu beiden Fällen?) Regressionsmodell: Wie wahrscheinlich ist ein Erfolg?

•	Was ist bezüglich Datenschutz, Datensicherheit und Ethik zu bedenken?
der datensatz an sich ist relativ unbedenklich, creatormund teamanalyse als attribut könnte zu bias führen.
haben creatir schon mehrere gescheiterte projekte-> bias

•	Welche analytische(n) Fragestellung(en) müssen bearbeitet werden? 

-Welche Arten von Modellen werden benötigt?

•	Welche nicht-funktionalen Anforderungen bestehen (z.B. Verständlichkeit des Modell, Skalierbarkeit, Echtzeitfähigkeit, …)?
Verständlichkeit des Modells ist sehr wichtig-> um aus prozentzahl der wahrscheinlichkeit die relevnaten attribute und einflüsse bestimmen zu können, um daraus basierend  das projekt zu optimieren.

•	Sonstiges


Projektfragen

-Modell: Die Erfolgschancen eines Projektes     vor dem Release bestimmen kann
-zeitliche Betrachtung: Gibt es Trendverämderung anhand der zeitachse in den daten?
--welche attribute sind am relevantesten für den Projekterfolg
-Projektbeschreibung als relevnates <attribut untersuchen
-wieso so viele Projekte in den usa, und nicht in de      
- creator mit mehreren Projekten: haben die mehr erfolg?
- Team als relevantes Attribut: Zusammnesetzung, alter, Präsentation

  
