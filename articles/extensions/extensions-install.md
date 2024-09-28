<!-- Filename: Help4.x:Extensions:_Install  / Display title: Extensies: Installeren -->

## Beschrijving

Extensies worden gebruikt om functionaliteiten aan Joomla! toe te voegen die niet aanwezig zijn in de standaard installatie. Honderden extensies zijn beschikbaar voor Joomla!, en er worden voortdurend meer ontwikkeld.

Extensies zijn onderverdeeld in vijf typen, als volgt:

- Een *Component* is een mini-applicatie die het hoofdgedeelte van de pagina weergeeft. Voorbeelden van Componenten zijn Contacten, de Voorpagina en Nieuwsfeeds.
- Een *Module* is een kleinere Extensie die doorgaans wordt gebruikt voor het weergeven van een klein element dat op meerdere pagina's wordt getoond. Voorbeelden van Modules zijn Menu's en Gerelateerde Items.
- Een *Plugin* is een stuk code dat wordt uitgevoerd wanneer een vooraf gedefinieerde gebeurtenis binnen Joomla! plaatsvindt. Bijvoorbeeld, editors zijn Plugins die worden uitgevoerd wanneer een bewerksessie wordt geopend.
- De *Taal*-extensie maakt het mogelijk om de Front-end en Back-end van Joomla! weer te geven in elke taal waarvoor een taalextensie bestaat. Op deze manier kan Joomla! in een nieuwe taal worden uitgebracht zonder wijzigingen in het kernprogramma.
- Een *Sjabloon* bepaalt de manier waarop de inhoud van een website wordt weergegeven, inclusief de locatie en indeling van elementen, kleuren, lettertypen, enzovoort. Sjablonen zorgen ervoor dat het uiterlijk van de website gescheiden is van de inhoud.

### Gemeenschappelijke Elementen

Sommige elementen van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).

## Hoe te Toegang

- Selecteer **Systeem → Installeren Paneel → Extensies** vanuit het
  Administrator menu.

Er zijn vier installatiemethoden beschikbaar. Als **Installeren vanuit Web** eerst in de lijst is gezet of de laatst geselecteerde methode was, zal er een kleine vertraging zijn terwijl Joomla een eerste selectie van Extensie gegevens downloadt van de Joomla Extensiedirectory.

De normale Tab-volgorde voor de installatiemethoden is als volgt:

* Upload Pakketbestand
* Installeren vanuit Map
* Installeren vanuit URL
* Installeren vanuit Web

Er is slechts één methode nodig om een gegeven Extensie te installeren. De normale procedure voor het installeren van een Joomla! Extensie is als volgt:

1.  Download een of meer archiefbestanden (normaliter ".zip" of "tar.gz" 
    formaat) van de website van de Extensie aanbieder naar een lokale directory
    op je computer. Let op dat sommige Extensies als één bestand worden geïnstalleerd 
    (bijvoorbeeld, één Component of Module) terwijl andere Extensies mogelijk 
    twee of meer bestanden hebben (bijvoorbeeld een Component en een Module). 
    Als er twee of meer onderdelen zijn, kan elk zijn eigen archiefbestand 
    hebben. Of de onderdelen kunnen zijn gecombineerd in een pakketbestand.
2.  Kies een van de beschreven methoden om de extensie te installeren.
3.  Wanneer het klaar is, zal het scherm een **Succes** of **Mislukt** 
    bericht tonen.
4.  Afhankelijk van de Extensie, kan het nodig zijn om de Extensie in te 
    schakelen (bijvoorbeeld, in de Modules of Plug-ins lijsten).

## Upload Pakketbestand Tab

![Extensie-installatie upload pakketbestand tab](../../../nl/images/extensions/install-upload-package-file.png)

- Sleep en plaats of blader naar de locatie waar je het archiefbestand
  van de extensie hebt gedownload.

