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

More Information: [A Dummies Guide to Joomla Bug Testing](https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing)

## Hoe toegang te krijgen

- Selecteer **Componenten → Joomla! patchtester** in het beheermenu.
  - Klik op de *Opties* knop in de werkbalk.

## Schermafbeelding

![Patchtester Options form](../../../en/images/joomla-patchtester/patchtester-options-github-repository-tab.png)

### Formulier velden

### GitHub repository tabblad

- **GitHub repository** De standaard is Joomla! CMS. Gebruik die.

### GitHub authenticatie tabblad

U heeft een Github account of Github token nodig. Helemaal gratis -
Bekijk het GitHub authenticatie tabblad voor de details.

![Patchtester Options github authentication tab](../../../en/images/joomla-patchtester/patchtester-options-github-authentication-tab.png)

- **GitHub authenticatie methode** Kies voor de Token methode. De
  inloggegevens methode zal vanaf november 2020 niet meer werken.
- **GitHub token** Voer de token in die u van GitHub krijgt.

### CI server-instellingen tabblad

Deze instellingen worden gebruikt voor het automatisch testen. Gebruik
de standaards voor handmatig testen.

![Patchtester Options github ci server settings tab](../../../en/images/joomla-patchtester/patchtester-options-ci-server-settings-tab.png)

- **CI-serveradres** Standaard: `https://ci.joomla.org`
- **Schakelen tussen CI-integratie** Standaard: Uit
