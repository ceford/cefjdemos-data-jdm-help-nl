<!-- Filename: Help4.x:Users:_Edit_Profile  / Display title: Gebruikers: Nieuw of Bewerken -->

## Beschrijving

De pagina *Gebruikers: Nieuw of Bewerken* wordt gebruikt om een nieuwe gebruiker aan te maken of een bestaande gebruiker te bewerken.

### Gemeenschappelijke Elementen

Enkele elementen van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).

## Toegang krijgen

Om een bestaande gebruiker te bewerken:

- Selecteer **Gebruikers → Beheren** vanuit het Beheerdersmenu. Vervolgens...
  - Zoek de gewenste gebruiker en selecteer de naamlink in de
    **Naam** kolom.

Om een nieuwe gebruiker aan te maken:

- Selecteer **Gebruikers → Beheren** vanuit het Beheerdersmenu. Vervolgens...
  - Selecteer de **Nieuw** knop in de werkbalk.
- Of... Selecteer **Gebruikers → Beheren → Plus-pictogram** vanuit het Beheerdersmenu.
- Of... Selecteer **Gebruikers → Dashboard-pictogram** vanuit het Beheerdersmenu. Vervolgens...
  - Selecteer het **Plus** pictogram in het Gebruikerspaneel.
- Of... Selecteer **Startdashboard → Sitepaneel → Gebruikers Plus-pictogram** vanuit het Beheerdersmenu.

## Screenshot

![gebruikersbewerkingsdetails tabblad](../../../nl/images/users/users-edit-account-details-tab.png)

## Formulier Velden

### Account Details

