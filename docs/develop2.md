## Develop 2

In deze fase verschuift de focus van de technische werking ("hoe het werkt") naar de gebruikerservaring ("hoe de mens het ervaart"). Omdat er voorheen een heldere value promise ontbrak, dreigde het product te complex te worden. In deze fase elimineren we overbodigheden en werken we toe naar frictieloze usability en een testbaar prototype.

## Gebruikersonderzoek en Usability Goals

We ontleden het huidige product via storyboards en user-flows. Via interviews toetsen we bij de doelgroep wat de échte value promise van PlayClean is. Met deze inzichten schrappen we onnodige functies en definiëren we meetbare usability goals die bepalen wat "gebruiksvriendelijkheid" voor ons product inhoudt.

Kort samengevat eisen deze doelen een veilige, fysiek toegankelijke kast die kinderen volledig intuïtief (zonder uitleg) kunnen bedienen, ondersteund door heldere feedback om zelfstandig opruimen spelenderwijs te stimuleren. De specifieke goals staan in [Design Requirements](design_requirements.md).

## Cognitieve & sensoriële ergonomie: Theoretische onderbouwing (The body & the senses)

Met de verzamelde data stellen we een morfologische matrix op om verschillende concepten te ontwikkelen:

<p align="center">
<img width="455" height="326" alt="image" src="https://github.com/user-attachments/assets/2bbf98f3-db05-4610-a4b9-6b795cc9fa41" />
</p>

Om te voorkomen dat jonge kinderen en vermoeide ouders onnodige cognitieve inspanning moeten leveren, is de interface — op basis van de geselecteerde opties uit de morfologische matrix — ontworpen om "in één oogopslag" begrepen te worden. Digitale displays die interpretatie vereisen (zoals cijferpercentages) en complexe kleurpatronen zijn bewust vermeden ten voordele van directe mapping en bekende mentale modellen.

## De Thermometer

De positionering van de LED-strip is verticaal langs de bak gekozen (of als alternatief horizontaal als dit de 'opvulling' beter weergeeft). Mensen associëren "hoogte" of "lengte" van een balk automatisch met "hoeveelheid". Als de bak voller raakt, stijgen de lichtjes mee omhoog. Dit vereist geen leercurve.

<p align="center">
<img width="46" height="487" alt="image" src="https://github.com/user-attachments/assets/ea6e3c96-1db0-4e99-b8fa-4618d4cece20" />
</p>

## Schaalverdeling als context

Subtiele markeringen bij 0%, 50% en 100% bieden de gebruiker context over de capaciteit, zonder de visuele rust te verstoren met getallen.

<p align="center">
<img width="140" height="509" alt="image" src="https://github.com/user-attachments/assets/8d0419a3-6fb0-4dfc-b4ba-f1e2ff6a9d54" />
</p>

## Duidelijke Signifiers en Feedback (7 Stages of Action)

In het kader van Norman's 7 Stages of Action moet de gebruiker direct de status van het systeem kunnen waarnemen (perceive) en evalueren (evaluate) om te weten of het doel (de bak opruimen) is bereikt.

<p align="center">
<img width="250" height="1000" alt="image" src="https://github.com/user-attachments/assets/d4b25ed7-a6fa-432c-95b8-d27afd9a3259" />
</p>

## Visuele Signifiers

Er is gekozen voor een consistente, logische kleurcodering:
- Leeg: neutrale kleur (grijs of dof rood)
- Deels vol: oranje
- Vol: groen

<p align="center">
<img width="736" height="226" alt="image" src="https://github.com/user-attachments/assets/cbe19662-5222-4a76-887c-c881d429fec9" />
</p>

Zodra de bak voor 100% is opgeruimd, geeft het systeem een extra fysieke of auditieve 'beloning'. De LEDs geven een korte puls of spelen een animatie af en er kan een auditieve melding worden afgespeeld. Dit is cruciale feedback die de actie van het kind positief afsluit.

## Antropometrische analyse 

We optimaliseren de fysieke vormfactor. Afmetingen en reikwijdtes worden afgestemd op de uiterste percentielen van de doelgroep (design for the extremes: the tall and the small). Dit bouwt voort op onderzoek uit de [definition-fase](definition.md) en wordt hier verder verfijnd.

Voor het garanderen van een comfortabele fysieke interactie met de PlayClean opruimkast, is een antropometrische analyse uitgevoerd gericht op de armafmetingen van de doelgroep (kinderen van 8 tot 11 jaar). De data hiervoor is ontleend aan [The Measure of Man and Woman](https://arc104201516.wordpress.com/wp-content/uploads/2016/02/the-measure-of-man-and-woman-human-factors-in-design-alvin-r-tilley-henry-dreyfuss.pdf).

Om ervoor te zorgen dat de kast voor de gehele doelgroep bruikbaar is, is de ontwerpstrategie design for the tall and the small toegepast. Hierbij wordt de interactie van twee uitersten vergeleken: een kind van 8 jaar (kleinste percentiel) en een kind van 11/12 jaar (grootste percentiel), in relatie tot de afmetingen van de speelgoedbak (gebaseerd op de standaard IKEA Trofast afmetingen).

<p align="center">
<img width="443" height="483" alt="image" src="https://github.com/user-attachments/assets/93aec24d-e1bf-4150-bc56-c90d87b461fc" />
</p>

## Relevante lichaamsafmetingen 

Om speelgoed uit een bak te pakken of erin te leggen, zijn de lengte van de onderarm en de hand de meest kritieke maten.

**Kleinste afmetingen (8 jaar):**
- Onderarm: 17.3 cm  
- Hand: 13.7 cm  
- Totale reiklengte: 31 cm  

**Grootste afmetingen (11 jaar):**
- Onderarm: 21 cm  
- Hand: 15.6 cm  
- Totale reiklengte: 36.6 cm  

## Productafmetingen (De speelgoedbak)

- Diepte: 28 cm  
- Lengte: 30 cm  
- Breedte: 20 cm  

<p align="center">
<img width="333" height="191" alt="image" src="https://github.com/user-attachments/assets/a9296dea-6321-4843-a125-98309c5ecd4a" />
</p>

## Ergonomische evaluatie en comfort

**Verticale reikwijdte:**  
De bak is 28 cm diep. Omdat de kortste reiklengte 31 cm is, kan zelfs de kleinste gebruiker de bodem bereiken (31 > 28 cm). Dit voorkomt oncomfortabel leunen.

**Horizontale reikwijdte:**  
De opening van 30 × 20 cm is volledig bereikbaar voor beide uitersten van de doelgroep.

**Vrije bewegingsruimte (clearance):**  
Voor oudere kinderen met langere armen en grotere handen is er voldoende ruimte om vrij te bewegen zonder contact met de randen.

<p align="center">
<img width="665" height="610" alt="image" src="https://github.com/user-attachments/assets/33bcebe0-dd9d-49ce-ab3f-76cd5afae568" />
</p>


