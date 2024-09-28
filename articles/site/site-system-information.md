<!-- Filename: Help4.x:Site_System_Information  / Display title: Systeeminformatie -->

## Beschrijving

De *Systeeminformatie* pagina biedt informatie over de hostserveromgeving. Er zijn vijf verschillende tabpanelen: Systeeminformatie, PHP-instellingen, Configuratiebestand, Maprechten en PHP-informatie. Elk paneel biedt gedetailleerde informatie over dat aspect van de site. Het is nuttig bij het oplossen van installatieproblemen.

- Let op dat geen van deze instellingen kan worden gewijzigd vanuit deze panelen. Dit moet op verschillende locaties in de Joomla!-installatie worden gedaan, afhankelijk van de specifieke instelling.
- Sommige instellingen kunnen worden gewijzigd vanaf de pagina Globale Configuratie. Andere zijn afhankelijk van de hostserverconfiguratie en kunnen niet van binnen Joomla! worden gewijzigd.

### Algemene Elementen

Sommige aspecten van deze pagina worden behandeld in aparte helpartikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).

## Toegang verkrijgen

- Selecteer **Systeem → Informatiepaneel → Systeeminformatie**
  in het menu van de Beheerder.

## Schermafbeelding

![startdashboard](../../../nl/afbeeldingen/site/systeem-informatie-tabblad.png)

## Formulieren Tabs

### Systeeminformatie Tab

- **PHP Gebouwd op** Biedt details over het belangrijkste besturingssysteem waarop de webserver draait waarop Joomla draait.
- **Databasetype** Biedt het type database dat wordt gebruikt door de installatie van Joomla.
- **Databaseversie** Biedt de huidige versie van de MySQL database die wordt gebruikt door de installatie van Joomla.
- **Database Collatie** Hoe de MySQL database is gestructureerd voor de informatie die door Joomla! wordt gebruikt.
- **Database Connectie Collatie** Het karakterset en collatie van de database.
- **PHP Versie** Biedt de huidige versie van de PHP-server side script die wordt gebruikt voor deze installatie van Joomla.
- **Webserver** Biedt het huidige type en versie van de webserver waarop de installatie van Joomla! draait.
- **Webserver naar PHP Interface** Het script dat interactie mogelijk maakt tussen de webserver (in de meeste gevallen, Apache) en de PHP-scripttaal.
- **Joomla! Versie** Biedt de huidige versie van Joomla!. Het wordt aanbevolen om dit altijd up-to-date te houden en de huidige stabiele release te gebruiken.
- **User Agent** De samenvatting van het besturingssysteem en de browserinformatie van de lokale machine van de huidige gebruiker die wordt gebruikt om een unieke sessie-ID te creëren voor toegang en functionaliteit binnen de Joomla! website.

### PHP-instellingen Tab

![home dashboard](../../../nl/images/site/php-settings-tab.png)

Dit scherm toont PHP-informatie. Als een van deze als onjuist wordt gemarkeerd, moeten ze worden gecorrigeerd.

- **Veilige Modus** Aanbevolen instelling: UIT
- **Open basedir** Aanbevolen instelling: Site-afhankelijk
- **Fouten Weergeven** Aanbevolen instelling: UIT
- **Korte Open Tags** Aanbevolen instelling: AAN
- **Bestanden Uploaden** Aanbevolen instelling: AAN
- **Magic Quotes** Aanbevolen instelling: UIT
- **Globals Registreren** Aanbevolen instelling: UIT
- **Output Buffering** Aanbevolen instelling: UIT
- **Sessiebestand Pad** Aanbevolen instelling: Site-afhankelijk
- **Sessie Auto Start** Aanbevolen instelling: 0
- **XML Ingeschakeld** Aanbevolen instelling: JA
- **Zlib Ingeschakeld** Aanbevolen instelling: JA
- **Native ZIP Ingeschakeld** Aanbevolen instelling: JA
- **Uitgeschakelde Functies** Aanbevolen instelling: Site-afhankelijk
- **Multibyte String (mbstring) Ingeschakeld** Aanbevolen instelling: JA
- **Iconv Beschikbaar** Aanbevolen instelling: JA
- **Maximum Input Variabelen** Aanbevolen instelling: 2500

