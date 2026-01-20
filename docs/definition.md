## Definition

### Doestellingen
- Opgestelde functies al dan niet valideren
- Vorm van het product en type knoppen definiëren
- Inzicht krijgen in de eisen en wensen van de doelgroep en dit verwerken in het eerder bedachte concept
- Belangrijke design requirements bepalen
### Materiaal & methoden
Wave 1:
We zijn vertrokken vanuit een storyboard.

<p align="center">
  <img src="../img/Schermafbeelding 2026-01-20 213930.png" width="100%">
</p>


In deze wave stonden volgende vragen centraal:
- Wat is de meest ideale vorm van het product in de geschikte context?
- Welke knoppen zijn het optimaalst om de hanteren?
- Hoe ervaren ze deze knoppen?
- Waarvoor zullen deze knoppen precies dienen?


Om op deze vragen antwoorden te krijgen, zijn we fysieke prototypes maken. Deze zullen we vervolgens in een user test gaan voorleggen aan onze doelgroep. De bedoeling is dat de verschillende knoppen getest zullen worden op de vormen. Deze prototypes zijn modulair, wat betekent dat je eenvoudig de knoppen m.b.v. klitteband makkelijk op de vormen kunt plaatsen. De bedoeling is dat ieder kind elke combinatie ervaart en ons zo de persoonlijke voorkeuren bezorgt in de vorm van een vragenlijst op het einde.  
<p align="center">
  <img src="../img/Schermafbeelding 2026-01-20 215616.png" width="100%">
</p>


Wave 2:
We zijn ook weer hier vertrokken vanuit een storyboard.

<p align="center">
  <img src="../img/Schermafbeelding 2026-01-20 213959.png" width="100%">
</p>

In deze wave stonden volgende vragen centraal:
- Kunnen kinderen de navigatie via vibraties correct volgen en is dit duidelijk?
- Kunnen kinderen elkaar sneller vinden met behulp van licht?
- Kunnen kinderen  interactief spelen met de armband?
- Is het gebruik van knoppen voor geluid intuïtief en plezierig?
- Ondersteunen de functies de samenwerking en sociale interactie?

Om op deze vragen antwoord te krijgen, hebben we weer fysieke prototypes gemaakt en deze laten testen door onze doelgroep in de vorm van een user test. In deze wave worden de functies zeer goed ervaren omdat dit in de juiste context namelijk de speelplaats. Tijdens de testen werd het think aloud protocol toegepast zodat wij steeds op de hoogte waren van hun ervaringen en bevindingen.

Trillingen: Deze kunnen veel hulp bieden bij navigatie. De vibratie motoren worden aangestuurd door een Arduino nano die op een Grove Shield wordt gezet. De motoren zullen om de beurt vibreren voor 1 seconden en daartussen is 4 seconden rust. 
De pijlen tonen het modeltraject wanneer vibratieMotor 1 het rechtse signaal geeft, vibratieMotor 2 aan de middelvinger is aangesloten en vibratieMotor 3 het signaal in de linkse richting geeft.
Het is dus de bedoeling dat de kinderen zelf snappen wat ze moeten doen en het traject zo goed mogelijk proberen af te leggen.

Licht: Dit kan ook een mogelijkheid zijn om elkaar te vinden voor de slechtziende kinderen. De test zal spelenderwijs gebeuren. We gebruiken hiervoor 1 fietslampje met zeer fel licht en 2 fietslampjes met minder licht.
In het eerste spel zal om beurten iemand zich verstoppen met een fietslampje op de speelplaats, de andere 4 kinderen zullen hem of of haar zo snel mogelijk moeten zoeken.  
Bij het tweede spel zullen alle kinderen moeten zoeken naar alle 3 de lichtjes.
De bedoeling is dat de slechtziende kinderen elkaar makkelijker kunnen vinden d.m.v. de lichtjes. 

