<!-- Filename: Help4.x:Site_Global_Configuration  / Display title: Algemene Configuratie -->

## Beschrijving

Het scherm Algemene Configuratie stelt je in staat om de Joomla-site te configureren met jouw persoonlijke instellingen. Instellingen die in dit scherm gemaakt worden, gelden voor de hele site.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in afzonderlijke Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het Tabblad Machtigingen](jdocmanual?article=help/common-elements/edit-permissions).

## Hoe te benaderen

- Selecteer **Systeem Paneel → Globale Configuratie** vanuit het startdashboard. Of...
- Selecteer **Systeem → Instellingen Paneel → Globale Configuratie** vanuit het beheerdersmenu.

## Screenshot

![wereldwijde configuratie site tab](../../../nl/images/site/global-configuration-site-tab.png)

## Formuliervelden

### Tabblad Site

#### Paneel Site

- **Sitenaam** Voer de naam van de website in. Deze zal op verschillende locaties worden gebruikt (bijvoorbeeld in de titelbalk van de Backend-browser en op Site Offline-pagina's).
- **Site Offline** Selecteer of toegang tot de Frontend beschikbaar is.
- **Offline Bericht**
    - *Verbergen*
    - *Gebruik Aangepast Bericht* Het bericht maakt gebruik van de waarde die gedefinieerd is in het veld *Aangepast Bericht*.
    - *Gebruik Standaard Bericht in Site Taal* Het bericht maakt gebruik van de waarde die gedefinieerd is in het ini-bestand van de site-taal.
- **Offline Afbeelding** Selecteer een afbeelding die op de offline pagina wordt weergegeven. Zorg ervoor dat de afbeelding minder dan 400px breed is.
- **Frontend Bewerken** Selecteer bewerken voor modules en menu-items.
- **Standaard Editor** Selecteer de standaard teksteditor. Geregistreerde Gebruikers kunnen hun voorkeur wijzigen in hun persoonlijke gegevens.
- **Standaard Captcha** Selecteer de standaard captcha voor uw site. Mogelijk moet u de vereiste informatie invoeren in de captcha plug-in.
- **Standaard Toegangsniveau** Selecteer het standaard toegangsniveau voor nieuwe items.
- **Standaard Lijstlimiet** Stelt de standaard lengte van lijsten in de Backend voor alle gebruikers in.
- **Standaard Feedlimiet** Selecteer het aantal content-items om weer te geven in de feeds.
- **Feed E-mailadres** De RSS- en Atom-nieuwsfeeds bevatten het e-mailadres van de auteur.
  - *Auteur E-mail* Voeg het e-mailadres van de artikel auteur uit het Gebruikersprofiel toe aan de nieuwsfeed.
  - *Site E-mail* Voeg het *Van E-mailadres* van de site toe aan elk artikel.

#### Paneel Metadata

- **Site Meta Beschrijving** Voer een beschrijving in van de algemene website die door zoekmachines gebruikt zal worden.
- **Robots** Robotinstructies.
  - *index, follow* Indexeer deze pagina en volg de links op deze pagina.
  - *noindex, follow* Niet indexeren deze pagina, maar volg nog steeds de links op de pagina. Zoals bij een sitemap waar je de links wilt laten indexeren maar niet de pagina zelf.
  - *index, nofollow* Indexeer deze pagina, maar volg geen enkele link op de pagina. Bijvoorbeeld bij een evenementenkalender waar je de pagina wilt tonen in zoekmachines maar niet elke gebeurtenis wilt indexeren.
  - *noindex, nofollow* Indexeer deze pagina niet en volg de links niet.
- **Inhoudsrechten** Beschrijf welke rechten anderen hebben om deze inhoud te gebruiken. Dit wordt aan zoekmachines meegedeeld via de `rights`-metatag in de HTML-kop.
- **Auteur Metatag** Toon de auteur metatag bij het bekijken van artikelen.
- **Joomla Versie** Regelt of de `generator`-metatag in de HTML-header van het document in de Frontend en in Atomfeeds de exacte versie van de Joomla-site bevat. Het wordt aanbevolen dit te verbergen om veiligheidsredenen.

#### Paneel SEO

- **Zoekmachinevriendelijke URL's** Selecteer of de URL's geoptimaliseerd zijn voor zoekmachines.
- **Gebruik URL-Herschrijving**
  - *Apache and Litespeed* Hernoem `htaccess.txt` naar `.htaccess`.
  - *IIS* Hernoem `web.config.txt` naar `web.config`.
  - *NginX* Je moet je server configureren.
  - *Other* Als je het niet zeker weet, raadpleeg dan je hostingbedrijf.
- **Voeg Suffix toe aan URL** Als ja, zal het systeem een achtervoegsel aan de URL toevoegen die gebaseerd is op het documenttype.
- **Unicode Aliassen** Kies tussen transliteratie en unicode aliassen. Transliteratie is de standaard.
- **Sitenaam in Paginatitels** Begin of eindig alle Paginatitels met de sitenaam (bijvoorbeeld, *Mijn Sitenaam - Mijn Artikelnaam*).

#### Paneel Cookies

- **Cookie Domein** Domein dat wordt gebruikt bij het instellen van sessiecookies. Voorzie domein van een '.' als de cookie voor alle subdomeinen geldig moet zijn.
- **Cookie Pad** Pad waar de cookie geldig zou zijn.

### Tabblad Systeem

![globale configuratie systeem tabblad](../../../nl/images/site/global-configuration-system-tab.png)

#### Paneel Debug

- **Debug Systeem** Als ingeschakeld wordt diagnostische informatie, taalvertaling en SQL-fouten (indien aanwezig) weergegeven. De informatie wordt onderaan elke pagina die je bekijkt in de Joomla Backend en Frontend weergegeven. Het is niet raadzaam de debug-modus geactiveerd te hebben bij een live website.
- **Debug Taal** Schakel in om de foutopsporingsindicatoren `**...**` of `??...??` te zien in de pagina-uitvoer waar Joomla Taalbestanden worden gebruikt om string-sleutels naar hun vertaalde waarden te vertalen. Het eerste formaat geeft aan dat de string succesvol is vertaald. Het tweede geeft aan dat de tekst in normale taal is ingevoerd en niet vertaald kan worden.
  - **Taalweergave** Selecteer of u de taalconstante of de taalwaarde wilt weergeven bij het debuggen van de taalstrings.

#### Paneel Cache

- **Systeemcache** Schakel cache in en stel het cacheniveau in.
  - *Conservatief niveau* kleinere systeemcache.
  - *Progressief niveau* snellere, grotere systeemcache inclusief module renderers cache. Niet geschikt voor extreem grote sites.
  - **Cache Handler**
    - *Bestand* Native caching-mechanisme is gebaseerd op bestandsopslag. Zorg ervoor dat de cachemappen beschrijfbaar zijn.
  - **Platform Specifieke Caching** Schakel in wanneer HTML-uitvoer op mobiele apparaten verschilt van andere apparaten.
  - **Cache Tijd (minuten)** De maximale tijd in minuten dat een cachebestand wordt opgeslagen voordat het vernieuwd wordt.
  - **Pad naar Cachemap** Specificeer een beschrijfbare map om cachebestanden op te slaan als je niet de standaardmap wilt gebruiken.

#### Paneel Sessie

- **Sessie Handler** Het mechanisme waarmee Joomla een Gebruiker identificeert zodra ze zijn verbonden met de website via niet-permanente cookies.
  - *Database* De databasesessie handler is de standaardhandler omdat dit de enige is die Joomla volledig kan configureren en controleren.
  - *Bestandssysteem* De bestandssysteem handler is iets sneller dan de databasesessiehandler, maar vereist dat PHP correct wordt geconfigureerd, anders kan deze crashen en wordt Joomla volledig onbruikbaar.
    - *Sessiebestand Pad* Voer een volledig bestandssysteem pad in. Zorg ervoor dat het pad de juiste rechten heeft voor PHP om bestanden te lezen en te schrijven en, indien 'session garbage collection' is ingeschakeld, om bestanden te verwijderen. Als dit pad niet is ingesteld, zal Joomla vertrouwen op de PHP `session.save_path INI` configuratie of terugvallen naar de systeemtijdelijke directory (zoals gedefinieerd door de sys_get_temp_dir() PHP functie). Als geen van deze paden zijn geconfigureerd of de rechten niet juist zijn, dan is het spel voorbij. Om te herstellen, bewerk het configuration.php bestand en stel `$session_handler = 'database'` in.
  - *Andere handlers* APCu, Memcached, Redis en WinCache zijn afhankelijk van optionele PHP-extensies en kunnen beschikbaar zijn als je systeem deze ondersteunt. APCu of WinCache zijn mogelijk niet beter dan de *eenvoudig* bestandssysteem optie. De Memcached en Redis handlers zijn overkill voor Joomla in een typische shared hosting-omgeving. Deze types handlers slagen als je Joomla implementeert in een load balanced omgeving waar meerdere servers betrokken zijn en je de sessiegegevens van de applicatie beschikbaar moet hebben over alle servers.
- **Sessie Levensduur (minuten)** Automatisch uitloggen van een Gebruiker nadat deze een bepaald aantal minuten inactief is geweest. Stel dit niet te hoog in.
- **Gedeelde Sessies** Indien ingeschakeld, wordt een gebruikerssessie gedeeld tussen de Frontend- en Backendsecties van de site. Merk op dat het wijzigen van deze waarde alle bestaande sessies op de site ongeldig maakt. Dit is niet beschikbaar wanneer de *Forceer HTTPS* optie is ingesteld op *Alleen Beheerder*.
- **Sessiemetadata bijhouden**
  - *Ja* Extra metadata over een gebruikerssessie (inclusief hun gebruikersnaam, gebruikers-ID en de applicatie waarin ze zijn ingelogd) wordt geregistreerd in de sessiedatabase tabel.
  - *Nee* Functies die afhankelijk zijn van deze gegevens zijn niet beschikbaar.

### Tabblad Server

![globale configuratie server tabblad](../../../nl/images/site/global-configuration-server-tab.png)

#### Paneel Server

- **Pad naar Tijdelijke Map** Specificeer een beschrijfbare map om tijdelijke bestanden op te slaan.
- **Gzip Pagina Compressie**
  - *Ja* Automatisch de gegenereerde HTML-pagina's comprimeren met Gzip, waardoor ze kleiner worden en de snelheidsscore van uw site toeneemt.
  - *Nee* Als uw server dit al voor u doet of als het conflicteert met extensies van derden.
- **Fout Rapportage** Deze parameter stelt het niveau van foutrapportage in dat door PHP op de Joomla-site wordt gebruikt.
  - *Systeemstandaard* Laat het foutrapportage niveau over aan wat in de server is ingesteld.
  - *Geen* Schakelt foutrapportage uit.
  - *Eenvoudig* Overschrijft de serverinstelling om een basisniveau van rapportage te geven.
  - *Maximum* Overschrijft de serverinstelling om alle fouten te rapporteren. Als uw Joomla-site zodanig faalt dat het niet mogelijk is om de beheerderspagina te gebruiken om foutrapportage in te schakelen, kan je volledige foutrapportage inschakelen door het `configuration.php` bestand te bewerken. Het instellen van `$error_reporting = 'maximum'` is gelijk aan het instellen van *Fout Rapportage* op *Maximum*.
- **Forceer HTTPS** Forceer toegang tot de site in de geselecteerde gebieden alleen via HTTPS (versleutelde HTTP-verbindingen met het https://-protocol voorvoegsel) en forceer ook het gebruik van beveiligde cookies. Let op, u moet HTTPS ingeschakeld hebben op uw server om deze optie te kunnen gebruiken.

#### Paneel Locatie

- **Website Tijdzone** Kies een stad in de lijst om de datum en tijd voor weergave in te stellen.

#### Paneel Web Services

- **Schakel CORS In** Cross-Origin Resource Sharing of [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) stelt scripts die in een browser draaien in staat om te communiceren met bronnen van een andere oorsprong.
  - **Access-Control-Allow-Origin** Geeft de oorsprong op die toegang heeft tot Webservices op deze site, teruggestuurd als antwoord op een preflight-verzoek. Standaard: `*` (=alle).
  - **Access-Control-Allow-Headers** Geeft de header(s) terug die als antwoord op een preflight-verzoek worden verzonden. Standaard: `Content-Type,X-Joomla-Token`.
  - **Access-Control-Allow-Methods** Geeft de Webservice methode(n) aan die toegang hebben tot deze site, teruggestuurd als antwoord op een preflight-verzoek. Standaard: alle methodes beschikbaar voor de aangevraagde route.

#### Paneel Proxy

- **Achter Load Balancer** Als uw site zich achter een load balancer of reverse proxy bevindt, schakel deze instelling in zodat IP-adressen en andere configuraties binnen Joomla hier automatisch rekening mee houden.
- **Schakel Uitgaande Proxy In** Sommige hosts staan standaard geen toegang vanaf uw site naar de buitenwereld toe en vereisen handmatige configuratie van een uitgaande proxy.
  - **Uitgaande Proxy Host** Host (domein) naam of IP-adres.
  - **Uitgaande Proxy Poort**
  - **Uitgaande Proxy Gebruikersnaam** Laat leeg als uw uitgaande proxy geen authenticatie vereist.
  - **Uitgaande Proxy Wachtwoord**

#### Paneel Database

- **Database Type** Het type database dat in gebruik is, geselecteerd tijdens het installatieproces. Bewerk dit veld niet tenzij het absoluut noodzakelijk is (bijvoorbeeld bij de overdracht van de database aan een nieuwe hostingprovider).
- **Host** De hostnaam voor uw database ingevoerd tijdens het installatieproces. Bewerk dit veld niet tenzij het absoluut noodzakelijk is (bijvoorbeeld bij de overdracht van de database aan een nieuwe hostingprovider).
- **Database Gebruikersnaam** De gebruikersnaam voor toegang tot uw database ingevoerd tijdens het installatieproces. Bewerk dit veld niet tenzij het absoluut noodzakelijk is (bijvoorbeeld bij de overdracht van de database aan een nieuwe hostingprovider).
- **Database Wachtwoord** Het wachtwoord dat wordt gebruikt voor toegang tot de database. Bewerk dit veld niet tenzij het absoluut noodzakelijk is (bijvoorbeeld bij de overdracht van de database aan een nieuwe hostingprovider).
- **Database Naam** De naam van uw database ingevoerd tijdens het installatieproces. Bewerk dit veld niet tenzij het absoluut noodzakelijk is (bijvoorbeeld bij de overdracht van de database aan een nieuwe hostingprovider).
- **Database Tabel Voorvoegsel** Het voorvoegsel dat gebruikt wordt voor uw database tabellen, aangemaakt tijdens het installatieproces. Bewerk dit veld niet tenzij het absoluut noodzakelijk is (bijvoorbeeld bij de overdracht van de database aan een nieuwe hostingprovider).
- **Verbinding Encryptie**
  - Standaard (server gecontroleerd)
  - Eenrichtingsauthenticatie
    - **Verifieer Server Certificaat**
      - **Pad naar CA Bestand** Bestandssysteem pad.
  - Tweezijdige authenticatie
    - **Pad naar Privé Sleutel Bestand** Bestandssysteem locatie.
    - **Pad naar Certificaat Bestand** Bestandssysteem locatie.
    - **Verifieer Server Certificaat**
      - **Pad naar CA Bestand** Bestandssysteem pad.
    - **Ondersteunde Cipher Suite (optioneel)** Geen invoer vereist (alleen aanbevolen voor ervaren gebruikers). Zie voor meer details de documentatie van uw database.

#### Paneel Mail

- **Mail Verzenden**
  - *Ja* Schakel e-mail verzenden in.
  - *Nee* Schakel e-mail verzenden uit. Het wordt aanbevolen de site offline te zetten wanneer de mailfunctie wordt uitgeschakeld.
- **Massa Mail Uitschakelen**
  - *Ja* Schakel de Massa Mail Gebruikersfunctie uit.
  - *Nee* Maak de Massa Mail Gebruikersfunctie actief.
- **Van E-mail** Het e-mailadres dat wordt gebruikt om site e-mails te verzenden.
- **Van Naam** Tekst die wordt weergegeven in het headerveld *Van:* bij het verzenden van een site e-mail. Meestal de sitenaam.
- **Antwoord-aan E-mail** Het e-mailadres dat wordt gebruikt om antwoorden van eindgebruikers te ontvangen.
- **Antwoord-aan Naam** Tekst die wordt weergegeven in het headerveld *Aan:* wanneer eindgebruikers op een ontvangen e-mail reageren.
- **Mailer** Selecteer welke mailer moet worden gebruikt voor het verzenden van site e-mail.

### Tabblad Loggen

![globale configuratie loggen tabblad](../../../nl/images/site/global-configuration-logging-tab.png)

#### Paneel Loggen

- **Pad naar Logmap** Joomla kan optioneel een logbestand bijhouden van zijn eigen en derde partij extensie operaties. Geef het absolute pad naar een map die door PHP beschrijfbaar is; als deze ontbreekt of niet beschrijfbaar is, wordt Joomla helemaal niet geladen. Gebruik om veiligheidsredenen geen map met systeem brede toegang zoals `/tmp`.
- **Log Bijna Alles** Logt alles, behalve verouderde APIs.
- **Log Verouderde API** Logt verouderde APIs.

#### Paneel Aangepast Loggen

- **Log Prioriteiten** Kan worden gebruikt voor het beheren van aangepast loggen. Selecteer de gebeurtenissen die je in het logbestand wilt zien. Standaard is *Alles*. De item(s) kunnen geselecteerd of gedeselecteerd worden door op de dropdownlijst te klikken.
- **Log Categorieën** Een door komma's gescheiden lijst van logcategorieën om in te sluiten of uit te sluiten. Veelvoorkomende logcategorieën zijn, maar zijn niet beperkt tot: `database`, `databasequery`, `database-error`, `deprecated` en `jerror`. Als het leeg is, is aangepast loggen uitgeschakeld.
- **Log Categorie Modus** Stelt de modus in voor de hierboven genoemde lijst met logcategorieën.

### Tabblad Tekstfilters

![globale configuratie tekstfilters tabblad](../../../nl/images/site/global-configuration-text-filters-tab.png)

Deze tekstfilterinstellingen worden toegepast op alle tekstredacteervelden die door gebruikers in de geselecteerde groepen worden ingediend.

Met deze filteropties heb je meer controle over de HTML die je contentproviders indienen. Je kunt zo streng of soepel zijn als je nodig acht voor je website. De filtering is opt-in en de standaardinstellingen bieden goede bescherming tegen opmaak die vaak wordt geassocieerd met websiteaanvallen.

## Tips

- De meeste van deze instellingen kunnen eenmalig worden ingesteld en daarna met rust worden gelaten.
- Als er grote wijzigingen moeten worden aangebracht, overweeg dan de site offline te halen om deze te testen en ervoor te zorgen dat alles naar behoren werkt.
- De instellingen worden opgeslagen in het `configuration.php` bestand in de hoofdmap van de site. De permissies van dit bestand worden ingesteld op alleen-lezen (444) nadat wijzigingen via de Global Configuration-pagina zijn gemaakt, en moeten eigenaars-toestemming voor schrijven (644) krijgen voordat ze met een teksteditor worden bewerkt.

*Vertaald door openai.com*