### Configuratiebestand Tab

![home dashboard](../../../nl/images/site/configuration-file-tab.png)

Deze tab toont de inhoud van het huidige Joomla! *configuration.php* bestand dat is opgeslagen in de `path-to-joomla-root` directory. Dit bestand wordt automatisch voor u aangemaakt wanneer u Joomla! voor het eerst installeert en waar de meeste wijzigingen van de globale configuratie gedeelten van Joomla! worden vastgelegd. Houd er rekening mee dat geen van de instellingen vanaf deze pagina kunnen worden gewijzigd. Gebruik de Global Configuration voor meer informatie over deze instellingen en om wijzigingen aan te brengen.

### Mapmachtigingen Tab

![home dashboard](../../../nl/images/site/folder-permissions-tab.png)

Deze tab toont een lijst van de directories waar de webserver schrijftoegang tot moet hebben. Houd er rekening mee dat alle directories die op deze pagina worden vermeld **Schrijfbaar** zouden moeten zijn. Zo niet, dan moet u mogelijk de machtigingen wijzigen om Joomla! succesvol te kunnen installeren en gebruiken. Het configuration.php bestand is inbegrepen en wordt weergegeven als **Niet Schrijfbaar**.

### PHP Informatie Tab

![home dashboard](../../../nl/images/site/php-information-tab.png)

Deze tab toont de configuratie-instellingen van de PHP-server-side scriptingtaal die Joomla! gebruikt, samen met alle bijbehorende systeeminformatie die bijdragen aan de creatie van de webserver. Het is de output van een geïntegreerd php.info script ingebouwd in Joomla!.

PHP is geïnstalleerd en draait op de server (vandaar de server-side hierboven), en daarom worden alle instellingen op de server aangepast. De bezoeker van de website hoeft niets bijzonders op zijn lokale machine te hebben om een extra functionaliteit te bekijken of te gebruiken die PHP aan de website geeft.

Alle instellingen die waarschijnlijk ooit nodig zijn worden hier weergegeven. Eventuele wijzigingen die nodig zijn, worden aangebracht binnen de *php.ini* en andere configuratiebestanden op de webserver.

Hoeveel controle een website-eigenaar over deze informatie heeft, hangt af van of hij de server bezit of als de serverhost flexibel is in hun klantbenadering.

Het is een goede gewoonte om de beperkingen van een bepaalde serverinstallatie te kennen. Deze schermuitvoer wordt gebruikt om gedetailleerde informatie te vinden over hoe PHP op de server wordt geïmplementeerd.

Voor volledige details over de informatie in de PHP Info tab, bezoek: [http://php.net/phpinfo](http://php.net/phpinfo).

## Tips

- Als je problemen hebt met het installeren van extensies, het uploaden van bestanden of
  het wijzigen van configuratieopties, controleer dan het tabblad Directory Permissions
  om er zeker van te zijn dat je toestemming hebt om bestanden op je webserver te schrijven.
  De *Status* van de mappen moet *Beschrijfbaar* zijn. Zo niet, dan kun je mogelijk geen
  bestanden in deze mappen uploaden of bewerken.
- Wanneer je hulp zoekt bij installatieproblemen, bijvoorbeeld in een
  Joomla! webforum, is het erg nuttig om specifieke informatie over
  je Joomla! installatie te plaatsen. Deze pagina is een gemakkelijke manier om
  al deze informatie op één plek te vinden. Nog beter - gebruik de 
  **Forum Post Assistant** die gedocumenteerd staat bovenaan de 
  individuele Joomla Forum pagina's, zoals het 
  [Algemene Vragen](https://forum.joomla.org/viewforum.php?f=834) forum.

*Vertaald door openai.com*

