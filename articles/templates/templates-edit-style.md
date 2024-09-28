<!-- Filename: Help4.x:Templates:_Edit_Style  / Display title: Sjablonen: Stijl Bewerken -->

## Beschrijving

De pagina *Templates: Stijl Bewerken* wordt gebruikt om sjabloonstijlen te bewerken. Wanneer een sjabloon voor het eerst wordt geïnstalleerd, wordt er een standaardstijl voor aangemaakt. De standaardstijl voor het sjabloon zal dezelfde naam hebben als het sjabloon met een achtervoegsel *- Standaard*. Om een andere variatie van de standaard sjabloonstijl te maken, vinkt u het selectievakje van de standaardstijl aan en drukt u op het *Dupliceren* pictogram in de werkbalk. Bewerk vervolgens de duplicaat.

### Gemeenschappelijke Elementen

Sommige elementen van deze pagina worden behandeld in afzonderlijke Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).

## Toegang Krijgen

- Selecteer **Systeem → Sjablonenpaneel → Sitesjablonen Stijlen**
  uit het beheerdersmenu. Of...
- Selecteer **Systeem → Sjablonenpaneel → Beheerderssjablonen
  Stijlen** uit het beheerdersmenu. Vervolgens...
  - Selecteer de naam van de Sjabloonstijl die je wilt bewerken in de kolom Stijl.

## Screenshot

![sjablonen cassiopeia stijl bewerken editor tabblad](../../../nl/images/templates/templates-site-edit-style-details-tab.png)

## Formulier Velden

- **Stijlnaam** De naam van de stijl. Dit is de naam die wordt getoond in de Stijl kolom van het *Template: Stijlen* scherm.

### Details Tab

- **Informatie** De naam van de template, Site of Administrator
  indicator en een korte beschrijving.

### Geavanceerd Tab

![templates cassiopeia edit style editor tab](../../../nl/images/templates/templates-site-edit-style-advanced-tab.png)

Deze sectie is mogelijk niet aanwezig voor alle stijlen. Als een template waarvan een stijl is afgeleid configureerbare opties heeft, zullen deze hier aanwezig zijn. Het zijn deze extra configureerbare opties die u in staat stellen om meerdere verschillende stijlen van templates te hebben met variaties van deze opties. De beschikbare opties zullen variëren op basis van wat de template-ontwikkelaar beschikbaar heeft gemaakt.

### Atum Kleureninstellingen

De standaard Administrator template stelt je in staat om met kleurvariaties te experimenteren. Sla op en zie!

### Atum Afbeeldingsinstellingen

Je kunt een afbeelding selecteren om het **Login Logo** in het Administrator inlogformulier te vervangen, en het **Merklogo** in de Administrator Titelbalk in uitgebreide modus en in compacte modus. De standaard zijn de Joomla Merklogo's. In de Titelbalk is het woord Joomla! aanwezig in de **Merk Groot** versie en weggelaten in de **Merk Klein** versie. Selecteer **Menu Wisselen** om de verandering te zien.

Als je je eigen Merk Klein levert, moet je ook een breedte stijl-override leveren. Om dit te doen, maak je een user.css bestand aan in de template-root en voeg je het volgende in, maar vervang 3rem met een geschikte breedte voor je afbeelding:

       .header .logo.small {
           width: 3rem;
       }

### Menu Toewijzing Tab

![templates cassiopeia edit style editor tab](../../../nl/images/templates/templates-site-edit-style-menu-assignment-tab.png)

Deze sectie bevat alle menu-items die in je Joomla! website zijn geconfigureerd. Om de huidige stijl toe te passen op de webpagina van een menu-item, vink je het vakje naast het menu-item aan. Je kunt op de *Selectie Wisselen* knop drukken om de menu-item selecties te omkeren.

**Opmerking** Als een selectievakje grijs is en niet kan worden aangevinkt, kan het zijn dat het menu-item door een andere gebruiker in gebruik is. Je kunt zien of dit het geval is door naar het menubeheerscherm van het betreffende menu te gaan. Als er een hangslotsymbool naast het menu-item staat, wordt het momenteel door een andere gebruiker gebruikt.

*Vertaald door openai.com*

