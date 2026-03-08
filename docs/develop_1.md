## Develop 1
### Doelstellingen
In deze fase werd het concept nog bijgestuurd en bepaalde functionele zaken gevalideerd. Er werd vertrokken vanuit opgestelde onderzoeksvragen en hypotheses die in deze fase beantwoordt zullen worden.

- Zijn ringen de optimaalste manier om de haptische feedback waar te nemen?
*Vermoedelijk niet, ringen kunnen onhandig zijn tijdens het spelen. Ook moeten er steeds drie ringen worden aangedaan, wat veel tijd kan kosten.*

- Op welke manier kan het spelen en interageren met elkaar beter gestimuleerd worden?
*Onderzoek wat er reeds bestaat m.b.v. benchmarking en vertaal deze speelvormen in prototypes.*


### Materiaal & methoden
In deze fase werden stonden twee aspecten centraal: De meest optimale manier om te navigeren en verschillende speelfuncties. Dit wordt gesplitst in twee waves. Er wordt vertrokken vanuit een centraal storyboard. 
<p align="center">
  <img src="../img/documentjes (3).jpg" width="100%">
</p>


#### Wave 1
In de eerste wave staat de manier van navigeren centraal. Reeds werd bevestigd dat navigeren via haptische feedback een goede oplossing is waar er in deze wave mee wordt verder gegaan. Trillingen vergen namelijk geen visuele ondersteuning en worden ervaren via de zintuigelijke waarnemingen. Ook wordt er een belangrijke scene gerolplayed waarbij de kinderen samen de armbanden dragen en de verschillende kleuren overlopen. Dit principe zal op de speelplaats getest worden.

[Protocol Wave 1](https://docs.google.com/document/d/1nPsdfydx2fvQFqMQH2k9aMCh4dT-5UrECPmXcozBuiY/edit?usp=sharing) (N=3)
[Rapport Wave 1](https://docs.google.com/document/d/1AFayvt5vMAW4omSunCLhBP_VLpjjSemOP6mUQBEzia4/edit?usp=sharing) (N=3)

##### Prototypes
Verschillende varianten werden met behulp van Arduino gerealiseerd.
1) Armband met drie ringen
Werking: 
Pink trilt = naar links, middelvinger trilt = rechtdoor, duim trilt = naar rechts
2) Twee armbanden  
Werking: 
Linker armband trilt = naar links, rechter armband trilt = naar rechts, beiden trillen = rechtdoor
3) Eén armband  
Werking: 
Pink trilt = naar links, middelvinger trilt = rechtdoor, duim trilt = naar rechts 


##### Conclusies & implicaties
De kinderen vonden algemeen de trillingen een goede manier om te navigeren. Dit is een visueel onafhankelijke oplossing en kan door iedereen gebruikt worden. Wel waren de meningen sterk verdeeld waardoor er wordt gegaan voor de optie die niemand als minst beste ervaarde namelijk één armband zonder ringen. De ringen zijn voor de slechtziende kinderen een te grote last aan de vingers tijdens het fysiek bewegen op de speelplaats en kunnen ook blijven hangen aan iets waardoor dit gevaarlijker is. Daarom is dit geen goede optie ondanks het voor het blinde kind, dat iets rustiger is op de speelplaats, wel de favoriete was. 
Uit de analyse zijn het bevestigen van de aankomst en het waarschuwen van obstakels zaken waar rekening mee gehouden moet worden in de volgende fases.

Bij het rolplayen werd er vastgesteld om voor de blinde kinderen niet alleen gekleurde knoppen te voorzien waarbij de kleur wordt voorgelezen bij het indrukken, maar ook tactiele knoppen met elke knop een specifieke vorm. Op die manier kunnen zij ook makkelijker personen ingeven in de armband zonder eerst alle opties te moeten doorlopen.



#### Wave 2
Het doel van deze tweede wave is het onderzoeken van de reactie en de onderlinge interactie tussen de kinderen bij het testen van de prototypes. Deze zijn gebaseerd op voelbare impulsen en geluidsbeleving. Belangrijk is om het gevoel van de kinderen goed te observeren en nagaan of de onderlinge interactie gestimuleerd wordt.

