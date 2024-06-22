<!-- Filename: Help4.x:Extensions:_Discover / Display title: Extensies: Ontdekken -->

## Beschrijving

Dit scherm geeft u de mogelijkheid extensies te ontdekken die niet door
het normale installatieproces zijn gegaan. Dit biedt een methode om
grote extensies te installeren die niet geïnstalleerd kunnen worden via
het normale proces. Sommige extensies zijn bijvoorbeeld te groot om te
uploaden via de web interface door beperkingen in de web hosting
omgeving. Door deze functie te gebruiken kunt u extensiebestanden direct
uploaden naar de server van de website door middel van andere middelen
zoals FTP of SFTP en deze extensiebestanden in de geschikte map te
plaatsen. U kunt dan de 'Ontdekken' functie gebruiken om de nieuw
geüploade extensie te vinden en hem te activeren in uw Joomla!
installatie. Door het gebruikmaken van de "Ontdekken" functie kunt u ook
meerdere extensies op hetzelfde moment ontdekken en installeren. Een
extensie kan geïnstalleerd worden via de "Ontdekken" functie door de
volgende stappen te volgen:

1.  Upload de uitgepakte extensie bestanden naar de juiste map in uw
    Joomla! installatie. Als u bijvoorbeeld een template extensie voor
    uw site naar uw Joomla! installatie wilt uploaden, dan maakt u een
    map voor het template aan in de /templates submap van uw Joomla!
    installatie. Upload daarna de template extensie bestanden naar de
    map die u heeft aangemaakt.
2.  Ga, nadat u de extensie bestanden heeft geüpload, terug naar het
    extensiebeheer - Ontdekken scherm en klik op de **Ontdekken** knop
    in de werkbalk. Dit activeert de zoekfunctie welke zoekt in uw
    extensiemappen naar niet geïnstalleerde extensies.
3.  Als de extensie die u geüpload heeft compatibel met de Joomla!
    versie is en nog niet geïnstalleerd is, dan verschijnt het in de
    gevonden extensies op dit scherm.
4.  Klik op het selectievakje links van de ontdekte extensie en klik
    daarna op de **Installeren** knop in de werkbalk. Dit installeert de
    extensie in uw Joomla! installatie.

## Hoe toegang te krijgen

- Selecteer **Systeem → Installeren venster → Ontdekken** vanuit
  het beheermenu.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/c/c8/Help-4x-Extensions-Extension-Manager-Discover-screen-nl.png/800px-Help-4x-Extensions-Extension-Manager-Discover-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c8/Help-4x-Extensions-Extension-Manager-Discover-screen-nl.png/1200px-Help-4x-Extensions-Extension-Manager-Discover-screen-nl.png 1.5x, https://docs.joomla.org/images/c/c8/Help-4x-Extensions-Extension-Manager-Discover-screen-nl.png 2x"
data-file-width="1203" data-file-height="396" width="800" height="263"
alt="Extensions Extension Manager Discover screen" />

## Kolomkoppen

- **Selectievakje**. Vink dit vakje aan om één of meer items te
  selecteren. Vink het vakje in de kolomkop aan om alle selectievakjes
  aan te vinken. Nadat één of meer vakjes zijn aangevinkt kan op een
  werkbalkknop geklikt worden om een actie uit te voeren op de
  geselecteerde item(s). De meeste acties via de werkbak, zoals
  Publiceren en Depubliceren kunnen op meerdere items tegelijkertijd
  uitgevoerd worden. Andere, zoals Bewerken, werken alleen voor één
  item. Indien er meerdere items geselecteerd zijn en op Bewerken wordt
  geklikt, opent het het eerste item om het te bewerken.
- **Naam.** De naam van de extensie.
- **Locatie.** Bepaalt of dit een website of beheer extensie is.
- **Type.** Het extensie type - module, plugin, template, taal.
- **Versie.** Het versienummer van de extensie.
- **Datum.** De datum dat deze extensie uitgebracht is.
- **Auteur.** De auteur van deze extensie.
- **Map.** Als de extensie een plugin is, staat de extensie in de submap
  van uw Joomla! installatie /plugins map. Standaard heeft Joomla! 3.x
  de volgende submappen in de plugins map welke de verschillende types
  plugins vertegenwoordigen die zijn gedefinieerd: authenticatie,
  inhoud, tekstverwerkers, editors-xtd, extensie, zoeken, systeem,
  gebruiker.
