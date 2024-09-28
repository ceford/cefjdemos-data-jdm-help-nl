<!-- Filename: Help4.x:Articles:_Edit  / Display title: Artikelen: Bewerken -->

## Beschrijving

Deze pagina wordt gebruikt om een nieuw artikel toe te voegen of een bestaand artikel te bewerken, meestal met behulp van een Wysiwyg-editor. De standaardeditor is TinyMCE, maar als er andere editors zijn geïnstalleerd, kan de standaardeditor worden ingesteld op iets anders voor de site als geheel of voor individuele gebruikers.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het Schema Tabblad](jdocmanual?article=help/common-elements/edit-schema).
* [Het Publicatie Tabblad](jdocmanual?article=help/common-elements/edit-publishing).
* [Het Associaties Tabblad](jdocmanual?article=help/common-elements/edit-associations).
* [Het Rechten Tabblad](jdocmanual?article=help/common-elements/edit-permissions).
* [De Versiegeschiedenis Popup](jdocmanual?article=help/common-elements/edit-version-history).

Of in Gebruikersartikelen:

* [Een Afbeelding Toevoegen aan een Artikel](jdocmanual?article=user/articles/adding-an-image-to-an-article).

## Hoe Toegang Krijgen

* Selecteer **Inhoud → Artikelen** in het Beheerdersmenu. Of...
* Selecteer **Artikelen** op het Startdashboard. Vervolgens...
    * Selecteer een bestaande artikel **Titel** in de lijst om het te bewerken. Of...
    * Selecteer de **Nieuw** knop in de Werkbalk om een nieuw artikel te maken.
Je kunt ook een nieuw artikel maken door het **+** pictogram in het Menu of
Startdashboard te selecteren.


## Screenshot

![Screenshot van het bewerken van artikelen](../../../nl/images/articles/articles-edit-content-tab.png)

## Formuliervelden

- **Titel** De titel van dit artikel.
- **Alias** De interne naam van dit artikel. Normaal gesproken kun je dit leeg laten en Joomla vult een standaardwaarde in op basis van de titel, maar dan in kleine letters en met streepjes in plaats van spaties.

### Inhoudstab

#### Linker paneel

- **Artikeltekst** Dit is waar je de inhoud van het artikel invoert. Joomla bevat 3 editors, de standaard editor - TinyMCE wordt hierboven weergegeven.

    De CMS-inhoud vervolgkeuzelijst biedt toegang tot koppelingen naar een artikel, contactpersoon, veld, mediabeeld, menu, module, pagina-einde of lees-meer-einde.

    Het beletselteken-symbool (<span class="icon-ellipsis-h"></span>) schakelt de zichtbaarheid van extra tools in of uit.
- **Toggle Editor** De knop onder het bewerkingsvenster stelt je in staat om te schakelen tussen de TinyMCE-editor en geen editor. Hiermee kun je de HTML-code bekijken en soms repareren.

#### Rechter paneel

- **Status** De publicatiestatus van dit artikel.
  - *Gepubliceerd* Artikel is zichtbaar op de voorkant van de site.
  - *Gedepubliceerd* Artikel is niet zichtbaar voor bezoekers op de voorkant van de site. Het kan zichtbaar zijn voor ingelogde gebruikers die toestemming hebben om de status van het artikel te bewerken.
  - *Gearchiveerd* Artikel wordt niet meer getoond op menu-items of categorieoverzichten.
  - *Verwijderd* Artikel is van de site verwijderd maar bevindt zich nog steeds in de database.
- **Categorie** Selecteer de categorie voor dit artikel.
- **Uitgelicht** Selecteer Ja als het artikel getoond wordt in het uitgelichte menu-item.
- **Toegang** Selecteer het toegangsniveau voor dit artikel. De toegangsniveaus zijn afhankelijk van de instellingen in Gebruikers: Toegangsniveaus.
- **Taal** Selecteer de taal voor dit artikel. Laat de standaardinstelling 'Alle' staan als je geen gebruik maakt van de meertalige functie.
- **Tags** Ken tags toe aan dit artikel. Je kunt een tag selecteren uit een vooraf gedefinieerde lijst of een nieuwe tag invoeren door de naam in het veld te typen en op enter te drukken.
- **Notitie** Dit is normaal gesproken voor gebruik door de beheerder (bijvoorbeeld om informatie over dit artikel te documenteren) en wordt niet weergegeven op de voorkant.
- **Versienotitie** Optioneel veld om de versie van dit artikel te identificeren in de versiegeschiedenis van het artikel.

### Beelden en Koppelingen tab

**Let op:** Deze tab kan worden verborgen in *Artikel: Opties* door een gebruiker met beheerdersrechten. Het stelt de weergave van afbeeldingen en links in artikelen op gestandaardiseerde lay-outs in.

