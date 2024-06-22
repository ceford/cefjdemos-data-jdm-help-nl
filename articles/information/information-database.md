<!-- Filename: Help4.x:Information:_Database / Display title: Informatie: Database -->

## Beschrijving

Dit scherm controleert of uw database tabel structuur up-to-date is met
de Joomla programma's en laat u proberen problemen op te lossen die
gevonden zijn. In een normale Joomla versie update, worden wijzigingen
aan de database tabelstructuur (ook "schema" genoemd) automatisch gedaan
om de database versie synchroon te houden met de Joomla versie. Als een
update handmatig is uitgevoerd, of een deel van een automatische update
fout gaat, kan de het database schema niet bijgewerkt worden om aan te
sluiten op de versie van de Joomla programma bestanden. In dat geval
ziet u een lijst met database problemen op het scherm. U kunt normaliter
ieder probleem oplossen door op de 'Repareren' knop te drukken.

## Hoe toegang te krijgen

- Selecteer **Systeem → Gegevens venster → Database** vanuit het
  beheermenu.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/0/0f/Help-4x-extension_manager-database-screen-nl.png/800px-Help-4x-extension_manager-database-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/0f/Help-4x-extension_manager-database-screen-nl.png/1200px-Help-4x-extension_manager-database-screen-nl.png 1.5x, https://docs.joomla.org/images/0/0f/Help-4x-extension_manager-database-screen-nl.png 2x"
data-file-width="1201" data-file-height="418" width="800" height="278"
alt="extension manager database screen" />

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
- **Problemen.** Als er problemen zijn dan worden ze hier getoond. Een
  hover tooltip biedt meer informatie.
- **Database versie.** Het versienummer van de database.
- **Manifest versie.** Het versienummer van Joomla of de extensie uit
  het manifestbestand.
- **Map.** Als de extensie een plugin is, de submap van uw Joomla!
  installatie /plugins map waar de extensie staat.
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
- **-Selecteer type-.** Selecteer het extensietype uit de drop-down
  lijst met beschikbare extensietypes.
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

- **Update Structure**. This program attempts to fix any database table
  structure problems found in the Database check. It runs any database
  schema change scripts (from the folder
  `administrator/components/com_admin/sql/updates`) that were not run
  during the version update. It then re-checks whether or not the
  database is up to date. If it is successful, the message "Database
  table structure is up to date" will show.
- **Opties.** Opent het venster Opties, waar instellingen zoals de
  standaard parameters kunnen worden bewerkt.
- **Help**. Opent dit helpscherm.

## Snelle tips

- Gebruik, als u problemen ondervindt tijdens het een update, de
  Database controle om te zien of uw database juist geüpdatet is.
- Er wordt zeer aangedrongen dat u de Joomla!
  update
  component gebruikt om uw site te updaten. Op deze manier worden de
  database updates automatisch uitgevoerd.
