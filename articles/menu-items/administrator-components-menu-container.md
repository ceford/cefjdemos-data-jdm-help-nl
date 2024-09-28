<!-- Filename: Help4.x:Menu_Item:_Components_Menu_Container  / Display title: Menu Item: Onderdelen Menu Container -->

## Beschrijving

De Componenten Menu Container wordt gebruikt om een componentcontainer weer te geven in de Beheerdersinterface. Een gebruiksvoorbeeld kan als volgt zijn:

Stel dat je alleen bepaalde gebruikers koppelingen naar een subset van de componenten op je site wilt tonen. Supergebruikers zullen uiteraard koppelingen naar alles zien. Je kunt dit als volgt doen:

- Maak een nieuwe Gebruikersgroep aan met de naam, laten we zeggen 'Filiaal', met 'Openbaar' als ouder.
- Stel de Globale Rechten voor deze groep in op 'Beheerder Login Toestaan'.
- Maak een nieuw menu aan met de naam, laten we zeggen 'Filiaal Menu' zonder geïmporteerde presets.
- Maak een gekoppelde Module met de naam, laten we zeggen 'Filiaal Menu' met menu om weer te geven als 'Filiaal Menu'. Stel 'Check Menu' in op 'Nee' en 'Toegang' op 'Openbaar'.
- Maak een Componenten Menu Container-menu-item voor het Filiaal Menu met de naam, laten we zeggen 'Filiaal Componenten'.
  - Verberg alle componenten die je niet wilt laten zien aan Filiaal-gebruikers.
  - Toon die waartoe zij toegang moeten hebben.
- Stel de Componentrechten voor de Filiaal-groep in op toegestaan voor alles behalve 'ACL Configureren' en 'Opties Configureren'.

Voor een Supergebruiker zal het Beheerdersmenu een duidelijke duplicatie van koppelingen hebben. Een Filiaal-gebruiker zal echter alleen het Filiaal Componentenmenu en het Startdashboard zien. Je moet ook de Toegangsrechten van de modules met Snelle Pictogrammen daar aanpassen! En je moet echt een Dashboard-module maken voor alle componenten waartoe Filiaal-gebruikers toegang hebben.

Voor gebruikers die toegang nodig hebben tot Artikelen kun je meer menu-items toevoegen aan het Filiaal Menu. Op deze manier kun je een compleet aangepast menu bouwen voor Filiaalgebruikers.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden in aparte Help-artikelen behandeld:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het Koppelingstype Tabblad](jdocmanual?article=help/menu-items-common/menu-item-link-type).

## Hoe Toegang te Krijgen

Om een nieuwe Component Container Menu Item te maken:

- Maak een nieuw Menu aan via **Menu's → Beheren** in het Administrator menu.
  - Selecteer **Administrator** in de *Site/Administrator* dropdown selector.
  - Selecteer de **Nieuw** knop in de Toolbar. Vul het formulier in:
    - **Titel** Branch Menu
    - **Unieke Naam** branch_menu
    - **Beschrijving** Aangepast menu voor Branch.
    - **Importeer Sjabloon** Geen
    - **Opslaan**
    - **Machtigingen** Selecteer de groep *Branch* en stel alles in op *Toestaan*.
    - **Opslaan & Sluiten**
    - Selecteer de knop **Maak een Module** en vul het dialoogvenster in:
    - **Titel** Branch Componenten
    - **Controleer Menu** Nee (anders verschijnt er een bericht dat je wordt 
      uitgenodigd om de *menuherstelfunctie aan te zetten*.)
    - **Toegang** Speciaal
    - **Positie** Menu
- Selecteer **Menu's → \[naam van het menu\]** in het Administrator menu.
- Selecteer de **Nieuw** knop in de Toolbar om een nieuw menu-item te maken.
- Selecteer de **Selecteer** knop bij het Menu-itemtype.
- Selecteer de link **List Component Container** onder **Systeemlinks** in
  het Menu-itemtype modal dialoogvenster.

Om een bestaand Component Container Menu Item te bewerken, selecteer de Titel in
de lijst met Menu-items.

## Screenshot

![Onderdelen Menu-item Menu Container](../../../en/images/menu-items/administrator-components-menu-container.png)

## Formuliervelden

- **Naam** De naam van het menu-item, bijvoorbeeld *Branch Menu*. Het verschijnt
  onderaan het Administrator-menu.
- **Alias** De interne naam van het item. Normaal gesproken kun je dit
  veld leeg laten en Joomla vult dan een standaardwaarde in: titel in kleine letters en
  met streepjes in plaats van spaties.

### Details Tab

#### Linker Paneel

- **Menu-itemtype** In dit geval *Componentenmenubak*.
- **Menu-items weergeven of verbergen** Lijst van menu-items met knoppen om de
  zichtbaarheidsstatus in te stellen. Als een bovenliggend item is ingesteld op *Verbergen*,
  worden alle onderliggende items ook verborgen, zelfs als ze zijn ingesteld op *Weergeven*.

#### Rechter Paneel

- **Menu** Geeft aan in welk menu de link zal verschijnen.
- **Ouder** Het item (categorie, menu-item, enzovoort) dat de
  ouder is van het item dat wordt bewerkt.
- **Volgorde** Geeft de volgorde aan van dit menu-item in het menu. De
  standaardvolgorde is om het menu-item aan het eind van het menu toe te voegen. Dit
  menu-item wordt verplaatst naar de volgorde net na het menu-item
  dat is geselecteerd in de keuzelijst. Merk op dat de volgorde van menu-items
  ook kan worden gewijzigd in de Menu-itembeheerder.
- **Status** De publicatiestatus van het item.
- **Opmerking** Dit is normaal gesproken voor gebruik door de sitebeheerder (bijvoorbeeld,
  om informatie over dit item te documenteren) en wordt niet weergegeven op
  de frontend van de site.

## Tips

- Het item **Branch Components** verschijnt onderaan het Administrator
  menu. Toegang tot het hoofdmenu van de Administrator en tot deze sectie kan
  worden aangepast voor de Branch groep.


*Vertaald door openai.com*

