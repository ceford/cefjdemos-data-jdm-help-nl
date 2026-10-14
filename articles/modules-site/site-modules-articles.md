<!--
{
    "source": "https://docs.joomla.org/Help5.x:Site_Modules:_Articles",
    "title": "Modules: Artikelen",
    "description": " ",
    "author": ""
}
-->

## Beschrijving

De module **Artikelen** geeft een lijst met artikelen weer. Deze is bedoeld ter vervanging
van vijf andere artikelmodules:

* [Modules: Artikelen - Gearchiveerd](jdocmanual?article=help/modules-site/site-modules-articles-archived).
* [Modules: Artikelen - Categorie](jdocmanual?article=help/modules-site/site-modules-articles-category).
* [Modules: Artikelen - Meest recent](jdocmanual?article=help/modules-site/site-modules-articles-latest).
* [Modules: Artikelen - Meest gelezen](jdocmanual?article=help/modules-site/site-modules-articles-most-read).
* [Modules: Artikelen - Nieuwsflits](jdocmanual?article=help/modules-site/site-modules-articles-newsflash).

De opties van de module **Artikelen** worden voornamelijk geconfigureerd via vier tabbladen:

- Het tabblad *Filteropties* wordt gebruikt om op te geven welke artikelen worden weergegeven.
- Het tabblad *Weergaveopties* bepaalt hoe de artikelen in de module worden weergegeven en welke details worden opgenomen.
- Het tabblad *Sorteeropties* wordt gebruikt om de prioriteit van artikelen te configureren.
- Het tabblad *Groeperingsopties* wordt gebruikt om de prioriteit van artikelen te configureren.

**Belangrijk:** De module wordt alleen weergegeven wanneer er een of meer overeenkomende artikelen zijn om weer te geven. Als de module leeg is, wordt deze niet weergegeven.

### Algemene elementen

Sommige elementen van deze pagina worden behandeld in afzonderlijke Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het tabblad Modules: Modules](jdocmanual?article=help/modules/modules-module-tab).
* [Het tabblad Modules: Menutoewijzing](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Het tabblad Modules: Geavanceerd](jdocmanual?article=help/modules/modules-advanced-tab).
* [Het tabblad Rechten](jdocmanual?article=help/common-elements/edit-permissions).

## Toegang

- Selecteer **Inhoud → Sitemodules** of **Systeem → Beheerpaneel → Sitemodules**
  in het beheerdersmenu of **Sitepaneel → Modules** op het startdashboard.
  Vervolgens...
  - Een nieuwe module maken: selecteer de knop **Nieuw** op de werkbalk in de
    lijst *Modules*. Vervolgens...
     - Selecteer de module **Artikelen**.
  - Een bestaande module bewerken: zoek de module in de lijst met geïnstalleerde modules
    en selecteer de titellink in de kolom **Titel**.

## Schermafbeelding

![Formulier van de module Artikelen, tabblad Module](../../../nl/images/modules-site/site-modules-articles/01-module-tab.png)

## Formuliervelden

### Tabblad Module

#### Linkerpaneel

- **Modus**
  - *Normale modus* configureert de module om een statische lijst met artikelen weer te geven.
  - *Dynamische modus* configureert de module om te detecteren of deze een categorieweergave gebruikt en de lijst met artikelen binnen die categorie dienovereenkomstig weer te geven. Wanneer de dynamische modus is geselecteerd, kunt u de module het beste instellen op weergave op alle pagina's, omdat de module dynamisch bepaalt of er iets moet worden weergegeven.
- **Weer te geven artikelen** Het maximale aantal artikelen dat wordt weergegeven.
- **Type categoriefiltering** Geeft aan hoe artikelen worden gefilterd op basis van de categorieën die in het veld *Categorie* zijn opgegeven.
  - *Inclusief* Alleen artikelen met de opgegeven categorieën worden weergegeven.
  - *Exclusief* Artikelen met de opgegeven categorieën worden uitgesloten.
