<!-- Filename: Help4.x:Users:_Options  / Display title: Gebruikers: Opties -->

## Beschrijving

De pagina *Gebruikers: Opties* wordt gebruikt om globale opties voor alle gebruikers in te stellen, waaronder:

- Captcha,
- registratie toegestaan en type registratie,
- standaard gebruikersgroep voor nieuwe gebruikers,
- teller voor wachtwoord- of gebruikersnaamherstel,
- e-mailmelding van nieuwe gebruikersregistratie aan de administratie en meer.

## Hoe te Toegang Krijgen

* Selecteer **Site → Gebruikers** vanaf het *Startdashboard*. Of...
* Selecteer **Gebruikers → Beheren** uit het Beheermenu. Vervolgens...
* Selecteer de **Opties** werkbalkknop

## Screenshot

![gebruikersopties gebruikersopties-tab](../../../nl/images/users/users-options-user-options-tab.png)

## Formuliervelden

### Gebruikersopties tabblad

- **Gebruikersregistratie toestaan**
  - *Ja* Gebruikers kunnen zich registreren via de frontend van de site met behulp van de
    *Maak een account aan* link die in het inlogformulier wordt aangeboden.
  - *Nee* De *Maak een account aan* link zal niet worden weergegeven.
- **Nieuwe gebruikersregistratiegroep** De groep waaraan gebruikers standaard worden toegewezen wanneer ze zich op de site registreren. Standaard ingesteld op *Geregistreerd*.
- **Gastgebruikersgroep** De groep waaraan gasten worden toegewezen (gasten zijn bezoekers van de site die niet ingelogd zijn). Het is mogelijk om inhoud op de site te creëren die zichtbaar is voor gasten maar niet voor ingelogde gebruikers.
- **Wachtwoord versturen** Als ingesteld op *Ja* wordt het eerste wachtwoord van de gebruiker naar de gebruiker gemaild als onderdeel van de registratiemail.
- **Nieuwe gebruikersaccountactivatie**
  - *Geen* Gebruikersaccount zal direct actief zijn zonder verdere actie.
  - *Zelf* De gebruiker ontvangt een e-mail met een activatielink. Het account wordt geactiveerd wanneer de gebruiker de activatielink aanklikt.
  - *Beheerder* De gebruiker ontvangt een e-mail met een activatielink. Wanneer de gebruiker deze link aanklikt, wordt de sitebeheerder via e-mail op de hoogte gesteld en gevraagd om het account van de gebruiker te activeren.
- **Verzend e-mail naar beheerders** Verstuur e-mailmelding naar beheerders wanneer *Nieuwe gebruikersaccountactivatie* is ingesteld op *Geen* of *Zelf*.
- **Captcha** De Captcha-plug-in voor gebruikersaccountregistratie, wachtwoordherinnering en gebruikersnaamherinnering.
- **Frontend gebruikersparameters**
  - *Weergeven* Gebruikers kunnen basisinstellingen wijzigen vanaf de frontend van de site.
  - *Verbergen* Gebruikers kunnen deze instellingen niet wijzigen.
- **Frontend taal** De site-taal weergeven of verbergen.
- **Gebruikersnaam wijzigen** Gebruikers de mogelijkheid geven om hun gebruikersnaam te wijzigen.

### E-maildomeinopties tabblad

![gebruikers opties e-maildomeinen tabblad](../../../nl/images/users/users-options-email-domain-options-tab.png)

- **Domeinnaam** Voer een lijst in van toegestane en niet-toegestane e-maildomeinen. Standaard zijn alle domeinen toegestaan. Wildcards (\*) worden ondersteund. Bijvoorbeeld:
  - \* (Asterisk): Staat alle domeinen toe of disallowd ze.
  - \*.com: Staat alle '.com' domeinen toe of disallowd ze.
  - \*.joomla.org: Staat alle 'joomla.org' subdomeinen toe of disallowd ze.
- **Regel** Selecteer of het domein is toegestaan of niet.

### Wachtwoordopties tabblad

![gebruikers opties wachtwoordopties tabblad](../../../nl/images/users/users-options-password-options-tab.png)

