<!-- Filename: Help4.x:Fields:_Edit  / Display title: Component: Bewerkingsveld -->

## Beschrijving

De *Component: Bewerk Veld* pagina is vergelijkbaar voor alle componenten die velden implementeren, maar de paginatitel verandert afhankelijk van de context: *Artikelen: Bewerk Veld*, *Contacten: Bewerk Veld* of *Gebruikers: Bewerk Veld*.

Het tabblad **Algemeen** verandert om het type veld dat wordt bewerkt weer te geven en zodra een veld is opgeslagen, kan het veldtype niet meer worden veranderd. Het is echter eenvoudig om velden te verwijderen en nieuwe aan te maken.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in afzonderlijke Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het Publicatie Tabblad](jdocmanual?article=help/common-elements/edit-publishing).
* [Het Machtigingen Tabblad](jdocmanual?article=help/common-elements/edit-permissions).

## Hoe te Toegang te Krijgen

* Selecteer **Content → Velden** in het Beheerdersmenu. Of...
* Selecteer **Contact → Velden** in het Beheerdersmenu. Of...
* Selecteer **Gebruikers → Velden** in het Beheerdersmenu. Dan...
  * Selecteer de knop **Nieuw** in de Werkbalk om een nieuw veld aan te maken. Of...
  * Selecteer een **Titel** uit de lijst om een bestaand veld te bewerken.

**Opmerking:** Er is een dropdownlijst die het mogelijk maakt om velden aan te maken voor een Categorie en Mail in de Contacten-component. Enige programmeerervaring is vereist om geschikte sjabloonoverrides voor te bereiden.

## Screenshot

![Artikelen bewerkveld](../../../nl/images/fields/articles-edit-field.png)

## Formuliervelden

- **Titel** De titel voor dit veld.

### Algemeen tabblad

#### Linker Paneel

Parameters voor alle velden:

- **Type** Als je een veld aanmaakt, kun je een van de 16 veldtypen kiezen. Wanneer je het veld opslaat, is dit type permanent.
- **Naam** De naam zal worden gebruikt om het veld te identificeren. Laat dit leeg en Joomla vult een standaardwaarde vanuit de titel in.
- **Label** Gebruik een beschrijvende tekst van het veld voor het label van het veld. Deze tekst is niet vertaalbaar. Als je geen tekst invoert voor een label, wordt de titeltekst ook gebruikt als labeltekst.
- **Beschrijving** De beschrijving van het veld. Een tekst die als tool tip wordt weergegeven wanneer de gebruiker met de muis over het tekstvak beweegt terwijl hij het in de Backend gebruikt om een artikel of een contactpersoon of een derde partij component die velden ondersteunt te maken. Deze tekst is niet vertaalbaar. Je ziet deze beschrijving niet in de Frontend.
- **Verplicht** Is dit een verplicht veld? In dit geval moet het veld ingevuld zijn voordat je een artikel, een contactpersoon of een derde partij component die velden ondersteunt kunt indienen.

#### Rechter Paneel

- **Status** De publicatiestatus van dit veld.
  - *Gepubliceerd* Het veld is zichtbaar tijdens het bewerken van een artikel of een contactpersoon. En het is zichtbaar in de Frontend.
  - *Gedepubliceerd* Het veld zal niet zichtbaar zijn voor gebruikers tijdens het bewerken van een artikel of een contactpersoon.
  - *Gearchiveerd* Het veld zal niet langer verschijnen bij het bewerken van een artikel of een contactpersoon. Je kunt het openen in Velden wanneer je het filter op gearchiveerd zet.
  - *Prullenbak* Het veld is verwijderd maar bevindt zich nog steeds in de database. Het kan permanent worden verwijderd uit de database in Velden met de functie Prullenbak legen.
- **Veldgroep** Je kunt een veld toewijzen aan een veldgroep.
- **Categorie** Je kunt een veld toewijzen aan een of meer categorieën. Merk op dat de standaard *Alle* geen *Niet-gecategoriseerde* artikelen omvat.
- **Toegang** Selecteer het toegangsweergaveniveau voor dit veld. De toegangslevels zijn afhankelijk van wat is ingesteld in *Gebruikers: Toegangslevels*.
- **Taal** Selecteer de taal voor dit veld. Als je de meertalige functie van Joomla niet gebruikt, houd dan de standaardwaarde *Alle* aan.
- **Notitie** Een optioneel veld om je persoonlijke notities voor het veld te maken.

