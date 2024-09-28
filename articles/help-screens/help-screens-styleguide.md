<!-- Filename: Help4.x:Help_screens_styleguide  / Display title: Stijlgids Helpschermen -->

<div class="alert alert-warning">
Deze stijlgids is voor de Joomla MediaWiki-installatie (docs.joomla.org).
</div>

Dit is een lopend project en dient als richtlijn voor het maken van
helpschermen voor **Joomla 3.x**. De helpschermen die zich op de Joomla! Docs Wiki bevinden, worden benaderd door elke Joomla! installatie die het standaard helpsysteem gebruikt. Door deze stijlgids te volgen, kan het Joomla! Project consistentie bieden door alle helpschermen, wat zorgt voor eenvoudigere navigatie.

Als je een vraag hebt, kun je deze stellen op de bijbehorende overlegpagina van het helpscherm door op het tabblad ***Overleg*** bovenaan de pagina van het helpscherm te klikken.

## Helpscherm Pagina-indeling

### Beschrijving

Elk helpscherm dient een sectie "**Beschrijving**" te hebben. Deze sectie gaat dieper in op wat het scherm doet en wordt gebruikt in helpschermtabellen door deze hele wiki. <a
href="https://docs.joomla.org/Menu_Management#Menu_Management_Help_Screens"
class="mw-redirect" title="Menu Management">Hier is een gebruiksvoorbeeld</a>.

Er is geen specifiek format voor deze sectie omdat de beschrijving direct in correlatie moet staan met het doel en de functionaliteit van het scherm. Er kunnen subsecties in de beschrijving zijn die meer specifieke details beschrijven. Probeer de beschrijving kort en bondig te houden; als de beschrijving lang is, overweeg dan om opsommingstekens te gebruiken om deze samen te vatten.

## Hoe te Toegang te Verkrijgen

Elke hulpscherm moet een sectie **Hoe te Toegang te Verkrijgen** hebben
die de stappen geeft die nodig zijn om het scherm te bereiken dat wordt
beschreven. Dit kan overbodig lijken omdat een gebruiker op het
administrator scherm moet zijn om het hulpscherm te hebben opgevraagd.
Onthoud dat de hulpschermen op verschillende manieren kunnen worden
opgevraagd. Bijvoorbeeld, iemand die een zoekmachine gebruikt om uit te
vinden hoe iets te doen, kan op een hulpscherm op de wiki stuiten zonder
ooit het helpsysteem te hebben benaderd.

#### Notities:

- Als de manier om het scherm te bereiken vanaf een ander scherm is, 
  moet de naam van dat scherm een link naar zijn hulpscherm zijn.
- Je "klikt" op knoppen, inclusief werkbalkknoppen, maar je "selecteert"
  menu-items. Consistente terminologie helpt gebruikers hierbij.
- Voor het gemak van rendering de rechtersymbool (→), **Dit
  wijzend → naar dat**.

### Screenshot

Screenshot dat de algemene weergave van het scherm laat zien.

#### Notities:

- Screenshotafbeeldingen kunnen elke breedte hebben, maar grotere 
  afbeeldingen moeten \|800px in de bron hebben toegevoegd.
- De bestandsnaam moet onze
  <a href="https://docs.joomla.org/JDOC:Image_naming_convention"
  class="mw-redirect" title="JDOC:Afbeelding naamgevingsconventie">standaard naamgevingsconventies</a>
  volgen voor hulpschermen.
  **Help-3x-***\<menusysteem-pad-in-kleine-letters-gescheiden-door-streepjes\>***-scherm-nl.png**.
  Bijvoorbeeld, een screenshot van het Artikel Beheer scherm zou zijn
  **\[\[Bestand:Help-3x--content-article-manager-screen-nl.png\]\]**.
- De bestandsnaam moet altijd een taalcode aan het einde van de naam hebben,
  voor Nederlands wordt -nl toegevoegd.
- Je kunt zowel .png- als .jpg-bestanden gebruiken.

## Formulieren (per tabblad)

### Tabblad Details

Deze sectie moet alleen worden opgenomen op helpschermen die schermen beschrijven die een formulier bevatten. Dit omvat alle toevoegen/bewerken schermen, maar omvat ook schermen zoals Site Globale Configuratie en modale pop-ups zoals <a href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options" title="Help4.x:Components Article Manager Options">Help4.x:Componenten Artikelenbeheer Opties</a>.

