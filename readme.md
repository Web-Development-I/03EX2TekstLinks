# Gevorderde oefeningen Les 3<br>Hoofdstuk 03 & 04 - Tekst markeren & Koppelingen maken

## Oefening 1
Pas de pagina oefening01.html aan volgens de volgende specificaties
 - de taal van de pagina is Nederlands
 - de titel van de pagina is Oefening01
 - de eerste twee elementen van de body vormen de header
 - elke daaropvolgende h2- en p-element vormen telkens een section
 - alle secties samen vormen de main
 - de adresgegevens moeten in de footer komen
 - breng een markering aan rond de adresgegevens zodat het duidelijk wordt dat dit een adres betreft en maak gebruik van \<br> om aparte regels te vormen voor de adresgegevens en voeg een speciaal teken in voor het telefoontje.

![oefening01.PNG](docs/images/oefening01.PNG 'oefening01')
<br><br>

## Oefening 2
 Maak gebruik van het **cite**-element, het **q**-element, het **blockquote**-element en eventueel het **attribuut cite** om de tekst in de pagina oefening02.html te markeren. Enkele tips:
 - gebruik het cite-element om een verwijzing naar een artikel of een werk te markeren in de eerste paragraaf
 - gebruik het blockqoute-element om een langere quote te markeren die in een apart blok komt.
   - de langere quote op deze pagina komt van https://www.hogent.be/opleidingen/bachelors/toegepaste-informatica/online-campus/, neem dit op in het cite-attribuut
- gebruik het q-element om in-line een kortere quote te markeren

![oefening02.PNG](docs/images/oefening02.PNG 'oefening02')
<br><br>

## Oefening 3
 Open de pagina oefening03.html. Plaats onder de kop een figure met een figcaption om het onderstaande te bekomen.<br>
Tips:
 - maak gebruik van het **pre**-element om het stukje css *(van body { t.e.m. })* exact te plaatsen zoals op het voorbeeld
 - geef via semantische markering aan dat het stukje css een stukje **code** is
- maak gebruik van het **figcaption**-element om het onderschrift *(Instellen van ... de pagina)* toe te voegen die bij het stukje css hoort

![oefening03.PNG](docs/images/oefening03.PNG 'oefening03')
<br><br>

## Oefening 4
Open pagina oefening04.html. De pagina bevat een thumbnail afbeelding. Pas de pagina als volgt aan
- wanneer op de thumbnail geklikt wordt dan opent de grote foto _elephants.png_ in een apart venster
- wanneer op 'download picture' wordt geklikt dan wordt de grote foto gedownload
- voeg aan de **<head>** sectie van de pagina een **link**-element toe zodat de grote afbeelding ge-**preload** wordt
  - _merk op dat een link van het type preload nog niet in elke browser wordt ondersteund; bekijk de tabel op [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content#Browser_compatibility) om te zien welke browsers ondersteuning bieden_ 
- stel de icon _favicon.ico_ uit de map images in als **favicon**
