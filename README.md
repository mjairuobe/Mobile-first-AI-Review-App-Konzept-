# Mobile-first AI-Review-App Konzept

Das AI-Zeitalter hat Softwareentwickung das grundlegend verändert. AI nimmt uns durch agentische Workflows viel Arbeit bei der Softwareentwicklung ab. 

In kürzerer Zeit produziert AI viel mehr Codingoutput als ein Entwickler. Entwickler kümmern sich mehr um architektonische Entscheidungen. Der Fokus hat sich also verschoben, vom Schreiben zum Denken.

## Das Problem 
Die meiste Denkarbeit machen wir nicht auf Knopfdruck. Die besten Ideen kommen bei mir beim Zähneputzen. 
Ich betrachte unser Bewusstsein als Richtungsgeber. Das Bewusstsein gibt die Richtung vor, unser Unterbewusstsein arbeitet an wichtigen Denkprozessen im Hintergrund weiter. 

Doch wenn wir beim Zähneputzen eine Idee bekommen, dann müssen wir immer noch AI-Agenten anstoßen, diese Ideen umzusetzen. Das geht vom Handy - jederzeit. 

Doch wie überprüfen wir die Arbeit von AI-Agentdn vom Handy?
Heutige Entwicklungswerkzeuge sind nicht unbedingt Mobile-first gebaut. 

### Herausforderungen 
- Quellcode-Review Handy optimiertlen
- neue große Codebasen ergründbar machen
- Text-Response von Agenten muss einfacher überblickbar sein z. B. einer Konvention folgen und die Textlänge begrenzen

## Lösungsansätze

### UML zum Review nutze

### Nahtlose Integration von interaktiven Klassendiagrammen im Review-Prozess
Ein Smartphone kann häufig ohne Scrollen ein Klassendiagramm komplett darstellen. Das macht ein Klassendiagramm, Mobbile-first Review-fähig. 

- Klassen-Diagramme helfen, um Software-Code schnell zu verstehen. 
- Klassendiagramme können automatisch generiert werden z. B. mit Pyreverse lassen sich Mermaid Diagramme generieren
- im Klassendiagramm könnten geänderte Funktionen gehighlighted werden
- Methoden, Zustände und Deklarationen könnten Hyperlinks zu Pages innerhalb der Review-App sein
- Tools wie Snapify können Programmcode z. B.  Methoden, Deklarationen ansehnlich darstellen

#### Konkretes Umsetzungsidee
- App-Pages mit hübschen Klassndiagrammen aus Formaten wie Mermaid mit verlinkbaren Klassenelementen zur Interaktion, Highlighting von geänderten Methoden, Variablen etc.
- Pages zur Review einzelner Methoden oder Codeelementen, Highlightimg der Änderungen, kein Scrollen

So kann ein effizienter Software-Review-Prozess auf dem Handy unterstützt werden. 

### Konzept-Todos
- Ideen zu automatischen Verstehen von Softwaresystemen z. B  Generierung von Sequenzdiagrammen
- Beschreibung von Templates mit Längenbegrenzungen für AI-Textresponse nach Kategorie z. B. PR, Bugfix-Report, Featureimplementation Bericht etc. - macht Review Prozess schneller 
