# Procesverslag
Markdown is een simpele manier om HTML te schrijven.  
Markdown cheat cheet: [Hulp bij het schrijven van Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Nb. De standaardstructuur en de spartaanse opmaak van de README.md zijn helemaal prima. Het gaat om de inhoud van je procesverslag. Besteedt de tijd voor pracht en praal aan je website.

Nb. Door *open* toe te voegen aan een *details* element kun je deze standaard open zetten. Fijn om dat steeds voor de relevante stuk(ken) te doen.





## Jij

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Auteur:
  Naimah sambo

  #### Je startniveau:
  Ik zit op de blauwe pieste maar vind vormgeven van een website enorm leuk. Als ik maar iets kan doen qua vormgeving vindt ik het process al fijner.

  #### Je focus:
  
 Ik denk toch responsive en service laag. Als ik goed begrijp wat met service laag bedoelt wordt is het de vormgeving en de look van de website. Dat vindt ik belangrijk.
</details>





## Je website

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Je opdracht:
  https://www.starbucks.com

  #### Screenshot(s) van de eerste pagina (small screen): 
  hier de naam van de pagina  
  <img src="readme-images/screenshot-mainpagina.png" alt="omschrijving van de pagina">

  #### Screenshot(s) van de tweede pagina (small screen):
  hier de naam van de pagina  
  <img src="readme-images/screenshot-ourcoffees.png" alt="omschrijving van de pagina">
 
</details>



## Toegankelijkheidstest 1/2 (week 1)

<details>
  <summary>uitwerken na test in 2<sup>e</sup> werkgroep</summary>

  ### Bevindingen screenreader
  Lijst met je bevindingen die in de test naar voren kwamen:
  -Headings worden goed gelezen door de screenreader.
  -Links moeten betere namen krijgen vooral op de home pagina, er staat nu bijvoorbeeld een button met "zie meer" maar van wat?

   ### Bevindingen WCAG
  Lijst met je bevindingen die in de test naar voren kwamen:

  -Content: op de homepagina zijn de buttons en links niet uniek.

  -Global code: Enorm veel errors in HTML, en geen duidelijke titles per pagina. De taal veranderd wel mee met de pagina:
  <img src="readme-images/globalcode-screenshot1.png" alt="Kiest voor EN ende taalveranderd mee">
  <img src="readme-images/globalcode-screenshot2.png" alt="Kiest voor NL ende taalveranderd mee">

  -Keyboard: Het is niet duidelijk genoeg waar de focus op staat door kleur contrast:<img src="readme-images/Keyboard-screenshot1.png" alt="Geselecteerde button met weinig contrast">

  -Mobile and touch: De website is extreem goed voor mobiel gebruik, en gebruikt grote duidelijke knoppen met genoeg afstand: 
  <img src="readme-images/mobile-and-touch-screenshot1.png" alt="mobile screen met een grote knop en witruimte">

  -Headings: De website maakt gebruik van headings in een duidelijke volgordere, volgends de regels en zonder een heading level te skippen.

  -Lists: De website maakt regelmatig gebruik van list items.

  -Images: Er zijn geen images zonder doel op deze website, maar maakt wel gebruikt van een alt bij img's. Alleen klopt deze alt niet altijd zoals bij het plaatje van de redvelvet latte waar "holliday campain" staat: 
  <img src="readme-images/images-screenshot1.png" alt="Geselecteerd plaatje van redvelvet latte">

  -Media: De website heeft geen Videos of audios.

  -Controls: Er wordt vrijwel altijd gebruik gebruik gemaakt van een a element bij een link, deze zijn dan ook te herkennen als link. Er wordt zelden gebruik gemaakt van een button element voor een button dit gebruikt maar bij één button op de homepagina: 
  <img src="readme-images/controls-screenshot1.png" alt="Button op de website wordt aangegeven als button"> <img src="readme-images/controls-screenshot2.png" alt="Button op de website wordt niet aangegeven als button">

  De links openen dan ook niet op een ander tablat.
  -Appearance: Darkmode wordt niet gesupport op de website. Ook kan de text niet groter dan het standaard formaat.

  -Animation: Er zijn bijna geen animations op de website, alleen kleine subtiele dingen zoals het uitklappen van het hamburger menu wat geleidelijk gaat. 

  -Color contrast: Er is een duidelijk verschil tussen achtergrond en tekst op de website, op een donkere achtergrond wordt bijvoorbeeld gebruik gemaakt van witte tekst en andersom:
hfbbhjebhjbrbfhjbef

  <img src="readme-images/colorcontrast-screenshot1.png" alt="Witte button groene achtergrond"> <img src="readme-images/colorcontrast-screenshot2.png" alt="Groene button op een witte achtergrond">






</details>



## Breakdownschets (week 1)

<details>
  <summary>uitwerken na afloop 3<sup>e</sup> werkgroep</summary>

  ### de hele pagina: 
  <img src="/readme-images/screenshot-breakdownschets.png" width="375px" alt="breakdown van de hele pagina">

  ### dynamisch deel (bijv menu): 
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="breakdown van een dynamisch deel">

  ### wellicht nog een dynamisch deel (bijv filter): 
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="breakdown van nog een dynamisch deel">

</details>





## Voortgang 1 (week 2)

<details>
  <summary>uitwerken voor 1<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  Tijdens het maken van de opzet van mijn website gingen er veel dingen goed: het werken met flexbox, omdat nog vers in mijn geheugen zat. Het stylen van de header ging ook erg goed.
  
  <img src="/readme-images/screenshot-header-voortgang1.png" width="375px" alt="screenshot header"> 
  
  En het werken met de :root (het kleuren pallet) ging ook heel goed
  
  <img src="/readme-images/screenshot-root-voortgang1.png" width="375px" alt="screenshot root">

  Wat minder goed ging is het verplaatsen van de elementen van de zijkant af.
  
  <img src="/readme-images/screenshot-section2-voortgang1.png" width="375px" alt="screenshot section 2">

  Ook vond ik het lastig om te werken met grid. Het omdraaien van de elementen in de sections vond ik enorm lastig ik heb er uiteindelijk wel iets voor gevonden.

  <img src="/readme-images/screenshot-omdraaien-elementen-voortgang1.png" width="375px" alt="screenshot code">


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    |
  | ---            | ---                | ---         |
  | dit bespreken  | en dit             | - HTML en CSS checken.   
  | en dat ook nog | dit als er tijd is | - Uitleg over de ruimte tussen elementen
  | ...            | ...                | - Uitleg over wanneer grid of flexbox 
  gebruiken op mijn website.            | - Uitleg over een fixed A met responsiveness 


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
  - ...

</details>





## Voortgang 2 (week 3)

<details>
  <summary>uitwerken voor 2<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
- ...

</details>





## Toegankelijkheidstest 2/2 (week 4)

<details>
  <summary>uitwerken na test in 9<sup>e</sup> werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen (geef ook aan wat er verbeterd is):

</details>





## Voortgang 3 (week 4)

<details>
  <summary>uitwerken voor 3<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
  - ...

</details>





## Eindgesprek (week 5)

<details>
  <summary>uitwerken voor eindgesprek</summary>

  ### Je uitkomst - karakteristiek screenshots:
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="uitomst opdracht 1">


  ### Dit ging goed/Heb ik geleerd: 
  Korte omschrijving met plaatjes

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="top">


  ### Dit was lastig/Is niet gelukt:
  Korte omschrijving met plaatjes

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="bummer">
</details>





## Bronnenlijst

<details open>
  <summary>continu bijhouden terwijl je werkt</summary>

  Nb. Wees specifiek ('css-tricks' als bron is bijv. niet specifiek genoeg). 
  Nb. ChatGpT en andere AI horen er ook bij.
  Nb. Vermeld de bronnen ook in je code.

  1. bron 1
  2. bron 2
  3. ...

</details>