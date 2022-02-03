# Procesverslag
Markdown is een simpele manier om HTML te schrijven.  
Markdown cheat cheet: [Hulp bij het schrijven van Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Nb. De standaardstructuur en de spartaanse opmaak van de README.md zijn helemaal prima. Het gaat om de inhoud van je procesverslag. Besteedt de tijd voor pracht en praal aan je website.

Nb. Door *open* toe te voegen aan een *details* element kun je deze standaard open zetten. Fijn om dat steeds voor de relevante stuk(ken) te doen.


## Je website

<details open>
<summary>uitwerken voor kick-off werkgroep</summary>

### Je opdracht:
link naar de website die je gaat namaken óf de naam/omschrijving van je eigen ontwerp
www.swapfiets.nl
https://swapfiets.nl/amsterdam/deluxe-7

#### Screenshot(s) van de eerste pagina (small screen): 
hier de naam van de pagina  
<img src="images/swapfiets-website-origineel-mobile.png" width="375px" alt="De homepagina van swapfiets">

#### Screenshot(s) van de tweede pagina (small screen):
hier de naam van de pagina  
<img src="images/swapfiets-website-deluxe7-mobile.png" width="375px" alt="De detailpagina over de fiets die Deluxe 7 heet">
 
</details>

## Toegankelijkheidstest

<details>
<summary>uitwerken na test</summary>

### Bevindingen
Lijst met je bevindingen die in de test naar voren kwamen:
- Ik had eerst nog niet genoeg alt-tags in de IMG's
- Alle div's die ik voor buttons gebruikte heb ik nu type button gemaakt 

#### Titel eerste bevinding
Hier korte omschrijving (met indien nodig een afbeelding)
- Niet alle img elementen hadden een alt tag, hierdoor is het gebruik van de website minder toegankelijk.

Hier een omschrijving van hoe het opgelost kan worden (met indien nodig een afbeelding)

met control F kon ik gemakkelijk alle img's terug vinden en er een goed beschreven alt-tag tussen zetten.

#### Titel tweede bevinding. 
Hier korte omschrijving (met indien nodig een afbeelding)
- De divs die ik gebruikte als button hadden nog geen button specificering

Hier een omschrijving van hoe het opgelost kan worden (met indien nodig een afbeelding)
- met CTRL+F heb ik de betreffende class .bekijkFietsen opgezocht en type="button" erbij gezet.

</details>

## Eindgesprek

<details>
<summary>uitwerken voor eindgesprek</summary>

### Stand van zaken
hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)

Dit ging goed:
Ik heb een redelijk goede reproductie kunnen maken van de swapfiets website. Dit is de aller-eerste keer dat ik een responsive website maak en het is naar mijn mening redelijk goed gedaan.

Wat ging minder goed:
Op een klein aantal schermgroottes kan de website er wat ongemakkelijk uit zien. En de footer verspringt op de deluxe7 pagina bij switchen naar mobiel, maar na uren onderzoek kon ik er niet achter komen wat het probleem was. 

Het lijkt er ook op dat Swapfiets een CMS achtig programma gebruikt, hierdoor gebruiken zij soms trucjes met div's waar ik niks mee kan. Ik heb met standaard HTML en CSS hieromheen proberen te bewegen op een nette manier.

Ik heb uren gestaart naar waarom mijn micro-interactie niet lukte, maar ik ben er uiteindelijk niet meer uit gekomen.


### Screenshot(s)

hier screenshot(s) van je eindresultaat

<img src="images/oplevering mobile homepage.png" width="375px" alt="De homepagina van swapfiets">

<img src="images/opleveren deluxe 7 mobile.png" width="375px" alt="Detailpagina van deluxe 7 fiets">

<img src="images/oplevering desktop homepage.png" width="600px" alt="De homepagina van swapfiets op groot scherm">

<img src="images/opleveren deluxe 7 desktop.png" width="600px" alt="De deluxe 7 pagina van swapfiets op groot scherm">

</details>

## Bronnenlijst

<details open>
<summary>continu bijhouden terwijl je werkt</summary>

Nb. Wees specifiek ('css-tricks' als bron is bijv. niet specifiek genoeg).

1. How to create responsive navigation bar using html and css. https://www.youtube.com/watch?v=oLgtucwjVII&ab_channel=CodingNepal
2. CSS @Media Rule, hoe pas ik dat toe, zodat ik elementen kan laten verdwijnen en vershcijnen op basis van schermgrootte. https://www.w3schools.com/cssref/css3_pr_mediaquery.asp
3. Background positioning https://www.w3schools.com/CSSref/pr_background-position.asp
4. GT Walsheim font google font alternatief: https://alternatype.net/relations.php?font-id=10466
5. Grid maken voor 2 items naast elkaar (play store en apple store) https://www.w3schools.com/css/css_grid.asp
6. Icon in search bar https://stackoverflow.com/questions/35173180/search-icon-in-search-field
7. Summary marker content https://developer.mozilla.org/en-US/docs/Web/CSS/content
8. Flexbox tutorial https://www.youtube.com/watch?v=b3xhm_2esTM&ab_channel=Codevolution
9. center alles https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/
10. overflow hidden https://stackoverflow.com/questions/2062258/floating-elements-within-a-div-floats-outside-of-div-why
11. Fixed header https://www.w3schools.com/howto/howto_js_sticky_header.asp
12. footer tutorial https://www.youtube.com/watch?v=YOb67OKw62s&ab_channel=TheWebShala
13. Make fancy animated text in JS https://www.youtube.com/watch?v=GUEB9FogoP8&ab_channel=DevEd

</details>