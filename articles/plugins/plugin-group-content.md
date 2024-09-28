<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Content_Group  / Display title: Inhoudsgroep -->

## Groepsbeschrijving

### Content - Bevestig Toestemming

![Content bevestig toestemming plugin](../../../en/images/plugins/plugin-group-content-confirm-consent.png)

- **Korte Privacyverklaring** Korte tekst die boven het Privacytoestemmingsvak wordt weergegeven.
- **Privacy Artikel** Selecteer of maak indien nodig je Privacy Artikel om te linken naar je formulier.

Voor meer informatie, zie Privacy Toestemming - Plugin Configuratie

### Content - Contact

![Content contact plugin](../../../en/images/plugins/plugin-group-content-contact.png)

- **Doorverwijzing** Je kunt de naam van de auteur linken naar:
  - Geassocieerde contactpagina.
  - Webpagina die in het geassocieerde contactprofiel is opgegeven.
  - E-mail die in het geassocieerde contactprofiel is opgegeven.
- **Link ook toepassen op aliasnaam** Link naar de echte gebruikersgegevens zelfs als een aliasnaam van de auteur is ingesteld in de artikelopties.

### Content - E-mailverhulling

Deze plugin verhult alle e-mails in content met behulp van JavaScript om spambots te dwarsbomen. Dit helpt voorkomen dat e-mails in artikelen worden toegevoegd aan spamlijsten. Je kunt E-mailverhulling in een artikel uitschakelen door {emailcloak=off} ergens in de tekst van het artikel in te voegen. In dit geval zullen geen e-mailadressen in het artikel door deze plugin verhuld worden.

![Content e-mailverhulling plugin](../../../en/images/plugins/plugin-group-content-email-cloaking.png)

- **Modus** Hoe de e-mails worden weergegeven. Opties zijn *Als aanklikbaar mailto-adres* of als *Niet-aanklikbare tekst*.

### Content - Velden

Deze plugin stelt je in staat om een aangepast veld weer te geven die is ingevoegd met de *Button - Velden* plugin of met behulp van Syntax: `{veld #}` direct in het editorgebied. Syntax:

- **`{veld 1}`** zal het veld met ID 1 weergeven.
- **`{veld 1,foo}`** zal het geselecteerde veld weergeven met behulp van de alternatieve layout `foo`.
- **`{veldgroep 2}`** zal alle velden binnen de veldgroep met ID 2 weergeven.

### Content - Joomla

![Content Joomla plugin](../../../en/images/plugins/plugin-group-content-joomla.png)

- **Categorie Verwijdering Controleren** Controleer of categorieën volledig leeg zijn voordat ze worden verwijderd.
- **E-mail bij Nieuw Site Artikel** Stuur een e-mail naar gebruikers als *E-mail versturen* aan staat wanneer er een nieuw artikel via de Frontend wordt ingediend.

### Content - Modules Laden

Deze plugin stelt je in staat om een Module in een Artikel te plaatsen met de syntax: `{loadposition xx}`, waarbij `xx` een door de gebruiker gedefinieerde positietag is. Bijvoorbeeld, als je een Module creëert met de Positie-waarde `myposition1`, dan zal het typen van de tekst `{loadposition myposition1}` binnen een Artikel die Module op dat punt in het Artikel weergeven.

![Content modules laden plugin](../../../en/images/plugins/plugin-group-content-load-modules.png)

- **Stijl** De stijl voor de geladen Module.

### Content - Pagina Onderbreking

Deze plugin voegt inhoudsopgavefunctionaliteit toe aan een gepagineerd Artikel. Dit wordt automatisch gedaan door de Paginaonderbrekingsknop die aan de onderkant van het tekstpaneel in een Artikel is toegevoegd te gebruiken. De HTML-code wordt hier als referentie opgenomen van wat beschikbaar is. De Paginaonderbreking zelf wordt weergegeven in het tekstvenster als een simpele horizontale lijn.

![Content pagina onderbreking plugin](../../../en/images/plugins/plugin-group-content-page-break.png)

- **Site Titel Weergeven** Of de titel en kopattributen van de plug-in worden toegevoegd aan de Site Titel-tag.
- **Artikel Index Kop** Toon of verberg de Artikel Index Kop. De Kop wordt bovenaan de Inhoudsopgave weergegeven.
- **Aangepaste Artikel Index Kop** Voer een aangepaste tekst in voor de Artikel Index Kop. Als deze leeg is, wordt de standaard gebruikt.
- **Inhoudsopgave** Verberg of toon een inhoudsopgave voor meerbladige Artikelen.
- **Alles Tonen** Of gebruikers de optie krijgen om alle pagina's van een Artikel te tonen.
- **Presentatiestijl** Toon het artikel met afzonderlijke pagina's, tabs of schuifregelaars.

![Content pagina onderbreking beschrijving](../../../en/images/plugins/plugin-group-content-page-break-description.png)

### Content - Paginanavigatie

Deze plugin stelt je in staat om Volgende & Vorige navigatielinks toe te voegen aan Artikelen, bijvoorbeeld wanneer je een blog- of lijstindeling gebruikt. Deze functie kan worden gecontroleerd met de volgende Joomla! parameters:

- **Navigatie Weergeven** in het Artikel - Globale Configuratie scherm
- **Navigatie Weergeven** in de Parameters - Component-sectie van het Menu-item - Nieuw/Bewerken - Parameters - Component voor Artikelen scherm voor Artikelindelingen.

Merk op dat, als de Paginanavigatie plug-in is uitgeschakeld in dit scherm, er geen Paginanavigatie wordt weergegeven en de bovenstaande parameters geen effect hebben.

![Content paginanavigatie plugin](../../../en/images/plugins/plugin-group-content-page-navigation.png)

- **Positie** Positie van de navigatielink. Opties zijn *Boven* het Artikel of *Onder* het Artikel.
- **Relatief Aan** Bepaald de relatieve locatie voor de Positie parameters. Tekst zal het direct boven of onder de artikelinhoud plaatsen. Volledig Artikel zal het boven of onder de volledige weergave inclusief titel en lees meer plaatsen.
- **Link Tekst** Kies wat er als de linktekst wordt weergegeven.

### Content - Slimme Zoekopdracht

Wijzigingen aan de inhoud zullen de index van Slimme Zoekopdracht niet bijwerken als je deze plugin niet inschakelt.

### Content - Stemmen

![Content stemmen plugin](../../../en/images/plugins/plugin-group-content-vote.png)

- **Positie** Positie van de stemming.

*Vertaald door openai.com*