- **Categorie** Geeft artikelen met de geselecteerde categorieën weer of sluit deze uit. Dit werkt naast andere filterparameters.
- **Artikelen uit onderliggende categorieën** Alleen zichtbaar wanneer de parameter *Artikelen uitsluiten of opnemen* is ingesteld op *Opnemen*. Neemt artikelen op uit of sluit artikelen uit met categorieën die subcategorieën zijn van de categorieën die in het veld *Categorie* zijn opgegeven.
- **Categoriediepte** Alleen zichtbaar wanneer de parameter *Artikelen uit onderliggende categorieën* is ingesteld op *Opnemen*. Geeft aan hoeveel niveaus met subcategorieën worden gebruikt.
- **Artikelen uitsluiten of opnemen** Neemt specifieke artikelen op of sluit deze uit.
- **Op te nemen artikelen** Alleen zichtbaar wanneer de parameter *Artikelen uitsluiten of opnemen* is ingesteld op *Opnemen*. Als dit leeg is, worden alle artikelen opgenomen; anders worden alleen de geselecteerde artikelen opgenomen.
- **Huidig artikel uitsluiten** Alleen zichtbaar wanneer de parameter *Artikelen uitsluiten of opnemen* is ingesteld op *Uitsluiten*. Sluit het huidige artikel uit of neemt het op.
- **Uit te sluiten artikelen** Alleen zichtbaar wanneer de parameter *Artikelen uitsluiten of opnemen* is ingesteld op *Uitsluiten*. Geeft aan welke artikelen van de lijst moeten worden uitgesloten.

### Tabblad Weergaveopties

![Formuliertabblad van de module Artikelen](../../../nl/images/modules-site/site-modules-articles/02-display-options-tab.png)

- **Alleen titel (lijsten)** (*Ja/Nee*). Als *Ja* is ingesteld, bestaat de lijst met artikelen alleen uit de aan het artikel gekoppelde artikeltitels. Alle andere opties zijn verborgen.
- **Indeling**
  - *Verticaal* Artikelen worden in één verticale kolom weergegeven.
  - *Horizontaal* Artikelen worden weergegeven in maximaal 1–4 verticale kolommen, afhankelijk van de modulebreedte; de modulebreedte wordt bepaald door de modulepositie, paginalay-out, template, schermbreedte, browservensterbreedte en andere factoren.
- **Max. aantal kolommen** Deze optie verschijnt alleen wanneer Indeling is ingesteld op Horizontaal. Hiermee wordt het maximale aantal kolommen in een horizontale indeling opgegeven (*2–4*).
- **Artikeltitel** Toont of verbergt de artikeltitel.
- **Kopniveau** Deze optie verschijnt alleen wanneer *Artikeltitel* is ingesteld op *Tonen*. Hiermee wordt het HTML-kopniveau van de artikeltitel opgegeven (*h1–h5, geen*).
- **Titellink** Deze optie verschijnt alleen wanneer *Artikeltitel* is ingesteld op *Tonen*.
  - *Ja* De titel is een hyperlink naar het artikel.
  - *Nee* De titel is geen hyperlink naar het artikel.
- **Auteur** Toont of verbergt de auteur van het artikel.
- **Categorie** Toont of verbergt de categorie van het artikel.
- **Categorielink** Verschijnt alleen als *Categorie* wordt getoond.
  - *Tonen* Koppelt de categorietitel aan de categoriepagina.
  - *Verbergen* Toont de categorietitel, maar maakt er geen link van.