- **ID.** Het ID nummer. Dit is een unieke identificatie van dit item,
  dat automatisch toegekend wordt door Joomla!. Het wordt gebruikt om
  het item intern te identificeren, bijvoorbeeld bij interne links. U
  kunt dit nummer niet aanpassen.

## Lijst filters

**Zoekbalk**. Bovenaan de pagina vind je de zoekbalk, zoals in
bovenstaande Screenshot.

- **Zoeken op tekst**. Voer een deel van de zoekterm in en klik op het
  zoekicoon. *Hover* (muis boven item) om een *Tooltip* te zien dat
  aangeeft welke velden doorzocht worden.Om te **Zoeken op ID** geef je
  "id:x" op, waarbij "x" het item ID nummer is (bijvoorbeeld, "id:19").
- **Filteropties**. Klik om de extra filters te tonen.
- **Wissen.** om het filterveld te wissen en de lijst in zijn initiële
  status te zetten.
- **Sortering**. Toont het huidige weergave volgorde veld. Er zijn 2
  manieren om de volgorde aan te passen:
  - Selecteer uit de uitklaplijst. De volgorde kan oplopend of aflopend
    zijn.
  - Klik op een kolomkop.De kolomkop wisselt tussen een oplopend en
    aflopend volgorde.
- **Te tonen aantal.** Toont het aantal items in een lijst. Selecteer
  uit de uitklaplijst om het te tonen aantal te veranderen.De standaard
  voor een site is '20' maar dit kan veranderd worden bij de

#### Filteropties

U kunt een van de beschikbare filters gebruiken of welke combinatie dan
ook om het aantal getoonde extensies dat getoond wordt te beperken tot
de extensies die overeenkomen met uw filterparameters.

- **Selecteer locatie.** Selecteer Site, Beheerder of API uit de
  drop-down lijst van de beschikbare locaties.
- **Selecteer type.** Selecteer het extensietype uit de drop-down lijst
  met beschikbare extensietypes.
- **-Selecteer map-.** Selecteer een plugin map uit de drop-down lijst
  met beschikbare mappen. Er is een aparte map voor ieder type plugin
  gedefinieerd binnen uw installatie van Joomla.

**Paginabesturing** Als het aantal items meer is dan een pagina, zie je
een paginabesturing bij de onderkant van de pagina zoals in bovenstaande
Screenshot. Het huidige paginanummer heeft een donkere
achtergrond.

- **Begin**. Klik om naar de eerste pagina te gaan.
- **Vorig**. Klik om naar de voorafgaande pagina te gaan.
- **Paginanummers**. Klik om naar de gewenste pagina te gaan.
- **Volgende**. Klik om naar de volgende pagina te gaan.
- **Einde**. Klik om naar de laatste pagina te gaan.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Installeren**. Installeert de geselecteerde extensie.
- **Ontdekken**. Doorzoekt de Joomla! installatie-mappen op niet
  geïnstalleerde extensies. Iedere niet-geïnstalleerde extensie die
  wordt gevonden wordt getoond in de extensielijst. Slaat het resultaat
  op, zodat ze steeds getoond worden bij een nieuwe bezoek aan dit
  scherm.
- **Opties.** Opent het venster Opties, waar instellingen zoals de
  standaard parameters kunnen worden bewerkt.
- **Help**. Opent dit helpscherm.

## Snelle tips

- Als u veel extensies wilt installeren dan kunt u ze allemaal naar de
  gewenste mappen uploaden van uw Joomla! installatie en daarna dit
  scherm te gebruiken om ze allemaal in één handeling te ontdekken. U
  kunt alle extensies daarna in één stap installeren door ze allemaal te
  selecteren en op de **Installeren** knop in de werkbalk te klikken.