De upload begint automatisch. Let op de **Maximale uploadgrootte: 32,00 MB**
die voor jouw installatie is gedefinieerd. Als je deze waarde niet kunt verhogen, kun je *Installeren vanuit map* gebruiken.

## Installeren vanaf Map Tab

![Extensie installeren vanaf map tab](../../../nl/images/extensions/install-from-folder.png)

1.  Maak een tijdelijke map aan op je lokale harde schijf en pak het
    archiefbestand van de extensie uit in deze tijdelijke map.
2.  Gebruik FTP om de inhoud van deze map (inclusief bestanden
    en submappen) te uploaden naar een map op je server.
3.  Specificeer in het veld *Installatiemap* de servermap waar
    je de bestanden en submappen van het pakket hebt geüpload.
4.  Klik op de knop *Controleren en Installeren* en Joomla! zal de
    inhoud van de opgegeven map installeren.

Merk op dat het gebruikelijk is om de map met je uitgepakte extensie in de tmp-map van je Joomla-site te plaatsen.

## Installeren vanaf URL Tabblad

![Extensie installeren vanaf URL tabblad](../../../nl/images/extensions/install-from-url.png)

In plaats van het archiefbestand naar je lokale computer te downloaden, kun je gewoon de URL van het doelarchiefbestand opgeven. Klik vervolgens op de knop "Controleren en Installeren" en Joomla! installeert het automatisch direct vanaf deze URL. *Let op dat je met deze methode geen kopie van het archiefbestand op je lokale computer hebt.*

## Installeren vanuit het Webtabblad

Om een extensie direct vanuit de Joomla Extension Directory (JED) te installeren. Je kunt extensies selecteren om weer te geven per Categorie of je kunt zoeken op een gedeeltelijke naam.

![Extensie installeren vanuit het webtabblad](../../../nl/images/extensions/install-from-web.png)

## Tips

- Vier alternatieve installatiemethoden zijn beschikbaar, zoals hierboven aangegeven. De meest gebruikelijke methode is de "Upload Pakketbestand" methode.
- Als je een externe Module of Plugin wilt installeren die bij een Component hoort, moet je over het algemeen zowel de Component als de Module of Plugin installeren om de Module of Plugin te kunnen gebruiken. Dit wordt meestal gedocumenteerd in de installatie-instructies van de Extensie op de website van de auteur.
- Evenzo, als je een externe Component deïnstalleert die ook zijn eigen Modules of Plugins heeft, kunnen deze Modules en Plugins niet langer worden gebruikt. Daarom wordt het normaal gesproken aanbevolen om deze afhankelijke Modules en Plugins ook te deïnstalleren.
- Sommige Componenten die door externe ontwikkelaars zijn ontwikkeld, kunnen hun eigen Modules of Plugins in de installer hebben inbegrepen. Zorg er in dit geval voor dat deze Module- of Plugindirectory's schrijfbaar zijn. Anders zal de Extensie niet goed werken.
- **VEILIGHEIDSWAARSCHUWING:** Het wordt aanbevolen dat je alleen die externe Extensies op je site gebruikt die je echt nodig hebt. Gebruik je live site niet voor testdoeleinden omdat dit je site en server in gevaar kan brengen. Test nieuwe extensies op een lokale testsite voordat je ze op je live site implementeert.
- Installeer geen Joomla! Extensies die zijn gedownload van [Warez](https://en.wikipedia.org/wiki/Warez) sites omdat ze mogelijk zijn geïnfecteerd met een virus of malware die schade aan de server veroorzaken en de computer van je bezoekers kunnen besmetten!
- Installeren vanaf een externe URL kan gevaarlijk zijn. Om deze reden wordt het over het algemeen aanbevolen om de opties "Installeren vanuit Web", "Upload Pakketbestand" of "Installeren vanuit Map" te gebruiken bij het installeren van nieuwe Extensies.

*Vertaald door openai.com*

