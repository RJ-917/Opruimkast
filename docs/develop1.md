## Develop 1 
Voor deze fase van het project waren er een aantal moelijk te definieren overbodigheden in ons product.
Dit kwam voornamelijk doordat er nog geen value promise was vastgelegd wat er voor zorgde dat het product veel verschillende kanten konden uit gaan.
Hierdoor was het niet duidelijk was wat de volgende stap in het ontwikkelingsproces van het product was.

Het doel voor deze fase van het project is om het product voledig te ontleden doormiddel van een storyboard, user-flow en nog een paar andere methoden.
Daarnaast gaan we doormiddel van intervieuws de overbodigheden bepalen en bij onze gebruikers toetsen wat zij de belangrijkste value promise vinden van ons product.
Eenmaal al deze info verzameld en gestructureerd is zal op basis van de info een morfologische matrix opgesteld worden en een nieuw consept uitgewerkt worden.
### Product analyse
#### Storyboard
Na een verdere analyse van het probleem en de bijhorende voorwaarden werd het storyboard aangepast. Het nieuwe storyboard legt meer nadruk op de interactie met het product en schetst duidelijker de context waarin het product gebruikt wordt.
<p align="left">
  <img width="1170" height="420" alt="image" src="https://github.com/user-attachments/assets/20b0fa40-44f2-4c61-ba8f-c767f5d9623a" />
</p>
1.	De vloer ligt vol met speelgoed.
2.	De ouder bestuurt de kast via een app op de smartphone.
3.	Er wordt een foto genomen van het speelgoed om het in de kast te registreren.
4.	Het speelgoed wordt aan een specifieke bak gekoppeld.
5.	Het speelgoed wordt in de gekoppelde bak geplaatst.
6.	Het kind kiest een bak om mee te spelen.
7.	Het kind opent een bak, terwijl de andere bakken vergrendeld blijven.
8.	Wanneer het tijd is om te stoppen met spelen, wordt een opruimlied afgespeeld.
9.	Het kind wordt gestimuleerd om het speelgoed op te ruimen.
10.	Het speelgoed is opgeruimd en de ruimte is weer netjes.

#### Functie structuur
Het schema van de productarchitectuur koppelt de gewenste functies direct aan de componenten die hiervoor dienen.
<p align="left">
<img width="849" height="615" alt="image" src="https://github.com/user-attachments/assets/494ef027-0318-4530-9ba2-82164dca8af5" />
</p>

#### Product architectuur
Het interfaceschema toont de fysieke en elektronische verbindingen tussen de systeemonderdelen. Het geeft de subklassen van de componenten weer en benoemt het type connectie
<p align="left">
<img width="941" height="645" alt="image" src="https://github.com/user-attachments/assets/a6bd43bc-f0e3-462f-8798-c48a61275ad9" />
</p>

#### User-flow
Deze userflow visualiseert het volledige interactieproces tussen het kind, de kast en het systeem tijdens het spelen en opruimen. Het schema doorloopt de stappen die het kind kan nemen tijdens het gebruik van het product en toont daarnaast de mogelijke controles en reacties van het systeem. Hierdoor wordt duidelijk hoe het kind stap voor stap door het systeem wordt geleid tijdens het spelen en het opruimen van het speelgoed.
<p align="left">
<img width="5128" height="6116" alt="image" src="https://github.com/user-attachments/assets/0f6eeb70-2f2d-4bc6-b77a-3ac029f1f122" />
</p>

#### MVP defenitie
De minimum viable product van ons project is een kast die is onderverdeeld in verschillende bakken/vakken. Deze kast moet gevuld en ingesteld worden door een ouder. Achter dat een ouder de kast heeft ingesteld zou de kast zelfstandig moeten kunnen gebruikt worden door het kind. Het kind moet enkel kunnen spelen met speelgoed uit de bak dat het kind mee aan het spelen is. Pas als het kind het speelgoed dat in deze bak zat opruimt dan kan het kind met speelgoed uit een andere bak spelen.

### Interviews
Toen we ons product waren aan het ontleden hebben we onder vonden dat we niet echt wisten wat de belangrijkste functies van ons product zijn voor de ouders. Ons doel van deze interviews is om te weten te komen wat de ouders het belangrijkste vinden.
Daarnaast gaan we doormiddel van hun feedback de zaken die onnodig zijn eruit halen.
Ook zullen we vragen achter hun ervaring om te weten te komen welke opruim strategieën het best werken.

[interview protocol & report](https://ugentbe-my.sharepoint.com/:w:/r/personal/arthur_verhaeghe_ugent_be/Documents/J%202025-2026/project%20gebruiksgericht%20ontwerpen/develop1.docx?d=w6168b8493fe04b6f912cd4a38d781c14&csf=1&web=1&e=qze038)


#### value promise
Omdat ons product verschillende mogelijke value promises had, hebben we deze voorgelegd aan de doelgroep. De respondenten rangschikten de value promises van meest naar minst belangrijk. Dit gaf ons inzicht in welke aspecten zij het meest waardevol vonden. Deze resultaten gebruikten we vervolgens als basis om zelf een uiteindelijke rangschikking te bepalen en zo een duidelijke richting voor het product te kiezen. De value promises zijn als volgt geordend:

1) Een product dat tijd bespaart voor de ouder door het kind meer autonoom te doen opruimen
2) Een product dat ervoor zorgt dat er een maximum hoeveelheid rommel is door het kind maar met een beperkte hoeveelheid speelgoed te gelijkertijd te laten spelen
3) Een product dat tijd bespaart voor de ouder door het kind meer autonoom te doen opruimen
4) Rommel snel en eenvoudig doen verbergen 4)Een product dat ervoor zorgt dat het kind meer opruimd door opruimen leuker te maken
5) Een product dat een ouder meer controle geef wanneer en met welk speelgoed het kind speelt

### Morfologiesche matrix
Het concept dat we hebben gekozen om verder uit te werken is een liggende kast. Deze vorm maakt het voor kinderen gemakkelijker om bij de bakken te komen en verhoogt zo de toegankelijkheid van het speelgoed.
Voor het deksel werd gekozen voor een vouwdeksel. Dit type deksel neemt weinig ruimte in wanneer het geopend wordt en is eenvoudig te gebruiken door kinderen. Uit eerder onderzoek bleek dat dit een praktische en gebruiksvriendelijke oplossing is.
De bediening van het systeem gebeurt via een smartphone. Hierdoor zijn er geen extra bedieningselementen nodig en blijven de kosten beperkt.
Om het kind te ondersteunen bij het opruimen werd een klok toegevoegd die als timer of alarm kan worden ingesteld. Daarnaast geeft een speaker feedback wanneer het kind iets fout doet of niet goed begrijpt wat er moet gebeuren. De speaker kan ook een opruimlied afspelen om het zelfstandig opruimen te stimuleren.
Verder zijn er LED-indicatoren die aangeven of een bak correct gesloten is. Tot slot wordt een weegschaal gebruikt om te controleren of het speelgoed correct werd opgeruimd, wat een betrouwbare manier is om dit te controleren.
<p align="left">
<img width="755" height="701" alt="image" src="https://github.com/user-attachments/assets/0914f7c0-2a4a-4962-85f6-2512f44346c4" />
</p>

#### Nieuw concept
<p align="left">
<img width="581" height="438" alt="image" src="https://github.com/user-attachments/assets/9668eb27-896c-4032-8716-9c30683efd46" />
</p>
