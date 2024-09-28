<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Tour  / Display title: Begeleide Tours: Tour Bewerken -->

## Beschrijving

Deze pagina wordt gebruikt om een nieuwe Tour toe te voegen of een bestaande Tour te bewerken. Een tour moet minstens één stap bevatten. Zodra een tour nieuw is aangemaakt, ga naar de Tours lijst en selecteer de knop met het *0* label uit de kolom Stappen. De eerste stap van de tour wordt automatisch gemaakt uit de titel en beschrijving van de tour.

### Gemeenschappelijke Elementen

Sommige aspecten van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Het Publiceren Tabblad](jdocmanual?article=help/common-elements/edit-publishing).


## Toegang krijgen

- Selecteer **Systeem -> Beheren -> Begeleide Rondleidingen** vanuit het Administrator-menu.
- Selecteer de knop **Nieuw** op de werkbalk om een rondleiding toe te voegen.
- Selecteer een **Titel** uit de lijst om een rondleiding te bewerken.


## Schermafbeelding

![Begeleide Rondleidingen Tour Bewerken](../../../nl/images/guided-tours/guided-tours-edit-tour.png)

## Formuliervelden

- **Titel** De titel voor deze tour. Als de titel een taalsleutel is, wordt een
aanvullend veld weergegeven, waarin de vertaling van die sleutel voor de
gebruikerslocale wordt weergegeven.
- **Tour Identifier (Touridentificatie)** Een unieke identificatie voor de tour. Bij het *Opslaan* of
*Opslaan als kopie*, wordt er standaard een waarde opgegeven. Een voorgesteld formaat zou zijn
*auteursnaam-tournnaam*, *bedrijfsnaam-tournaam* of *domein-tournaam*.
Deze identifier heeft meerdere doeleinden: start een tour vanaf elke locatie
(niet alleen vanaf de Guided Tours-module), differentieer tours van verschillende oorsprongen,
en op meertalige sites bepaalt het de structuur van de bestandsnamen voor de talen.

### Tabblad Tour bewerken

#### Linkerpaneel

- **Relatieve URL** Het verplichte relatieve pad van waar de tour start.
   Bijvoorbeeld, om een tour te starten vanaf de tourpagina, voer in
   `administrator/index.php?option=com_guidedtours&view=tours`.
- **Beschrijving** Hier voer je de beschrijving van de tour in.
   De tourbeschrijving kan een taalsleutel zijn. Wanneer dit het geval is,
   presenteert een secundair veld de vertaalde beschrijving van die sleutel voor de
   gebruikerslocale.

#### Rechterpaneel

- **Componentkiezer** De tour zal met prioriteit zichtbaar zijn op pagina's van
   de geselecteerde extensies. Gebruik *Alles* om de tour op alle pagina's weer te geven. Wanneer
   ingesteld op *Alles*, wordt de tour als laatste geplaatst in de lijst van contextuele tours
   in de module-dropdown. Dit is een verplicht veld.
- **Auto Start** Hiermee kan de tour automatisch starten wanneer een gebruiker
   de context bereikt waarin de tour moet worden weergegeven.

## Tips

- Er zijn 2 methoden om een afbeelding in de beschrijving van de tour in te voegen met behulp van de TinyMCE-editor.
  1. De **CMS Content** dropdownlijst biedt toegang tot het **Media**-scherm waarmee je afbeeldingsbestanden kunt bekijken en afbeeldingen kunt uploaden.
  2. De *Insert* dropdownlijst is een eenvoudig formulier waarvoor je de afbeeldings-url moet weten. Dit wordt gebruikt voor externe afbeeldingen.
- Er zijn 2 manieren waarop tours kunnen worden gemaakt voor meertalige omgevingen:
  1. Maak één tour voor elke ondersteunde taal.
  2. Maak slechts één tour voor alle talen en gebruik taalcodes voor de titel en beschrijving.
- Gebruik **GUIDEDTOUR** in taalcodes als conventie waar taalcodes worden gebruikt (voor titel en beschrijving).

