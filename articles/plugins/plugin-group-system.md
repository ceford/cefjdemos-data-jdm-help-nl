<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_System_Group  / Display title: Systeemgroep -->

## Groepsbeschrijving

### Systeem - Extra Toegankelijkheidsfuncties

Deze plugin voegt een toegankelijkheidstoolbar toe aan je site met extra toegankelijkheidsopties.

![Systeem extra toegankelijkheidsfuncties formulier](../../../en/images/plugins/plugin-group-system-additional-accessibility-features.png)

### Systeem - Debug

Deze plugin biedt foutopsporingsinformatie. Het rapport wordt onder het hoofdscherm van de voor- en achterkant van een Joomla!-installatie weergegeven.

#### Plugin tabblad

![Systeem debug formulier plugin tab](../../../en/images/plugins/plugin-group-system-debug-plugin-tab.png)

- **Toegestane Groepen** Gebruikersgroepen die de foutopsporingsinformatie zullen zien wanneer deze is ingeschakeld.
- **Profiling Tonen** Of de profileringsgegevens getoond moeten worden.
- **Queries Tonen** Of de SQL-querylog moet worden opgenomen in de foutopsporingsinformatie.
- **Geheugengebruik Tonen** Of de gegevens over het geheugengebruik moeten worden opgenomen in de foutopsporingsinformatie.

#### Taal tabblad

![Systeem debug formulier taal tab](../../../en/images/plugins/plugin-group-system-debug-language-tab.png)

- **Fouten tonen bij het parsen van taalbestanden** Of een lijst van taalbestanden met fouten getoond moet worden vanwege non-compliance met de Joomla! taalbestand specificatie.
- **Taalbestanden Tonen** Of de geladen taalbestanden getoond moeten worden om de pagina te genereren.
- **Taalstring Tonen** Of niet-gedefinieerde taalstrings moeten worden opgenomen in de foutopsporingsinformatie.
- **Eerste Woord Verwijderen** Of altijd het eerste woord in meervoudige woordenstrips moet worden verwijderd.
- **Van Begin Verwijderen** Verwijdert de opgegeven woorden vanaf het begin van de taalstring. Voor meerdere woorden, scheid elk woord met het pipe ( | ) teken, bijvoorbeeld: woord1|woord2
- **Van Einde Verwijderen** Verwijdert de opgegeven woorden vanaf het einde van de taalstring. Voor meerdere woorden, scheid elk woord met het pipe ( | ) teken, bijvoorbeeld: woord1|woord2

#### Loggen tabblad

![Systeem debug formulier loggen tab](../../../en/images/plugins/plugin-group-system-debug-logging-tab.png)

### Systeem - Velden

De systeemveldenplugin die nodig is om de aangepaste velden weer te geven.

### Systeem - HTTP Headers

Deze plugin kan Security HTTP Headers instellen. Raadpleeg de HTTP Header Management documentatie voor meer details over deze plugin.

![Systeem http headers formulier](../../../en/images/plugins/plugin-group-system-http-headers.png)

### Systeem - Highlight

Systeemplugin om gespecificeerde termen te markeren.

### Systeem - Takenplanner

Deze plugin zoekt naar taakplugins om uit te voeren.

![Systeem takenplanner formulier](../../../en/images/plugins/plugin-group-system-job-scheduler.png)

- **Frequentie (in minuten)** Stel in op nul om bij elke paginalading te draaien (voor testen).
- **Webcron** Stel in op Ja om als een CLI-commando te bellen. Voor meer informatie zie Schrijven van een CLI Applicatie.
- **Activeringssleutel** De sleutel die moet worden doorgegeven in een Webcron-commando.

### Systeem - Joomla! Statistieken

![Systeem joomla statistieken formulier](../../../en/images/plugins/plugin-group-system-joomla-statistics.png)

- **Unieke ID** Een identificatie die het Joomla!-project in staat stelt om unieke installaties van de plugin te tellen. Dit wordt samen met de statistieken teruggestuurd naar de server.
- **Interval (uren)** Statistieken worden elke X uur verzonden. De standaard is 12.
- **Modus** Kies de wijze waarop je de statistieken wilt versturen.

### Systeem - Joomla! Update Melding

![Systeem joomla update melding formulier](../../../en/images/plugins/plugin-group-system-joomla-update-notification.png)

