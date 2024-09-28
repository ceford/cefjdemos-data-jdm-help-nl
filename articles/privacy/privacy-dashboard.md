<!-- Filename: Help4.x:Privacy_Dashboard  / Display title: Privacy Dashboard -->


## Beschrijving

De *Privacy Dashboard* pagina toont het type gebruikersprivacyverzoek, de status en
het aantal verzoeken.

### Tutorials

- [Privacy Overzicht - Inhoud en Workflow](https://docs.joomla.org/Help4.x:Components_Privacy_Outline/en)
- [De Privacy Toolkit](https://docs.joomla.org/J3.x:Privacy/en)
  (Gedetailleerde Tutorial van Joomla 3)
- [Informatieverzoek Workflow](https://docs.joomla.org/J3.x:Information_Request_Workflow_in_Privacy_Component/en)
  (Gedetailleerde Tutorial van Joomla 3)

## Hoe te benaderen

- Selecteer **Gebruikers → Privacy Dashboard icoon** in het beheerdermenu.

## Screenshot

![privacy-dashboard](../../../nl/images/privacy/privacy-dashboard.png)

## Dashboardpanelen

### Privacy Status

- **Gepubliceerd privacybeleid** Of er een privacybeleid beschikbaar is. Navigeer naar *Plugins → System - Privacy Consent* en selecteer je Privacybeleid Artikel. Zodra dit is gepubliceerd, kun je je privacybeleid artikel vanaf deze pagina bewerken.
- **Gepubliceerde aanvraagformulier menu-item** Of het menu-item (dat gebruikers in staat stelt om verzoeken te sturen) is gepubliceerd of niet gepubliceerd. Om het aan te maken, navigeer naar je Menu → Nieuw menu-item toevoegen → Menu-itemtype: Verzoek maken. Zodra dit is gepubliceerd, kun je je menu-item vanaf dit scherm bewerken.
- **Uitstaande dringende verzoeken** Aantal dringende verzoeken die ouder zijn dan het aantal dagen ingesteld in de Componentopties (van 10 tot 29 dagen).
- **Mailverzending ingeschakeld**
- **Versleuteling van databaseverbinding**

### Privacyverzoeken

- **Verzoektype** Toont de twee verschillende soorten verzoeken
  - *Exporteren* wanneer een gebruiker een verzoek heeft ingediend om zijn gegevens te exporteren
  - *Verwijderen* wanneer een gebruiker een verzoek heeft ingediend om te worden verwijderd.
- **Status** Toont de status van het verzoek
  - *Ongeldig* een supergebruiker heeft het verzoek ongeldig verklaard
  - *In afwachting* wanneer een gebruiker een verzoek heeft ingediend maar dit verzoek nog niet heeft bevestigd. Gebruikers hebben twee manieren om te bevestigen: door de URL te bezoeken die vermeld staat in de e-mail die naar de gebruiker is gestuurd of door het token uit de e-mail te kopiëren en te plakken in het formulier op de opgegeven URL. Het token is 24 uur geldig.
  - *Bevestigd* de gebruiker heeft zijn verzoek bevestigd.
  - *Voltooid* een supergebruiker heeft het verzoek voltooid
- **Aantal verzoeken** Toont het aantal verzoeken voor elk type. Dit blok toont ook het totale aantal verzoeken en het aantal actieve verzoeken.

## Tips

- Selecteer een Verzoektype om de lijst met verzoeken van dat type te bekijken.

*Vertaald door openai.com*

