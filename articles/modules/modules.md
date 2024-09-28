<!-- Filename: Help6.x:Modules  / Display title: Modules -->

## Beschrijving

Modules zijn lichte en flexibele uitbreidingen die worden gebruikt om fragmenten van informatie weer te geven in vakken die rond een component op een pagina zijn gerangschikt. Een bekend voorbeeld is de *Inlog* module. Modules worden per menu-item toegewezen, zodat je kunt beslissen om een module wel of niet weer te geven afhankelijk van welke pagina de gebruiker momenteel bekijkt.

Sommige modules zijn gekoppeld aan componenten. De module *Laatste Nieuws* is bijvoorbeeld gekoppeld aan de inhoud-component om links naar de nieuwste artikelen weer te geven. Modules hoeven niet gekoppeld te zijn aan componenten. Ze hoeven zelfs niet aan iets gekoppeld te zijn en kunnen gewoon statische HTML of tekst bevatten.

Er kunnen meerdere exemplaren van dezelfde module zijn. Je kunt bijvoorbeeld één exemplaar van de *Willekeurige Afbeelding* module voor sommige pagina's gebruiken en een ander exemplaar voor andere pagina's, waarbij elke pagina een andere afbeeldingsmap gebruikt om afbeeldingen uit te selecteren.

De lijsten *Modules (Site)* en *Modules (Beheerder)* tonen de momenteel geïnstalleerde modules in elke interface en bieden toegang om nieuwe modules toe te voegen of bestaande modules te bewerken.

### Veelvoorkomende Elementen

Sommige elementen van deze pagina worden behandeld in afzonderlijke Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Lijst Filters](jdocmanual?article=help/common-elements/list-filters).
* [Lijst Kolomkoppen](jdocmanual?article=help/common-elements/list-column-headers).
* [Lijstvolgorde](jdocmanual?article=help/common-elements/list-ordering).
* [Lijst Paginering](jdocmanual?article=help/common-elements/list-pagination).
* [Lijst Batch Verwerken](jdocmanual?article=help/common-elements/list-batch-process).

Om lijsten van geïnstalleerde modules en beschikbare modules te zien, selecteer een van de volgende:

* [Site modules](jdocmanual?article=help/modules-site/site-modules-site)
* [Beheer modules](jdocmanual?article=help/modules-admin/admin-modules-administrator)

## Toegang krijgen

- Selecteer **Content → Site Modules** in het Administrator-menu. Of...
- Selecteer **Content → Administrator Modules** in het Administrator-menu.

## Lijstenfilters

* **Site of Beheerder** Selecteert ofwel Site- of Beheerdermodules.

## Kolomkoppen

Dit is een korte lijst van de unieke koppen in de modulenlijsten.

- **Positie** De positie op de pagina waar dit module wordt weergegeven.
- **Type** De systeemnaam van het Module.
- **Pagina's** De Menu-items waar dit Module zal worden weergegeven. Dit item is 
  niet aanwezig in de administrator modulenlijsten.
  - *Alle* Weergegeven op alle pagina's
  - *Geen* Weergegeven op geen enkele pagina
  - *Geselecteerd* Weergegeven alleen op de geselecteerde pagina's
  - *Alles behalve geselecteerd* Weergegeven op alle pagina's behalve de geselecteerde
- **Toegang** Het weergaveniveau voor toegang tot dit module.
- **Taal** De taal van de modules, standaard is *Alle*. Dit item is niet aanwezig in
  administrator modulenlijsten.

### Moduleposities

Om moduleposities in een live site te bekijken, ga naar **Systeem → Sjablonen** en selecteer
de **Opties** knop in de Werkbalk. Stel *Moduleposities Voorvertoning* in op
ingeschakeld en *Opslaan*. Deze instelling is goed voor zowel site- als administrator-sjablonen. Voeg vervolgens `?tp=1` toe aan het einde van een URL die nog geen querystring bevat of `&tp=1` aan het einde van een URL die al een querystring bevat. De pagina zal alle beschikbare moduleposities tonen, ook die waaraan geen modules zijn toegewezen. Posities zijn ook te zien in het modulebewerkingsformulier.

## Tips

- Joomla-websites vereisen ten minste één Menu-module.
- Andere Module-types (bijvoorbeeld Banners) zijn optioneel.
- Sommige Modules zijn gekoppeld aan componenten. Bijvoorbeeld, elke Menu-module
  is gerelateerd aan één Menu.
- Andere Modules (bijvoorbeeld Breadcrumbs) zijn niet afhankelijk van andere inhoud.
- Meerdere voorkomens van een Module zijn toegestaan en gebruikelijk.

*Vertaald door openai.com*

