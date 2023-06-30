# Meesterproef Strandeiland
[Team repo](https://github.com/RainbowJM/strandeiland) 

<img width="200" alt="" src="https://github.com/laibaaac/meesterproef-2223/assets/94360732/04c50d13-61b1-44f9-a76b-9f3d1d3cef71">

Voor het eindproject voor het minor web (MEESTERPROEF), gaan wij in groepjes aan de slag met een opdracht. 
We mochten zelf een opdracht uitkiezen en ons voorkeuren van groepjes. 
Uiteindelijk ben ik verdeeld onder het project Strandeiland, samen met mijn teamleden: Hilal Tapan, Keisha Alexander, Jevona Magdelena. 

De aankomende 5 weken gaan wij samen werken aan het project strandeiland. 

**Wat houdt het project in?**

De komende jaren ontstaat een compleet nieuwe wijk aan de oostkant van Amsterdam: Strandeiland. Ambities zijn hoog: de wijk moet energieleverend zijn, groener dan de eerste versie van IJburg, bewoners moeten plezierig met elkaar kunnen samenwonen en de kansengelijkheid moet verbeterd worden.
Het bedrijf CrossmarX wil een nieuwe functionaliteit toevoegen voor de hallostrandeiland.nl website waar IJburg bewoners nieuwe voorstellen kunnen insturen voor de nieuwe wijk van Strandeiland. Hiermee wordt de communicatie tussen toekomstige bewoners van Strandeiland en de projectleiders van de gemeente Amsterdam bevorderd. Het doel is om via Hallo Strandeiland goede ideeën en voorstellen te verzamelen, te verbeteren en de mooie en haalbare ideeën/voorstellen gerealiseerd te krijgen.

**User Stories**
Er worden ook een aantal user stories aan ons gegeven om rekening mee te houden tijdens dit projec:
1. Als toekomstig bewoner, wil ik mijn voorstel voor een duurzamer, groener en socialer strandeiland kunnen delen, zodat dit onderzocht en hopelijk gerealiseerd kan worden.

2. Als toekomstig bewoner, wil ik een reactie kunnen geven op voorstellen van andere toekomstige bewoners, zodat we kunnen samenwerken aan het vormgeven van de voorstellen.

3. Als projectmanager van de gemeente, wil ik voorstellen van toekomstige bewoners kunnen filteren op thema's, zodat ik per thema kan bekijken of er ideeën bijzitten die kunnen bijdragen aan een lagere ecologische footprint, of betere sociale cohesie van de wijk.


Dus aan ons de opdracht om de volgende functionaliteiten toe te voegen: 
- Wensen kunnen filtreren op populariteit
- Wensen kunnen filtreren van oud tot nieuw
- Wens kunnen filtreren op thema's
- Het formulier van de wens opslaan in localstorage
- Een real time chat, zodat de gebruikers tot elkaar kunnen praten


# Inhoudsopgave
- [Week 1](#week-1)
  * [Wat heb ik deze week gedaan](#wat-heb-ik-deze-week-gedaan)
  * [Scrum opzet](#scrum-opzet)
  * [Debriefing](#debriefing)
  * [Schetsen (formulier)](#schetsen--formulier-)
  * [Feedback Debriefing](#feedback-debriefing)
  * [Test met opdrachtgever](#test-met-opdrachtgever)
  * [Feedback van opdrachtgever / docent (code en design review) verwerken](#feedback-van-opdrachtgever---docent--code-en-design-review--verwerken)
  * [Reflectie](#reflectie)
- [Week 2](#week-2)
  * [Wat heb ik deze week gedaan](#wat-heb-ik-deze-week-gedaan-1)
  * [Thema’s opstellen](#thema-s-opstellen)
  * [Formulier afmaken](#formulier-afmaken)
  * [De bevestiging pagina](#de-bevestiging-pagina)
  * [Localstorage](#localstorage)
  * [Dropdown menu en afbeelding onderzoek](#dropdown-menu-en-afbeelding-onderzoek)
  * [Schetsen formulier](#schetsen-formulier)
  * [Bevestiging pagina maken](#bevestiging-pagina-maken)
  * [Img preview](#img-preview)
  * [Feedback van opdrachtgever / docent (code en design review) verwerken](#feedback-van-opdrachtgever---docent--code-en-design-review--verwerken-1)
  * [Reflectie](#reflectie-1)
- [Week 3](#week-3)
  * [Wat heb ik deze week gedaan](#wat-heb-ik-deze-week-gedaan-2)
  * [Img preview](#img-preview-1)
  * [Img link parsen](#img-link-parsen)
  * [Toggle toepassen](#toggle-toepassen)
  * [De design aanpassen](#de-design-aanpassen)
  * [Formulier post](#formulier-post)
  * [Afbeelding pop up](#afbeelding-pop-up)
  * [Micro interactie](#micro-interactie)
  * [Feedback van opdrachtgever / docent (code en design review) verwerken](#feedback-van-opdrachtgever---docent--code-en-design-review--verwerken-2)
  * [Reflectie](#reflectie-2)
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
- [Reflectie](#reflectie-3)
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
Voor het begin van meesterproef, werd er een kick-off gehouden. Daarin werd uitgelegd wat we de aankomende weken gaan doen, wat de opdrachten precies inhouden en hoe de beoordeling in elkaar zit. 
Na het verdeling van de groepen, is ons groep (Keisha, Jevona, Hilal en ik) wat dieper in de opdracht gaan duiken. We hadden vrijdag al een gesprek met ons opdrachtgever en we wouden voorbereid naar het gesprek. 

##  Scrum opzet
We zijn in teams verdeeld en wij hebben een team van 4. Samenwerking en het opzetten van het project kan moeilijk zijn. 
Hiervoor hebben wij gekozen om aan de scrum methode te houden. Dit houdt in elke dag een daily standup hebben, waar we kijken waar we zijn en wat we moeten doen, aan de hand daarvan stellen wij taken op voor de dag en gaan aan die werken. Zo kunnen we conflicten tussen de groep voorkomen en bevordert het ons samenwerking. 
Ik hou de scrum elke dag bij, ik ben dus de scrum master. 
Zie hier de scrum:
https://github.com/RainbowJM/strandeiland/wiki/Daily-Stand-ups--&-Retrospective 

## Vragen aan de opdrachtgever
Voor vrijdag hebben wij een paar vragen opgesteld die wij aan de opdrachtgever Michiel Vogler wouden vragen. 

1. Wat wil de opdrachtgever met deze opdracht?
2. Eigen repo op github of repo van het bedrijf zelf? (vanuit school moet github)
3. Prototype start from scratch?
4. Wat is de doelstelling?
5. Wat zijn de randvoorwaarden?
6. Heeft het project relatie met een andere project?
7. Voor desktop alleen? of desktop en mobile?
8. Hosten jullie het zelf?
9. Is er al een design? Is er een huisstijl? Is de huisstijl van de hello strandeiland?
10. Moet het een progressive web app worden? (zodat de app downloadbaar is)
11. Hoe moeten de voorstellen eruit komen te zien? Moet het een soort document worden of tekst met eventueel een afbeelding?
12. Hoe ziet u het onderdeel van de projectmanager voor zich? Bewoners en projectmanager een account of alleen projectmanager een account.
13. Zijn er specifieke thema’s, zoals lagere ecologische footprint en betere sociale cohesie van de wijk of moeten gebruikers deze zelf aan kunnen maken bij het voorstel?
14. Wanneer er meerdere voorstellen zijn geüpload, wilt u deze dan op een pagina zien waar u kunt filteren of onder verschillende tabbladen wilt met de verschillende thema’s?
15. In hoeverre verschilt dit project met hallostrandeiland.nl, aangezien je daar ook berichten hebt waar je een reactie bij kan plaatsen?Hebben jullie het logo en beeldmateriaal, zodat wij dit kunnen gebruiken?

## Mindmap
We hebben ook een mindmap gemaakt, met de informatie die bekend was hebben wij een uitgebreide mindmap kunnen maken
![mindmap](https://github.com/K3A101/meesterproef-2223/blob/main/images/Meesterproef-3.jpg)


## Debriefing 
We hadden naast het gesprek met de opdrachtgever ook een debriefing die wij moesten afmaken. De debriefing bestond uit een zo uitgebreid mogelijk project beschrijving. Hier is de debriefing te zien 
 https://github.com/RainbowJM/strandeiland/wiki/Debriefing

## Ideegeneratie
Na de briefing begonnen we met brainstormen, we moesten al bedenken wat we precies willen uitwerken en hoe precies we dit kunnen behalen. Hiervoor hebben we miro gebruikt omdat we hier gezamelijk in kunnen werken.

## Moscow Methode
![Moscow](https://github.com/K3A101/meesterproef-2223/blob/main/images/brainstorming.png)
Om de moscow methode toe te passen, hadden we een beter overzicht en konden we beter prioriteiten stellen

## Requirement list
- Er is een overzichtpagina waar gebruiker een overzicht van alle wensen kan zien.
- Gebruikers kan filteren op basis van populariteit, recentheid en thema's.
- Gebruikers moeten zelf een voorstel kunnen aanmaken met behulp van een wens aanmaak formulier.
- Localstorage toepassen op het formulier
- Een real time chat waar gebruikers berichten kunnen sturen 


## Visuele analyse
Vanuit Michel hebben we een brandbook gekregen die de gemeente van Amsterdam heeft ontworpen voor de website van strandeiland. Keisha heeft dit brandbook vertaald naar visuele elementen, gebasseerd op de visuele elementen hebben wij per pagina verschillende schetsen kunnen maken. 

## Schetsen formulier pagina
foto hiero 

Hier is de eerste versie van het formulier te zien, de gebruiker kan de titel van de wens meegeven, de beschrijving en ook de thema's. Om de thema's te kiezen, kunne wij makkelijker filteren. 

## Feedback Michel 
- We kunnen het thema bepalen met sustainability development goals of Donut economics
- Kan wel van de huisstijl afwjken, moet wel strandeland gevoel uiten
- meerdere thema's kunnen selecteren in het formulier
- thema's moeten goed bekeken worden, strandeiland bestaat nog niet, dus speeltuin etc gaat niet handig zijn
- alle dingen die fout gaan op dit moment, die kun je vooraf voorkomen, zulke wensen wilt hij zien

## Design iteratie
Op basis van de feedback, die we tijdens het gesprek kregen, hebben wij de design kunnen maken.
Zie hieronder 

foto hiero 

## Code
De eerste week was meer het opbouwen van de code, ik heb verschillende packages gedownload, gekeken hoe ik de elementen van het formulier het beste in html, css en javascript kan verwerken.

Hier kan je een lege opzet van css zien

```css
*,
*::before,
*::after {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
:root {
}

body{
}

header{
}

h1, h2, a{
}

footer{

}

```


## Reflectie 
De afgelopen week hadden wij onze eerste sprint, Wij hebben allemaal onze taken kunnen afmaken, hierdoor konden wij onze meest recentelijke werk aan onze opdrachtgever laten zien en bij behorende feedback krijgen. 
Qua samenwerking gaat het wel goed, we proberen zo goed mogelijk te communiceren en tijdens takenverdeling, geeft iedereen zelf aan wat ze willen doen. 
In het begin van de sprint was het nog allemaal onduidelijk, we begonnen dinsdag en we hadden letterlijk vrijdag al iets nodig om aan de opdrachtgever te laten zien. 
Door strak te plannen hebben wij best veel kunnen doen. Wat ik anders misschien had gedaan is taken beter plannen en ze ook in figma ze uit te werken, dit maakt coderen wat makkelijker.



# Week 2
W hebben een aantal taken vorige week af kunnen maken, maar deze week moeten wij weer aan de bak. W
e zijn de dag begonnen om alvast te kijken naar de verschillende thema’s die wij bij de wensen pagina kunnen hebben. 
Na het samen bepalen van de thema’s, hebben wij gekeken naar de feedback van de opdrachtgever en wat we verder nog moeten uitwerken. Dit hebben wij verdeeld onder de taken. 

## Thema’s opstellen
opgestelde thema's 

## De bevestiging pagina

## Localstorage 

## Dropdown menu en afbeelding onderzoek

## Schetsen formulier


## Bevestiging pagina maken


## Img preview


## Feedback van opdrachtgever / docent (code en design review) verwerken

## Reflectie 
Deze week zijn we bezig geweest met de design verder uit te werken en de functionaliteiten uit te werken. Voor mijn gevoel ging het best goed, maar ik kreeg een aantal errors net als de thema’s kon ik niet goed stylen, hier aan had ik te veel tijd aan besteed. Uiteindelijk heeft Keisha mij enorm geholpen met de thema, verder heb ik ook de localstorage erin verwerkt.
Verder hebben wij constant de feedback van onze docenten ook erin verwerkt, wij hopen dat wij een fantastisch prototype kunnen opleveren!!!



# Week 3


Ik heb de volgende taken deze week gedaan
## Img preview 
## Img link parsen 
## Toggle toepassen 
## De design aanpassen 
## Formulier post 
## Afbeelding pop up
## Micro interactie 

## Feedback van opdrachtgever / docent (code en design review) verwerken

## Reflectie 
Deze week was onze 3e week, we zijn langzamerhand aan het voorbereiden voor het leveren van het product, deze week wouden wij de designimplementatie afronden en hierna focussen op het fine tunen van het eind product, maar na de feedback van de opdrachtgever en de docenten hebben wij besloten om wat nog meer tijd aan design te besteden. We hebben wel de database geïmplementeerd en proberen ons voor te bereiden voor het eind sprint. 
Wat we deze week anders konden aanpakken is misschien de tijd beter kunnen inschatten, we hadden eerlijk gezegd niet verwacht dat we feedback zouden krijgen over ons design vanuit onze docent, die vond dat we wat meer konden experimenteren. Hierop moeten wij natuurlijk weer wat tijd er aan besteden. Hiermee moesten wij rekening mee houden. Nu dat we hiervan weten, gaan wij zeker de aankomende weken wat tijd vrij maken om de feedback te kunnen toepassen. 




# Week 4
## Wat heb ik deze week gedaan
Deze week begint de ena laatste sprint (oftewel de laatste volledige sprint), Ik zeker veel te doen, naast mijn taken kregen wij constant feedback van zowel onze docenten als onze docenten. 

Verder is dit ook de laatste week waar we feedback kunnen krijgen van de project begeleider, Ik wil voor vrijdag al een compleet prototype hebben en als ik feedback krijg kan ik die volgende week toepassen. 

Ik heb deze week de volgende taken afgerond. 

## Pop up
Ik was al bezig met het maken van de pop up vorig week, alleen ging het niet zo makkelijk. Ik gebruikte een div als een pop up, die zou ik stylen via css en togglen via javascript. Alleen via javascript ging het met togglen niet goed. 
Zie hieronder de code. 

```html
                <div id="popup" class="hidden">
    
                
        
                    <div id="links">
                        <label for="links">Websites waar je rechtvrije afbeelding kan vinden</label>
       
                        <div class='linkjes'>
                            <a href="https://unsplash.com/">Unsplash</a>
                            <a href="https://www.pexels.com/nl-nl/">Pexels</a>
                            <a href="https://pixabay.com/nl/">Pixabay</a>
                        </div>
                      
        
                        <p class="hierarchy">Link</p>
                    
           
                        <input type="text" name="imageLink" id="imageLink" placeholder="Plaats hier uw link">
                        
                        <div id="imagePreview"></div>
                    
        
                        <label for="or">Of</label>
                 
        
                        <p class="hierarchy">Bestand</p>
                   
        

                        <div class="file-input-container">
                            <img src="/images/wolkje.png" alt="een wolkje dat staat voor uploaden van een afbeelding">
                            <p>Selecteer een bestand</p>
                            <input type="file" id="file" name="file" accept="image/jpeg, image/png, image/jpg">
                     
                        </div>
                        <div id="customImagePreview"></div>
                    
                        <p id="selectedFileName">Geen bestand geselecteerd</p>
            
                        <div id="closeButton" class="hidden">&#10006;</div>
                     
                    </div>
                </div>

```



Tijdens de design review kreeg ik de feedback van Vasilis dat ik ipv een div, beter dialog kan gebruiken. 
Een HTML-dialog is een ingebouwd element in HTML5 waarmee je modale dialoogvensters kunt maken, zoals bevestigingsvensters of formulieren, zonder extra JavaScript-code te schrijven.

Ik vond de dialog tag makkelijker toe te passen en ben er meteen aan de slag gegaan. 

Zie hier de code. 

```html
                <dialog class="no-js">   
                <div id="links">
                    <label for="links">Websites waar je rechtvrije afbeelding kan vinden</label>
                    <div class='linkjes'>
                        <a href="https://unsplash.com/">Unsplash</a>
                        <a href="https://www.pexels.com/nl-nl/">Pexels</a>
                        <a href="https://pixabay.com/nl/">Pixabay</a>
                    </div>
                    <p class="hierarchy">Link</p>
                    <input type="text" name="imageLink" id="imageLink" placeholder="Plaats hier uw link">
                    <div id="imagePreview"></div>
                    <label for="or">Of</label>
                    <p class="hierarchy">Bestand</p>
                    <div class="file-input-container">
                        <img src="/images/wolkje.png" alt="een wolkje dat staat voor uploaden van een afbeelding">
                        <p>Selecteer een bestand</p>
                        <input type="file" id="file" name="file" accept="image/jpeg, image/png, image/jpg">
                    </div>
                    <div id="customImagePreview"></div>
                    <p id="selectedFileName">Geen bestand geselecteerd</p>
                    <div id="closeButton" class="hidden">&#10006;</div>

                    <button id="closeDialog">sluiten</button>
                </div>

```


## Form validatie 
Het valideren van een formulier hebben wij tijdens het vak browser technologies geleerd. 
Je hebt dan 3 lagen van validation, html, css en javascript. 

Bij html ziet de validation zo er uit

```html 
<input type="text" id="title" name="title" placeholder="Geef je wens een titel" minlength="2" maxlength="40" required>
```


Bij css ziet de validation er zo uit

```css
textarea:required:invalid {
  border: 2px solid red;
}

textarea:required:valid {
  border: 2px solid green;
}
```

Bij javascript ziet de validation er zo uit

```javascript
if (titleInput) {
  titleInput.addEventListener('input', function() {
    if (titleInput.value.trim() === '') {
      titleInput.setCustomValidity('Please enter a title');
    } else {
      titleInput.setCustomValidity('');
    }
  });
}
```

## Javascript errors 
Tijdens het mergen van de code, kwamen we steeds veel errors tegen. Er kwamen steeds variable undefined, niet goed geplaatst, etc. Localstorage heeft een bug en nog veel meer. Omdat we in modules werken, kan het soms tricky zijn om code op te halen en die dan in de main.js terug te halen. Gelukkig hadden wij de tijd genomen tijdens de refator om de errors te kunnen fixen. 

Jevona was in controle van version control, zij was ons github master. Als je een error had, kon je het zelf oplossen, of ging Jevona soms samen zitten om eraan te werken. 




## Form data versturen naar database
Wij gebruiken de database, supabase. Ik heb geen ervaring van supabase, dus moest ik en ook de andere gewend aan raken. 
Aan mij was de opdracht gegeven, van het posten van het formulier data naar de database en die dan terug te halen vanuit de database naar de index.ejs

Hier laat ik even mijn code van versturen van de data naar de database 

```javascript

router.post("/form", async (req, res) => {
  try {
    const { data, error } = await supabase
      .from("suggestion")
      .insert([
        {
          title: req.body.title,
          description: req.body.description,
          image: req.body.imageLink,
        },
      ])
      .select();

    const insertId = data.length > 0 ? data[0].id : null;
    if (error || !insertId) {
      throw error;
    }

    console.log([parseInt(req.body.theme)])
    const themes = req.body.theme;

    const themeInsertPromises = themes.map(async (theme) => {
      const { data: themeData, error: themeError } = await supabase
        .from("theme")
        .select("id")
        .eq("id", theme)
        .single();
      if (themeError) {
        throw themeError;
      }

      const { error: suggestionThemeError } = await supabase
        .from("suggestion_theme")
        .insert([
          {
            suggestionId: insertId,
            themaId: themeData.id,
          },
        ]);
      if (suggestionThemeError) {
        throw suggestionThemeError;
      }
    });

    await Promise.all(themeInsertPromises);
    res.render("sent", {
      title: "sent",
    });
  } catch (error) {
    res
      .status(500)
      .json({ error: "Het toevoegen van de wens ging fout, probeer opnieuw" });
    console.log(error);
    return;
  }
});
```

## Design afronden
Tijdens het heen en weer testen, kwam ik een paar punten tegen die ik wou toepassen in mijn productbio net als:
- Ronde hoeken, geen scherpe hoeken
- Kleuren van de buttons moeten anders, geen boxshadow 
- Extra validatie bij het selecteren van de thema's 
- De pop-up verder stylen, wat groter en de content erin ook 

Zie hier de verbeterde versie 
![5dc2a675-4415-4bd9-adf5-a41567a9fdae](https://github.com/RainbowJM/strandeiland/assets/94360732/314a65f4-4f1f-42b3-a61d-482d599753d3)

<img width="1300" alt="Schermafbeelding 2023-06-28 om 15 17 47" src="https://github.com/RainbowJM/strandeiland/assets/94360732/a1b6dfe5-5358-482c-a2a6-27a6270c1096">





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

## Reflectie
Deze week lag de stress hoog, we moesten ervoor zorgen dat alles af was voor volgende week, zodat we kunnen focussen op het schoonmaken van de code, de code te mergen om een stabiele versie van de code te hebben in onze main branch. Ik heb deze week geprobeerd om zo ver mogelijk te werken en mijn pagina keer op keer te testen om tot volgende week de errors te kunnen oplossen. Volgende week hebben wij een drukke sprint, dus wou ik deze week zoveel mogelijk doen, om mijzelf niet meer zo druk te maken. 
Ik heb deze week wel nog veel taken kunnen afmaken gelukkig, ik vind hoe het formulier eruit ziet, een compleet mooi formulier.



# Week 5





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
- NPM: multer 
https://www.npmjs.com/package/multer



- Developer.mozilla: <dialog>: The Dialog element
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog?retiredLocale=nl



- Developer.mozilla: Local storage
https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage 



- Supabase Javascript Client - Insert data.
https://supabase.com/docs/reference/javascript/insert


- GeeksforGeeks. (2023). How to add an object to an array in JavaScript. GeeksforGeeks.
https://www.geeksforgeeks.org/how-to-add-an-object-to-an-array-in-javascript/ 


- (2023, 2 februari). Building a CRUD App with Supabase and Express: A Step-by-Step Guide for Junior Developers. Medium.
https://medium.com/@heshramsis/building-a-crud-app-with-supabase-and-express-a-step-by-step-guide-for-junior-developers-81456b850910 


- How make to make dropdown without html select.  Stack Overflow. 
https://stackoverflow.com/questions/43362588/how-make-to-make-dropdown-without-html-select


- How to use Checkbox inside Select Option. Stack Overflow. 
https://stackoverflow.com/questions/17714705/how-to-use-checkbox-inside-select-option 

- Babich, N. (2022, 11 oktober). Radio buttons, checkboxes, toggle switches, and dropdown lists: design tips for using selection controls.
https://uxplanet.org/radio-buttons-checkboxes-toggle-switches-and-dropdown-lists-design-tips-for-using-selection-d120a1e323c5


- Pure CSS Custom Checkbox Style | Modern CSS Solutions.
https://moderncss.dev/pure-css-custom-checkbox-style/ 


- Client-side form validation - Learn web development | MDN. (2023, 2 juni)
https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation

- Coyier, C. (2021, 16 september). Form Validation UX in HTML and CSS | CSS-Tricks.
https://css-tricks.com/form-validation-ux-html-css/ 

- Alligator.Io. (2020). Styling Form Inputs in CSS With :required, :optional, :valid and :invalid. DigitalOcean.
https://www.digitalocean.com/community/tutorials/css-styling-form-input-validity 