![Artikelen bewerk afbeeldingen en koppelingen tab](../../../nl/images/articles/articles-edit-images-tab.png)

#### Intro Afbeelding

- **Intro Afbeelding** Klik op de Selecteer-knop om een afbeelding te kiezen die wordt weergegeven op een vaste locatie in de inleidingstekst van dit artikel. Er wordt een venster geopend waarmee je een afbeelding kunt kiezen uit de afbeeldingsmap.
- **Afbeeldingsbeschrijving (Alt-tekst)** Stel het alt-attribuut in voor deze afbeelding. Een paar beschrijvende woorden voor schermlezers.
- **Geen Beschrijving** Vink aan in het zeldzame geval van een puur decoratief beeld. Merk op dat als de afbeeldingsbeschrijving leeg is en het selectievakje Geen Beschrijving niet is aangevinkt, de afbeelding niet voldoet aan de toegankelijkheidscriteria. Als er een afbeeldingsbeschrijving aanwezig is, heeft dit selectievak geen effect.
- **Afbeeldingsklasse** Voeg eventueel een extra CSS-klasse toe voor aangepaste styling.
  Bijvoorbeeld, voor beeldpositie gebruik float-start of float-end.
- **Bijschrift** Creëer een bijschrift voor deze afbeelding.

#### Volledige Artikel Afbeelding

- **Volledige Artikel Afbeelding** Klik op de Selecteer-knop om een afbeelding te kiezen die wordt weergegeven op een vaste locatie in de volledige tekst van dit artikel. Er wordt een venster geopend waarmee je een afbeelding kunt kiezen uit de afbeeldingsmap.
- **Afbeeldingsbeschrijving (Alt-tekst)** Stel het alt-attribuut in voor deze afbeelding. Een paar beschrijvende woorden voor schermlezers.
- **Geen Beschrijving** Vink aan in het zeldzame geval van een puur decoratief beeld. Merk op dat als de afbeeldingsbeschrijving leeg is en het selectievakje Geen Beschrijving niet is aangevinkt, de afbeelding niet voldoet aan de toegankelijkheidscriteria. Als er een afbeeldingsbeschrijving aanwezig is, heeft dit selectievak geen effect.
- **Afbeeldingsklasse** Voeg extra CSS-klasse toe voor aangepaste styling.
  Bijvoorbeeld, voor beeldpositie gebruik float-start of float-end.
- **Bijschrift** Voer een optioneel bijschrift in voor deze afbeelding.

#### Link A

- **Link A** De URL voor de eerste link die op een vaste locatie in de artikeltekst wordt weergegeven. Dit moet een volledige URL zijn, niet relatief. Bijvoorbeeld, het zou normaal beginnen met `https:`.
- **Link A Tekst** De tekst die wordt gebruikt voor Link A. Als het veld leeg is, wordt de URL weergegeven.
- **URL Doelvenster** Stelt de standaardwaarde in voor het doel voor de eerste link in dit artikel. Keuzes zijn:
  - *Open in oudervenster* Opent in het hoofdvenster van de browser, vervangt het huidige Joomla-artikel.
  - *Open in nieuw venster* Opent de link in een nieuw browservenster.
  - *Open in pop-up* Opent de link in een pop-up browservenster (zonder volledige navigatiecontroles).
  - *Modaal* Opent de link in een modaal pop-up venster.

#### Link B, Link C

- Dezelfde opties als Link A.

### Opties tab

**Let op**: Deze tab kan verborgen worden door een gebruiker met beheerdersrechten in de Artikel: Opties. Het is een set opties die worden gebruikt om te bepalen hoe dit artikel op de voorkant wordt weergegeven.

![Opties tab](../../../nl/images/articles/articles-edit-options-tab.png)

#### Lay-out

- **Lay-out** Gebruik een lay-out van de meegeleverde artikelweergave of overschrijvingen in de sjablonen.
- **Titel** Toon de titel van het artikel.
- **Gekoppelde Titels** Toon de titel als een link naar het artikel.
- **Tags** Voer tags in voor dit artikel. Selecteer bestaande tags door de eerste paar letters in te voeren of maak nieuwe tags aan door ze hier in te voeren.
- **Intro Tekst**
  - *Toon* De intro tekst van het artikel zal worden weergegeven op een pagina met het volledige artikel.
  - *Verberg* Alleen het deel van het artikel na de Lees Meer-regel wordt weergegeven op een pagina met het volledige artikel.
- **Positie van Artikelinformatie**
  - *Boven* Plaatst het informatieblok boven de tekst.
  - *Onder* Plaatst het informatieblok onder de tekst.
  - *Gedeeld* Verdeelt het informatieblok in twee afzonderlijke blokken. Een blok is boven en het andere onder de tekst.
