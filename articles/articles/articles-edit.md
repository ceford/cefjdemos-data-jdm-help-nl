<!-- Filename: Help4.x:Articles:_Edit / Display title: Artikelen: Bewerken -->

## Beschrijving

Dit scherm wordt gebruikt om een nieuw artikel toe te voegen of een
bestaand artikel te bewerken, meestal met behulp van een WYSIWYG
tekstverwerker. De standaard tekstverwerker is TinyMCE maar als een
andere tekstverwerker is geïnstalleerd kan de standaard tekstverwerker
een andere zijn voor de gehele site, of voor individuele gebruikers.

De meeste parameters hebben geschikte standaards maar u wilt misschien
een bepaalde categorie instellen of Metadata voor specifieke artikelen.

## Tutorials

[Adding an Image to an Article](jdocmanual?article=user/articles/adding-an-image-to-an-article "Adding an Image to an Article")

## Hoe toegang te krijgen
Selecteer **Inhoud → Artikelen**

Om een artikel aan te maken:

- Klik de **Nieuw** werkbalk knop.

Om een artikel te bewerken:

- Selecteer de **titel** in de lijst.

## Schermafbeelding

![Articles edit screenshot](../../../nl/images/articles/articles-edit-content-tab.png "Articles edit")

## Formulier velden

- **Titel**. De titel van dit artikel.
- **Alias**. De interne naam van het artikel. Normaliter, kunt u dit
  leeg laten en Joomla zal de standaardwaarde invullen. De standaard
  waarde is de titel of naam in kleine letters en streepjes in plaats
  van spaties. Meer
  leren.

### Inhoud tabblad

#### Linker venster

- **Artikeltekst**. Dit is waar de inhoud van het artikel wordt
  geplaatst. Joomla bevat 3 tekstverwerkers, de standaard
  Tekstverwerker - TinyMCE wordt hier getoond.

  De CMS inhoud drop-down lijst biedt toegang tot een link naar artikelen,
  contactpersonen, velden, media, menu of module. Meer leren.
- **Schakelen tekstverwerker**. Er wordt direct onder het tekstvenster
  een knop Schakelen tekstverwerker zichtbaar. Met deze knop kun je
  schakelen tussen de TinyMCE tekstverwerker en

#### Rechter venster

