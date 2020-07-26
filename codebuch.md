Codebuch 
Inhalt

    edgelist_kohle.csv (Edgelist)
    nodelist_kohle.csv (Nodelist)
    Codebuch.md (Codierung der Datensätze)

Ursprung und Datenerhebung

Im Zentrum der Analyse steht das Netzwerk der Kohlekommission, welches auf seine Mitglieder und deren Mitgliedschaften in weiteren Organisationen (Partei) untersucht und interpretiert werden soll. Als Grundlage für die Analyse dienen ein Artikel der klimareporter über die Mitglieder der Kohlekommission (https://www.klimareporter.de/deutschland/das-sind-die-mitglieder-der-kohlekommission), ergänzend dazu das Munzinger Archiv (https://www.munzinger.de/search/start.jsp) und die Pressemeldung des Bundesministerium für Wirtschaft zur Kommission (https://www.bmwi.de/Redaktion/DE/Pressemitteilungen/2018/20180606-bundeskabinett-setzt-kommission-wachstum-strukturwandel-und-beschaeftigung-ein.html).
Es wird ein ungerichtetes two-mode Netzwerk (Akteur-Organisations-Netzwerk) aus Personen/Mitgliedern der Kohlekommission und Organisationen erstellt. Fehlende Daten werden mit 99 kodiert.

Edgelist

Id 

(eindeutige Codierung des Knoten, jede ID entspricht einem Mitglied oder einer Organisation)

From (id Mitglied der Kommission)

To (id alle Mitgliedschaften der Person in anderen Organisation wie zB politische Parteien, Unternehmen, Verbände, Vereine)

Nodelist

Id

(identische Id wie aus der Edgelist zur Identifikation der Knoten)

Name (Zusätzliche Angabe zur Identifikation)

Type (Handelt es sich um eine Person oder Organisation?)
0 = Person, 
1 = Organisation

Sex (Geschlecht)
0 = männlich, 
1 = weiblich

Age (Alter der Person, bei Organisation NA)
0 = 25-40,
1 = 40-55, 
2 = 55-70, 
3 = Ü70

Party (Ist die Person Mitglied einer politischen Partei?)
0 = keine,
1 = CDU
2=SPD
3=FDP
4=Grüne

Representation (Funktion einer Person innerhalb der Kommission)
0 = Politik
1 = Wirtschaft 
2 = Gewerkschaft
3 = Umwelt 
4 = Regionen
5 = Wissenschaft)

Position (Position der Person in der Kommission)
0 = kein Stimmrecht 
1 = Mitglied
2 = Vorsitz

State (Aus welchem Bundesland stammt die Person?)
0 = Baden Württemberg
1 = Bayern
2 = Berlin
3 = Brandenburg
4 = Bremen
5 = Hamburg
6 = Hessen
7 = Mecklenburg-Vorpommern
8 = Niedersachsen
9 = Nordrhein-Westfalen
10 = Rheinland-Pfalz
11 = Saarland
12 = Sachsen
13 = Sachsen-Anhalt
14 = Schleswig-Holstein
15 = Thüringen



