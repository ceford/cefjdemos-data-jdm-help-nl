<!-- Filename: Help4.x:Smart_Search:_Indexed_Content  / Display title: Slim Zoeken: Geïndexeerde Inhoud -->

## Beschrijving

De *Slimme Zoeken: Geïndexeerde Inhoud* pagina toont een lijst van alle inhoudsitems
die zijn geïndexeerd in Slimme Zoeken.

### Gemeenschappelijke Elementen

Enkele elementen van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Lijstfilters](jdocmanual?article=help/common-elements/list-filters).
* [Kolomkoppen van de Lijst](jdocmanual?article=help/common-elements/list-column-headers).
* [Lijst Item Volgorde](jdocmanual?article=help/common-elements/list-ordering).
* [Paginanummering van de Lijst](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Als u nieuw bent met Slimme Zoeken, lees dan de 
  [Slimme Zoeken snelstartgids](https://docs.joomla.org/Smart_Search_quickstart_guide).


## Hoe toegang te krijgen

- Selecteer **Componenten → Smart Search → Index** via het Administratormenu.

## Screenshot

![smart search geïndexeerde inhoud](../../../nl/images/smart-search/smart-search-indexed-content.png)

## Index Maken

Selecteer de **Index** knop in de werkbalk. Dit opent een venster om de voortgang van de indexeringsbewerking te tonen. De indexeringsbewerking kan enige tijd duren, afhankelijk van het aantal inhoudsitems op de site en het aantal zoekwoorden en -zinnen in elk inhoudsitem. Een voortgangsbalk zal aangeven hoeveel van het indexeringsproces er tot nu toe is voltooid. Sluit dit venster niet totdat het indexeren is voltooid. Op sites met een grote hoeveelheid inhoud kan dit lang duren (tientallen minuten).

U moet de indexering uitvoeren nadat nieuwe inhoud op de website is geïntroduceerd, waar de Smart Search-functie niet automatisch van op de hoogte is. Bijvoorbeeld, batchimport van nieuwe inhoud waarbij de importeur niet automatisch Smart Search triggert om elk nieuw inhoudsitem te indexeren. OPMERKING: De Smart Search-indexering kan ook via de command-line interface (CLI) worden uitgevoerd indien nodig. Zie Automatische Smart Search-indexering instellen.

## Werkbalk

- **Index** Voert de Smart Search indexering uit. Er verschijnt een klein popup
  venster met een voortgangsbalk die vordert terwijl het indexeringsproces
  door de site-inhoud werkt.
- **Acties** Selecteer een selectievakje om de vervolgkeuzelijst te activeren.
  - **Publiceren** Maakt de geselecteerde items beschikbaar voor bezoekers van de website.
  - **Niet publiceren** Maakt de geselecteerde items niet beschikbaar voor bezoekers
    van de website.
- **Verwijderen** Verwijdert de geselecteerde contentitems. Werkt met één of meerdere
  geselecteerde contentitems. Het verwijderen van een contentitem uit Smart Search
  verwijdert het alleen uit de index en heeft geen invloed op het contentitem zelf.
- **Onderhoud**
  - **Optimaliseren**
  - **Index wissen** Zuivert de Smart Search index door alle index tabellen te legen.
    Om Smart Search te blijven gebruiken selecteer de Index knop in de Werkbalk na het
    zuiveren. WAARSCHUWING: Het zuiveren van de index maakt ook de inhoudsfilters leeg.
    Deze moeten handmatig opnieuw worden ingevoerd na een Zuiver-Index cyclus.
- **Statistieken** Toont enkele basisstatistieken over Smart Search.

## Tips

- Als je de indexer uitvoert en je krijgt een *undefined null* fout, controleer dan
  de permissies van de Joomla `/logs` directory. De webserver moet schrijfrechten
  hebben op die directory zodat de indexer werkt.
- Als de lijst leeg is, zorg er dan voor dat de Smart Search plug-in
  is ingeschakeld.

*Vertaald door openai.com*

