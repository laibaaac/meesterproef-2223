# Meesterproef Strandeiland
[Team repo](https://github.com/RainbowJM/strandeiland) 

<img width=200 alt= src=https://github.com/laibaaac/meesterproef-2223/assets/94360732/04c50d13-61b1-44f9-a76b-9f3d1d3cef71>

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
  * [Scrum opzet](#scrum-opzet)
  * [Vragen aan de opdrachtgever](#vragen-aan-de-opdrachtgever)
  * [Mindmap](#mindmap)
  * [Debriefing](#debriefing)
  * [Ideegeneratie](#ideegeneratie)
  * [Moscow Methode](#moscow-methode)
  * [Requirement list](#requirement-list)
  * [Visuele analyse](#visuele-analyse)
  * [Schetsen formulier pagina](#schetsen-formulier-pagina)
  * [Feedback Michel](#feedback-michel)
  * [Design iteratie](#design-iteratie)
  * [Code](#code)
  * [Reflectie](#reflectie)
- [Week 2](#week-2)
  * [Thema’s opstellen](#thema-s-opstellen)
  * [De bevestiging pagina](#de-bevestiging-pagina)
  * [Localstorage](#localstorage)
  * [Dropdown menu en afbeelding onderzoek](#dropdown-menu-en-afbeelding-onderzoek)
  * [Schetsen formulier](#schetsen-formulier)
  * [Bevestiging pagina maken](#bevestiging-pagina-maken)
  * [Img preview](#img-preview)
  * [Feedback van opdrachtgever / docent (code en design review) verwerken](#feedback-van-opdrachtgever---docent--code-en-design-review--verwerken)
  * [Reflectie](#reflectie-1)
- [Week 3](#week-3)
  * [Img preview](#img-preview-1)
  * [Img link parsen](#img-link-parsen)
  * [Toggle toepassen](#toggle-toepassen)
  * [De design aanpassen](#de-design-aanpassen)
  * [Formulier post](#formulier-post)
  * [Afbeelding pop up](#afbeelding-pop-up)
  * [Feedback van opdrachtgever / docent (code en design review) verwerken](#feedback-van-opdrachtgever---docent--code-en-design-review--verwerken-1)
  * [Reflectie](#reflectie-2)
- [Week 4](#week-4)
  * [Wat heb ik deze week gedaan](#wat-heb-ik-deze-week-gedaan)
  * [Pop up](#pop-up)
  * [Form validatie](#form-validatie)
  * [Javascript errors](#javascript-errors)
  * [Form data versturen naar database](#form-data-versturen-naar-database)
  * [Design afronden](#design-afronden)
    * [Feedback van opdrachtgever / docent (code en design review) verwerken](#feedback-van-opdrachtgever---docent--code-en-design-review--verwerken-2)
  * [Multer](#multer)
  * [Reflectie](#reflectie-3)
- [Week 5](#week-5)
  * [Documentatie](#documentatie)
  * [Testen  (lighthouse)](#testen---lighthouse-)
  * [Code refactor](#code-refactor)
  * [Localstorage](#localstorage-1)
  * [Reflectie](#reflectie-4)
- [Reflectie](#reflectie-5)
  * [Wat heb ik geleerd?](#wat-heb-ik-geleerd-)
  * [Wat ging er goed?](#wat-ging-er-goed-)
  * [Wat ging er minder goed?](#wat-ging-er-minder-goed-)
  * [Waar ben ik trots op](#waar-ben-ik-trots-op)
- [Toepassing meesterproef Vakken](#toepassing-meesterproef-vakken)
  * [Browser Technologies](#browser-technologies)
  * [CSS to the rescue](#css-to-the-rescue)
  * [Web app from scratch](#web-app-from-scratch)
  * [Progressive web app](#progressive-web-app)
  * [Human Centered Design](#human-centered-design)
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
*::after
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
:root
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
We hebben een aantal taken vorige week af kunnen maken, maar deze week moesten wij weer aan de bak. 
We waren begonnen om alvast te kijken naar de verschillende thema’s die wij bij de wensen pagina kunnen hebben. 
Na het samen bepalen van de thema’s, hebben wij gekeken naar de feedback van de opdrachtgever en wat we verder nog moeten uitwerken. 
De volgende taken had ik deze week afgerond. 

## Thema’s opstellen
Vooraf had ik al naar de website van hallo ijburg gekeken en een paar thema's opgesteld. Ik zag dat er veel voorkomende thema's waren, maar anders verwoord. Hierdoor heb ik een lijst opgesteld. Daarna hebben we even besproken welke thema's wel en niet relevant waren. 
De opgestelde thema's die wij samen hebben besloten zijn: 

1 = Recreatie
2 = Infrastructuur
3 = Sport
4 = Natuur
5 = Winkel
6 = Milieu
7 = Jeugd
8 = Cultuur
9 = Huisvesting
10 = Veiligheid
11 = Verkeer
12 = Strand
13 = Onderwijs
14 = Overig

## De bevestiging pagina
De sent.ejs pagina, is bedoeld wanneer de data wordt verzonden vanuit het formulier naar de database, dan zie je dit pagina. 

Ik render de pagina al in routing, wanneer alles goed gaat, dan zie je deze pagina. zo niet krijg je een error te zien. 

```javascript
  res.render("sent", { title: "sent" });
 
```

**Design**
De styling zelf lijkt op de banner op de index pagina. Alleen qua grootte is het anders en ook de tekst. We wouden dit weer teurg laten komen en het zag er ook leuk uit om het als een bevestigingspagina te krijgen  

foto hiero 


**Animatie**
Ik heb zelf ook animatie op de 1e vakje en 3e vakje gezet. 
De opdrachtgever geloofde niet dat het een css animatie is, hij dacht dat het een javascript code was.  

```css
@keyframes slogan-1{
  0% {transform: translateY(0);}
  100% {transform: translateY(-1rem);}
}

@keyframes slogan-2 {
  0% {transform: rotate(0);}100% {transform: rotate(-8deg);}
}

```


## Localstorage 
Wat als de gebruiker aan het typen was en perongeluk refreshed. Dan moet de gebruiker weer alles opnieuw invullen. 

Hiervoor heb ik als progressive enhancement het opslaan van data in localstorage opgeslagen, daarvoor is de fallback als de gebruiker localstorage heeft, dan wordt de data opgeslagen, zo niet dan kan de gebruiker niet de data opslaan in localstorage, maar wel nog sturen naar de database (supabase).


```javascript
// Function to update form data
function updateFormData() {
  // ...

  const formData = {
    title: document.getElementById("title").value,
    description: document.getElementById("description").value,
    themas: selectedThemes
  };

  // Save form data to localStorage
  localStorage.setItem(localStorageKey, JSON.stringify(formData));
}


```

## Dropdown menu 
Het maken van de dropdown menu doe je normaal met de select tag, alleen is die heel slecht om te stijlen. Wij willen een hele mooie dropdown menu, die je makkelijk kan stijlen en ook kan togglen. 

Ik ging onderzoeken naar verschillende opties van een dropdown menu, ik kwam toen op dit.

```html
  <fieldset class="dropdown">
                    <div class="selected-option" id="selectedOption" tabindex="0">Selecteer de passende thema's
                    </div>
                    <p class="valid">Kies maximaal uit 4 thema's</p>
                    <div class="dropdown-container" id="themeDropdownMenu">
                        <ul class="dropdown-menu">
                            <% themes.forEach(theme =>{ %>
                            <li>
                                <label>
                                    <input type="checkbox" value="<%= theme.id %>" name="theme">
                                    <span>
                                        <%= theme.label %>
                                    </span>

                                </label>
                            </li>
                            <% }); %>
                        </ul>
                    </div>
                </fieldset>

```

hier maak ik gebruik van een fieldset, daarin heb ik ul en li's. Die zijn wat makkelijker te stijlen en om de dropdown menu open en dicht te kunnen doen moet ik wel javascript gebruiken. 


```javascript

function handleSelectedOptionClick() {
  dropdownMenu.classList.toggle("show");
  selectedOption.classList.toggle("open");
}

```

Ik voeg een class toe om de dropdown menu te togglen, ik zet een class show en open, open wanneer het open dicht moet en show wanneer de dropdown menu moet gezien worden


## Img preview
Ik heb een optie om een link te zetten en die kan je als een afbeelding doorsturen naar de database, ook heb ik de optie om een bestand te selecteren en van dat een soort voorbeeld te zien. Ik wil van beide opties een voorbeeld laten zien van de afbeeldingen, 
Hier over heb ik wat onderzoek gedaan, maar hier bleef ik vast. Hierover ga ik even aan  pip en ine hulp vragen. 

Op dit moment heb ik dit 

```javascript
 if (file) {
    selectedFileName.textContent = file.name;

    const reader = new FileReader();
    reader.onload = function(e) {
      const img = document.createElement("img");
      img.src = e.target.result;
      img.alt = "Selected Image";
      customImagePreview.innerHTML = "";

      const closeButton = document.createElement("button");
      closeButton.classList.add("close-button");
      closeButton.innerHTML = "&times;"; // Use × symbol as the close icon

      closeButton.addEventListener("click", function() {
        // Clear the file input value
        fileInput.value = "";

        // Clear the image preview
        customImagePreview.innerHTML = "";
        selectedFileName.textContent = "Geen bestand geselecteerd";

        // Remove the close button
        closeButton.remove();
      });

      customImagePreview.appendChild(img);
      customImagePreview.appendChild(closeButton);
    };
    reader.readAsDataURL(file);
  } else {
    selectedFileName.textContent = "Geen bestand geselecteerd";

```

## Feedback van opdrachtgever / docent (code en design review) verwerken
Deze week hadden wij  onze eerste code review 
Op 7 juni kreeg ik van Robert code review over het kunnen controleren van de data vanuit het formulier die naar de database wordt gesturud. 
Dit is de data sanitization van het formulier. Lijkt mij wel interessant, ik ga even kijken als ik de tijd er voor heb op dit daadwerkelijk te kunnen toepassen. 
Ik vroeg dit aan de opdrachtgever, als er veel troep werd ingegooid op zijn website en hij zei hij hij heeft de website 8 jaartjes al en  nogsteeds heeft hij geen nare content gezien. 

## Reflectie 
Deze week zijn we bezig geweest met de design verder uit te werken en de functionaliteiten uit te werken. Voor mijn gevoel ging het best goed, maar ik kreeg een aantal errors net als de thema’s kon ik niet goed stylen, hier aan had ik te veel tijd aan besteed. Uiteindelijk heeft Keisha mij enorm geholpen met de thema, verder heb ik ook de localstorage erin verwerkt.
Verder hebben wij constant de feedback van onze docenten ook erin verwerkt, wij hopen dat wij een fantastisch prototype kunnen opleveren!!!


# Week 3
Begin van een nieuwe sprint!! We hebben nog 2 weken te gaan!
Maar dit betekent dat we echt aan de bak moesten gaan!
Ik heb deze week ontzettend veel gedaan, ik probeerde verschillende elementen echt te laten werken. 
Ik heb de volgende taken deze week gedaan. 

## Img preview
Vorig week was ik bezig met het laten zien van een geselecteerde afbeelding. De afbeelding werd toch niet gepakt. Hierdoor was ik deze week weer bezig met het zoeken van een nieuwe manier van een voorbeeld laten zien. Hieronder is het gelukt met een voorbeeld laten zien bij een geselecteerd input type file. 

```javascript
 if (customImagePreview) {
      customImagePreview.innerHTML = "";
      customImagePreview.appendChild(img);
    }


```
## Img link parsen 
Vorige week  kreeg ik een error bij het parsen van de link en een voorbeeld ervan te krijgen. Deze week heb ik weer onderzoek gedaan en gekeken hoe ik dit toch anders kan aanpakken. Ik had Ine gevraagd om hulp en zij hielp mij hiermee. 

Wij zijn toen op de volgende gekomen. 

```javascript
if (imageLinkInput) {
  imageLinkInput.addEventListener("input", () => {
    imagePreview.innerHTML = `<img src="${imageLinkInput.value}" alt="">`;
  });
}
```

## Toggle toepassen 
Vorige week besefte ik dat de toggle niet zo ging, de classes werder uberhaupt niet erbij gezet. 
Deze week was ik ook bezig met de toggle en ik kwam toen hierop. 


```javascript 


function handleSelectedOptionClick() {
  dropdownMenu.classList.toggle('show');
  selectedOption.classList.toggle('open');
}


```

## De design aanpassen
foto hiero


## Formulier post
Het posten van de data vanuit het formulier. oh man oh man, dit was moeilijk!!!
Ik kwam er maar niet uit,  ik ging van alles zoeken, maar ik kwam er maar niet, omdat ik supabase niet begreep. 
Ik ging toen even kijken hoe supabase aan de slag gaat en hoe je data kan versturen met ejs. 
Na veel trial en error kwam ik op dit. 
```javascript
app.post("/form", async (req, res) => {

  console.log('even kijken');
  
  const {error} = await supabase
      .from('form')
      .insert({
        title: req.body.titel,
        description: req.body.beschrijving,
        theme: req.body.thema,
        image: req.body.imageLink,
        link: req.body.file
      })
  if (error) {
      res.send(error);
  }
  res.send("created!!");
});
```

Ik ging toen vragen aan Jevona en ze gaf aan dat de data toch niet verstuurd wordt.
Ik ga hier volgende week aan werken, want ik kom er maar niet uit. 


## Afbeelding pop up
Vasilis gaf deze week aan, dat de bestand selecteren en de link kunnen doorgeven als afbeelding, te veel gaat zijn op een pagina en dat ik beter een pop up ervan kan maken. 
Ik ging toen aan de slag met het maken van de pop, ik vond het nog lastig, want ik heb nog nooit een pop up gemaakt. 

uiteindelijk kwam ik op het idee een div te maken en de content erin te zetten, om die uiteindelijk als een pop te stijlen. 
Alleen de stijling ervan ging niet zo lekker. 

```html 
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
                        <input type="file" id="file" name="file" accept="image/jpeg, image/png, image/jpg" >
                        </div>
                        <div id="customImagePreview"></div>
                        <p id="selectedFileName">Geen bestand geselecteerd</p>
                        <div id="closeButton" class="hidden">&#10006;</div>
             
              </div>
```
Toevallig kwam ik Ine tegen en ik had het over de pop up, zij raadde aan om ipv een div een dialog te maken, die krijgt een algemene stijling mee en is altijd boven de content. Dit ga ik volgende week toepassen

## Feedback van opdrachtgever / docent (code en design review) verwerken
We hebben deze week onze eerst design review gehad en ook de code review.

Op 14 juni kreeg ik van  Justus feedback op de volgenge 
- De hierarchy van code en content moet ik op letten 
- Ik moet goed kijken bij wat bij waar hoort. 


Verder kreeg ik ook op 15 juni van Vasilis design review, hij gaf wat feedback op het formulier (kleur en wat meer experimenteren qua input)en ook ging ik wat vragen stellen over het maken van de  pop up. 

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
                <div id=popup class=hidden>
    
                
        
                    <div id=links>
                        <label for=links>Websites waar je rechtvrije afbeelding kan vinden</label>
       
                        <div class='linkjes'>
                            <a href=https://unsplash.com/>Unsplash</a>
                            <a href=https://www.pexels.com/nl-nl/>Pexels</a>
                            <a href=https://pixabay.com/nl/>Pixabay</a>
                        </div>
                      
        
                        <p class=hierarchy>Link</p>
                    
           
                        <input type=text name=imageLink id=imageLink placeholder=Plaats hier uw link>
                        
                        <div id=imagePreview></div>
                    
        
                        <label for=or>Of</label>
                 
        
                        <p class=hierarchy>Bestand</p>
                   
        

                        <div class=file-input-container>
                            <img src=/images/wolkje.png alt=een wolkje dat staat voor uploaden van een afbeelding>
                            <p>Selecteer een bestand</p>
                            <input type=file id=file name=file accept=image/jpeg, image/png, image/jpg>
                     
                        </div>
                        <div id=customImagePreview></div>
                    
                        <p id=selectedFileName>Geen bestand geselecteerd</p>
            
                        <div id=closeButton class=hidden>&#10006;</div>
                     
                    </div>
                </div>

```



Tijdens de design review kreeg ik de feedback van Vasilis dat ik ipv een div, beter dialog kan gebruiken. 
Een HTML-dialog is een ingebouwd element in HTML5 waarmee je modale dialoogvensters kunt maken, zoals bevestigingsvensters of formulieren, zonder extra JavaScript-code te schrijven.

Ik vond de dialog tag makkelijker toe te passen en ben er meteen aan de slag gegaan. 

Zie hier de code. 

```html
                <dialog class=no-js>   
                <div id=links>
                    <label for=links>Websites waar je rechtvrije afbeelding kan vinden</label>
                    <div class='linkjes'>
                        <a href=https://unsplash.com/>Unsplash</a>
                        <a href=https://www.pexels.com/nl-nl/>Pexels</a>
                        <a href=https://pixabay.com/nl/>Pixabay</a>
                    </div>
                    <p class=hierarchy>Link</p>
                    <input type=text name=imageLink id=imageLink placeholder=Plaats hier uw link>
                    <div id=imagePreview></div>
                    <label for=or>Of</label>
                    <p class=hierarchy>Bestand</p>
                    <div class=file-input-container>
                        <img src=/images/wolkje.png alt=een wolkje dat staat voor uploaden van een afbeelding>
                        <p>Selecteer een bestand</p>
                        <input type=file id=file name=file accept=image/jpeg, image/png, image/jpg>
                    </div>
                    <div id=customImagePreview></div>
                    <p id=selectedFileName>Geen bestand geselecteerd</p>
                    <div id=closeButton class=hidden>&#10006;</div>

                    <button id=closeDialog>sluiten</button>
                </div>

```


## Form validatie 
Het valideren van een formulier hebben wij tijdens het vak browser technologies geleerd. 
Je hebt dan 3 lagen van validation, html, css en javascript. 

Bij html ziet de validation zo er uit

```html 
<input type=text id=title name=title placeholder=Geef je wens een titel minlength=2 maxlength=40 required>
```


Bij css ziet de validation er zo uit, wanneer er text in de input field zit, wordt het groen, zo niet dan is het rood. 

```css
textarea:required:invalid
  border: 2px solid red;
}

textarea:required:valid
  border: 2px solid green;
}
```

In javascript zet ik een limiet bij de thema's de gebruiker kan maximaal alleen 4 thema's kiezen, zo zorgen we ervoor dat de gebruiker bijvoorbeeld niet alle thema's selecteerd

Zo ziet de validation er zo uit

```javascript
const maxThemes = 4;

let selectedThemes = [];

function updateSelectedOptionText()
  selectedThemes = Array.from(themeCheckboxes)
    .filter((checkbox) => checkbox.checked)
    .map((checkbox) => checkbox.value);

  themeCheckboxes.forEach((checkbox) =>
    checkbox.disabled = selectedThemes.length >= maxThemes && !checkbox.checked;
  });
}
```



## Javascript errors 
Tijdens het mergen van de code, kwamen we steeds veel errors tegen. Er kwamen steeds variable undefined, niet goed geplaatst, etc. Localstorage heeft een bug en nog veel meer. Omdat we in modules werken, kan het soms tricky zijn om code op te halen en die dan in de main.js terug te halen. Gelukkig hadden wij de tijd genomen tijdens de refator om de errors te kunnen fixen. 

Jevona was in controle van version control, zij was ons github master. Als je een error had, kon je het zelf oplossen, of ging Jevona soms samen zitten om eraan te werken. 


## Form data versturen naar database
Wij gebruiken de database, supabase. Ik heb geen ervaring van supabase, dus moest ik en ook de andere gewend aan raken. 
Aan mij was de opdracht gegeven, van het posten van het formulier data naar de database en die dan terug te halen vanuit de database naar de index.ejs

Hier laat ik even mijn code van versturen van de data (van het formulier) naar de database zien. 

```javascript

router.post(/form, async (req, res) =>
  try
    const data, error } = await supabase
      .from(suggestion)
      .insert([
       
          title: req.body.title,
          description: req.body.description,
          image: req.body.imageLink,
        },
      ])
      .select();

    const insertId = data.length > 0 ? data[0].id : null;
    if (error || !insertId)
      throw error;
    }

    console.log([parseInt(req.body.theme)])
    const themes = req.body.theme;

    const themeInsertPromises = themes.map(async (theme) =>
      const data: themeData, error: themeError } = await supabase
        .from(theme)
        .select(id)
        .eq(id, theme)
        .single();
      if (themeError)
        throw themeError;
      }

      const error: suggestionThemeError } = await supabase
        .from(suggestion_theme)
        .insert([
         
            suggestioninsertId,
            themathemeData.id,
          },
        ]);
      if (suggestionThemeError)
        throw suggestionThemeError;
      }
    });

    await Promise.all(themeInsertPromises);
    res.render(sent,
      title: sent,
    });
  } catch (error)
    res
      .status(500)
      .json({ error: Het toevoegen van de wens ging fout, probeer opnieuw });
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

<img width=1300 alt=Schermafbeelding 2023-06-28 om 15 17 47 src=https://github.com/RainbowJM/strandeiland/assets/94360732/a1b6dfe5-5358-482c-a2a6-27a6270c1096>

## Feedback van opdrachtgever / docent (code en design review) verwerken
Deze week kreeg ik voor de laatste keer een code en design review. Dit was zeer handig, want zo kon ik nog de laatste feedback krijgen
Op 21 juni kreeg ik van Justus code review: 
hij vond de samenwerking etc. goed gaan
Ik had alleen nog een vraag over het versturen van de bestand naar de database, hij raadde aan om multer te gebruiken. Alleen jammer genoeg vanwege de tijdsgebrek, heb ik alleen onderzoek er naar gedaan. Als ik wat meer tijd had, zou ik het meteen kunnen implementeren 
 
Op 22 juni kreeg ik van vasilis design review:
Ik had een vraag over de verschillende fallbacks in mijn code en hoe ik dat makkelijk kan implementeren. Vasilis had een hele makkelijke manier, je zet in je html een class in en als javascript aan is, dan kan je met de class de dropdown menu verbergen, als de javascript uit staat, dan blijft het uitgeklapt. Dit was heel handig en heb ik het meteen geimplementeerd in mijn code. 

## Multer 
**Wat is multer?**
Multer is een middleware voor het verwerken van multipart/form-data in Node.js en Express.js. Het wordt vaak gebruikt in combinatie met webapplicaties die bestandsuploads ondersteunen. Multer maakt het gemakkelijk om bestanden te ontvangen via HTTP-verzoeken en ze op te slaan op de server.

Multer biedt functionaliteit voor het verwerken van meerdere bestanden, het beperken van bestandstypen en het instellen van maximale bestandsgroottes. Het is ook mogelijk om aangepaste bestandsopslaglocaties en bestandsnamen te definiëren. Multer maakt gebruik van het concept van middleware in Express.js, waardoor het eenvoudig kan worden geïntegreerd in bestaande Express.js-applicaties.

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
Dit is de laatste week, het was een beetje chaotisch, omdat het natuurlijk de laatste week is. 
Deze week waren we bezig met de laatste foutjes verbeteren, we hadden uitgebreide code refactor nog kunne doen op donderdag. 
Zo was onze code productie ready.
We hadden best veel errors, dit gebeurt natuurlijk altijd in de laatste week, daarom namen wij even de tijd om deze op te lossen en voor het einde van de sprint (donderdag) alles af te hebben. We moesten ook de tijd nemen om alle documentatie bij te houden, die hadden we natuurlijk al, alleen moesten wij nog een paar kleine dingetjes erbij zetten. 

## Documentatie
typen, typen en nogmaals typen. 
Ik was meerendeels bezig met het afmaken van de check in en check outs op scrum, we hebben elke dag de scrum bij gehouden. Alleen de laatste week hadden wij geen tijd meer om de check in en check outs bij te houden. Op donderdag was ik nog even hier mee bezig en op de gezamenlijke repo, was ik ook bezig met de design rationale. Meer vertellen over mijn deel. 
Naast de documentatie had ik nog een aantal dingen die ik moest afronden.

## Testen  (lighthouse)
Hilal en ik waren bezig met het testen van de prototype, we hebben hiervoor de lighthouse gebruikt. 
Hilal ging aan de slag met de desktop variant er van en ik ging met de mobiel variant. 

Eerst over het algemeen waren de score best hoog, behalve de index pagina had een score van 60. 

Ik bleef maar dingen aanpasen en door testen, uiteindelijk had ik alles boven de 90. 
De volgende dingen moest ik aanpassen:
- Meta name
```html
<meta charset=UTF-8>
<meta http-equiv=X-UA-Compatible content=IE=edge>
<meta name=viewport content=width=device-width, initial-scale=1.0>
<meta name=theme-color content=#fffff/>
<meta name=Strandeiland content=Welkom op Strandeiland.>
<meta name=description content=Hallostrandeiland.nl is een website dat gaat over het versturen van wensen voor het nietu.>
<meta name=Author: Hilal Keisha Jevona Laiba>
<link rel=stylesheet href=/css/global.min.css>
<link rel=preconnect href=https://fonts.googleapis.com>
<link rel=preconnect href=https://fonts.gstatic.com crossorigin>
<link href=https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap rel=stylesheet media=all>
<script src=https://kit.fontawesome.com/87a1015511.js crossorigin=anonymous defer></script>
<link rel=manifest href=/manifest.json>
<link rel=shortcut icon href=/images/favicon.ico type=image/x-icon>
<title> <%= title %></title>
```
- Reduce css 
- Img resizing (dit kon ik niet aanpassen, want de afbeelding komen rechtstreeks vanuit de database)
foto hiero 

Na dat Jevona de css had geminified (bij de reduce css)
foto hiero


## Code refactor 
**Code vanuit script.js eruit halen en die zetten in form.js**
Ik heb heel veel javascript code voor mijn formulier en die is allemaal erin gesmeten in de script.js, wij gebruiken zelf modules en script.js is de main file. 
Om de script.js wat overzichtelijk te houden, moet is mijn javascript code naar de form.js verhuizen en die dan later op te roepen in mijn script.js.

```javascript 
import selectedOption, dropdownMenu, localStorageKey, themeCheckboxes, fileInput, customImagePreview, selectedFileName,
  savedFormData, imageLinkInput, imagePreview, titleInput, descriptionTextarea, uploadDialog, closeDialogButton, imgCloseDialogButton, themes } from ./modules/variables.js;

function loadFormData()
  if (savedFormData)
    if (titleInput)
      titleInput.value = savedFormData.title;
    }

    if (descriptionTextarea)
      descriptionTextarea.value = savedFormData.description;
    }

    if (themeCheckboxes)
      themeCheckboxes.forEach((checkbox) =>
        checkbox.checked = savedFormData.themes.includes(checkbox.value);
      });
    }

    if (imageLinkInput)
      imageLinkInput.value = savedFormData.imageLink;
      imagePreview.innerHTML = `<img src=${savedFormData.imageLink} alt=>`;
    }

    if (fileInput)
      selectedFileName.textContent = savedFormData.file ? savedFormData.file.name : Geen bestand geselecteerd;
      customImagePreview.innerHTML = savedFormData.file ? `<img src=${URL.createObjectURL(savedFormData.file)} alt=Selected Image>` : ;
    }
  }
}

function saveFormData()
  const formData =
    title: titleInput.value,
    description: descriptionTextarea.value,
    themes: [],
    imageLink: imageLinkInput.value,
    file: fileInput.files[0]
  };

  if (themeCheckboxes)
    themeCheckboxes.forEach((checkbox) =>
      if (checkbox.checked)
        formData.themes.push(checkbox.value);
      }
    });
  }
  localStorage.setItem(localStorageKey, JSON.stringify(formData));
}

function updateSelectedOptionText()
  const selectedThemes = Array.from(themeCheckboxes)
    .filter((checkbox) => checkbox.checked)
    .map((checkbox) => checkbox.value);

  themeCheckboxes.forEach((checkbox) =>
    checkbox.disabled = selectedThemes.length >= maxThemes && !checkbox.checked;
  });
}

function updateFormData()
  const selectedCheckboxes = Array.from(themeCheckboxes)
    .filter((checkbox) => checkbox.checked)
    .map((checkbox) => checkbox.value);

  const selectedThemes = themes
    .filter((theme) => selectedCheckboxes.includes(theme.id))
    .map((theme) => theme.label);

  selectedOption.textContent = selectedThemes.length > 0 ? selectedThemes.join(, ) : Selecteer de passende thema's;
}

function showDialog(event)
  event.preventDefault();
  uploadDialog.showModal();
}

function closeDialog(event)
  event.preventDefault();
  uploadDialog.close();
}

function imgCloseDialog(event)
  event.preventDefault();
  uploadDialog.close();
}

function handleCheckboxChange()
  updateFormData();
}

function handleFileInputChange()
  const file = fileInput.files[0];

  if (file)
    selectedFileName.textContent = file.name;
    const reader = new FileReader();
    reader.onload = function (e)
      const img = document.createElement('img');
      img.src = e.target.result;
      img.alt = 'Selected Image';
      customImagePreview.innerHTML = '';
      const closeButton = document.querySelector('button');
      closeButton.classList.add('close-button');
      closeButton.innerHTML = '&times;'; 
      closeButton.addEventListener('click', function ()
        fileInput.value = '';
        customImagePreview.innerHTML = '';
        selectedFileName.textContent = 'Geen bestand geselecteerd';
        closeButton.remove();
      });
      customImagePreview.appendChild(img);
      customImagePreview.appendChild(closeButton);
    };
    reader.readAsDataURL(file);
  } else
    selectedFileName.textContent = 'Geen bestand geselecteerd';
    customImagePreview.innerHTML = '';
  }
}

function handleSelectedOptionClick()
  dropdownMenu.classList.toggle('show');
  selectedOption.classList.toggle('open');
}

// ------------------ event listeners -------------------------------------------------------
if (themeCheckboxes)
  themeCheckboxes.forEach((checkbox) =>
    checkbox.addEventListener('change', handleCheckboxChange);
  });
}

if (fileInput)
  fileInput.addEventListener('change', handleFileInputChange);
}

if (selectedOption)
  selectedOption.addEventListener('click', handleSelectedOptionClick);
}

if (closeDialogButton)
  closeDialogButton.addEventListener('click', closeDialog);
}

if (imgCloseDialogButton)
  imgCloseDialogButton.addEventListener('click', imgCloseDialog);
}

loadFormData();
updateSelectedOptionText();
updateFormData();

export showDialog, closeDialog, imgCloseDialog, handleSelectedOptionClick, handleCheckboxChange, updateFormData,
  saveFormData};


```



**EJS schoon maken, geen comments of extra white space**
Verder om de ejs files schoon te houden, moest ik alle comments er uit halen en ook onnodige white space. 
Verder ging de code goed formatten, dat deed ik heel makkelijk met de extension beautify.

**Code in engels (geen nederlands, zie coding standards)**
In ons coding standards, stond dat alles in nederlands gaat zijn, behalve ons code. Om aan de agreement te houden, ging ik nog kijken wat in nederlands is en die ging ik meteen vervangen iets in engels


## Localstorage
Ik heb natuurlijk nieuwe dingen in mijn formulier erbij gezet, maar die worden nog niet in mijn localstorage opgeslagen. 
Ik moest hiervoor mijn localstorage code weer aanpassen, checken wat wel en niet al wordt opgeslagen. 
Uteindelijk zag mijn code er zo uit


```javascript

if (localStorage.getItem(localStorageKey))
  const savedFormData = JSON.parse(localStorage.getItem(localStorageKey));

  if (titleInput)
    titleInput.value = savedFormData.title;
  }
  if (descriptionTextarea)
    descriptionTextarea.value = savedFormData.description;
  }
  if (themeCheckboxes)
    themeCheckboxes.forEach((checkbox) =>
      checkbox.checked = savedFormData.themes.includes(checkbox.value);
    });
  }
  if (imageLinkInput)
    imageLinkInput.value = savedFormData.imageLink;
    imagePreview.innerHTML = `<img src=${savedFormData.imageLink} alt=>`;
  }
  if (fileInput)
    selectedFileName.textContent = savedFormData.file
      ? savedFormData.file.name
      : Geen bestand geselecteerd;
    customImagePreview.innerHTML = savedFormData.file
      ? `<img src=${URL.createObjectURL(
          savedFormData.file
        )} alt=Selected Image>`
      : ;
  }
}

function saveFormData()
  const formData =
    title: titleInput.value,
    description: descriptionTextarea.value,
    themes: [],
    imageLink: imageLinkInput.value,
    file: fileInput.files[0],
  };

  if (themeCheckboxes)
    themeCheckboxes.forEach((checkbox) =>
      if (checkbox.checked)
        formData.themes.push(checkbox.value);
      }
    });
  }
  localStorage.setItem(localStorageKey, JSON.stringify(formData));
}
```

## Reflectie
Deze week was de laatste week van de eindopdracht. We hebben ontzettend veel geleerd tijdens dit minor, maar ik vind dat wij nog meer hebben kunnen tijdens de meesterproef. We hebben zelf de nieuwe technieken die wij hebben geleerd vanuit de minor moeten toepassen. Hierdoor viel op sommige onderdelen nu pas het kwartje😂
Deze week heb ik best veel gedaan, qua fine tunen, productie ready maken van de code. Laatste momenten gaat het altijd fout met code, dan opeens krijg je veel errors, etc. Die hadden wij zeker, ik probeerde altijd mijn errors op te lossen voordat ik iets stuurde, maar tijdens  het mergen ging het toch fout. Verder hebben wij ook verschillende tests afgelegd, ik heb met lighthouse de test op mobiel afgelegd, ik heb de score tot 96 kunnen opbouwen, hierop ben ik zeker trots op.


# Reflectie
De afgelopen 5 weken zijn heel snel voorbijgevlogen!
We hebben ontzettend veel kunnen doen in 5 weken, met de nieuwe kennis vanuit minor web. 
Hier leg ik even uit wat ik heb geleerd gedurend de 5 weken (meesterproef)

## Wat heb ik geleerd?
Vanuit minor web heb ik ontzettend veel geleerd.  In de minor Web Design & Development leer je interactieve toepassingen maken met HTML, CSS en JavaScript. In verschillende vakken en projecten leer je over browsers, het ‘real time web’, performance, rapid prototyping, usability, documenteren, versiebeheer, debuggen, testen, responsive, reactive, micro interacties, API’s en … het web.
Tijdens de meesterproef moet je zelf kijken hoe je de bepaalde elementen vanuit verschillende vakken in je applicatie kan toepassen. Tijdens het toepassen van sommige elementen viel het kwartje nu pas, of ik vond het makkelijker te implementeren vergeleken de eerste keer. 

Wat ik verder heb geleerd is hoe wij samenwerken tijdens het realiseren van een front-end / back-end  applicatie. 
We hebben veel maatregelen moeten ondernemen, om de samenwerking te bevorderen. 
De version control, dus met github (mergen, vanuit verschillende branches werken) moesten wij steeds heel goed communiceren, om conflicten met de code te voorkomen. 
De github master was Jevona, zij komt ook vanuit de opleiding HBO-ICT, ik heb zeker een paar voorbeelden van haar overgenomen. Ze deed het heel goed met vermijden van merge conflict en ook al als er merge conflicts waren, pakte ze het heel gemakkelijk aan. 

## Wat ging er goed?
Ik vind de samenwerking tussen ons ging best goed, we namen zelf taken op zich. Door middel van scrum werd ons samenwerking al helemaal bevordert. Ieder van ons wist wel we moeten iets doen en niet still blijven en niks doen. 
We hebben altijd gecommuniceerd als er wat is en we hebben elkaar altijd laten weten als er iets is, communiceer het gelijk. 
Qua version control ging het ook goed, we werkte steeds vanuit verschillende branches. Waardoor wij ons code nog altijd konden beschermen. 


## Wat ging er minder goed?
Bij ons hebben we afgesproken voor elke verandering een nieuwe branch te maken, zo verkomen we de merge conflict. Alleen vergat ik steeds bij een nieuwe verandering een branch te maken. Tijdens het mergen, moest Jevona heel veel stukken code dan mergen en dit is echt gevaarlijk. 
Ik dacht steeds oh mijn nieuwe feature (die ik net heb geimplementeerd) heeft nog een error, die moet eerst opgelost worden, voordat ik die push naar github. Maar wat eigenlijk de bedoeling is om de nieuwe feature eerst te pusen en dan een nieuwe branch aan te maken waar ik de error van de feature op los. 
Ik vond dit een beetje moeilijk het te onderscheiden. Voor de volgende keer ga ik dit zeker proberen te doen.

## Waar ben ik trots op
Ik ben trots op het prototype, waar we 5 weken hebben aan gewerkt. We hebben echt veel bloed, zweet en tranen erin gestoken.
Ik ben trots op hoe ik zoveel elementen vanuit verschillende vakken heb laten implementeren in het formulier pagina. Tijdens het implementeren viel het kwartje pas, dit gebeurd altijd met mij, ik moet wat meer tijd nodig hebben om een bepaalde onderwerpen te kunnen begrijpen. 
Ik ben ook trots op dat zo ver ben gekomen om aan meesterproef te kunnen deelnemen, in het begin van de minor web had ik major imposter syndrome. Ik dacht dat ik het niet aan kon en ook niet tot meesterproef zou komen, maar het is toch gelukt, ik heb alle vakken van minor web gehaald en ook een succesvolle meesterproef kunnen afronden.
Ik wil gewoon zeggen dat ik heel erg trots op mezelf ben. 


# Toepassing meesterproef Vakken
Een van de criteria van meesterproef was het toepassen van de vakken vanuit minor web. We moesten minimaal 3 vakken toepassen per persoon in ons prototype. Ik heb de volgende vakken toegepast.

## Browser Technologies 
Het eerste vak die ik toe pas is browser tech, we hebben het daar meer over progressive enhancement geleerd, het testen op verschillende broswers en het toegankelijk maken voor elk gebruiker. 
De volgende leerdoelen heb ik toegepast:
- student begrijpt de principe van Feature detection en hoe je dit kan toepassen, Student kan voorbeeld noemen van hoe Feature Detection werkt en wat fallback is
- je leert wat Progressive enhancement is en hoe je dit kan toepassen.

Ik heb als progressive enhancement het opslaan van data in localstorage opgeslagen, daarvoor is de fallback als de gebruiker localstorage heeft, dan wordt de data opgeslagen, zo niet dan kan de gebruiker niet de data opslaan in localstorage, maar wel nog sturen naar de database (supabase).

Verder bij het formulier validatie heb ik verschillende fallbacks, wanneer de css en javascript uit staat. 

In html heb ik een maximum en minimun length bij input fields gezet. Zo wordt gebruiker wat gelimiteerd met het invoeren van tekst. 

```html
  <label for=title>Titel</label>
                <input type=text id=title name=title placeholder=Geef je wens een titel minlength=2
                    maxlength=40 required>

```


In css heb ik de invalid en valid element gebruikt, wanneer de input field leeg is het rood en wanneer er tekst wordt ingevoerd dan wordt het groen. 
```css
input:required:invalid
  border: .2em solid #f6a192;
}

input:required:valid
  border: .2em solid green;
}

```

In javascript heb ik bij thema's een extra validatie, dat de gebruiker niet meer dan 4 thema's kan selecteren. 
```javascript
const maxThemes = 4;

let selectedThemes = [];

function updateSelectedOptionText()
  selectedThemes = Array.from(themeCheckboxes)
    .filter((checkbox) => checkbox.checked)
    .map((checkbox) => checkbox.value);

  themeCheckboxes.forEach((checkbox) =>
    checkbox.disabled = selectedThemes.length >= maxThemes && !checkbox.checked;
  });
}

```

Als de javascript en css uitstaat, krijg de gebruiker toch wel de html validatie mee en kan nogsteeds het formulier versturen (niet zonder javascript).

## CSS to the rescue
Tijdens het vak css to the rescue had ik geleerd hoe ik met verschillende manier met css kan experimenteren. We probeerden ook de nieuwste technieken van css toe te passen. 

Ik heb de volgende leerdoelen toegepast vanuit het vak css to the rescue:
- Je hebt begrip van de volle kracht en mogelijkheden van CSS. Je laat zien dat CSS meer kan dan allen web pages 'stylen'.
- Je hebt begrip van de interactie-technieken van CSS (en HTML). De UX is aangenaam bruikbaar binnen de gekozen context(en)

Ik heb bijvoorbeeld grid en verschillende kleine animaties in het formulier pagina gemaakt. We hebben in het algemeen een aangenaam ux design voor ons prototype aangehouden. Het is makkelijk te navigeren bij ons applicatie (zie test lighthouse, zit ook navigatie erin).


## Web app from scratch 
Voor het vak Web app from scratch hebben we veel over het fetchen van data vanuit een api geleerd. Dit keer fetch ik en post ik data naar een api/database genaamd Supabase. 
Zie hierboven hoe ik data post en haal vanuit de database. 

Ik heb de volgende leerdoel toegepast vanuit het vak WAFFS:
- Data management - you understand how you can work with an external API using asynchronous code. You can retrieve data, manipulate and dynamically convert it to structured html


## Progressive web app
Voor het vak Progressive web app hebben wij meer naar de backend kant gekeken en dat heb ik zeker ook bij de prototype toegepast. 
In de server side haal fetch ik en post ik data op het formulier pagina, we gebruiken de database/ api Supabase (opgezet door Jevona). 
Verder heb ik ook verschillende testen gedaan om de performance van de prototype te verbeteren (zie test lighthouse)

- Serverside rendering You’ve implemented serverside rendering and have articulated how it works and why you should want it.
- Critical render path You’ve enhanced the critical render path for a better runtime or perceivved performance in multiple ways and have described how you managed to do this.





## Human Centered Design 
Bij het vak Human Centered Design moesten wij rekening houden met 1 soort gebruiker en moesten de user need implementeren in onze prototype. 
We hebben dit zeker in ons prototype kunnen verwerken, elke week gingen wij met ons opdrachtgever zitten om het te laten testen en elke week kregen wij wel feedback, die gingen wij steeds toe passen in ons prototype. 

Ik heb de volgende leerdoel toegepast vanuit het vak WAFFS:
 - Testresultaten - Aan de hand van de tests wordt duidelijk gemaakt hoe deze hebben bijgedragen aan het verbeteren van het ontwerp of hoe dit een volgende keer beter of anders kan.

- User Needs - Er is een user scenario geschreven dat aansluit bij de identiteit van de test persoon. Er is een duidelijk en volledig user scenario geschreven dat antwoord geeft op de 4 w-vragen: Who? What? How? en Why?





# Bronnen
- NPM: multer 
https://www.npmjs.com/package/multer



- Developer.mozilla: dialog: The Dialog element
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

- Using Each Loop in EJS Template and Express JS. (2021, July 8). The freeCodeCamp Forum. https://forum.freecodecamp.org/t/using-each-loop-in-ejs-template-and-express-js/468398/2 


- Supabase Javascript Client - Using filters. (n.d.). https://supabase.com/docs/reference/javascript/using-filters

- EJS - pass data to partial view and use it in every view/page. How can i do that? (n.d.). Stack Overflow. https://stackoverflow.com/questions/60551806/ejs-pass-data-to-partial-view-and-use-it-in-every-view-page-how-can-i-do-that

- Hallo IJburg - houdt je verbonden. (n.d.). halloijburg.nl. https://halloijburg.nl/

- Hallo Strandeiland. (n.d.). hallostrandeiland.nl. https://hallostrandeiland.nl/

- Isheanesu. (2022). How To SELECT, COUNT and JOIN Supabase Data. DEV Community. https://dev.to/thisisisheanesu/how-to-select-count-and-join-supabase-data-3ihk


- Shooft. (z.d.). CSS Filter: Desaturate Example CodePen. Geraadpleegd van https://codepen.io/shooft/pen/xxVmpEP?editors=0110






