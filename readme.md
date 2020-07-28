# Codebuch 
--> Netzwerk der Mitglieder der Kohlekommission

# Edgelist:

# id (eindeutige Codierung der Knoten)
- codiert mit Namen der Person/Organisation/Verband/Partei

# from 
- ID Mitglied der Kommission

# to
- alle Mitgliedschaften der Person (z.B. politische Partei)

# Nodelist: 

# id
- Identische ID wie aus der Edgelist zur Identifikation der Knoten 

# type
- 0=Person
- 1=Organisation

# sex 
- Geschlecht des Knotens 
- male=1 
- female=2 
- NA(Organisationen)= 99

# age 
- 0 = Organisationen/Unternehmen/Verbände
- 1 = bis 40 Jahre
- 2 = 41 bis 50 Jahre
- 3 = 51 bis 60 Jahre
- 4 = 61 und älter
 
# party 
- Mitgliedschaft in politischer Partei
- 1=CDU
- 2=SPD
- 3=Die Grünen
- 4=FDP
- 5=Tierschutzpartei
- 6=CSU
- 7=parteilos
 
# representation 
- bezieht sich auf die Funktion innerhalb der Kommission
- 1=Politik
- 2=Wirtschaft
- 3=Gewerkschaft
- 4=Umwelt 
- 5=Regionen
- 6=Wissenschaft
- 99= NA(keine Funktion in der Kommission)

# position
- 1=Vorsitz
- 2=Mitglied
- 3=kein Stimmrecht
- 99=NA(keine Position) 

# state (Bundesland)
- 1=Brandenburg 
- 2=Nordrhein-Westfalen 
- 3=Sachsen 
- 4=Bayern 
- 5=Baden-Württemberg
- 6=Hessen 
- 7=Niedersachsen
- 8=Schleswig-Holstein 
- 9=Hamburg
- 10=Berlin
- 99=NA(keine Angaben)
