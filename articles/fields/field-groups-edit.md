<!-- Filename: Help4.x:Component:_New_or_Edit_Field_Group  / Display title: Component: Bewerken Veldgroep -->

## Beschrijving

Veldgroepen worden gebruikt om verwante velden te verzamelen onder een benoemd tabblad in een gegevensinvoerformulier. De component: Veldgroep bewerken is vergelijkbaar voor alle componenten die velden implementeren, maar de paginatitel verandert afhankelijk van de context: Artikelen: Veldgroep bewerken, Contacten: Veldgroep bewerken of Gebruikers: Veldgroep bewerken.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het Publiceer Tabblad](jdocmanual?article=help/common-elements/edit-publishing).
* [Het Rechten Tabblad](jdocmanual?article=help/common-elements/edit-permissions).

## Hoe te Toegang

* Selecteer **Content → Veldgroepen** vanuit het Administratormenu. Of...
* Selecteer **Contact → Veldgroepen** vanuit het Administratormenu. Of...
* Selecteer **Gebruikers → Veldgroepen** vanuit het Administratormenu. Dan...
  * selecteer de **Nieuw** knop in de Toolbar om een nieuw veld aan te maken. Of...
  * Selecteer een **Titel** uit de lijst om een bestaand veld te bewerken.

**Opmerking:** Er is een dropdownlijst die het mogelijk maakt om velden te maken voor een 
Categorie en Mail in de Contactcomponent. Ze vereisen enige programmeerervaring 
om geschikte sjabloonoverrides voor te bereiden.

## Screenshot

Dit voorbeeld is een *Artikelen: Bewerk Veldgroep* pagina. *Contacten: Bewerk Veldgroep*
en *Gebruikers: Bewerk Veldgroep* zijn vergelijkbaar.

![artikelen bewerk veldgroep](../../../nl/images/fields/articles-edit-field-group.png)

## Formuliervelden

- **Titel** De titel voor deze veldgroep.

### Algemeen

#### Linker Paneel

- **Beschrijving** Tekst die wordt weergegeven als een tool tip wanneer
  je over het tekstvak zweeft tijdens het aanmaken van een artikel, 
  een contactpersoon of een derde partij component die aangepaste velden ondersteunt. Deze tekst is niet
  vertaalbaar. Je ziet deze beschrijving niet in de Frontend.

#### Rechter Paneel

- **Status** De gepubliceerde status van deze veldgroep.
  - *Gepubliceerd* De veldgroep is zichtbaar tijdens het bewerken van een artikel of
    een contactpersoon. En het is zichtbaar in de Frontend.
  - *Gedepubliceerd* De veldgroep zal niet zichtbaar zijn voor gebruikers tijdens
    het bewerken van een artikel of een contactpersoon.
  - *Gearchiveerd* De veldgroep zal niet langer worden weergegeven bij het bewerken van een artikel
    of een contactpersoon. Je kunt het openen in Veldgroepen wanneer je het filter 
    op gearchiveerd zet.
  - *Verwijderd* De veldgroep is verwijderd maar staat nog steeds in de database. Het
    kan permanent uit de database worden verwijderd in Veldgroepen met de 
    functie Prullenbak Leegmaken.
- **Toegang** Selecteer het toegangs niveau voor deze veldgroep. De
  toegangsniveaus hangen af van wat er is ingesteld in Gebruikers: Toegangsniveaus.
- **Taal** Selecteer de taal voor deze veldgroep. Als je de meertalige functie van Joomla niet gebruikt, behoud dan de standaard instelling *Alle*.
- **Notitie** Een optioneel veld om je persoonlijke notities voor de veldgroep te maken.

### Opties

- **Weergeven bij Alleen-lezen** Als de veldgroep alleen-lezen is (misschien
  heeft de gebruiker niet het juiste toegangs niveau) moet de veldgroep
  weergegeven of verborgen worden.

*Vertaald door openai.com*

