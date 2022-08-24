# Carnot-Spotprice-Sensor
7 day forecast on spot prices for electricity by Carnot/7 dags prognose på spotpriser på el

Et projekt som findes: https://www.carnot.dk, og som laver prognoser 7 dage frem på spotpriser for el. For at få glæde at data skal man anskaffe sig en bruger og api-nøgle, som skal bruges i sensoren hvor der står <USER_NAME> og <API_KEY>. Ønsker man data fra andre områder, så skal region=dk1 ændres til eksempelvis DK2

Sensor skal indsættes i configuration.yaml eller den fil du bruger til sensorer i HA.

"Tilføj kort" til din brugergrænseflade/dashboard, og vælg apexcharts-card. Så kopier du koden ind vinduet til venstre, så skulle grafen komme til syne i højre vindue.
Diagramet bruger grøn, gul og rød farve for at marke forskelle pris, hvor grøn er lavest og rød højest.

![image](https://user-images.githubusercontent.com/103023823/183442330-8b9001a8-89b4-4f08-867b-d1780cdfcbd0.png)
