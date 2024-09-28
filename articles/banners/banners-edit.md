<!-- Filename: Help4.x:Banners:_Edit  / Display title: Banners: Bewerken -->

## Beschrijving

Gebruikt om banners toe te voegen of te bewerken die op je Joomla!
website kunnen worden weergegeven. Vergeet niet om ten minste één Banner Client en één Banner Categorie
aan te maken voordat je banners maakt.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in afzonderlijke Help
artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Tabblad Publiceren](jdocmanual?article=help/common-elements/edit-publishing).
* [De Versiegeschiedenis Popup](jdocmanual?article=help/common-elements/edit-version-history).

## Toegang

Vanuit het Administrator-menu:
- Selecteer **Componenten → Banners** om naar de Bannersetlijstpagina te gaan.
- Selecteer de **Nieuw** knop in de Werkbalk om een nieuwe Banner aan te maken.
- Selecteer een Banner **naam** uit de *Naam* kolom om een bestaande Banner te bewerken.

## Screenshot

Een banner kan een klikbare afbeelding of aangepaste code zijn. Het afbeeldingt.
type wordt weergegeven in de onderstaande screenshot. Bij het aangepaste type 
wordt het afbeeldingselectievak vervangen door een tekstgebied voor code.

![Banners bewerk details tabblad](../../../nl/images/banners/banners-edit-details-tab.png)

## Formuliervelden

- **Naam** De naam van de Banner. Dit is de naam die wordt weergegeven in de kolom *Naam* van de lijst met Banners.
- **Alias** De interne naam van het item. Normaal gesproken kun je dit leeg laten en zal Joomla een standaardwaarde invullen, afgeleid van de Naam maar in kleine letters en met streepjes in plaats van spaties.

## Details Tabblad

### Linker Paneel

- **Type** Het type banner dat weergegeven moet worden. Opties zijn een afbeeldingsbestand of
  aangepaste HTML-code.
  - **Afbeelding** Het afbeeldingsbestand dat voor de banner wordt weergegeven. Klik op de knop *Selecteren*
    om te bladeren en het afbeeldingsbestand te selecteren dat gebruikt moet worden. Gebruik de Mediabladzijde
    om Banner-afbeeldingsbestanden naar uw site te uploaden. Afbeeldingen voor Banners
    moeten in de /images/banners/ directory staan.
    - **Breedte** De vaste breedte om de bannerafbeelding naar te schalen. Laat
      dit leeg als u de werkelijke breedte van het bannerafbeeldingsbestand
      wilt gebruiken.
    - **Hoogte** De vaste hoogte om de bannerafbeelding naar te schalen. Laat
      dit leeg als u de werkelijke hoogte van het bannerafbeeldingsbestand
      wilt gebruiken.
    - **Alternatieve Tekst** Tekst die wordt weergegeven in plaats van de bannerafbeelding
      als de afbeelding niet kan worden weergegeven.
    - **Alternatieve Tekst** Alternatieve tekst voor de afbeelding van de banner.
  - **Aangepast** Selecteer Aangepast als u een aangepaste code voor
    uw banner wilt invoeren.
    - **Aangepaste Code** Gebruik {CLICKURL} en {NAME} om respectievelijk 'Klik URL'
      en 'Naam' waarden in uw aangepaste code samen te voegen. Bijvoorbeeld:<br>
      `<a href=`&#34;`{CLICKURL}"><img src=`&#34;`voer afbeelding-URL in" alt="{NAME}" title="{NAME}"></a>`.
      Een andere optie is om een HTML-aangepaste code in te voeren. Bijvoorbeeld:<br>
      `<div class="uwklasse"><a href=`&#34;`https://uwdomein.com"><img src=`&#34;`padnaaruwaesbeelding"></a></div>`
- **Klik URL** De URL waarnaar wordt genavigeerd wanneer de gebruiker op de
  Banner klikt.
- **Beschrijving** Voer een beschrijving voor de Banner in.

### Rechter Paneel

- **Status** De publicatiestatus van het item.
- **Vastgezet** Of de Banner *vastgezet* is of niet. Als
  een of meer Banners in een Categorie als *plakkerig* zijn aangewezen, zullen ze
  voorrang hebben op Banners die niet plakkerig zijn.
    - Bijvoorbeeld, als twee Banners in een Categorie vastgezet zijn en een derde Banner
    niet vastgezet is, wordt de derde Banner niet weergegeven als de Banner weergeven
    module-instelling *Vastgezet, Willekeurig* of *Vastgezet, Ordenen* is. Alleen de
    twee vastgezette Banners worden weergegeven. Als de vastgezette banners een vast
    aantal impressies hebben, zullen na het gebruik van die impressies, de vastgezette
    banners niet langer worden weergegeven en de niet-vastgezette banners automatisch
    verschijnen.
- **Taal** Itemtaal.
- **Versie Opmerking** Optioneel veld om deze versie van het item 
  te identificeren in het Venster Versiegeschiedenis van het item.

### Banner Details tabblad

![Banners bewerken banner details tabblad](../../../nl/images/banners/banners-edit-banner-details-tab.png)

- **Max. Impressies** Het aantal Impressies dat voor deze
  Banner is gekocht. Impressies zijn het aantal keren dat een Banner wordt weergegeven
  op een pagina. Vink het selectievakje 'Onbeperkt' aan als een onbeperkt aantal
  Impressies is toegestaan.
- **Totale Impressies** Het aantal keren dat deze Banner is
  weergegeven op een webpagina aan een gebruiker. Geen invoer is toegestaan. U kunt dit
  aantal op 0 terugzetten door op de knop 'Impressies terugzetten' te drukken.
- **Totale Klikken** Het aantal keren dat op deze Banner is
  geklikt. Geen invoer is toegestaan. U kunt dit aantal op 0 terugzetten door op de 
  knop *Klikken terugzetten* te drukken.
- **Klant** De Klant voor deze Banner. Selecteer er een uit de keuzelijst
  van bestaande Klanten.
- **Aankoop Type:** Het aankooptype van de banner. Dit wordt gebruikt om
  aan te geven hoe de bannerklant de weergavetijd voor de
  banner heeft gekocht.
- **Impressies Bijhouden** Of het aantal keren dat de banner
  wordt weergegeven aan websitebezoekers wordt bijgehouden.
- **Klikken Bijhouden** Of het aantal keren dat er op de
  banner wordt geklikt door websitebezoekers wordt bijgehouden.

## Tips

- Banners worden op specifieke pagina's geplaatst door Modules van het type *Banners* toe te voegen via de Modules lijst.
- Als je een reeks Banners hebt die je willekeurig op één of meer pagina's wilt weergeven:
  1.  Maak de Banners die je wilt opnemen, zorg ervoor dat ze dezelfde Client en Categorie hebben.
  2.  Maak een Banner Module voor deze Client en Categorie, en kies in de Menu Toewijzing de Menu Selecties waarop de module moet worden weergegeven.
  3.  Stel in de Banner Module de waarde *Willekeurig* in op *Plakkerig, Willekeurig*.

  Met deze instellingen worden de verschillende Banners voor die Client en Categorie in willekeurige volgorde weergegeven op de geselecteerde pagina's.

*Vertaald door openai.com*