- **Super User Emails** Een door komma's gescheiden lijst van de e-mailadressen die de update meldings-e-mails zullen ontvangen. De adressen in de lijst MOETEN behoren tot bestaande gebruikers van je site die de Super User-privilege hebben. Als geen van de vermelde e-mails toebehoort aan Super Users, of als het leeg is gelaten, zullen alle Super Users van deze site de update meldingse-mail ontvangen.
- **E-mail Taal** Als je Auto (standaard) kiest, zal de update meldings-e-mail naar Super Users in de site-taal zijn op het moment dat de plugin wordt geactiveerd. Door hier een taal te selecteren, dwing je de update meldings-e-mails te verzenden in deze specifieke taal.

### Systeem - Taalcode

Biedt de mogelijkheid om de taalcode in het gegenereerde HTML-document te wijzigen om de SEO te verbeteren. De velden verschijnen wanneer de plugin is ingeschakeld en opgeslagen. Meer informatie op W3.org.

### Systeem - Taalfilter

![Systeem taalfilter formulier](../../../en/images/plugins/plugin-group-system-language-filter.png)

- **Taalselectie voor nieuwe Bezoekers** Of de standaardtaal van de site moet worden gekozen of de browserinstellingen automatisch moeten worden gedetecteerd.
- **Automatische Taalwijziging** Deze optie wijzigt automatisch de taal die in de Frontend wordt gebruikt wanneer een gebruiker de site-taal wijzigt.
- **Associaties** Staat item associatie toe bij het wisselen van de ene taal naar de andere.
- **Alternatieve Meta Tags Toevoegen** Voeg alternatieve meta tags toe voor menu-items met geassocieerde menu-items in andere talen.
- **x-default Meta Tag Toevoegen** Voeg x-default meta tag toe om de SEO te verbeteren.
- **x-default Taal** Kies je x-default taal.
- **URL Taalcode Verwijderen** Of je de gedefinieerde URL Taalcode (bijv. jouw_domeinnaam/en) van je Inhoudstaal wilt verwijderen die overeenkomt met de standaardtaal van de site wanneer SEF URL is ingesteld op *Ja*.
- **Cookie Levensduur** Taalcookies kunnen worden ingesteld om te verlopen aan het einde van de *Sessie* of na een *Jaar*.

### Systeem - Log Rotatie

![Systeem log rotatie formulier](../../../en/images/plugins/plugin-group-system-log-rotation.png)

- **Log Rotatie (in dagen)** Hoe vaak de logs moeten worden geroteerd.
- **Maximale Logs** Het maximaal aantal oude logs dat behouden moet blijven.

### Systeem - Uitloggen

De systeem uitlogplugin stelt Joomla in staat om de gebruiker naar de homepage te leiden als deze ervoor kiest om uit te loggen terwijl hij op een pagina met beveiligde toegang is.

### Systeem - Pagina Cache

Deze plugin maakt paginacaching mogelijk. Paginacaching stelt de webserver in staat om snapshots van pagina's op te slaan en te gebruiken bij het serveren van webpagina's. Dit verbetert de prestaties van je website en vermindert de belasting van de server. Deze plugin heeft de volgende opties:

![Systeem pagina cache formulier](../../../en/images/plugins/plugin-group-system-page-cache.png)

- **Browser Caching Gebruiken** Of je het mechanisme wilt gebruiken om een paginacache op te slaan in de lokale browser. De standaard is *Nee*.
- **Menu-items Uitsluiten** Selecteer welke menu-items je wilt uitsluiten van caching.

### Systeem - Privacy Consent

Deze plugin stelt je in staat om de toestemming van je gebruikers voor het privacybeleid van de site te verzamelen en het verlopen van de toestemming te beheren.

![Systeem privacy consent formulier](../../../en/images/plugins/plugin-group-system-privacy-consent.png)

- **Kort Privacybeleid** Hiermee kun je een samenvatting van je privacybeleid invoeren of de bestaande behouden.
- **Privacytype** Kies tussen Artikel en Menu-item. Afhankelijk van je keuze zal een van de twee volgende velden aanwezig zijn.
- **Privacy Artikel** Selecteer of creëer een Artikel voor je privacybeleid om te linken naar het formulier van je gebruiker.
- **Privacy Menu-item** Selecteer of creëer een Menu-item dat is gekoppeld aan een Artikel met je privacybeleid.
    - *Opmerking:* Wees extra voorzichtig met meertalige sites. Het is het beste om ervoor te zorgen dat het Artikel of Menu-item voorkomt als Associaties in alle talen.
- **Doorstuurbericht** Het bericht dat wordt weergegeven bij het doorsturen. Voer je eigen bericht in of behoud het bestaande.

![Systeem privacy consent formulier verval tab](../../../en/images/plugins/plugin-group-system-privacy-consent-expiration.png)

