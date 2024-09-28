<!-- Filename: Help4.x:Redirects:_Links  / Display title: Doorverwijzingen: Links -->

## Beschrijving

De pagina *Redirects: Links* toont een lijst van huidige website-omleidingen.

De omleidingscomponent wordt gebruikt om URL's door te sturen van webpagina's die niet meer op uw website bestaan naar werkende webpagina's. De URL waarvan u wilt omleiden, moet niet werken en daadwerkelijk een webpagina laden. Het kan de URL zijn van een webpagina die u hebt uitgeschakeld.

De *Verlopen URL* die u opgeeft wanneer u de omleiding maakt, moet de volledige URL zijn zoals u die in uw webbrowser zou typen. De component zal alleen het laatste deel van de bron-URL weergeven in de omleidingslijst.

De *Nieuwe URL* die u opgeeft wanneer u een omleiding maakt, moet ook de volledige URL zijn. U moet de optie *URL-herschrijven gebruiken* hebben ingeschakeld in uw Joomla! installatie *Algemene Configuratie* opties om ervoor te zorgen dat de door u gemaakte omleidingen functioneren.

### Gemeenschappelijke Elementen

Sommige elementen van deze pagina worden behandeld in afzonderlijke Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Lijstfilters](jdocmanual?article=help/common-elements/list-filters).
* [Lijstkolomkoppen](jdocmanual?article=help/common-elements/list-column-headers).
* [Lijstpaginering](jdocmanual?article=help/common-elements/list-pagination).

## Hoe te openen

- Selecteer **Systeem → Paneel beheren → Redirects** uit het Administrator-menu.

## Screenshot

![Links met doorverwijzingen](../../../nl/images/redirects/redirects-links.png)

## Kolomkoppen

- **Verlopen URL** De URL die wordt doorgestuurd op uw website.
  Alleen het webpagina gedeelte van de URL wordt in deze lijst weergegeven.
- **Nieuwe URL** De bestemming URL voor de doorverwijzing.
- **Verwijzende pagina** De verwijzende webpagina voor de doorverwijzing.
- **Aangemaakt op** De datum waarop het item (Artikel, Categorie, enzovoort)
  is aangemaakt.
- **404 Hits** Het aantal 404-hits dat op deze URL is geweest.
- **Statuscode** De statuscode van de pagina.

## Tips

- Om ervoor te zorgen dat je omleidingen werken, moet je de optie 
  **Gebruik URL herschrijven** inschakelen in de **Globale Configuratie** opties van je
  Joomla! installatie. Let er ook op dat het alleen inschakelen van de optie *Gebruik URL
  herschrijven* niet voldoende is. Je moet de extra stap nemen om het `htaccess.txt` bestand in de map van je website waar je
  Joomla! hebt geïnstalleerd, te hernoemen naar `.htaccess` of naar welke bestandsnaam je Apache webserver ook vereist voor extra configuratierichtlijnen. In het
  Apache configuratiebestand wordt deze instelling `AccessFileName` genoemd en standaard is dit ingesteld op `.htaccess`.

*Vertaald door openai.com*