### Opties tabblad

![Artikelen bewerken veld opties tabblad](../../../nl/images/fields/articles-edit-field-options-tab.png)

#### Formulier Opties

- **Plaatshouder** Een plaatshoudertekst die binnen het veld verschijnt als een hint voor de invoer. De plaatshouder is actief in de Backend terwijl je een artikel of een contactpersoon of een derde partij component die velden ondersteunt maakt. Je ziet het niet in de Frontend.
- **Veldklasse** De klasse-attributen van het veld wanneer het veld wordt gerenderd. Als verschillende klassen nodig zijn, vermeld ze dan met spaties.
- **Label Klasse (Formulier)** CSS-klasse om toe te passen op het veldlabel wanneer het in de bewerkingsmodus is (invoer in een veld).
- **Bewerkbaar In** Op welk deel van de site moet het veld worden getoond. In de Backend, in de Frontend of beide?
- **Showon Attribuut** Toon of verberg het veld conditioneel afhankelijk van de waarde van andere velden. De syntaxis hier te gebruiken, bijvoorbeeld:
  `lijst-van-items:waarde1[OF]lijst-van-items:waarde2`
  - lijst-van-items: De *naam* van een reeds gemaakt veld waarop dit veld afhankelijk is om te worden getoond.
  - waarde1: De waarde die nodig is om het veld waarop het afhankelijk is te laten zien.
  - `[OF]`: Om een keuze te creëren tussen meerdere velden. In het voorbeeld wordt dit veld getoond wanneer het veld *lijst-van-items* de waarde heeft: *waarde1* OF *waarde2*
  - `[EN]`: Om meerdere velden te combineren. Dit veld wordt alleen getoond wanneer het veld *lijst-van-items* de waarde heeft: *waarde1* EN *waarde2*
  - Je kunt ook de waarde *is niet gelijk aan* gebruiken zoals in *lijst-van-items!:waarde1*. De syntaxis toont dit veld alleen wanneer *lijst-van-items* niet gelijk is aan *waarde1*
  - Om dit veld te tonen wanneer het veld *lijst-van-items* is geselecteerd en geen lege waarde heeft, gebruik de syntaxis *lijst-van-items!:* (zonder een waarde opgegeven).

**Opmerking:** Subformuliervelden hanteren de identificator *naam* van *lijst-van-items* anders. Als je een Aangepast Subformulier veld maakt en je voegt dit conditionele veld daar toe, moet je *veld\[ID\]* gebruiken in plaats van *lijst-van-items*, waar ID de id van het veld *lijst-van-items* is. Daarom moet het *showon* attribuut voor dit conditionele veld dat je maakt zijn: `veld36:waarde1[OF]veld36:waarde2` waar 36 de ID van het veld 'Lijst van items' is.

#### Weergaveopties

- **Weergave Klasse** De klasse van de veldcontainer in de output.
- **Waarde Klasse** De klasse van de veldwaarde in de output.
- **Label** Toon het label wanneer het veld wordt weergegeven.
- **Label Klasse (Uitvoer)** CSS-klasse om toe te passen op het veldlabel wanneer het wordt weergegeven (weergave van de output van een veld).
- **Automatische Weergave** Joomla biedt enkele inhoudsgebeurtenissen die worden geactiveerd tijdens het contentcreatieproces. Dit is de plaats om te definiëren hoe de velden in de inhoud moeten worden geïntegreerd. Je kunt kiezen:
  - Na Titel
  - Voor Weergave Inhoud
  - Na Weergave Inhoud
  - Niet automatisch weergeven
- **Voorvoegsel** Vaste tekst om vóór een veld weer te geven, bijvoorbeeld &pound;.
- **Achtervoegsel** Vaste tekst om na een veld weer te geven, bijvoorbeeld &euro;.
- **Lay-out** Als er een aangepaste lay-out is, zou deze hier worden geselecteerd.
- **Weergave Wanneer Alleen-lezen** Als het veld alleen-lezen is (misschien heeft de gebruiker niet het toegangslevel), moet het veld dan worden weergegeven of verborgen.

#### Smart Search

- **Zoekindex**  Waarschuwing: Wanneer *Zoekbaar maken* is geselecteerd, wordt de inhoud van het veld geïndexeerd met de weergaverechten van het inhoudsitem. Dit kan leiden tot onverwachte informatieopenbaarmaking.

*Vertaald door openai.com*

