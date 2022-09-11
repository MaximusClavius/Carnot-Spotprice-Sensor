# Carnot-Spotprice-Sensor
7 day forecast on spot prices for electricity by Carnot/7 dags prognose på spotpriser på el

Et projekt som findes: https://www.carnot.dk, og som laver prognoser 7 dage frem på spotpriser for el. For at få glæde at data skal man anskaffe sig en bruger og api-nøgle, som skal bruges i sensoren hvor der står <USER_NAME> og <API_KEY>. Ønsker man data fra andre områder, så skal region=dk1 ændres til eksempelvis DK2

TO-DO:
1) Tilføj sensor
2) Tilføj kort (Søjlediagram)

Ad 1:
Hele koden til sensor smides ind i configuration.yaml eller bruger du separat fil til sensorer, så alle linjer undtagende den første (som starter med sensor). Eventuel "TJEK KONFIGURATION" og derefter "GENSTART"! Alternativt kan man nøjes ned "GENINDLÆS KOMMANDOLINJE ENTITETER", hvis denne funktionalitet er aktiveret.

Ad 2:
"Tilføj kort" til din brugergrænseflade/dashboard, og vælg apexcharts-card. Så kopier du koden ind vinduet til venstre, så skulle diagrammet komme til syne i højre vindue. Diagramet bruger grøn, gul og rød farve for at markere forskelle pris, hvor grøn er lavest og rød højest.

![image](https://user-images.githubusercontent.com/103023823/183442330-8b9001a8-89b4-4f08-867b-d1780cdfcbd0.png)

PS
Viser diagrammet "Loading" i stedet for data fra sensor, så er formentlig noget gal med formattering af koden eller ikke komplet kopiering. Vælg ikon "Copy raw content" på Github, og brug Ctrl+a for at markere al tekst og indsæt/erstat med Ctrl+v...
