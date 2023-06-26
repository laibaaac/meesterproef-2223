# Meesterproef Strandeiland

<img width="500" alt="" src="https://github.com/laibaaac/meesterproef-2223/assets/94360732/04c50d13-61b1-44f9-a76b-9f3d1d3cef71">

Voor het eindproject voor het minor web (MEESTERPROEF), gaan wij in groepjes aan de slag met een opdracht. 
We mochten zelf een opdracht uitkiezen en ons voorkeuren van groepjes. 
Uiteindelijk ben ik verdeeld onder het project Strandeiland, samen met mijn teamleden: Hilal Tapan, Keisha Alexander, Jevona Magdelena. 

De aankomende 5 weken gaan wij samen werken aan het project strandeiland. 

**Wat houdt het project in?**

De komende jaren ontstaat een compleet nieuwe wijk aan de oostkant van Amsterdam: Strandeiland. Ambities zijn hoog: de wijk moet energieleverend zijn, groener dan de eerste versie van IJburg, bewoners moeten plezierig met elkaar kunnen samenwonen en de kansengelijkheid moet verbeterd worden.
Het bedrijf CrossmarX wil een nieuwe functionaliteit toevoegen voor de hallostrandeiland.nl website waar IJburg bewoners nieuwe voorstellen kunnen insturen voor de nieuwe wijk van Strandeiland. Hiermee wordt de communicatie tussen toekomstige bewoners van Strandeiland en de projectleiders van de gemeente Amsterdam bevorderd. Het doel is om via Hallo Strandeiland goede ideeën en voorstellen te verzamelen, te verbeteren en de mooie en haalbare ideeën/voorstellen gerealiseerd te krijgen.


Dus aan ons de opdracht om de volgende functionaliteiten toe te voegen: 
- Wensen kunnen filtreren op populariteit
- Wensen kunnen filtreren van oud tot nieuw
- Wens kunnen filtreren op thema's
- Het formulier van de wens opslaan in localstorage
- Een real time chat, zodat de gebruikers tot elkaar kunnen praten


# Inhoudsopgave
- [Week 1](#week-1)
  * [Wat heb ik deze week gedaan](#wat-heb-ik-deze-week-gedaan)
- [Week 2](#week-2)
  * [Wat heb ik deze week gedaan](#wat-heb-ik-deze-week-gedaan-1)
- [Week 3](#week-3)
  * [Wat heb ik deze week gedaan](#wat-heb-ik-deze-week-gedaan-2)
- [Week 4](#week-4)
  * [Wat heb ik deze week gedaan](#wat-heb-ik-deze-week-gedaan-3)
  * [Pop up](#pop-up)
  * [Form validatie](#form-validatie)
  * [Javascript errors](#javascript-errors)
  * [Form data versturen naar database](#form-data-versturen-naar-database)
  * [Design afronden](#design-afronden)
  * [Multer](#multer)
- [Week 5](#week-5)
  * [Wat heb ik deze week gedaan](#wat-heb-ik-deze-week-gedaan-4)
- [Reflectie](#reflectie)
  * [Wat heb ik geleerd?](#wat-heb-ik-geleerd-)
  * [Wat ging er goed?](#wat-ging-er-goed-)
  * [Wat ging er minder goed?](#wat-ging-er-minder-goed-)
  * [Waar ben ik trots op](#waar-ben-ik-trots-op)
- [Toepassing meesterproef Vakken](#toepassing-meesterproef-vakken)
  * [Browser Tech](#browser-tech)
  * [CSS to the rescue](#css-to-the-rescue)
  * [Web app from scratch](#web-app-from-scratch)
  * [Progressive web app](#progressive-web-app)
- [Bronnen](#bronnen)


# Week 1
## Wat heb ik deze week gedaan


# Week 2
## Wat heb ik deze week gedaan


# Week 3
## Wat heb ik deze week gedaan


# Week 4
## Wat heb ik deze week gedaan
Deze week begint de ena laatste sprint (oftewel de laatste volledige sprint), Ik zeker veel te doen, naast mijn taken kregen wij constant feedback van zowel onze docenten als onze docenten. 

Verder is dit ook de laatste week waar we feedback kunnen krijgen van de project begeleider, Ik wil voor vrijdag al een compleet prototype hebben en als ik feedback krijg kan ik die volgende week toepassen. 

Ik heb deze week verschillende taken afgerond, zoals:
- Pop up, voor de optie afbeelding uploaden 
- Begin form validatie (html, css en javascript)
- javascript errors oplossen
- Data uit form versturen 
- Design afronden 

Ik ga nu per taak verder uitleggen, wat ik heb gedaan. 

## Pop up


## Form validatie 


## Javascript errors 

## Form data versturen naar database


## Design afronden







## Multer 
**Wat is multer?**
Multer is een middleware voor het verwerken van multipart/form-data in Node.js en Express.js. Het wordt vaak gebruikt in combinatie met webapplicaties die bestandsuploads ondersteunen. Multer maakt het gemakkelijk om bestanden te ontvangen via HTTP-verzoeken en ze op te slaan op de server.

Multer biedt functionaliteit voor het verwerken van meerdere bestanden, het beperken van bestandstypen en het instellen van maximale bestandsgroottes. Het is ook mogelijk om aangepaste bestandsopslaglocaties en bestandsnamen te definiëren. Multer maakt gebruik van het concept van "middleware" in Express.js, waardoor het eenvoudig kan worden geïntegreerd in bestaande Express.js-applicaties.

**Waarom multer eigenlijk?**
Deze week was ik bezig met het versturen van de data vanuit het formulier. Wij hebben een aantal informatie die wij uit het formulier willen uit halen, dat zijn titel, beschrijving, thema's, afbeelding link of afbeelding bestand. Het versturen van bijna alles ging goed behalve afbeelding bestand, wij kwamen er achter, dat het versturen van het bestand naar supabase (database), niet zo makkelijk is. 
Tijdens de code review met Justus, werd er aangeraden om multer te gebruiken om de images toch naar de database te versturen. 
Hij raadde het aan om dit tutorial te volgen. 
https://medium.com/geekculture/nodejs-image-upload-with-multer-e6cf08c1562f


**Hoe verder?**
Ik was deze hele week wel bezig met het versturen van de data vanuit het formulier, het ging niet zo makkelijk.
Ik was hier ontzettend lang mee bezig, hierdoor ben ik jammer genoeg niet aan toe gekomen om multer toe te passen. Volgende week heb ik ook geen mogelijkheid om Multer toe te passen, want wij gaan langzamerhand onze project afronden en de deadline is al donderdag. 
Verder is het selecteren van het bestand toch niet zo populair als het img link toevoegen. 
Strandeiland bestaat nog niet, dus de gebruikers hebben geen foto's om te uploaden vanuit hun bestanden, ze gebruiken sneller stock foto's vanuit de genoemde website's (in het formulier)

Wij hebben alleen voor de zekerheid de mogelijkheid om een bestand toe te voegen gelaten, dit kan handig zijn in de toekomst en dan kan ik ook eindelijk multer toe voegen om toch de bestanden te kunnen door sturen naar de database. 








# Week 5
## Wat heb ik deze week gedaan




# Reflectie
## Wat heb ik geleerd?
## Wat ging er goed?
## Wat ging er minder goed?
## Waar ben ik trots op



# Toepassing meesterproef Vakken
## Browser Tech
## CSS to the rescue 
## Web app from scratch 
## Progressive web app



# Bronnen
- https://www.npmjs.com/package/multer 



