<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Step  / Display title: Gidsen: Stap Bewerken -->

## Beschrijving

Deze pagina wordt gebruikt om een nieuwe Stap toe te voegen of een bestaande Stap van een rondleiding te bewerken.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in afzonderlijke Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het Publicatietabblad](jdocmanual?article=help/common-elements/edit-publishing).

## Hoe te Toegangen

- Selecteer **Systeem -> Beheer -> Begeleide Rondleidingen** uit het menu van de Beheerder.
- Selecteer de genummerde **Stappen** knop voor een rondleiding om de pagina met rondleidingsstappen te openen.
- Selecteer de **Nieuw** werkbalkknop om een stap toe te voegen.
- Selecteer een **Titel** uit de lijst om een stap te bewerken.

## Screenshot

![Rondleidingen bewerkstap](../../../nl/images/guided-tours/guided-tours-edit-step.png)

## Formulieren

- **Titel** De Titel voor deze stap. Meestal is het een oproep tot actie, bijvoorbeeld `Voer een titel in` als de stap gebruikersinteractie vereist. Als de titel een taalsleutel is, wordt een extra veld getoond dat de vertaling van die sleutel voor de gebruikerslocale weergeeft.

### Bewerk Stap Tab

#### Linker Paneel

- **Beschrijving** Dit is waar je de beschrijving van de stap invoert, meestal een gedetailleerde uitleg of hulp voor de stap. De stapbeschrijving kan een taalsleutel zijn. In dat geval wordt een secundair veld gepresenteerd met de vertaalde beschrijving van die sleutel voor de gebruikerslocale.

#### Rechter Paneel

- **Positie** De positie van de stap ten opzichte van de informatie waarnaar het verwijst.
  - **Onderkant** Stap wordt onder het doel weergegeven.
  - **Midden** Stap wordt in het midden van het scherm weergegeven. Als een doel ontbreekt, is dit de standaardpositie.
  - **Links** Stap wordt links van het doel weergegeven.
  - **Rechts** Stap wordt rechts van het doel weergegeven.
  - **Bovenkant** Stap wordt boven het doel weergegeven.
- **Doel** Het element van het scherm waarnaar de stap verwijst. Het gebruikt CSS-syntaxis.

  Bijvoorbeeld, *.button-new* zal de knop op de pagina targeten met klasse *button-new*.

  Als het doel niet uniek is, wordt het eerste gevonden doel gebruikt. Zorg ervoor dat het doel focusbaar is voor toegankelijkheid bij het maken van interactieve stappen. Je kunt meerdere selectoren gebruiken, gescheiden door komma's. De eerste geldige wordt het doel (een selector is geldig als: gevonden op de pagina, niet uitgeschakeld, niet alleen-lezen en niet verborgen). Als een doel is ingesteld maar niet wordt gevonden of ongeldig is, zal de rondleiding niet breken maar de stap in het midden van het scherm tonen.
- **Type** Het type stap.
  - **Volgende** De gebruiker die de rondleiding uitvoert, gaat door naar de volgende stap.
  - **Omleiden** De stap wordt omgeleid naar een andere pagina.
  - **Interactief** De stap vereist gebruikersinteractie, zoals het invoeren van gegevens.
- **URL** De url om naar om te leiden voor een stap van het type *Omleiden*. Bijvoorbeeld, *administrator/index.php?option=com_users&view=user&layout=edit* zal de stap omleiden naar het scherm voor gebruikersbewerking.
- **Interactieve Type** Het type interactie voor een interactieve stap.
  - **Formulier Verzenden** Het doel is een knop die een formulier indient.
  - **Tekstveld** Het doel is een tekstinvoerveld. Als het veld verplicht is, kan de persoon die de rondleiding uitvoert niet doorgaan naar de volgende stap totdat gegevens zijn ingevoerd.
  - **Knop** Het doel is een knop op het scherm.
  - **Anders** Het doel is een ander formelement.

### Opties Tab

![Geleide rondleidingen bewerk stap opties tab](../../../nl/images/guided-tours/guided-tours-edit-step-options-tab.png)

## Tips

- Gebruik **GUIDEDTOUR** in taalsleutels als een conventie waar taalsleutels worden gebruikt (voor titel en beschrijving).

*Vertaald door openai.com*

