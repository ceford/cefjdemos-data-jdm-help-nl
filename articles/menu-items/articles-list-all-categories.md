<!-- Filename: Help4.x:Menu_Item:_List_All_Categories  / Display title: Alle Categorieën Weergeven -->

## Beschrijving

Het menu-itemtype *Alle Categorieën in een Artikelcategorieboom Weergeven* wordt gebruikt om Categorieën in een hiërarchische lijst weer te geven. Afhankelijk van de geselecteerde opties voor deze lay-out, kunt u op een categorie Titel klikken om de artikelen in die categorie weer te geven.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het Details Tabblad](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Het Categorie Tabblad](jdocmanual?article=help/menu-items-common/menu-item-category).
* [Het Blog Lay-out Tabblad](jdocmanual?article=help/menu-items-common/menu-item-blog-layout).
* [Het Lijst Lay-outs Tabblad](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [Het Opties Tabblad](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [Het Integratie Tabblad](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [Het Link Type Tabblad](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Het Pagina Weergave Tabblad](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Het Metadata Tabblad](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Het Associaties Tabblad](jdocmanual?article=help/common-elements/edit-associations).
* [Het Module Toewijzing Tabblad](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Hoe Toegang te Krijgen

Selecteer **Menu's → \[naam van het menu\]** uit het Beheerdersmenu.

Om een Menu-item toe te voegen:

1.  Selecteer de knop **Nieuw** in de Werkbalk.
2.  Selecteer de knop **Selecteren** bij Menu-itemtype.
3.  Selecteer het item **Artikelen**.
4.  Selecteer het item **Lijst van Alle Categorieën in een Artikelcategorie Boom**.

Om een Menu-item te bewerken:

- selecteer een **Titel** uit de lijst

## Screenshot

![Menu-item Artikelenlijst Alle categorieën details tabblad](../../../nl/images/menu-items/articles-list-all-categories-details-tab.png)

## Formulieren

### Velden

- **Titel** De titel die voor dit menu-item wordt weergegeven.
- **Alias** De interne naam van het menu-item. Normaal gesproken kunt u dit leeg laten en Joomla zal een standaardwaarde invullen: Titel in kleine letters en met streepjes in plaats van spaties.

### Details-tabblad

#### Linker Paneel

- **Menu-itemtype** Het Menu-itemtype dat is geselecteerd bij het maken van dit menu-item. Dit kan een van de standaard menu-itemtypes zijn of een menu-itemtype dat wordt geboden door een geïnstalleerde extensie.
- **Selecteer de bovenste categorie**
  - *Root* Omvat alle artikelcategorieën.
  - Anders, selecteer de gewenste bovenste categorie. Alle subcategorieën van de geselecteerde categorie worden in het menu-item weergegeven.
- **Link** De systeem gegenereerde link voor dit menu-item. Dit veld kan niet worden veranderd en is alleen voor informatie.
- **Doelvenster** Selecteer uit de dropdownlijst.
- **Sjabloonstijl** Selecteer uit de dropdownlijst.

#### Rechter Paneel

- **Menu** Toont in welk menu de link zal verschijnen.

### Categorieën-tabblad

![Menu Item Artikelen Lijst Alle Categorieën categorieën tabblad](../../../nl/images/menu-items/articles-list-all-categories-categories-tab.png)

- **Beschrijving van bovenste categorie** Toon de beschrijving voor de bovenste categorie.
- **Alternatieve Beschrijving** Voer een beschrijving in om de categorie beschrijving voor het menu-item te overschrijven.
- **Subcategorie Niveaus** Beheer hoeveel niveaus van subcategorieën worden weergegeven.
- **Lege Categorieën** Toon categorieën die geen artikelen of subcategorieën bevatten.
- **Subcategorieën Beschrijvingen** Toon de beschrijving voor subcategorieën.
- **\# Artikelen in Categorie** Toon een telling van het totale aantal artikelen in elke categorie.

### Blogindeling-tabblad

Blogindeling Opties beheersen het uiterlijk van de categorieverdieping als dat resulteert in een blogindeling.

Het blogindelingsformulier heeft een andere lay-out dan de gemeenschappelijke elementen hierboven, maar de velden zijn vergelijkbaar.

### Gedeeld tabblad

De gemeenschappelijke opties gelden voor gedeelde opties in Lijst, Blog en Uitgelicht, tenzij ze worden gewijzigd door de menu-instellingen.

![Menu Item Artikelen Lijst Alle Categorieën gedeelde tabblad](../../../nl/images/menu-items/articles-list-all-categories-shared-tab.png)

- **Paginering** Paginering biedt paginalinks onderaan de pagina waarmee de gebruiker naar extra pagina's kan navigeren. Deze zijn nodig als de artikelen niet op één pagina passen.
  - *Verbergen* Paginering links worden niet getoond. *Opmerking* Gebruikers kunnen niet naar extra pagina's navigeren.
  - *Tonen* Paginering links worden indien nodig getoond.
  - *Automatisch* Paginering links worden indien nodig getoond.
- **Samenvatting Paginering** Toon het huidige paginanummer en totaal aantal pagina's (bijvoorbeeld, *Pagina 1 van 2*) onderaan elke pagina.

## Tips

- Categorieën kunnen *genest* worden in niveaus, vergelijkbaar met mappen op een schijfstation. In theorie is er geen absoluut limiet aan het aantal niveaus dat je kunt hebben. Echter, praktisch gezien wordt aanbevolen om het aantal niveaus tot een minimum te beperken. De "Toon alle Categorieën" layout werkt mogelijk niet correct als het aantal getoonde niveaus groter is dan 5.
- Als je categorietitels als koppelbaar instelt, kan de gebruiker doordrillen in de categorie. Wanneer ze dat doen, zullen ze normaal gesproken een categorie lijst of categorie blog menu-item zien, afhankelijk van welke optie is geselecteerd. Als er een bestaand menu-item voor deze categorie is (bijvoorbeeld een categorie blog menu-item), dan zal dat menu-item worden getoond in de drill down en zullen de instellingen voor dat menu-item bepalen hoe de pagina wordt weergegeven. Anders zullen de instellingen voor het huidige "Toon alle Categorieën" menu-item de paginweergave bepalen.
- Je kunt de optie instellen om door te drillen naar een lijst of blog op 2 plaatsen.
  - In *Artikelen: Opties* kun je de standaardwaarde instellen voor alle categorieën.
  - In *Categorie: Bewerken* kun je een waarde instellen voor een specifieke categorie. Als dit is ingesteld, overschrijft het de standaardwaarde.
- Om een *Datum Formaat* aan te passen, kun je `D M Y` gebruiken voor dag maand jaar of `d-m-y` voor een korte versie, bijvoorbeeld 17-08-05. Als dit leeg blijft, wordt de DATE_FORMAT_LC1 vertaalsleutel gebruikt uit je taalbestand.

*Vertaald door openai.com*

