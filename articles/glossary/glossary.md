<!-- Filename: Help4.x:Glossary  / Display title: Woordenlijst -->

De Joomla! Woordenlijst is nuttig voor het uitleggen van veelvoorkomende termen die worden gebruikt in Joomla! tutorials, helpschermen en geavanceerde documentatie.

## Toegangslijst

## Alias

## Anker

Een anker wordt gemaakt met behulp van de `<a>` tag in HTML. Een anker stelt je in staat om een bladwijzer binnen een HTML-pagina te plaatsen. In Joomla! kun je een anker in een artikel plaatsen (bijvoorbeeld met de TinyMCE-editor). Hierdoor kun je een link maken die direct naar dat punt in het artikel gaat.

De HTML-broncode voor een anker ziet er als volgt uit:

    <a name="my_anchor" title="My Anchor"></a>

Je kunt naar een anker binnen dezelfde pagina linken met behulp van de HTML-code

    <a href="#my_anchor" ></a>

Als je op die link klikt, word je rechtstreeks naar de locatie van de ankertag geleid.

Je kunt naar een anker op een andere pagina linken door "#" plus de ankernaam toe te voegen aan het einde van de URL. In het bovenstaande voorbeeld, als de URL voor het artikel `http://www.mysite.com/my_article.html` was, zou je rechtstreeks naar het anker op die pagina kunnen linken met de URL `http://www.mysite.com/my_article.html#my_anchor`.

## Artikel

## Cascading Style Sheet (CSS)

Een Cascading Style Sheet of CSS wordt gebruikt om de presentatie van
een XHTML-pagina te regelen. Bijvoorbeeld, een CSS-bestand bepaalt vaak
het lettertype, de marges, de kleur, achtergrondafbeeldingen en andere
aspecten van het uiterlijk van een webpagina. CSS maakt het mogelijk om
de inhoud van een XHTML-pagina te scheiden van het uiterlijk. In Joomla! 
zijn CSS-bestanden (bijvoorbeeld template.css) normaal gesproken onderdeel van de template.

**Zie ook:** Template, Pagina Klasse Suffix, Module Klasse Suffix

## Categorie

