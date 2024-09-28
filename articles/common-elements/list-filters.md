<!-- Filename: Help6.x:List_Filters  / Display title: Lijsten Filteren -->

## Doel¶

De meeste componenten hebben lijstweergaven die items uit de database weergeven. Er kunnen honderden items zijn, misschien wel duizenden of zelfs miljoenen. Dus worden Lijstfilters gebruikt om de weergegeven lijst te verkleinen tot die items die waarschijnlijk het item bevatten waar je aan wilt werken.

Bijvoorbeeld, verwijderde items worden meestal niet standaard weergegeven. Als je je verwijderde items wilt zien, moet je de **- Selecteer Status -** filter instellen op **Verwijderd**. De volgende schermafbeelding toont de Filters voor de Artikelenpagina.

## Opties voor Artikel Lijst Filteren¶

![Articles list](../../../nl/images/common-elements/articles-list-filter-options.png)

Om de opties te **tonen** of **verbergen**, selecteer de **Filteropties** knop. Let
op dat de opties altijd getoond worden bij terugkeer naar een pagina waarin een optie
is geselecteerd.

Het aantal weergegeven opties varieert afhankelijk van de component. Zelfs de Inhoud
component, die de artikellijst weergeeft, kan extra filters hebben. Bijvoorbeeld, een **- Selecteer Fase -** filter wordt weergegeven als de Inhoud component **Workflows** ingeschakeld heeft.

## De Zoekbalk

### Zoeken op Tekst

*Hover* of *Selecteer* het *Zoeken* veld om een *Tooltip* of een *Audio*
equivalent te zien of te horen dat aangeeft welke velden worden doorzocht. Het standaardgedrag
is om te zoeken naar de ingevoerde tekst binnen de titeltekst.

De inhoudscomponent maakt gebruik van een prefix om binnen de ID, Auteur of
Inhoud te zoeken. Elk van die termen heeft een dubbele punt nodig maar mag in elke *Case* zijn, bijvoorbeeld *ID:19* of *Auteur:John* of *inhoud:lorem ipsum*.

Om een zoekopdracht uit te voeren, voer een deel van de zoekterm in en selecteer het **Zoeken**
pictogram (<span class="filter-search-bar__button-icon icon-search" aria-hidden="true"></span>).

### Filteropties en Wissen

De knop **Filteropties** wordt gebruikt om de weergave van de verschillende filters in of uit te schakelen. Als er geen filters voor een component zijn, zal deze knop ontbreken.

De knop **Wissen** wordt gebruikt om alle filters te wissen en de lijst terug te brengen naar de niet-gefilterde staat. Als er geen filters voor een component zijn, zal deze knop ontbreken.

### Resultaatvolgorde

De volgorde waarin resultaten worden gepresenteerd kan door de gebruiker worden geselecteerd. Voor artikelen is
de standaardvolgorde *ID Aflopend*, wat de meest recente artikelen bovenaan de lijst plaatst. Maar je kunt ervoor kiezen om te zoeken naar artikelen met de meeste hits tijdens *Hits aflopend*, of artikelen die binnenkort verdwijnen,
*Beëindig publicatie oplopend*.

De resultaatvolgorde kan worden gewijzigd door een volgorde-pictogram in de lijstkolomkoppen te selecteren. Het standaard *ID Aflopend* pictogram wordt weergegeven door een
omlaag wijzende carre (<span class="ms-1 icon-caret-down" aria-hidden="true"></span>).
Het verandert in een omhoog wijzende carre als de sorteervolgorde wordt omgekeerd, *ID Oplopend*.

### Aantal Resultaten

Het aantal resultaten in een lijst wordt ingesteld op de Global Configuration-pagina, Site
tabblad, veld Standaard lijstlimiet. De standaardwaarde voor een nieuwe installatie is 20.

Er zijn gelegenheden waarop dit niet handig is. Je zou er bijvoorbeeld voor kunnen kiezen om *50* of
*100* resultaten te zien. Wees voorzichtig als je *Alle* kiest. Het kan lang duren om
de resultaten op te halen en de pagina weer te geven. De server kan door geheugen- of tijdoverlading een fatale fout veroorzaken. En je browser kan lange tijd nodig hebben om de pagina weer te geven.

De standaardwaarde voor deze documentatieset is ingesteld op 5 omdat dat voldoende is voor illustratieve screenshots.

## Hoe Filters te Gebruiken

Het doel van elk filter zou duidelijk moeten zijn uit het label van de niet-gefilterde selector. Bijvoorbeeld, het Artikelen **- Selecteer Status -** Filter biedt vijf keuzes: *Verwijderd*, *Niet-gepubliceerd*, *Gepubliceerd*, *Gearchiveerd* en *Alle*. De laatste is functioneel gelijk aan ongefilterd (*- Selecteer Status -*).

Wanneer een filteroptie wordt gewijzigd, laadt de pagina automatisch opnieuw met de nieuwe resultaten gefilterd door de nieuwe filteroptie.

## Kolommen Verbergen

Sommige componentenlijsten hebben veel kolommen en kunnen te breed zijn voor je scherm. Dit
is vooral het geval bij sommige vertalingen van de kolomkoptekst. Het meest
vervelende resultaat is dat de titels kunnen afbreken en moeilijk leesbaar zijn.

Om meer ruimte voor de titel te maken kun je de lijst met Kolommen openen en
minder belangrijke kolommen selecteren om te verbergen. Sluit daarna de lijst met Kolommen weer. Het
effect is direct omdat JavaScript wordt gebruikt om de geselecteerde kolommen in de
indeling te verbergen. Ze zijn nog steeds aanwezig op de pagina.

Je instellingen worden door je browser opgeslagen en zullen worden gebruikt totdat je ze
weer wijzigt, zelfs als je uitlogt en opnieuw inlogt.

*Vertaald door openai.com*