- **Naam** Vul de naam van de gebruiker in.
- **Inlognaam** Vul de inlognaam (gebruikersnaam) van de gebruiker in.
- **Wachtwoord** Vul een (nieuw) wachtwoord in. Hoewel dit veld niet verplicht is, kan de gebruiker niet inloggen als er geen wachtwoord is ingesteld.
- **Bevestig Wachtwoord** Vul opnieuw het wachtwoord in uit het bovenstaande veld om het te verifiëren. Dit veld is verplicht wanneer je een nieuw wachtwoord hebt ingevuld.
- **E-mail** Vul een e-mailadres voor de gebruiker in.
- **Registratiedatum** Registratiedatum van de gebruiker.
- **Datum van laatste bezoek** Datum waarop de gebruiker de site voor het laatst bezocht heeft.
- **Datum van laatste reset** Datum en tijd van de laatste wachtwoordreset.
- **Aantal wachtwoordresets** Aantal wachtwoordresets sinds de laatste reset.
- **Ontvang systeem-e-mails** (*Ja*/*Nee*) Indien ingesteld op ja, ontvangt de gebruiker systeem-e-mails.
- **Gebruikersstatus** (*Geblokkeerd*/*Ingeschakeld*) Schakel deze gebruiker in of blokkeer deze.
- **Wachtwoord reset vereist** (*Ja*/*Nee*) Indien ingesteld op ja, moet de gebruiker zijn wachtwoord resetten bij de volgende keer inloggen op de site.
- **ID** Recordnummer in de database.

### Toegewezen Gebruikersgroepen tab

![gebruiker bewerken toegewezen gebruikersgroepen tab](../../../nl/images/users/users-edit-assigned-user-groups-tab.png)

De standaardinstelling is *Geregistreerd* maar kan worden gewijzigd op de pagina *Gebruiker: Opties*.

### Basisinstellingen

![gebruiker bewerken basisinstellingen tab](../../../nl/images/users/users-edit-basic-settings-tab.png)

- **Backend Template Stijl** Selecteer een template stijl voor de beheerinterface. Dit heeft alleen effect op deze gebruiker.
- **Backend Taal** Selecteer de taal voor de beheerinterface. Dit heeft alleen effect op deze gebruiker.
- **Frontend Taal** Selecteer de taal voor de frontend interface. Dit heeft alleen effect op deze gebruiker.
- **Editor** Selecteer een editor voor deze gebruiker. De standaard is TinyMCE tenzij gewijzigd in de globale configuratie.
- **Tijdzone** Er is een lange lijst met tijdzones om uit te kiezen, georganiseerd per continent met Europa aan het einde. De standaardtijdzone van de site is ingesteld in de globale configuratie.

### Toegankelijkheidsinstellingen

![gebruiker bewerken toegankelijkheidsinstellingen tab](../../../nl/images/users/users-edit-accessibility-settings-tab.png)

- **Monochroom** Ja/Nee
- **Hoog Contrast** Ja/Nee
- **Links Markeren** Ja/Nee
- **Lettergrootte Vergroten** Ja/Nee

### Gebruikersacties Log Opties

Deze tab is alleen beschikbaar voor Super Users!

- **Stuur notificaties voor gebruikersacties log** Indien ingesteld op ja, ontvangt de gebruiker meldingen van gebruikersacties log per e-mail.
- **Selecteer gebeurtenissen voor notificatie** Selecteer de gebruikersacties log notificaties die per e-mail verzonden moeten worden.

### W3C Web Authenticatie (WebAuthn) Inloggen

Deze tab is alleen aanwezig wanneer de site wordt benaderd via https. Voor het instellen van wachtwoordloos inloggen heb je een hardware apparaat nodig, beschikbaar bij Amazon en vergelijkbare winkels voor ongeveer £15, of een apparaat met vingerafdruk- of gezichtsherkenning of vergelijkbare biometrische software. Je kunt meer dan één authenticator toevoegen. Zodra alles is ingesteld, kun je inloggen door op de Web Authenticatie knop op het inlogformulier te klikken en vervolgens op de knop op het apparaat te drukken wanneer daarom wordt gevraagd.

Deze tab is aanwezig maar kan niet worden gebruikt in het Gebruiker bewerken formulier omdat wachtwoordloos inloggen alleen kan worden ingesteld door de individuele gebruiker via het Profiel bewerken formulier.

### Joomla API Token

Deze tab wordt gebruikt om de beveiligingstokens te beheren die gebruikt worden voor authenticatie bij de Joomla API applicatie (remote toegang tot je site). Als je niet zeker weet wat dit doet, is de kans groot dat je dit niet nodig hebt en deze instellingen veilig kunt negeren.

Het token is alleen zichtbaar voor je eigen account.

### Meervoudige Authenticatie

![gebruiker bewerken meervoudige authenticatie tab](../../../nl/images/users/users-edit-multi-factor-authentication-tab.png)

Deze tab stelt je in staat om een of meer methoden in te stellen om toegang te krijgen tot je account na inloggen met gebruikersnaam en wachtwoord. Deze tab is alleen aanwezig bij het bewerken van je eigen profiel. Er zijn verschillende methoden beschikbaar. Als je om een of andere reden de toegang tot een methode verliest, kun je een andere methode kiezen vanaf het post-login verificatiescherm. De alternatieve methoden moeten van tevoren zijn ingesteld!

#### Back-up Codes

Deze methode genereert een set nummers die je kunt opslaan of afdrukken. Elk nummer kan slechts één keer worden gebruikt, dus vergeet niet je lijst te wijzigen na gebruik.

#### Verificatiecode

Een extra formulier om in te vullen met alternatieve methoden voor het instellen van de code. Kijk en klik op de Annuleer knop als je besluit niet door te gaan.

#### Yubi Key

Dit is voor een ander type hardware key die een code op een scherm weergeeft. Kijk en selecteer Annuleren als je besluit niet door te gaan.

#### Web Authenticatie

Voor een hardware apparaat met een knop om in te drukken. Kijk en selecteer Annuleren als je besluit niet door te gaan. Merk op dat deze methode wordt overgeslagen als je de aparte WebAuthn Inloggen methode gebruikt.

#### Code per e-mail

Bij deze methode wordt een code naar je e-mailadres verzonden. Je wordt gevraagd die code in te voeren om toegang tot de site te krijgen. Het is een eenmalige code. Een nieuwe wordt verzonden bij elke login. Kijk en selecteer Annuleren als je besluit niet door te gaan.

## Tips

- Naam, Login Naam en E-mail zijn verplicht.
- Als je een specifieke taal, editor, help-website en/of
  tijdzone niet hebt ingevuld, worden de standaardinstellingen
  uit de Globale Configuratie, Taalbeheer en/of Templatebeheer gebruikt.

*Vertaald door openai.com*