- **Artikel Info Titel** Toont 'Details' bovenaan het informatieblok.

#### Categorie

- **Categorie** Toon de categorietitel van het artikel.
- **Link Categorie** Toon de titel als een link naar die categorie.
- **Hoofdcategorie** Toon de hoofdcategorie titel van het artikel.
- **Link Hoofdcategorie** Toon de titel als een link naar die categorie.

#### Associaties

- **Associaties** Toon de geassocieerde vlaggen of taalcodes. Alleen meertalig.

#### Auteur

- **Auteur** Toon de auteur van het artikel.
- **Link naar auteur's contactpagina** Toon het als een link naar een contact lay-out voor die auteur. Opmerking: De auteur moet zijn ingesteld als een contactpersoon.

#### Datum

- **Aanmaken Datum** Toon de aanmaakdatum van het artikel.
- **Wijzigingsdatum** Toon de wijzigingsdatum van het artikel.
- **Publicatiedatum** Toon de start publicatiedatum van het artikel.

#### Opties

- **Navigatie** Toon navigatielinks, *Vorige* en/of *Volgende*, bij het weergeven van een pagina met het volledige artikel.
- **Hits** Toon het aantal keren dat het artikel door een gebruiker is weergegeven.
- **Niet gemachtigde links** Als Ja, wordt de intro tekst voor beperkte artikelen weergegeven. Het klikken op de Lees meer-link vereist inloggen om de volledige inhoud van het artikel te bekijken.
- **Positionering van de links**
  - *Boven* Links worden boven de inhoud weergegeven.
  - *Onder* Links worden onder de inhoud weergegeven.
- **Lees Meer Tekst** Pas de tekst aan die wordt weergegeven voor de standaardtekst 'Lees meer'.
- **Browser Paginatitel** Tekst voor de pagina titel van de browser die wordt gebruikt wanneer het artikel wordt bekeken met een menu-item dat geen artikel is. Als dit veld leeg is, wordt de titel van het artikel in plaats daarvan gebruikt.

### Velden tab

In dit gedeelte worden de aangepaste velden weergegeven die voor dit artikel zijn gedefinieerd. Dit zijn velden die niet zijn toegewezen aan een veldgroep. Elke veldgroep, indien gedefinieerd, zal verschijnen als een aparte tab.

![Velden tab](../../../nl/images/articles/articles-edit-fields-tab.png)

### Bewerkingsscherm Configureren tab

**Let op:** Dit kan worden verborgen door een gebruiker met beheerdersrechten in de Artikel: Opties.

![Bewerkingsscherm configureren tab](../../../nl/images/articles/articles-edit-editor-tab.png)

- **Publiceer Opties** Als Verbergen, zal het tabblad Publiceer Opties niet worden weergegeven in het Backend. Dit betekent dat Backend-gebruikers de velden in dit tabblad niet zullen kunnen bewerken. Deze velden zullen altijd worden ingesteld op hun standaardwaarden.
- **Artikel Opties** Als Verbergen, zal het tabblad Artikel Opties niet worden weergegeven in het Backend. Dit betekent dat Backend-gebruikers de velden in dit tabblad niet zullen kunnen bewerken. Deze velden zullen altijd worden ingesteld op hun standaardwaarden.
- **Administrator Afbeeldingen en Koppelingen** Als Ja, wordt het tabblad Afbeeldingen en Koppelingen weergegeven.
- **Voorzijde Afbeeldingen en Koppelingen** Als Ja, wordt het tabblad Afbeeldingen en Koppelingen weergegeven in het artikelbewerkingsscherm aan de voorkant.


## Tips

- Er zijn 2 methoden om een afbeelding in een artikel in te voegen met behulp van de TinyMCE editor.
  1. De *CMS Content* dropdownlijst biedt toegang tot het Media scherm.
  2. De *Insert* dropdownlijst is een eenvoudig formulier dat de afbeeldingsurl vereist. Dit wordt gebruikt voor externe afbeeldingen.
- Een *Read More* invoeging bespaart ruimte op elke Featured of Blog lay-outpagina door alleen het eerste gedeelte van een artikel weer te geven. *Page Break* invoegingen bieden navigatie over meerdere pagina's voor lange artikelen. Beide kunnen indien gewenst in een enkel artikel worden gebruikt. Bijvoorbeeld, een *Read More* invoeging kan worden geplaatst na de eerste alinea en *Page Break* invoegingen kunnen worden geplaatst na latere groepen van alinea's om een artikel over meerdere pagina's te creëren. Er zou geen paginanavigatie worden weergegeven op de Featured of Blog pagina totdat de gebruiker de Read more link selecteert. Op dat moment zou de inhoudsopgave van het artikel worden weergegeven met links naar elke pagina.

*Vertaald door openai.com*