- **Inschakelen** (Ja/Nee) Vervalmelding is standaard uitgeschakeld. Schakel het in als je controles wilt uitvoeren voor het verlopen van privacytoestemmingen.
- **Periodieke Controle (dagen)** (0 tot 120 dagen) Standaard 30 dagen. Als Verval is ingeschakeld, definieer het aantal dagen voor de controle.
- **Vervaldatum** (180 tot 720 dagen) Standaard 360 dagen. Als Verval is ingeschakeld, definieer het aantal dagen waarop de privacytoestemming vervalt.
- **Herinneren** (0 tot 120 dagen) Standaard 30 dagen. Als Verval is ingeschakeld, definieer het aantal dagen waarop een herinnering moet worden verzonden voordat de privacytoestemming vervalt.

### Systeem - Redirect

![Systeem redirect formulier](../../../en/images/plugins/plugin-group-system-redirect.png)

- **URLs Verzamelen** Deze optie regelt de verzameling van URLs. Dit is handig om onnodige belasting van de database te voorkomen.
- **Domeinnaam Inbegrepen in Vervallen URLs** Sla de vervallen URL op als absoluut (inclusief domein) of relatief (exclusief domein).
- **URLs Uitsluiten** Definieer reguliere expressies of termen die moeten worden uitgesloten van opslag.

### Systeem - Wachtwoord Onthouden

Deze plugin biedt *Wachtwoord Onthouden* functionaliteit. Dit stelt de website in staat om je gebruikersnaam en wachtwoord te *onthouden* zodat je automatisch kunt worden ingelogd wanneer je terugkeert naar de site. Deze plugin heeft geen opties.

### Systeem - SEF

Deze plugin voegt SEF-ondersteuning toe aan links in het document. Het opereert direct op de HTML en vereist geen speciaal tag. Het heeft de volgende opties:

![Systeem sef formulier](../../../en/images/plugins/plugin-group-system-sef.png)

- **Site Domein** Als je site via meer dan één domein toegankelijk is, voer hier het voorkeursdomein (soms het canonieke domein genoemd) in. Let op: https://example.com en https://www.example.com zijn verschillende domeinen.

### Systeem - Sessie Data Opschoning

![Systeem sessie data opschoning formulier](../../../en/images/plugins/plugin-group-system-session-data-purge.png)

- **Inschakelen Sessie Data Opschoning** Wanneer ingeschakeld, zal deze plugin proberen verlopen data te verwijderen op basis van de frequentie berekend door de waarschijnlijkheid en de deler.
- **Inschakelen Sessie Metadata Opschoning** Wanneer ingeschakeld, zal deze plugin optionele sessie metadata uit de database verwijderen. Merk op dat deze operatie niet wordt uitgevoerd wanneer de database handler in gebruik is, aangezien die data wordt verwijderd als onderdeel van de Sessie Data Opschoning operatie.
- **Waarschijnlijkheid** In combinatie met het deler veld, worden deze twee velden gebruikt om de frequentie van de sessie data opschoning operatie te bepalen die op verzoek wordt geactiveerd.
- **Deler** In combinatie met het waarschijnlijkheid veld, worden deze twee velden gebruikt om de frequentie van de sessie data opschoning operatie te bepalen die op verzoek wordt geactiveerd. De waarschijnlijkheid wordt berekend door het gebruik van waarschijnlijkheid/deler, bijvoorbeeld 1/100 betekent dat er een 1% kans is dat het proces bij elk verzoek wordt uitgevoerd.

### Systeem - Snel Naar Navigatie

De plugin maakt een dropdownmenu bestaande uit de links naar de belangrijke plaatsen op een gegeven webpagina. Dit maakt het makkelijker voor toetsenbord- en schermlezer-gebruikers om snel naar de gewenste locatie te springen door deze uit de lijst met opties te kiezen.

![Systeem snel naar navigatie formulier](../../../en/images/plugins/plugin-group-system-skip-to-navigation.png)

### Systeem - Gebruikersacties Log

![Systeem gebruikersacties log formulier](../../../en/images/plugins/plugin-group-system-user-actions-log.png)

- **Dagen om logs na te verwijderen** Geef op hoeveel dagen logs moeten worden bewaard voordat ze worden verwijderd. Voer 0 in als je de logs niet wilt verwijderen.

### Systeem - Gebruikerslog

![Systeem gebruikerslog formulier](../../../en/images/plugins/plugin-group-system-user-log.png)

- **Log Gebruikersnamen** Deze optie logt de gebruikersnaam die is gebruikt wanneer een authenticatie mislukt.

*Vertaald door openai.com*

