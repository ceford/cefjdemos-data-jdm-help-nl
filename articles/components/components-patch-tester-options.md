<!-- Filename: Help4.x:Components_Patch_Tester_Options / Display title: Componenten - Patchtester - Opties -->

## Beschrijving

De Joomla! patchtester wordt door testers gebruikt om te controleren dat
code aanpassingen, aangeleverd door ontwikkelaars, doen wat ze zouden
moeten doen zonder ongewenste bijwerkingen. De opties pagina wordt
gebruikt om een verbinding met Github op te zetten.

Meer informatie:

- <a
  href="https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">A Dummies Guide to Joomla Bug
  Testing</a>

## Hoe toegang te krijgen

- Selecteer **Componenten → Joomla! patchtester** in het beheermenu.
  - Klik op de *Opties* knop in de werkbalk.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/b/b5/Help-4x-Component-Patch-Tester-Options-screenshot-nl.png/800px-Help-4x-Component-Patch-Tester-Options-screenshot-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/b/b5/Help-4x-Component-Patch-Tester-Options-screenshot-nl.png 1.5x"
data-file-width="1170" data-file-height="644" width="800" height="440"
alt="Component Patch Tester Options screenshot" />

### Formulier velden

### GitHub repository tabblad

- **GitHub repository.** De standaard is Joomla! CMS. Gebruik die.

### GitHub authenticatie tabblad

U heeft een Github account of Github token nodig. Helemaal gratis -
Bekijk het GitHub authenticatie tabblad voor de details.

<img
src="https://docs.joomla.org/images/d/df/Help-4x-Component-Patch-Tester-Options-github-authentication-subscreen-nl.png"
decoding="async" data-file-width="694" data-file-height="527"
width="694" height="527"
alt="Component Patch Tester Options github authentication subscreen" />

- **GitHub authenticatie methode.** Kies voor de Token methode. De
  inloggegevens methode zal vanaf november 2020 niet meer werken.
- **GitHub token.** Voer de token in die u van GitHub krijgt.

### CI server-instellingen tabblad

Deze instellingen worden gebruikt voor het automatisch testen. Gebruik
de standaards voor handmatig testen.

<img
src="https://docs.joomla.org/images/9/96/Help-4x-Component-Patch-Tester-Options-ci-server-settings-subscreen-nl.png"
decoding="async" data-file-width="701" data-file-height="348"
width="701" height="348"
alt="Component Patch Tester Options ci server settings subscreen" />

- **CI-serveradres.** Standaard:
  <a href="https://ci.joomla.org" rel="noreferrer noopener">https://ci.joomla.org</a>
- **Schakelen tussen CI-integratie.** Standaard: Uit.

### Rechten tabblad

Het is heel onwaarschijnlijk dat een tester de rechten voor deze
component wil wijzigen.

<img
src="https://docs.joomla.org/images/5/59/Help-4x-Component-Patch-Tester-Options-permissions-subscreen-nl.png"
decoding="async" data-file-width="700" data-file-height="631"
width="700" height="631"
alt="Component Patch Tester Options permissions subscreen" />

Om de rechten van deze extensie te wijzigen moet u de volgende
handelingen uitvoeren.

- Selecteer de **Groep** door op de titel aan de linkerzijde te klikken.
- Zoek de gewenste **Actie**. Mogelijke Acties zijn:
  - **Instellen ACL & Opties**. Gebruikers kunnen de opties en rechten
    van deze extensie bewerken.
  - **Toegang tot beheerdersinterface**. Gebruikers hebben toegang tot
    de beheerdersinterface van deze extensie.
- Selecteer de gewenste rechten voor de actie die u wilt wijzigen.
  Mogelijke instellingen zijn:
  - '**Overgenomen:'** Overgenomen van gebruikers in deze groep vanuit
    de Algemene instellingen rechten van deze extensie.
  - '**Toegestaan:'** Toegestaan voor gebruikers in deze groep. Let op
    dat wanneer deze actie op één van de hogere niveaus Geweigerd is het
    Toegestaan-recht hier geen effect heeft. Een Geweigerd-instelling
    kan niet worden overschreven.
  - '**Geweigerd:'** Geweigerd voor alle gebruikers in deze groep.
- Klik op **Opslaan** in de **werkbalk** bovenin. Wanneer het scherm
  herladen wordt zal de nieuwe gecalculeerde rechten voor deze groep en
  actie weergegeven worden.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de afbeelding hierboven.
De functies zijn.

- **Opslaan.** Slaat item op en blijft op het huidige scherm.
- **Opslaan & sluiten**. Slaat item op en sluit het huidige scherm.
- **Sluiten**. Sluit het huidige scherm en keert terug naar het vorige
  scherm zonder wijzigingen die u misschien heeft gedaan op te slaan.
- **Help**. Opent dit helpscherm.
