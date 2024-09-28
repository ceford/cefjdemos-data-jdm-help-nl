<!-- Filename: Help4.x:Tags:_New_or_Edit  / Display title: Tags: Nieuw of Bewerken -->

## Beschrijving

De pagina *Tags: Nieuw of Bewerken* wordt gebruikt om tags toe te voegen of te bewerken die kunnen worden gebruikt om site-inhoud weer te geven op tagnaam.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).

## Toegang Verkrijgen

- Selecteer **Componenten → Tags** in het Administrator menu. Vervolgens:
  - Selecteer de '**Nieuw'** knop in de Toolbar om een nieuwe Tag aan te maken.
  - Selecteer een Tag's Titel uit de **Titel** kolom van de lijst om een bestaande tag te bewerken.

## Schermafbeelding

![tags bewerk tag details tabblad](../../../nl/images/tags/tags-edit-tag-details-tab.png)

## Formuliervelden

- **Titel** De naam van dit item. Dit veld is verplicht.
- **Alias** De interne naam van het item. Normaal gesproken kun je dit
  leeg laten en Joomla zal een standaardwaarde invullen met de titel in kleine letters en
  met koppeltekens in plaats van spaties.

### Tag Details-tabblad

#### Linkerpaneel

- **Omschrijving** Geef het doel van deze tag op.

#### Rechterpaneel

- **Ouder** Het item (categorie, menu-item, enzovoort) dat de
  ouder is van het item dat wordt bewerkt.
- **Status** De gepubliceerde status van het item.
- **Toegang** Het kijktoegangsniveau voor dit item.
- **Taal** Ta(a)l(en) van het item.
- **Notitie** Dit veld is normaal gesproken bedoeld voor gebruik door de sitebeheerder (bijvoorbeeld om informatie over dit item te documenteren) en wordt niet weergegeven in
  de frontend van de site.
- **Versie notitie** Optioneel veld om deze versie van het item te identificeren in het venster met de versiegeschiedenis van het item.

### Opties-tabblad

![tags bewerk tag opties-tabblad](../../../nl/images/tags/tags-edit-options-tab.png)

#### Optiepaneel

- **Lay-out** Gebruik een lay-out van de meegeleverde componentweergave of overrides
  in de sjablonen.
- **CSS-klasse voor taglink** Voeg specifieke CSS-klassen toe voor de taglink.
  Indien leeg, wordt *label label-info* toegevoegd door de standaard tag lay-out.

#### Afbeeldingspanelen

- **Teaserafbeelding** De afbeelding die als onderdeel van de lijst zal worden weergegeven.
- **Float** Float-attribuut voor de afbeelding.
- **Alt** Alt-tekst voor de afbeelding.
- **Bijschrift** Het bijschrift voor de afbeelding.
- **Volledige afbeelding** Een afbeelding die zal worden weergegeven in de weergave van een enkele tag.

### Publiceren-tabblad

![tags bewerk tag publiceren-tabblad](../../../nl/images/tags/tags-edit-publishing-tab.png)

#### Publiceerpaneel

- **Gemaakt op** Datum waarop het item (artikel, categorie, enz.) is gemaakt.
- **Gemaakt door** Naam van de Joomla-gebruiker die dit item heeft gemaakt. Dit
  wordt standaard ingesteld op de gebruiker die momenteel is ingelogd. Als je dit wilt veranderen
  in een andere gebruiker, klik dan op de knop Selecteer gebruiker om een andere gebruiker te selecteren.
- **Gemaakt door alias** Dit optionele veld stelt je in staat een alias in te voeren voor deze auteur voor dit artikel. Dit stelt je in staat om een andere auteursnaam voor dit artikel weer te geven.
- **Laatst aangepast op** Datum van de laatste wijziging.
- **Laatst aangepast door** Gebruikersnaam van degene die de laatste wijziging heeft uitgevoerd.
- **Revisie** ...
- **Hits** Het aantal keer dat een item is bekeken.
- **ID** Dit is een uniek identificatienummer voor dit item dat automatisch wordt toegewezen door Joomla. Het wordt gebruikt om het item intern te identificeren,
  en je kunt dit nummer niet wijzigen. Bij het maken van een nieuw item geeft dit veld "0" weer totdat je het nieuwe item opslaat, waarna een nieuw ID wordt toegewezen.

#### Metagegevenspaneel

- **Meta Omschrijving** Een optionele paragraaf die als beschrijving van de pagina in de HTML-output kan worden gebruikt. Dit wordt over het algemeen weergegeven in de resultaten van zoekmachines. Als je iets invoert, creëert dit een HTML-meta-element met een naamattribuut van `<description>` en een inhoudsattribuut gelijk aan de ingevoerde tekst.
- **Sleutelwoorden** Optionele invoer voor sleutelwoorden. Moeten met komma's worden gescheiden (bijvoorbeeld: katten, honden, huisdieren) en mogen in hoofd- of kleine letters worden ingevoerd. (Bijvoorbeeld: *KATTEN* zal overeenkomen met *katten* of *Katten*). Sleutelwoorden kunnen op verschillende manieren worden gebruikt:
  1.  Om zoekmachines en andere systemen te helpen de inhoud van het artikel te classificeren.
  2.  In combinatie met bannertags, om specifieke banners weer te geven
      op basis van de inhoud van het artikel. Bijvoorbeeld, stel dat je één banner hebt met een advertentie voor hondenproducten en een andere banner voor kattenproducten. Je kunt je hondenbanner weergeven wanneer een gebruiker een
      hond-gerelateerd artikel bekijkt en je kattenbanner voor een kat-gerelateerd artikel. Hiervoor doe je het volgende:
      - Voeg de sleutelwoorden "hond" en "kat" toe aan de juiste artikelen.
      - Voeg de tags "hond" en "kat" toe aan de juiste banners in Banners: Bewerken.
      - Stel de parameter 'Zoeken op tags' van de bannermodule in op "Ja" in de lijst met Site Modules: Banners.
  3.  Alleen voor artikelen, in combinatie met de module Artikelen - Gerelateerd,
      om artikelen weer te geven die ten minste één sleutelwoord gemeen hebben. Bijvoorbeeld, als het huidige weergegeven artikel de sleutelwoorden "katten, honden, apen" heeft, worden alle andere artikelen met ten minste een van deze sleutelwoorden weergegeven in de module 'Artikelen - Gerelateerd'.
- **Auteur** Optionele invoer voor een auteursnaam binnen de metadata. Als je iets invoert, creëert dit een HTML-meta-element met het naamattribuut 'auteur' en het inhoudsattribuut zoals hier ingevoerd.
- **Robots** De instructies voor web'robots' die naar deze pagina browsen.
  - *index, follow* Indexeer deze pagina en volg de links op deze pagina.
  - *noindex, follow* Indexeer deze pagina niet, maar volg nog steeds de links op de pagina. Bijvoorbeeld, je wilt dit misschien doen voor een site-mappagina waar je wilt dat de links worden geïndexeerd maar je wilt niet dat deze pagina in zoekmachines verschijnt.
  - *index, nofollow* Indexeer deze pagina, maar volg geen enkele link op de pagina. Bijvoorbeeld, je wilt dit misschien doen voor een evenementenagenda, waar je wilt dat de pagina in zoekmachines verschijnt, maar je wilt niet dat elk evenement wordt geïndexeerd.
  - *noindex, nofollow* Indexeer deze pagina niet en volg geen enkele link op de pagina.
  - *Gebruik Globaal* Ingesteld in Globale Configuratie: Metadata-instellingen.

*Voorzien van vertaling door openai.com*