### Andere typen tabbladen

Als velden zijn gegroepeerd in fieldsets of tabbladen, groepeer dan de velden onder sub-kopjes.

### Kolomkoppen

Deze sectie moet alleen worden opgenomen op helpschermen die back-end beheerschermen beschrijven; dat wil zeggen, waar een lijst met items wordt weergegeven. Deze sectie moet elke kolom van de lijst beschrijven.

### Lijst Filters

Deze sectie moet alleen worden opgenomen op helpschermen die back-end beheerschermen beschrijven; dat wil zeggen, waar een lijst met items wordt weergegeven. Deze sectie moet beschrijven hoe de lijstfilters te gebruiken om de inhoud van het scherm te filteren. Zie <a href="https://docs.joomla.org/Screen.content.15#List_Filters" title="Screen.content.15">Screen.content.15#List_Filters</a> voor een voorbeeld uit 1.5.

### Opties

Deze sectie moet alleen worden opgenomen op helpschermen waar het scherm een Opties werkbalkknop heeft die een modaal opties subscreen opent. Als er veel opties zijn en het helpscherm zou overdreven lang worden als ze hier zouden worden beschreven, dan moeten ze linken naar een apart helpscherm met een "\_Opties" achtervoegsel. Zie bijvoorbeeld <a href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options" title="Help4.x:Components Article Manager Options">Componenten Artikelenbeheer Opties</a>.

Aangezien het Opties modale scherm meestal getabbeld is, moet je een subsectie onder deze sectie toevoegen voor elk tabblad. Bijvoorbeeld, als er een tabblad "Bewerk lay-out" is, voeg dan een derde-niveau kop van die naam toe en binnen die subsectie beschrijf je elk van de beschikbare velden. Begin elke subsectie met een screenshot van het juiste Opties paneel.

### Werkbalk

Uiteraard moet deze sectie alleen worden opgenomen op helpschermen waar een werkbalk aanwezig is.

Beschrijft de beschikbare knoppen en hun bijbehorende functies. Gebruik hier **chunks** omdat veel hetzelfde zullen zijn voor verschillende schermen. Het is het beste om een afbeelding van de werkbalk te verstrekken.

Het eerste woord moet altijd een werkwoord zijn en, tenzij het een onregelmatig werkwoord is, moet het ook eindigen op de letter "t". Dit betekent dat je de beschrijving moet structureren alsof je het woord "dit" als onderwerp gebruikt, maar het onderwerp uit de zin houdt. Dit maakt de zin eigenlijk een zinsfragment. Bijvoorbeeld:

- In plaats van "Klik op deze knop om begraven schatten te vinden."
  - Zeg, "Vindt begraven schatten."
- In plaats van "Je kunt op deze knop klikken om een afbeelding van John Stamos in het huidige document in te voegen."
  - Zeg, "Voegt een afbeelding van John Stamos in."
- In plaats van "Informeer jezelf dat een afbeelding van John Stamos hetzelfde is als een begraven schat."
  - Zeg, "Informeert je dat een afbeelding van John Stamos hetzelfde is als een begraven schat."

Aangezien veel werkbalken hetzelfde zijn op meerdere schermen, is de bestandsnaamconventie voor werkbalken gericht op het gemakkelijk hergebruiken van werkbalkafbeeldingen waar mogelijk. Werkbalk afbeeldingen moeten deze naamconventie volgen: Help\<versie\>-Werkbalk-\<iconenlijst\>.png waar \<iconenlijst\> een '-' gescheiden lijst van de werkbaknamen is. Elk woord moet met een hoofdletter, spaties en '&' verwijderd. Bijvoorbeeld: Help30-Werkbalk-Nieuw-Bewerken-Verwijderen-Opties-Help.png

### Batchverwerking

Deze sectie moet alleen worden opgenomen op helpschermen waar het scherm een batchverwerkingsfunctie heeft. Zie bijvoorbeeld <a href="https://docs.joomla.org/Help4.x:Components_Banners_Categories" title="Help4.x:Components Banners Categories">Componenten Banners Categorieën</a>.

### Tips

Zoals de naam al doet vermoeden, moet deze sectie tips, hints en suggesties bevatten die een gebruiker kunnen helpen bij het uitvoeren van taken met betrekking tot het scherm.

*Vertaald door openai.com*