Spelletjes: Een van de speelfuncties zijn knoppen die geluid maken. Dit is een zeer leuke methode om op een auditieve manier interactie met elkaar te maken. 
Met behulp van de Makey Makey setup is het zeer makkelijk om dit waar te maken. Je kan deze simpelweg aansluiten op je laptop en het makey makey platform openen waar er talloze activiteiten te vinden zijn. Deze omvatten zowel games als geluidmakende tools. De bedoeling is om te kijken of de kinderen dit een aangename tool vinden en of ze hier graag nog in de toekomst mee willen spelen.
Ook kan een ingebouwde walkie-talkie veel voordelen beiden voor zowel de speel- als de navigatiefuncties.


<p align="center">
  <img src="../img/Schermafbeelding 2026-01-20 224633.png" width="100%">
</p>


### Resultaten
Rapporteer over de resultaten (incl. foto's, quotes, analyseframeworks, ...)
Resultaten Wave 1:
De resultaten van de verschillende vormenen en knoppen zijn in de tabellen weergegeven.
De armband scoort duidelijk het best. De proefpersonen vinden het een handige 
plaats om dingen te bedienen zonder dat er restricties in beweging zijn. 
De ringen erbij vonden ze cool en stoorde niemand.
De ketting stoorde bij sommigen. Daarnaast is het handig 
dat deze altijd binnen handbereik hebt.
De stok kreeg veel gemengde oordelen. Deze moet je ook effectief vasthouden in je hand als je de bediening wilt gebruiken. Dit kan dus moeilijkheden geven voor kinderen met CVI die minder mobiel zijn of kinderen die mobiliteitshulpmiddelen nodig hebben. 
De mouw scoorde het slechtste omdat de kinderen vonden dat het restricties gaf in hun bewegingen. 

Daarnaast vonden ze de auditieve feedback bij de rode knop het allerbelangrijkste maar helaas was deze net iets te klein.
De blauwe knop zijn beste eigenschappen zijn grootte en zachtheid. 
Het laagste gerangschikt was de draaiknop. Deze gaf namelijk ook weinig feedback. Daarnaast zou de draaifunctie moeilijker zijn dan het drukken voor kinderen met CVI die het motorisch moeilijker hebben.
<p align="center">
  <img src="../img/Schermafbeelding 2026-01-20 222945.png" width="100%">
</p>

Design Requirements:


Resultaten Wave 2:

Tijdens het traject met de vibrerende motoren vonden de kinderen het heel handig en ervaarden geen ongemak. Het kon zelfs gecombineerd worden met een looprek.

de experte vertelt: “Veel kinderen met CVI weten het verschil niet snel tussen links en rechts, als je hun zou zeggen ga naar rechts zou dit moeilijkheden geven.” 

Ook is door moeilijkheid met oriëntatie de hoek die ze maken niet altijd 90°. Hier moet wel rekening mee worden gehouden.
Bij het zoeken naar het vriendje was wel degelijk een verschil te zien tussen het zoeken naar hem/haar zonder lichtje of met lichtje.
Om de speelfunctie te testen maken we gebruik van de Makey Makey en externe knoppen. De kinderen waren steeds aan het lachen en bleven het leuk vinden om op hun knopje te duwen. 
Ook waneer je de knop inhoudt, zal het geluid blijven komen en pas stoppen als de knop terug wordt losgelaten. De experte verklaart dat ook de kinderen die minder mobiliteit in hun handen hebben zo toch makkelijk zouden kunnen meespelen. 

<p align="center">
  <img src="../img/Schermafbeelding 2026-01-20 222931.png" width="100%">
</p>

Design Requirements:



### Conclusies & implicaties
Door al deze testen zijn we tot belangrijke besluiten gekomen. 
Uit Wave 1 hebben we vastgesteld dat het product een armband moet zijn en deze geen draaiknoppen mag bevatten. 
Uit Wave 2 constateerden we dat de navigatiefunctie een groot succes was bij de trillingen als de lichtjes alhoewel de trillingen een groter doelpubliek bereiken. Deze kunnen door zowel slechtziende als blinde kinderen gebruikt worden. Daarnaast waren de spelletjes ook een grote troef en vonden de kinderen het zeer aangenaam deze te gebruiken.