[Protocol Wave 2](https://docs.google.com/document/d/1_SrTmNFUYpZebSoyYL-cApbTEUQ2hVBj7rHwhpm2ETI/edit?usp=sharing) (N=2)
[Rapport Wave 2](https://docs.google.com/document/d/1WfAI9g7FnhT1T2cpIMoxWpf2htsGCqGHAacFuqu-JKY/edit?tab=t.0) (N=2)


##### Prototypes
Verschillende opties werden overwogen en getest via walkie talkies en Arduino.

##### Conclusies & implicaties
Uit de testen blijkt dat beide functies , het zoekspel met trillingen en de walkie-talkie, goed werken en duidelijk sociale interactie tussen de kinderen stimuleren.
Bij het zoekspel begrepen beide kinderen snel hoe het systeem werkte. De trillingen hielpen hen om elkaar te lokaliseren en het spel leidde tot veel enthousiasme en interactie. De testpersonen gaven aan dat ze het spel leuk vonden en opnieuw zouden willen spelen (5/5). De trillingen waren volgens hen wel wat te zacht, wat een belangrijk aandachtspunt is. De trillingen minder intens maken was een goede oefening maar bleek niet zo nodig als gedacht. Voor het blinde kind was deze functie zeer toegankelijk en bruikbaar. Algemeen werd dit eerder als een extra spelvorm gezien dan als een noodzakelijk hulpmiddel.
De walkie-talkie functie werkte zeer vlot. De kinderen konden gemakkelijk met elkaar communiceren en vonden elkaar snel via verbale instructies. Ook hier waren de scores zeer positief: beide kinderen vonden het leuk en voor herhaling vatbaar (5/5). Dit toont aan dat communicatie via geluid een sterke manier is om samenwerking en interactie te stimuleren. Een geslaagde test dus! 
Op basis van deze test kan geconcludeerd worden dat zowel haptische feedback (trillingen) als audiocommunicatie geschikte interactievormen zijn voor blinde en slechtziende kinderen. Beide functies zorgen voor spelenderwijs contact en samenwerking tussen de kinderen. Voor de verdere ontwikkeling is het vooral belangrijk om de trillingssterkte terug aan te passen, zodat de feedback nog duidelijker waarneembaar is. De walkie-talkie functie is voldoende gevalideerd en zal geïntegreerd worden in de armband.



### Functionele breakdown
De functionele breakdown bevat verschillende deelaspecten voor betere grip te krijgen op de architectuur. Deze werden doorheen deze fase opgesteld en bijgewerkt na de testen om duidelijk de verschillende aspecten van het concept te evolueren naar een onderbouwde functionele architectuur.

#### Morfologische Matrix
Eerst werden alle mogelijkheden nog eens uitgeschreven per functie om vervolgens de beste combinatie hieruit te maken.

<p align="center">
  <img src="../img/documentjes (2).jpg" width="100%">
</p>


#### Productarchitectuur
De productarchitectuur geeft een overzicht van de gebruikte elektronica verwezen naar de armband.

<p align="center">
  <img src="../img/documentjes (1).jpg" width="100%">
</p>

#### User flows 
De user flows verduidelijkt de interactie tussen mens en product. Het helpt de gebruiker hoe die stap per stap een handeling moet uitvoeren.
<p align="center">
  <img src="../img/Information Architecture & User flows (11).jpg" width="100%">
</p>


#### Informatiearchitectuur
De informatiearchitectuur ordent informatie over het product op een gestructureerde wijze om zo gebruiksgemak en effeciëntie te optimaliseren.
<p align="center">
  <img src="../img/Information Architecture & User flows (12).jpg" width="100%">
</p>

#### MVP-definitie
Via de MoSCoW methode werden de primaire en secundaire functies gedefinieerd.
<p align="center">
  <img src="../img/Information Architecture & User flows.jpg" width="100%">
</p>