- **Status**. De publicatiestatus van dit artikel.
  - Gepubliceerd: Artikel is zichtbaar op de website.
  - Gedepubliceerd: Artikel is niet zichtbaar voor gasten op de website.
    Het kan zichtbaar zijn voor ingelogde gebruikers die [bewerk status
    rechten](#permissions) hebben om de status van het artikel te
    bewerken.
  - Gearchiveerd: Artikel zal niet langer getoond worden in
    Categorieblog
    of
    Categorielijst
    menu-items.
  - Verplaatst naar prullenbak: Artikel is verwijderd van de site maar
    nog steeds in de database. Meer
    leren.
- **Categorie**. Selecteer de categorie voor dit artikel.
- **Speciaal**. Selecteer ja indien dit artikel getoond moet worden in
  het menu-item voor speciale
  artikelen.
- **Toegang**. Selecteer het weergave toegangsniveau van dit artikel. De
  toegangsniveaus hangen af van wat ingesteld is bij Gebruikers:
  Toegangsniveaus.
- **Taal**. Selecteer de taal voor dit item. Wanneer u de meertalige
  functie
  in Joomla niet gebruikt, laat dan de standaard ingevulde 'Alle'
  ongewijzigd.
- **Tags**. Wijs tags toe aan inhoudsartikelen. U kunt een label
  selecteren uit de voorgedefinieerde
  lijst of
  voer een nieuwe tag in door de naam te typen in het veld en druk op
  enter.
- **Notitie**. Dit wordt normaal gesproken door de beheerder gebruikt
  (bijvoorbeeld om informatie te documenteren voor dit artikel) en is
  niet op de website zichtbaar.
- **Versie notitie**. Optioneel veld om deze versie van dit artikel te
  identificeren in het
  versiegeschiedenis.

### Afbeeldingen en links tabblad

Deze sectie maakt het mogelijk om afbeeldingen en links in een standaard
weergave aan artikelen toe te voegen.

**Let op**: Dit kan verborgen worden door een gebruiker met
administratie rechten in de

![Articles edit images and links tab](../../../nl/images/articles/articles-edit-images-tab.png "Articles edit images and links tab")

#### Afbeelding introtekst

- **Afbeelding introtekst**. Klik op de knop Selecteren om een
  afbeelding te selecteren die op een bepaalde locatie in de introtekst
  van het artikel wordt weergegeven. Dit opent een venster die het
  mogelijk maakt een afbeelding te selecteren uit de map images. Meer
  leren.
- **Beschrijving van afbeelding (Alt-tekst)**. Stelt het Alt attribuut
  in voor deze afbeelding. Een paar beschrijvende woorden voor
  schermlezers.
- **Geen beschrijving**. Aanvinken in de zeldzame omstandigheid van een
  volledige *Decoratieve afbeelding - geen beschrijving nodig*. Let op
  dat als de beschrijving van de afbeelding leeg is en het 'Geen
  beschrijving' vakje niet is aangevinkt, de afbeelding niet voldoet aan
  de toegankelijkheidscriteria. Als een afbeeldingsbeschrijving aanwezig
  is heeft dit vinkje geen effect.
- **Class van de afbeelding**. Elke CSS class kan toegevoegd worden voor
  eigen styling ideeën. Gebruik voor de positie van afbeeldingen
  bijvoorbeeld 'float-star' en 'float-end'.
- **Bijschrift**. Maak een bijschrift voor de afbeelding.

#### Afbeelding volledig artikel

- **Afbeelding volledig artikel**. Klik op de knop Selecteren om een
  afbeelding te selecteren die op een bepaalde locatie in het volledige
  artikel wordt weergegeven. Dit opent een venster die het mogelijk
  maakt een afbeelding te selecteren uit de map images. Meer
  leren.
- **Beschrijving van afbeelding (Alt-tekst)**. Stelt het Alt attribuut
  in voor deze afbeelding. Een paar beschrijvende woorden voor
  schermlezers.
- **Geen beschrijving**. Aanvinken in de zeldzame omstandigheid van een
  volledige *Decoratieve afbeelding - geen beschrijving nodig*. Let op
  dat als de beschrijving van de afbeelding leeg is en het 'Geen
  beschrijving' vakje niet is aangevinkt, de afbeelding niet voldoet aan
  de toegankelijkheidscriteria. Als een afbeeldingsbeschrijving aanwezig
  is heeft dit vinkje geen effect.
- **Class van de afbeelding**. Elke CSS class kan toegevoegd worden voor
  eigen styling ideeën. Gebruik voor de positie van afbeeldingen
  bijvoorbeeld 'float-start' en 'float-end'.
- **Bijschrift**. Vul optioneel een bijschrift in voor de afbeelding.

#### Link A

- **Link A**. De URL van de eerste link die wordt weergegeven op een
  bepaalde locatie in de tekst van het artikel. Dit moet een volledige
  URL zijn, niet relatief. Bijvoorbeeld, normaal gesproken begint het
  met `https:`.
- **Link A tekst**. De tekst die voor link A gebruikt wordt. Indien
  niets is ingevuld wordt de URL weergegeven.
- **URL doelvenster**. Stelt de standaard waarde in voor het doelvenster
  van de eerste link in het artikel. Keuzes zijn:
  - Openen in het hoofdvenster: Opent de link in het hoofdvenster en
    vervangt het huidige Joomla artikel.
  - Openen in een nieuw venster: Opent de link in een nieuw
    browservenster.
  - Openen in pop-upvenster: Opent de link in een pop-up venster (zonder
    volledige navigatie-elementen).
  - Modaal: Opent de link in een modaal pop-up venster.
- **Link B**, **Link C**: Zelfde opties als 'Link A'.

### Opties tabblad

**Let op**: Dit kan verborgen worden door een gebruiker met
administratie rechten in de
Dit is een set opties die u kunt gebruiken om te beheersen hoe dit
artikel wordt getoond in de Frontend.

![Options tab](../../../nl/images/articles/articles-edit-options-tab.png "Options Tab")

#### Weergave

- **Weergave**. Gebruik een layout uit de beschikbare artikelweergave of

- **Titel**. Toon de titel van het artikel.
- **Gelinkte titels**. Toont de titel als link naar het artikel.
- **Tags**. Voer één of meer optionele tags in voor dit item. U kunt
  bestaande tags invoeren door het intikken van de eerste paar letters.
  U kunt ook nieuwe tags toevoegen door ze hier in te voeren. Meer
  leren.
- **Introtekst**.
  - Toon: De Introtekst van het artikel wordt getoond als men naar het
    artikel gaat.
  - Verberg: Alleen het deel van het artikel na de 'Lees meer' wordt
    getoond.
- **Positie van artikelinformatie**.
  - Boven: Plaatst het artikel-informatieblok boven de tekst.
  - Onder: Plaatst het artikel-informatieblok onder de tekst.
  - Verdelen: Splitst het artikel-informatieblok in 2 aparte blokken.
    Eén boven en de ander onder de tekst.
- **Titel artikelinformatie**. Toont 'Details' boven het
  artikelinformatie gedeelte.

#### Categorie

- **Categorie**. Toont de categorietitel van een artikel.
- **Link categorie**. Toont de titel als link naar die categorie.
- **Hoofdcategorie**. Toont de titel van de hoofdcategorie van een
  artikel.
- **Link bovenliggende categorie**. Toont de titel als link naar die
  categorie.

#### Associaties

- **Associaties**. Toont de geassocieerde vlaggen of taalcodes. Alleen
  meertaligheid.

#### Auteur

- **Auteur**. Toont de auteur van een artikel.
- **Link naar de contactpagina van de auteur**. Toont het als link naar
  een contactpersonen weergave van die auteur.Let op: De auteur moet
  als contactpersoon
  ingesteld
  zijn.

#### Datum

- **Aanmaakdatum**. Toont de aanmaakdatum van een artikel.
- **Aanpassingsdatum**. Toont de aanpassingsdatum van een artikel.
- **Publicatiedatum**. Toont de publicatiedatum van een artikel.

#### Opties

- **Navigatie**. Toont een navigatie link 'vorige' of 'volgende' indien
  door artikelen gebladerd wordt.
- **Hits**. Toon het aantal keren dat een artikel getoond is aan
  gebruikers.
- **Niet-toegestane links**. Ja: De Introtekst voor beperkte artikelen
  wordt getoond. Klikken op de 'Lees meer' link heeft tot gevolg dat
  gebruikers in moeten loggen om de inhoud van het artikel te zien.
- **Positionering van de links.**
  - Boven: Links worden boven de inhoud getoond.
  - Onder: Links worden onder de inhoud getoond.
- **Lees meer tekst**. Pas de tekst aan die weergegeven wordt voor de
  standaard tekst "Lees meer".
- **Browserpaginatitel**. Tekst voor het "Browserpaginatitel" dat
  gebruikt wordt wanneer het artikel bekeken wordt vanuit een menu item
  dat niet aan artikelen is gerelateerd. Indien dit veld wordt leeg
  gelaten, wordt in plaats daarvan de titel van het artikel gebruikt.

### Velden tabblad

Deze sectie toont de extra velden die gedefinieerd zijn voor dit artikel.

![Fields tab](../../../nl/images/articles/articles-edit-fields-tab.png "Filds Tab")

### Schema tab

![Schema tab](../../../en/images/articles/articles-edit-schema-tab.png "Schema Tab")

The schema mechanism allows you to enter metadata for individual articles,
choosing from the following schema types:

* None
* Article
* BlogPosting
* Book
* Event
* JobPosting
* Organisation
* Person
* Recipe
* Custom

Each is a plugin which can disable or enable as required. More schmema types
my be added later or available from third party sources.

### Publiceren tabblad

Deze sectie geeft u de mogelijkheid parameters en Metadata op te geven voor 
dit artikel.

**Let op**: Dit kan verborgen worden door een gebruiker met
administratie rechten in de

![Publishing tab](../../../nl/images/articles/articles-edit-publishing-tab.png "Publishing Tab")

#### Publiceren

- **Start publiceren**. Datum en tijd waarop de publicatie moet starten.
  Maak een artikel voortijdig aan en publiceer het automatisch op een
  bepaalde tijd in de toekomst.
- **Stop publiceren**. Datum en tijd om te stoppen met publiceren. Het
  artikel krijgt automatisch de status gedepubliceerd op een tijdstip in
  de toekomst.
- **Begin speciaal**. Datum en tijd om de Speciaal status in te
  schakelen. Voer artikel voortijdig in en en laat het automatisch de
  status Speciaal krijgen op een tijdstip in de toekomst.
- **Einde speciaal**. Datum en tijd om de 'Speciaal' status uit te
  schakelen. Het artikel krijgt automatisch de status 'Niet speciaal' op
  een tijdstip in de toekomst.
- **Aanmaakdatum**. Het tijdstip waarop het artikel gemaakt was. Voer
  een andere datum en tijd in of klik op het kalender icoon om de
  gewenste datum te selecteren.
- **Gemaakt door**. Naam van de gebruiker die dit artikel gemaakt heeft.
  Dit is standaard de huidig ingelogde gebruiker. Klik op de knop
  selecteer gebruiker en selecteer een andere gebruiker indien dit
  aangepast moet worden naar een andere gebruiker.
- **Gemaakt door alias**. Voer een alias in voor de auteur van dit
  artikel. Dit geeft de mogelijkheid een andere auteursnaam te tonen.
- **Aanpassingsdatum**. Datum van laatste wijziging.
- **Aangepast door**. Gebruikersnaam wie de laatste aanpassing heeft
  gedaan.
- **Herzien**. Aantal aanpassingen van dit artikel.
- **Hits**. Het aantal keren dat een artikel is bekeken.
- **ID**. Een uniek identificatienummer voor dit artikel, men kan dit
  nummer niet veranderen. Als een nieuw artikel wordt aangemaakt, is dit
  veld '0' totdat het wordt opgeslagen.

#### Metadata

- **Metabeschrijving**. Een paragraaf die gebruikt wordt als
  beschrijving van de pagina. Meer
  leren.
- **Trefwoorden**. Invoer voor trefwoorden. Meer
  leren.
- **Robots**. De instructies voor web 'robots' die naar deze pagina
  bladeren. Zet op 'Gebruik algemeen' in
- **Auteur**. Plek voor een auteursnaam binnen de metadata.
- **Inhoudsrechten**. Beschrijft wat de rechten van andere zijn om deze
  inhoud te gebruiken.

### Associaties tabblad

**Let op**: Dit kan verborgen worden door een gebruiker met
administratie rechten in de
Tabblad wordt alleen getoond bij

![Associations tab](../../../nl/images/articles/articles-edit-associations-tab.png "Associations Tab")

### Configuratie bewerkvenster tabblad

**Let op**: Dit kan verborgen worden door een gebruiker met
administratie rechten in de

![Configure edit screen tab](../../../nl/images/articles/articles-edit-editor-tab.png "Configure edit screen Tab")

- **Publicatie opties**. Indien Verborgen dan wordt het ([Publicatie
  optie
  tabblad](https://docs.joomla.org/Help4.x:Articles:_Edit/nl#publishing "Help4.x:Articles: Edit/nl"))
  niet getoond in het beheergedeelte. Dit betekent dat gebruikers aan de
  beheerkant niet in staat zijn de velden op dit tabblad te bewerken.
  Deze velden worden altijd op hun standaard waarde gezet.
- **Artikel opties**. Indien Verborgen, dan wordt het (Artikel opties
  tabblad
  niet getoond in beheer. Dit betekent dat gebruikers in het
  beheergedeelte niet in staat zijn de velden op dit tabblad te
  bewerken. Deze velden worden altijd op hun standaard waarde gezet.
- **Afbeeldingen en links - beheergedeelte**. Indien Ja, dan wordt het
  (afbeeldingen en links tabblad getoond.
- **Afbeeldingen en links - website**. Indien Ja, dan verschijnt het
  afbeeldingen en links tabblad op het bewerkscherm van het artikel op
  de website.

### Rechten tabblad

**Let op**: Dit kan verborgen worden door een gebruiker met administratie 
rechten in de Hier kunt u rechten invoeren voor dit artikel. 

![Permissions tab](../../../nl/images/articles/articles-edit-permissions-tab.png "Permissions Tab")

Doe, om de rechten van dit artikel te wijzigen, het volgende.

1.  Selecteer de **Groep** door op de titel aan de linkerzijde te
    klikken.
2.  Zoek de gewenste **Actie**.
    - **Verwijderen**. Gebruikers kunnen dit artikel verwijderen.
    - **Bewerken**. Gebruikers kunnen dit artikel bewerken.
    - **Bewerk status**. Gebruikers kunnen de 'gepubliceerd' status en
      verwante informatie van dit artikel wijzigen.
3.  Selecteer de gewenste rechten voor de actie die u wilt wijzigen.
    - **Overgenomen**. Overgenomen voor gebruikers in deze groep uit de
      algemene
      instellingen,
      Artikelbeheer
      Opties,
      of
    - **Toegestaan**. Toegestaan voor gebruikers in deze groep.Let op:
      Als deze actie 'Geweigerd' is op een van de hogere niveaus, dan
      heeft de 'Toegestaan' rechten hier geen effect. Een 'Geweigerd'
      instelling kan niet overschreven worden.
    - **Geweigerd**. Geweigerd voor gebruikers in deze groep.
4.  Klik op **Opslaan** in de **werkbalk** bovenin. Wanneer het scherm
    herladen wordt zal de nieuwe gecalculeerde rechten voor deze groep
    en actie weergegeven worden.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#screensho) hierboven.

- **Opslaan**. Slaat artikel op en blijft op het huidige scherm.
- **Opslaan & sluiten**. Slaat artikel op en sluit het huidige scherm.
  - **Opslaan & nieuw**. Slaat artikel op en houdt het bewerkscherm
    open, klaar voor het aanmaken van een ander artikel.
  - **Opslaan in menu**. Slaat het item op in het menu-item en opent het
    menu-item scherm.
  - **Opslaan als kopie**. Slaat uw wijzigingen op als een kopie van het
    huidige artikel. Beïnvloed het huidige artikel niet.
- **Sluiten**. Sluit het huidige scherm en keert terug naar het vorige
  scherm zonder wijzigingen die u misschien heeft gedaan op te slaan.
- **Versies**. Opent het item versie geschiedenis scherm om eerdere
  versies van dit item te tonen. Dit stelt u in staat oudere versies van
  het item te bekijken en een oudere versie te herstellen. Meer
  leren.
- **Voorbeeld**. Opent een modaal venster met een voorbeeld van dit
  artikel op de site. Vereist gedeelde
  sessies
  of ingelogd zijn op de website.
- **Toegankelijkheid controle**. Opent een scherm dat het resultaat van
  de toegankelijkheidscontrole van het artikel toont.
- **Associaties**. Met een bepaalde taal ingesteld voor een artikel
  geeft het de mogelijkheid tot het naast elkaar bewerken van een andere
  taal. Dit werkbalk icoon wordt alleen getoond bij
- **Inline help in-/uitschakelen**. Toon helptekst onder enkele opties.
- **Help**. Opent dit helpscherm.

## Snelle tips

- Er zijn 2 methodes om een afbeelding in een artikel in te voegen met
  behulp van de TinyMCE tekstverwerker.
  1.  De CMS
      inhoud
      keuzelijst biedt toegang tot het Media
      scherm dat
      afbeelding bestanden laat zien en afbeeldingen laat uploaden.
  2.  De 'Invoegen' keuzelijst is een eenvoudig formulier waarvan men de
      afbeelding-URL moet weten. Het wordt gebruikt voor externe
      afbeeldingen.
- Lees
  meer
  afbrekingen geven de mogelijkheid ruimte te sparen op de startpagina
  of een blog-weergave pagina door alleen het eerste deel van een
  artikel te tonen. Pagina
  afbrekingen
  bieden meer-pagina navigatie voor lange artikelen. U kunt beide,
  desgewenst, ook in één artikel gebruiken.Men kan bijvoorbeeld een
  'Lees meer' regel na de eerste paragraaf van een meer-pagina artikel
  plaatsen en pagina afbrekingen na iedere pagina. Er is geen pagina
  navigatie zichtbaar op de voorpagina tot de gebruiker de 'Lees meer'
  link gebruikt. Dan wordt de inhoudsopgave zichtbaar welke links naar
  iedere pagina toont.
