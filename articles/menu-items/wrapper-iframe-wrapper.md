<!-- Filename: Help4.x:Menu_Item:_Iframe_Wrapper  / Display title: Iframe Wrapper  -->


## Beschrijving

Het *Iframe Wrapper* menu-item type wordt gebruikt om een pagina te maken met ingebedde inhoud met behulp van een IFrame, waarbij je controle hebt over de iframe-grootte, breedte en hoogte.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in afzonderlijke Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het Details Tabblad](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Het Link Type Tabblad](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Het Paginaweergave Tabblad](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Het Metadata Tabblad](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Het Associaties Tabblad](jdocmanual?article=help/common-elements/edit-associations).
* [Het Module Toewijzing Tabblad](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Hoe Toegang Krijgen

Om een nieuw IFrame Wrapper Menu Item aan te maken:

- Selecteer **Menu's → \[naam van het menu\]** vanuit het Beheerdersmenu (bijvoorbeeld, **Menu's → Hoofdmenu**). Vervolgens...
  - Selecteer de **Nieuw** knop in de Toolbar. Vervolgens...
  - Selecteer de Menu Item Type Select-knop.
  - In de modale dialoog selecteer het Gebruikers item om een lijst te openen en selecteer daarna het **Iframe Wrapper** menu item.

Om een bestaand *IFrame Wrapper* menu item te bewerken:

- Selecteer de Titel in de *Menu: Items* lijst.

## Screenshot

![Iframe wrapper details tab](../../../nl/images/menu-items/wrapper-iframe-wrapper-details-tab.png)

## Formulier Velden

### Scrollbalk Parameters Tab

![Iframe wrapper scrollbalk parameters tab](../../../nl/images/menu-items/wrapper-scroll-bar-parameters-tab.png)

- **Breedte** Breedte van het IFrame-venster. Voer een aantal pixels in of een percentage. Bijvoorbeeld, *550* betekent 550 pixels; *75%* betekent 75% van de
  `<main>` container breedte. Een absoluut aantal pixels kan breder zijn dan de container en lay-outproblemen veroorzaken. Bij twijfel, probeer 100%.
- **Hoogte** Hoogte van het IFrame-venster. Voer een aantal pixels in. Bijvoorbeeld, *550* betekent 550 pixels.

### Geavanceerd Tab

![Iframe wrapper geavanceerd tab](../../../nl/images/menu-items/wrapper-advanced-tab.png)

- **Auto hoogte** Automatisch de hoogte instellen op de hoogte van de externe pagina. *Opmerking* - Dit werkt alleen als de externe pagina zich op **dezelfde domein** bevindt. Bijvoorbeeld, `http://www.example.com` de externe html moet in de `example.com` root structuur staan. Subdomeinen zullen niet werken, aangezien een subdomein als een apart domein wordt beschouwd.
- **Auto toevoegen** Automatisch webadres voorvoegen met http://. Deze functie zal automatisch detecteren en geen voorvoegsel toevoegen aan een URL die al http:// of https:// in de URL gebruikt.
- **Lui Laden** ...