- **Maximaal aantal resets** Het maximale aantal wachtwoordresets dat binnen de tijdsperiode is toegestaan. Nul betekent geen limiet.
- **Reset periode** De tijdsperiode, in uren, voor de reset-teller.
- **Minimale lengte** Stel de minimale lengte in voor een wachtwoord.
- **Minimaal aantal cijfers** Stel het minimale aantal cijfers in dat in een wachtwoord moet worden opgenomen.
- **Minimaal aantal symbolen** Stel het minimale aantal symbolen (zoals !@#\$) in dat vereist is in een wachtwoord.
- **Minimaal aantal hoofdletters** Stel het minimale aantal hoofdletters in dat vereist is voor een wachtwoord.
- **Minimaal aantal kleine letters** Stel het minimale aantal kleine letters in dat vereist is voor een wachtwoord.

### Multifactor-authenticatie tabblad

![gebruikers opties multifactor-authenticatie tabblad](../../../nl/images/users/users-options-multi-factor-authentication-tab.png)

- **Toegestane frontend-moduleposities** Bij weergave van de frontend Multifactor-authenticatiepagina zullen alle modules verborgen worden, behalve die in de hier geselecteerde posities.
- **Titel weergeven in frontend** Een titel weergeven op de frontend Multifactor-authenticatie verificatiepagina? Houd er rekening mee dat de titel altijd zichtbaar is in de backend. Als je de titel wilt wijzigen, overschrijf dan de taalsleutel `COM_USERS_HEADING_MFA` met behulp van Talen: Overschrijvingen.
- **Toegestane backend-moduleposities** Bij weergave van de backend Multifactor-authenticatiepagina zullen alle modules verborgen worden, behalve die in de hier geselecteerde posities. Houd er rekening mee dat modules in de `titel` positie altijd worden weergegeven: dit is nodig om het backend-pictogram en de titel weer te geven.
- **Multifactor-authenticatie uitschakelen** Elke gebruiker die behoort tot *een van* de geselecteerde gebruikersgroepen zal worden vrijgesteld van Multifactor-authenticatie. Zelfs als ze multifactor-authenticatiemethoden hebben opgezet, zullen ze niet worden gevraagd deze te gebruiken bij het inloggen, noch zullen ze deze kunnen bekijken, verwijderen of wijzigen.
- **Multifactor-authenticatie afdwingen** Elke gebruiker die behoort tot *een van* de geselecteerde gebruikersgroepen moet Multifactor-authenticatie inschakelen voordat hij de site kan gebruiken.
- **Frontend sjabloonstijl** Kies de frontend sjabloonstijl die gebruikt moet worden op de Multifactor-authenticatiepagina. Kies *Gebruik standaard* om de standaardsjabloonstijl van de site te gebruiken.
- **Multifactor-authenticatie na stille login** Moet de gebruiker Multifactor-authenticatie ondergaan na een stille gebruikerslogin? Stille logins zijn logins die geen gebruikersnaam en wachtwoord vereisen, bijvoorbeeld de Onthoud mij functie, WebAuthn, enz.
- **Stille login authenticatie responstypen (voor experts)** Voor experts. Een door komma's gescheiden lijst van Joomla-authenticatieresponstypen die worden beschouwd als stille logins. De standaard is `cookie` (de Onthoud mij functie) en `passwordless` (WebAuthn).
- **Nieuwe gebruikers onboarden** Als de gebruiker nog geen Multifactor-authenticatie heeft ingesteld en deze optie is ingeschakeld, wordt hij doorgestuurd naar de opzetpagina voor Multifactor-authenticatie of de aangepaste URL die je hieronder hebt ingesteld. Dit is bedoeld als een eenvoudige manier om je gebruikers te laten weten dat Multifactor-authenticatie een optie is op je site.
- **Aangepaste omleidings-URL** Als deze niet leeg is, leidt deze door naar deze URL in plaats van de opzetpagina voor Multifactor-authenticatie wanneer de hierboven genoemde optie is ingeschakeld. Waarschuwing: Dit moet een URL binnen je site zijn. Je kunt niet inloggen op een externe link of een ander subdomein.

### Gebruikersnotities geschiedenis tabblad

![gebruikers opties gebruikersnotities geschiedenis tabblad](../../../nl/images/users/users-options-user-notes-history-tab.png)

- **Versies inschakelen** Versiegeschiedenis opslaan voor gebruikersnotities.
- **Maximaal aantal versies** Het maximale aantal versies dat opgeslagen wordt voor een gebruikersnotitie. Als een gebruikersnotitie wordt opgeslagen en het maximale aantal versies is bereikt, wordt de oudste versie automatisch verwijderd. Als ingesteld op 0, worden versies nooit automatisch verwijderd.

### Massamail gebruikers tabblad

![gebruikers opties massamail gebruikers tabblad](../../../nl/images/users/users-options-mass-mail-users-tab.png)

- **Onderwerp voorvoegsel** Voer optionele tekst in die automatisch wordt toegevoegd aan het onderwerp van de massa-e-mail.
- **Mailbody suffix** Voer optionele tekst in die automatisch wordt toegevoegd aan het lichaam van de e-mail (bijvoorbeeld, een handtekening).

### Integratie tabblad

![gebruikers opties integratie tabblad](../../../nl/images/users/users-options-integration-tab.png)

- **Aangepaste velden inschakelen** De creatie van aangepaste velden inschakelen.

## Tips

Als je een beginnende gebruiker bent, houd dan hier de standaardwaarden aan
totdat je meer leert over het gebruik van globale opties.

*Vertaald door openai.com*