- **Datum** Toont of verbergt de datum van het artikel.
- **Datumveld** Deze optie verschijnt alleen wanneer *Datum* is ingesteld op *Tonen*. Hiermee wordt opgegeven welke artikeldatum wordt weergegeven: *Aanmaakdatum/ wijzigingsdatum/ startdatum publiceren*.
- **Datumindeling** Deze optie verschijnt alleen wanneer *Datum* is ingesteld op *Tonen*. Hiermee wordt de datumnotatie opgegeven, bijvoorbeeld Y-m-d H-i-s. Zie de [PHP-handleiding](https://www.php.net/manual/en/datetime.format.php) voor informatie over de opmaak.
- **Hits** Toont of verbergt het aantal keer dat het artikel is bekeken.
- **Indeling artikeldetails** Verschijnt alleen als een van de bovenstaande metagegevensvelden (*Auteur, Categorie, Datum* of *Hits*) wordt getoond. Hiermee wordt opgegeven hoe artikelmetadata wordt weergegeven:
  - *Meerdere regels* Elke parameter wordt op een eigen regel weergegeven.
  - *Eén regel* Parameters worden naast elkaar op één regel weergegeven. Afhankelijk van hun grootte en de modulebreedte kunnen ze doorlopen op een volgende regel.
- **Tags** Toont of verbergt de tags van een artikel.
- **Plug-inevenementen activeren** Stel dit in op *Ja* om aanvullende plug-inevenementen te activeren voor het weergeven van aanvullende inhoud, zoals aangepaste velden of steminformatie.
- **Introtekst** Toont of verbergt de introtekst van het artikel. De hoeveelheid weergegeven tekst wordt bepaald door de parameter *Limiet introtekst (tekens)*.
- **Limiet introtekst (tekens)** Deze optie verschijnt alleen wanneer *Introtekst* is ingesteld op *Tonen*. Hiermee wordt het aantal weergegeven inleidende tekens opgegeven. Als dit is ingesteld op 0, wordt de tekst van het volledige artikel weergegeven.
- **Artikelafbeeldingen tonen** Deze optie verschijnt alleen wanneer *Introtekst* is ingesteld op *Tonen* en *Limiet introtekst (tekens)* is ingesteld op nul (waardoor de volledige artikeltekst wordt weergegeven). Als dit is ingesteld op *Tonen*, worden de afbeeldingen van het artikel samen met de tekst weergegeven.
- **Intro-/volledige afbeelding tonen** Toont de introafbeelding, volledige afbeelding of geen afbeelding van het artikel boven de artikeltitel en -details.
- **Link "Lees meer"** Toont of verbergt een link "Lees meer" onder de artikeldetails.
- **Lees meer met titel** Deze optie verschijnt alleen wanneer de optie *Lees meer* is ingesteld op *Tonen*. Hiermee wordt de titel aan de link *Lees meer* toegevoegd.
- **Limiet Lees meer (tekens)** Deze optie verschijnt alleen wanneer de optie *Lees meer met titel* is ingesteld op *Tonen*. Hiermee wordt het maximale aantal tekens in de titel opgegeven dat in de link *Lees meer* wordt weergegeven.

### Tabblad Filteropties

![Formuliertabblad van de module Artikelen](../../../nl/images/modules-site/site-modules-articles/03-filtering-options-tab.png)

- **Uitgelichte artikelen**
  - *Tonen* Staat toe dat uitgelichte artikelen in de lijst worden weergegeven.
  - *Verbergen* Sluit uitgelichte artikelen uit van de lijst.
  - *Alleen* Toont alleen uitgelichte artikelen in de lijst.
- **Gearchiveerde artikelen** Geeft aan hoe gearchiveerde artikelen in de lijst worden weergegeven.
  - *Geen* Sluit gearchiveerde artikelen uit van de lijst.
  - *Alleen* Toont alleen gearchiveerde artikelen in de lijst.
- **Tags** Beperkt, indien opgegeven, de lijst tot artikelen die een of meer van de opgegeven tags hebben.
- **Type auteursfiltering** Filtert de lijst op auteur.
  - *Inclusief* Beperkt de lijst uitsluitend tot artikelen van de opgegeven auteurs.
  - *Exclusief* Sluit artikelen van de opgegeven auteur uit.
  - *Alleen van huidige gebruiker* Toont alleen artikelen waarvan de huidige gebruiker de auteur is.
- **Auteurs** Lijst met auteurs die moeten worden opgenomen of uitgesloten.
- **Type filtering op auteursalias** Filtert de lijst op auteursalias.
  - *Inclusief* Beperkt de lijst uitsluitend tot artikelen van de opgegeven auteursaliassen.
  - *Exclusief* Sluit artikelen van de opgegeven auteursaliassen uit.
- **Auteursaliassen** Lijst met auteursaliassen die moeten worden opgenomen of uitgesloten.
- **Datumfiltering** Geeft aan hoe artikelen op datum worden gefilterd.
  - *Uit* Geen datumfiltering.
  - *Datumbereik* Beperkt de lijst tot artikelen met datums binnen het opgegeven datumbereik.
  - *Relatieve datum* Beperkt de lijst tot artikelen die binnen een opgegeven aantal dagen vanaf de huidige datum vallen.
- **Veld voor datumbereik** Deze optie verschijnt alleen wanneer *Datumfiltering* is ingesteld op *Datumbereik* of *Relatieve datum*. Geeft aan welke artikeldatum moet worden gebruikt bij het filteren op datum (*Aanmaakdatum/Datum van wijziging/Startdatum publicatie*).
- **Begindatum van bereik** Deze optie verschijnt alleen wanneer *Datumfiltering* is ingesteld op *Datumbereik*. Hiermee worden de begin­datum en -tijd van het datumfilter opgegeven.
- **Tot en met datum** Deze optie verschijnt alleen wanneer *Datumfiltering* is ingesteld op *Datumbereik*. Hiermee worden de einddatum en -tijd van het datumfilter opgegeven.
- **Relatieve datum** Deze optie verschijnt alleen wanneer *Datumfiltering* is ingesteld op *Relatieve datum*. Hiermee wordt het aantal dagen ten opzichte van de huidige datum opgegeven dat in de artikellijst moet worden opgenomen.

### Tabblad Sorteeropties

![Formuliertabblad van de module Artikelen](../../../nl/images/modules-site/site-modules-articles/04-ordering-options-tab.png)

- **Artikelveld om op te sorteren**
  - *Artikelvolgorde* De volgorde waarin de artikelen handmatig worden gerangschikt in het beheerscherm *Inhoud > Artikelen*.
  - *Volgorde uitgelichte artikelen* De volgorde waarin uitgelichte artikelen worden gerangschikt in het beheerscherm *Inhoud > Uitgelichte artikelen*.
  - *Hits* Gesorteerd op het aantal paginaweergaven (hits).
  - *Titel* Gesorteerd op de titel van het artikel.
  - *ID* Gesorteerd op het ID-nummer van het artikel.
  - *Alias* De navigatiealias van het artikel.
  - *Aanmaakdatum/Datum van wijziging/Startdatum publicatie/Einddatum publicatie* Gesorteerd op de datum van het artikel.
  - *Willekeurig* Elke keer dat de pagina wordt geopend of vernieuwd, wordt een willekeurige volgorde gebruikt. *Sorteerrichting* wordt genegeerd.

### Tabblad Groeperingsopties

![Formuliertabblad van de module Artikelen](../../../nl/images/modules-site/site-modules-articles/05-grouping-options-tab.png)

Het *Veld voor datumgroepering* en de *Weergave-indeling voor maand en jaar* zijn alleen zichtbaar wanneer een datumgerelateerde groepering is geselecteerd.

- **Artikelgroepering**
  - *Geen* Geen groepering.
  - *Jaar* Geeft het jaar als kop weer.
  - *Maand en jaar* Geeft de maand en het jaar als kop weer.
  - *Auteur* Geeft *Auteursalias* of *Auteur* als kop weer.
  - *Categorie* Categorieën worden als koppen weergegeven.
  - *Tags* Tags worden als koppen weergegeven. Artikelen met meerdere tags worden onder meerdere koppen weergegeven.
- **Veld voor datumgroepering** Alleen weergegeven wanneer *Jaar* of *Maand en jaar* is geselecteerd. De artikeldatum waarop moet worden gegroepeerd (*Aanmaakdatum/Datum van wijziging/Startdatum publicatie*).
- **Weergave-indeling voor maand en jaar** Alleen weergegeven wanneer *Jaar* of *Maand en jaar* is geselecteerd. Hiermee wordt aangegeven hoe de kop voor de maand en het jaar moet worden weergegeven. Zie de [PHP-handleiding](https://www.php.net/manual/en/datetime.format.php) voor informatie over de opmaak.
- **Groeperingsrichting** Geeft aan hoe de groepskoppen moeten worden gesorteerd (*Oplopend/Aflopend*).

## Front-end-screenshot

*Afbeeldingen van de voorbeeldsite aan de front-end zijn verkregen met de Cassiopeia-template.*

Module Artikelen in de rechterzijbalk met alleen titels.

![Site-screenshot van module met alleen artikeltitels](../../../en/images/modules-site/site-modules-articles/06-site-titles.png)

Module Artikelen in de rechterzijbalk met titel, auteur en datum.

![Site-screenshot van module met artikeltitels, auteur en datum](../../../en/images/modules-site/site-modules-articles/07-title-author-date.png)

Module Artikelen op de hoofdlocatie bovenaan met inleidende tekst en afbeelding, en een knop *Meer lezen*.

![Site-screenshot van module op de bovenste locatie en Meer lezen](../../../en/images/modules-site/site-modules-articles/08-top-text-image-readmore.png)

Module Artikelen op de hoofdlocatie bovenaan, geconfigureerd voor een horizontale lay-out met inleidende tekst en afbeelding, en een knop *Meer lezen*.

![Site-screenshot van module met inleidende tekst, afbeelding en Meer lezen](../../../en/images/modules-site/site-modules-articles/09-text-image-readmore.png)

## Configuratievoorbeelden

De module Artikelen toont een lijst met artikelen in verschillende indelingen en lay-outs. De module is ontworpen met als doel één zeer configureerbare module te creëren die de beperkte functionaliteit van vijf afzonderlijke artikelenmodules kan vervangen. Deze sectie biedt eenvoudige voorbeelden van hoe de module voor elk van deze functies kan worden geconfigureerd.

## Artikelen - Gearchiveerd

De module *Artikelen - Gearchiveerd* toont een lijst met koppen voor maanden en jaren waarin gearchiveerde artikelen staan. De kop is een koppeling naar de weergave van gearchiveerde artikelen, waarin de afzonderlijke artikelen worden weergegeven. De module *Artikelen* kan worden geconfigureerd om een vergelijkbaar resultaat te bereiken.

**Configuratie-instellingen**

| Tabblad           | Parameter          | Instelling |
|-------------------|--------------------|---------|
| Weergaveopties   | Alleen titel (lijsten) | Ja     |
| Filteropties | Gearchiveerde artikelen  | Alleen    |
| Groeperingsopties  | Artikelen groeperen   | Maand en jaar |
| Groeperingsopties  | Weergave-indeling maand en jaar | F, Y |

![Vergelijking van gearchiveerde artikelen met beide methoden](../../../en/images/modules-site/site-modules-articles/10-config-archived.png)

<big>*Opmerkingen*</big>

De module *Artikelen - Gearchiveerd* toont één koppeling naar een pagina met gearchiveerde artikelen waarop de lijst met gearchiveerde artikelen wordt weergegeven, samen met de mogelijkheid om de archiefdatum aan te passen. De module *Artikelen* toont de lijst met artikelen rechtstreeks—groeperen op maand en jaar is optioneel. De lijst kan nauwkeurig worden gefilterd met behulp van de vele verschillende beschikbare besturingselementen en er is een groot aantal weergaveopties beschikbaar om aanvullende artikelgegevens weer te geven. 

## Artikelen - Categorie

De module *Artikelen - Categorie* toont een lijst met koppelingen naar artikelen binnen een opgegeven categorie.

**Configuratie-instellingen**

| Tabblad             | Parameter          | Instelling |
|-----------------|--------------------|----|
| Module          | Categorie           | [geef de gewenste categorie en subcategorieën op]|
| Weergaveopties | Alleen titel (lijsten) | Ja |

![Vergelijking van artikelen per categorie met beide methoden](../../../en/images/modules-site/site-modules-articles/11-config-category.png)

## Artikelen - Nieuwste

De module *Artikelen - Nieuwste* toont een lijst met koppelingen naar de meest recente artikelen.

**Configuratie-instellingen**

| Tabblad              | Parameter          | Instelling |
|------------------|--------------------|----|
| Weergaveopties  | Alleen titel (lijsten) | Ja |
| Sorteeropties | Artikelveld om op te sorteren | Startdatum publicatie|
| Sorteeropties | Sorteerrichting | Aflopend |

![Vergelijking van de nieuwste artikelen met beide methoden](../../../en/images/modules-site/site-modules-articles/12-config-latest.png)

<big>*Opmerkingen*</big>

De module *Artikelen* biedt niet de sortering *Touched* die in de module *Artikelen - Nieuwste* te vinden is, maar beschikt wel over een aantal sorteeropties die niet in de module *Artikelen - Nieuwste* te vinden zijn. 

## Artikelen - Meest gelezen

De module *Artikelen - Meest gelezen* toont een lijst met koppelingen naar artikelen met de meeste hits.

**Configuratie-instellingen**

| Tabblad              | Parameter          | Instelling |
|------------------|--------------------|----|
| Weergaveopties  | Alleen titel (lijsten) | Ja |
| Sorteeropties | Artikelveld om op te sorteren | Hits |
| Sorteeropties | Sorteerrichting | Aflopend |

![Vergelijking van de meest gelezen artikelen met beide methoden](../../../en/images/modules-site/site-modules-articles/13-config-most-read.png)

## Artikelen - Nieuwsflits

De module *Artikelen - Nieuwsflits* toont de tekst van een of meer artikelen. Standaard wordt alleen de artikeltekst weergegeven; de module kan echter zo worden geconfigureerd dat ook de titel, afbeeldingen, links voor meer lezen en meer worden weergegeven. Hier is de module geconfigureerd om de titel en tekst van meerdere artikelen weer te geven. In dit voorbeeld is de module *Artikelen* geconfigureerd om dit basisgedrag te repliceren.

**Configuratie-instellingen**

| Tabblad           | Parameter          | Instelling |
|------------------|--------------------|----|
| Sorteeropties | Artikelveld om op te sorteren | Startdatum publiceren |
| Sorteeropties | Sorteerrichting | Aflopend |
| Weergaveopties  | Alleen titel (lijsten) | Nee |
| Weergaveopties  | Titelkoppeling         | Nee |
| Weergaveopties  | Introductietekst          | Tonen |
| Weergaveopties  | Limiet introductietekst (tekens) | 0 (voor onbeperkte tekst) |

![Vergelijking van nieuwsflitsen van artikelen met behulp van elke methode](../../../en/images/modules-site/site-modules-articles/14-config-news-flash.png)

*Vertaald door openai.com*