Elke Joomla! aangedreven website of elk type CMS-website heeft een methode nodig om de inhoud logisch weer te geven en op te slaan. De gebruikelijke methode is door middel van categorieën en subcategorieën. Joomla! biedt meerdere manieren om inhoud te weergeven en te gebruiken, gecontroleerd door categorisatie. Enkele inhoudstypen die categorisatie hebben, zijn Artikelen (de belangrijkste inhoud van webpagina's), Banners en Contacten.

Een categorie genaamd *Niet-gecategoriseerd* is de standaardcategorie die aan de meeste inhoudstypen wordt toegewezen. De categorie *Niet-gecategoriseerd* is niet beschrijvend en moet naar behoefte worden gebruikt voor inhoudstypen die niet onder een specifieke categorie vallen.

Bij het maken en toewijzen van categorieën, moet je een geplande structuur hebben. Als voorbeeld, dit is een manier om verschillende artikelen over vogels te categoriseren: 

- Maak twee hoofdcategorieën voor artikelen genaamd *Dieren* en *Planten*.
- Onder de categorie *Dieren*, maak je subcategorieën genaamd *Vogels* en 
  *Zoogdieren*. 
- Onder de subcategorie *Vogels*, maak je categorieën genaamd *Haviken*, *Papegaaien* 
  en *Mussen*. Dit is de resulterende categorie-structuur:

```
- Dieren
  - Vogels
    - Haviken
    - Papegaaien
    - Mussen
  - Zoogdieren
```

Nu kun je meerdere artikelen maken in de subcategorieën Havik, Papegaai en Mus, door gebruik te maken van de verschillende geslachts- of veelvoorkomende namen van de specifieke soorten van deze vogels.

## Chrome

De zichtbare grafische interfacekenmerken van een applicatie worden soms
verwezen naar als *chrome*.

## Component

## Kern

Het woord *kern* in Joomla! heeft betrekking op de gedistribueerde bestanden die nodig zijn om een Joomla CMS-aangedreven website te creëren en te beheren. De Joomla-kern bevat alle benodigde functionaliteit om snel en eenvoudig een nieuwe website te maken en te beheren.

## Database Tabel Voorvoegsel

Het database tabel voorvoegsel is een tekenreeks (een paar tekens lang) die wordt voorafgegaan
aan de naam van Joomla! tabellen. Het gebruik van een voorvoegsel maakt het mogelijk om meerdere 
installaties van Joomla! te draaien met behulp van één enkele database.

Het database tabel voorvoegsel kan tijdens de installatie worden ingesteld. Het later wijzigen 
is mogelijk, maar vereist toegang tot de database via een niet-Joomla medium of een Joomla 
Extensie zoals Akeeba Admin Tools en zal enige downtime veroorzaken.

Extensie ontwikkelaars moeten de tekenreeks `#__` gebruiken om het voorvoegsel weer te geven.
Dit wordt tijdens runtime vervangen door het daadwerkelijke voorvoegsel.

## Uitbreiding

## LDAP

## Taal

Talen zijn misschien wel het meest basale en cruciale extensietype. Talen worden verpakt als een kern-taalpakket of een extensie-taalpakket. Deze pakketten bestaan uit INI-bestanden die sleutel/waarde-paren bevatten om de vertaling van statische tekststrings binnen de Joomla!-broncode te bieden. Dit maakt het mogelijk om zowel de Joomla!-kern als de componenten en modules van derden te internationaliseren. Kern-taalpakketten bevatten ook een XML-metabestand dat de taal beschrijft en informatie geeft over de te gebruiken lettertypen voor de generatie van PDF-inhoud.

## Menu

In Joomla! is een **Menu** een module die een set van **menu-items** bevat die worden gebruikt voor navigatie. Elk menu-item definieert een URL naar een pagina op de site. Het bevat instellingen die de weergave van de pagina inhoud en stijl bepalen.

## Model-View-Controller

Joomla maakt uitgebreid gebruik van het
<a href="http://en.wikipedia.org/wiki/Model-view-controller"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">Model-View-Controller</a> (MVC) design
pattern.

Wanneer Joomla wordt gestart om een verzoek van een gebruiker te verwerken, zoals een GET
voor een bepaalde pagina, of een POST met formuliergegevens, is een van de eerste
dingen die Joomla doet, de URL analyseren om te bepalen welke
component verantwoordelijk zal zijn voor het verwerken van het verzoek, en de
controle over te dragen aan die component.

Als de component is ontworpen volgens het MVC-patroon, zal het
de controle doorgeven aan de controller. De controller is verantwoordelijk voor
het analyseren van het verzoek en het bepalen welke model(len) nodig zullen zijn om
het verzoek te vervullen, en welke view moet worden gebruikt om de resultaten
terug te sturen naar de gebruiker.

Het model omvat de gegevens die door de component worden gebruikt. In de meeste gevallen
zullen deze gegevens uit een database komen, hetzij de Joomla-database, of een
externe database, maar het is ook mogelijk voor het model om gegevens te verkrijgen
van andere bronnen, zoals via een webservices-API die op een andere
server draait. Het model is ook verantwoordelijk voor het bijwerken van de database waar
gepast. Het doel van het model is om de controller en
view te isoleren van de details van hoe gegevens worden verkregen of gewijzigd.

De view is verantwoordelijk voor het genereren van de output die naar de
browser wordt gestuurd door de component. Het roept het model aan voor alle informatie die het
nodig heeft en formatteert deze op de juiste manier. Bijvoorbeeld, een lijst van gegevensitems
uit het model zou door de view in een HTML-tabel kunnen worden geplaatst.

Aangezien Joomla is ontworpen om zeer modulair te zijn, is de output van de
component meestal slechts een deel van de volledige webpagina die de gebruiker
uiteindelijk zal zien. Zodra de view de output heeft gegenereerd, geeft de
component de controle terug aan het Joomla-framework, dat vervolgens de
template laadt en uitvoert. De template combineert de output van de
component en alle modules die actief zijn op de huidige pagina, zodat
het als één pagina naar de browser kan worden verzonden.

Om extra kracht en flexibiliteit te bieden aan webontwerpers, die
mogelijk alleen bezig zijn met het creëren van nieuwe ontwerpen in plaats van het manipuleren van de
onderliggende code, splitst Joomla de traditionele view in een aparte view
en layout. De view haalt gegevens uit het model, zoals in een traditioneel MVC-
patroon, maar maakt deze gegevens vervolgens gewoon beschikbaar voor de layout, die
verantwoordelijk is voor het formatteren van de gegevens voor presentatie aan de gebruiker. Het
voordeel van deze splitsing is dat het Joomla-templatesysteem
een eenvoudige mechanismen biedt voor layouts om te worden overschreven in de
template. Deze layout-overschrijvingen (vaak "template-overschrijvingen" genoemd
omdat ze deel uitmaken van de template, hoewel eigenlijk de
layout wordt overschreven) worden bij de template gebundeld en geven de
template-ontwerper volledige controle over alle output van de
Joomla-core en alle geïnstalleerde derde-partij-extensies die voldoen aan
het MVC-designpatroon.

## Module

## Module Class Suffix

Een Module Class Suffix is een parameter die in modules wordt gebruikt om een nieuwe CSS-klasse aan een module toe te voegen. Het wordt gebruikt in combinatie met stijlen die zijn gedefinieerd in een user.css-bestand om het standaard uiterlijk van een module te wijzigen.

De nieuwe klassenaam kan worden gebruikt om elke gewenste opmaak aan de module toe te voegen zonder dat alle bestaande CSS-code opnieuw moet worden gemaakt. Let op dat als je een nieuwe klassenaam maakt, deze een unieke naam heeft en niet in conflict komt met bestaande klassennamen.

## Module positie

## Module chrome

## PHP

PHP is een scripttaal voor computers die is ontworpen voor het maken van dynamische webpagina's. PHP wordt veel gebruikt voor webontwikkeling en kan in HTML worden geïntegreerd. Het draait meestal op een webserver, waarbij het PHP-code als input neemt en webpagina's als output creëert. Joomla! is voornamelijk geschreven in de PHP-taal.

## Pagina Klasse Achtervoegsel

Een Pagina Klasse Achtervoegsel is een parameter die wordt gebruikt in inhoudsmenu-items om een nieuwe CSS-klasse toe te voegen aan de paginalay-out. Het wordt gebruikt in combinatie met stijlen die zijn gedefinieerd in een user.css-bestand om het standaard uiterlijk van een module te veranderen.

De nieuwe klassenaam kan worden gebruikt om elke gewenste stijl aan de pagina toe te voegen zonder dat alle bestaande CSS-code opnieuw hoeft te worden gemaakt. Merk op dat, als je een nieuwe klassenaam aanmaakt, je ervoor zorgt dat deze een unieke naam heeft en niet conflicteert met bestaande klassennamen.

## Patch

## Plug-in

## Zoekmachinevriendelijke URL's

Zoekmachinevriendelijke URL's is een term die vaak wordt afgekort als SEF URL's
of kortweg SEF. Normale Joomla!-URL's zien er ongeveer zo uit:

    http://www.jouwsite.org/index.php?option=com_content&view=section&id=3&Itemid=41

Je kunt er optioneel voor kiezen om URL's weer te geven die eruitzien als statische HTML-pagina's zoals deze:

    http://www.jouwsite.org/faq.html

Er zijn ingebouwde opties voor het genereren van SEF-URL's. Deze worden ingeschakeld in de 
*SEO-instellingen* (zoekmachineoptimalisatie) op het tabblad Site van de 
Globale Configuratiepagina. Er zijn ook externe extensies die 
SEF-URL's voor Joomla! maken.

## Gesplitste menu's

Een gesplitst menu is waar verschillende niveaus van een enkel menu op twee of meer locaties op een enkele webpagina worden weergegeven.

Een veelvoorkomend voorbeeld is dat een menu met topniveauelementen bovenaan de pagina verschijnt. Wanneer op een van de items wordt geklikt, wordt de gebruiker naar een pagina geleid waar een secundair menu, bijvoorbeeld links op de pagina, tweede-niveauelementen binnen de reikwijdte van het topniveauelement toont.

De menu's verschijnen op verschillende locaties op de pagina, maar zijn gerelateerd omdat een menu alleen topniveauelementen toont terwijl het andere tweede-niveauelementen toont. Dit idee kan worden uitgebreid om menu's voor derde-niveauelementen en verder op te nemen.

Dit kan in Joomla worden geïmplementeerd met behulp van een enkel meerlagenmenu en vervolgens meer dan één menumodule maken die elk naar een ander niveau verwijzen.

## Sjabloon

Een sjabloon is een type Joomla! extensie die de paginaverschijning regelt.
- Een Sitesjabloon bepaalt het openbare uiterlijk van de site-inhoud.
- Een Beheerderssjabloon bepaalt het uiterlijk van de site voor 
  administratieve taken zoals: gebruikers-, menu-, artikel-, categorie-, module-, 
  component-, plug-in- en sjabloonbeheer.

## Sjabloonstijl

## Upgradepakket

Een Upgradepakket in Joomla! is een pakket met bestanden die de
gewijzigde bestanden tussen Joomla!-versies bevatten. Wanneer dit archief wordt
uitgepakt, vervangt het de oude versie van de gewijzigde bestanden met de nieuwe
versie. Bijvoorbeeld, als vijftig bestanden werden gewijzigd tussen versie 5.1
en 5.2, zou het upgradepakket deze vijftig bestanden bevatten en instructies
over hoe de upgrade uit te voeren. Soms omvat dit ook database-updates en
het verwijderen van niet langer gebruikte bestanden.

*Vertaald door openai.com*

