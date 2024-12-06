# mentoring

## maandag 30.09.2024
Vandaag heb ik mijn eerste mentoring sessie gehad. De les ging over hoe je met behulp van verschillende CSS technieken bepaalde layouts kunt creëren. De 1e jaars studenten kregen hierbij een deeltaak met 9 layouts die ze mochten nabouwen, met CSS grid, flexbox, float, position etc..

Ik zat niet met mijn hele mentor team, ik ben aan gaan schuiven aan een tafel waar nog geen andere mentor bij zat. Hier heb ik de 1e jaarsstudenten geholpen met algemene dingen als "hoe maak je een issue aan" tot aan stap voor stap door één zo'n opdracht heen gaan. 

In eerste instantie wisten ze niet zo goed hoe er precies een breakdown van de layouts gemaakt moesten worden. Een student had het volgende geschetst op basis van de bronnen die ze had gelezen, maar had eigenlijk niet zo'n goed idee waarom ze dit had gedaan.
Ik heb toen geholpen met hoe je zo een layout beter kunt opdelen. Daarna had ik nog wat verteld over 'grid-template-areas' en uitgelegd hoe je met behulp van de breakdown de `grid-template-area` kunt invullen/koppelen.
2 studenten aan mijn tafel hadden moeite met de indeling van het grid, als in hoe zorg je dat elke element de juiste breedte/grootte krijgt? Ik heb toen uitleg gegeven over `1fr` en uitgetekend hoe fracties werken.


Ander voorbeeld:
layout met 2 kolommen, waarvan de 2e kolom 2x zo breed was als de 1e kolom.
student: 
```css
grid-template-areas: 
"nav main main";
grid-template-columns: 1fr 1fr 1fr;
```

Ik heb toen een tip gegeven dat het inprincipe klopt, maar dat het ook anders kan:
namelijk met 2 kolommen ipv 3. Ze hadden daarna gelijk door hoe ze dat konden aanpassen.

https://github.com/halima98/layout-in-css/issues/1
https://github.com/halima98/layout-in-css/issues/2

## woensdag 9 oktober
Vandaag was de 2e mentor sessie. Op de planning stond voor de 1e jaars de wrap-up met het schrijven van een readMe en het voorbereiden op de sprintreview.
Ik heb geholpen met de sprint review voorbereiden en issues ingeschoten met feedback op de readMe's van 1e jaarsstudenten.

ingeschoten issues:
* https://github.com/ambersr/the-client-website/issues/22
* https://github.com/kimnikitaschijf/the-client-website/issues/17
* https://github.com/DivaniNL/red-pers/issues/14

## vrijdag 18 oktober
Vandaag stond het volgende op de planning: een code / design review. Hiervoor moesten de 1e jaarsstudenten eerst nog even nadenken over 5 extra criteria's waar op gelet kan worden tijdens een accessibility review.
Hier heb ik ze bij geholpen, door vragen te stellen als je terugkijkt naar je WCAG audit wat zijn dan dingen die belangrijk zijn om mee te nemen?
Hier is het volgende lijstje van gemaakt:
* class names een duidelijk beschrijving meegeven
* outline/focus bij interactieve elementen 
* `ul` `ol` `menu` moeten een <li> bevatten
* aria label
* genoeg contrast tussen tekst en achtergrond

Vervolgens zijn zij bij elkaar een code/design review gaan doen en hebben zij deze punten meegenomen om op te controleren.
En ik heb erbij gezeten om vragen en onduidelijkheden te beantwoorden.

Als laatst ben ik met andere mentoren samen aan tafel gaan zitten en konden 1e jaarsstudenten naar ons toekomen om feedback te vragen op hun design en evt. code.

## maandag 11 nov 2024
Ik zat aan tafel met Julia, Viresh en Robin. Vandaag kregen de 1e jaars een sprintplanning en een workshop styleguide. Ze hebben eerst een nieuwe projectboard aangemaakt en de issues van de vorige repo overgezet naar de nieuwe, daarnaast hebben ze een sitemap en wireframe gemaakt. Ik heb hierbij feedback gegeven over het nummeren van de pagina’s in de sitemap en het netjes maken van de schetsen (nette lijnen, die niet uitlopen). Daarna hebben we gekeken naar de huisstijl van transavia en geanalyseerd welke uitingen transavia heeft en wat transavia herkenbaar maakt. Vervolgens zijn zij zelf aan de slag gegaan met het analyseren van de elementen van hun eigen website/huisstijl, zodat ze in het vervolg hiervan een styleguide kunnen maken.
Ik heb tussendoor nog een aantal korte vragen beantwoord over evt. onduidelijkheden hoe styleguides werken.


## woensdag 20 nov 2024 input types
Vandaag ging de les over formulieren, input types en hun attributes. De 1e jaarsstudenten moesten in een groepje onderzoek doen naar de verschillende <input> types. Daarna moest elke student 4 input types bouwen. Ik heb hierbij geprobeerd hun tips te geven, bijv. niet '<search>', maar input `type="search"`. Daar was namelijk wat verwarring over.


## vrijdag 29 nov 2024 connecting assignees
Vandaag stond de retrospect op de planning voor de 1e jaars. Zij moesten terugkijken naar de samenwerkkng binnen hun groepjes door een overzicht te maken van hun issues en welke daarvan zijn gesloten, welke nog open staan en wie de issue heeft opgelost. Vervolgens moesten ze als groep hierop reflecteren. Waar ging het goed, Waar ging het mis en wat kan volgende keer beter als groep. Hierbij heb ik ze begeleid.


## vrijdag 06 dec 2024 code / design review
Op de planning van de 1e jaars stond een code/design review. Ik zat aan tafel bij groepen 4 & 5. Zij mochten bij andere klasgenoten issues inschieten over de javascript en over het design qua feedback en feedforward op de interactieve element dat is gebouwd met javascript. Dit aan de hand van de volgende lijst: https://github.com/fdnd-task/fix-the-flow-interactive-website/blob/main/docs/code-design-review-programming-user-interaction.md
Ik heb hierbij feedback gegeven over hoe ze de issues duidelijker kunnen beschrijven.




