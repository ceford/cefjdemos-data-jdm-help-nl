<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Editor_Group  / Display title: Redacteursgroep -->

## Groepsbeschrijving

Editor-plug-ins helpen gebruikers om tekst in te voeren met opmaak of lay-outs voor speciale doeleinden, zoals fragmenten van HTML of code. Om een Editor te gebruiken, markeert de softwareontwikkelaar het gegevensinvoerveld als type `Editor`. Als er geen editor-plug-ins zijn ingeschakeld, wordt dit weergegeven als een eenvoudig tekstvlak. Met een of meer ingeschakelde editor-plug-ins wordt de standaard plug-in van de site gebruikt, ingesteld in de Globale Configuratie, tenzij deze wordt overschreven door de door de gebruiker gekozen plug-in, ingesteld in het Gebruikersprofiel. Joomla heeft de drie kern-editor-plug-ins hieronder opgesomd. Extra plug-ins van derden kunnen beschikbaar zijn. Sommige editors hebben een zeer grote selectie aan opties.

### Editor - CodeMirror

De CodeMirror-editor is een code-editor die meer geschikt is voor broncode. Het heeft syntaxis markering voor veel programmeertalen. Het kan niet-overeenkomende tags weergeven en helpt ook om consistente code-inspringingen te behouden.

![CodeMirror opties formulier](../../../en/images/plugins/plugin-group-editor-codemirror.png)

- **Regelnummers** Toon regelnummers in de editor.
- **Code Vouwen** Sta toe dat blokken code worden gevouwen.
- **Goten** Code Markering en Code Vouwen.
- **Markeer Actieve Regel** Voegt een markering toe aan de regel waarop de cursor zich bevindt.
- **Markeer Selectieovereenkomsten** Markeer instanties van het geselecteerde woord in het hele document.
- **Overeenkomende Tags** Markeer overeenkomende tags.
- **Overeenkomende Haakjes** Markeer overeenkomende haakjes.
- **Tag Voltooiing** Automatische tag-voltooiing.
- **Haakjes Voltooiing** Automatische haakjes-voltooiing.
- **Toetsenmap** Laat CodeMirror werken als andere populaire editors.
- **Schakel Volledig Scherm In** Selecteer de functietoets om de volledig schermmodus in en uit te schakelen.
- **Gebruik Modifiers** Selecteer eventuele modificeer toetsen om te gebruiken met de volledig scherm toets.

![CodeMirror geavanceerde opties formulier](../../../en/images/plugins/plugin-group-editor-codemirror-advanced.png)

- **Thema** Stelt de kleuren voor de editor in.
- **Actieve Regel Kleur** De kleur die wordt gebruikt om de actieve regel te markeren. Wordt weergegeven met 50% dekking.
- **Overeenkomende Tag Kleur** De achtergrondkleur die wordt gebruikt om overeenkomende tags te markeren. Wordt weergegeven met 50% dekking.
- **Lettertype** Het lettertype dat in de editor wordt gebruikt. Als het niet is geïnstalleerd, wordt het geladen van https://www.google.com/fonts/.
- **Lettergrootte (px)** De grootte van het lettertype in de editor.
- **Regelhoogte (em)** De hoogte van één tekstregel. Dit is in ems, wat betekent dat 1.0 gelijk is aan de lettergrootte en 2.0 gelijk is aan 2x de lettergrootte.
- **Scrollbalk Stijl** Selecteer de stijl van de scrollbalk die je wilt dat CodeMirror gebruikt.
- **Voorbeeld** Een voorbeeld van hoe je CodeMirror invoervelden eruit zullen zien met de huidige instellingen (opslaan om bij te werken).

### Editor - Geen

Deze plug-in laadt een basis tekst editor. Deze optie kan worden gebruikt wanneer je HTML-code uit een andere bron plakt en je niet wilt dat de HTML wordt aangepast door een WYSIWYG-editor. Deze plug-in heeft geen opties.

### Editor - TinyMCE

De TinyMCE-editor is een WYSIWYG-editor en is de standaard editor voor het invoeren van HTML in Joomla!.

![Het TinyMCE plug-in opties formulier](../../../en/images/plugins/plugin-group-editor-tinymce.png)

- **Selectie tab instellen** Selecteer de functionaliteit *Set 2*, *Set 1* of *Set 0*. Met *Set 2* geselecteerd, zie je de editor voor *Publiek* gebruik. *Set 1* geselecteerd, is standaard voor Managers en Geregistreerden, *Set 0* geselecteerd, is standaard voor Administrators, Redacteuren en Super Users.

Elke tab heeft een lange lijst van opties die hier niet worden geïllustreerd. De volgende lijst is een selectie.

- **Site Skin** Kies de skin die zal worden toegepast op de TinyMCE-editor wanneer deze op je website wordt weergegeven.
- **Administrator Skin** Kies de skin die zal worden toegepast op de TinyMCE-editor wanneer deze in je Beheerders Backend wordt weergegeven.
- **Werkbalk Modus** Bepaalt hoe de werkbalkknoppen worden weergegeven die niet in de eerste rij staan.
- **Afbeeldingen Slepen en Neerzetten** Sta slepen en neerzetten toe voor het uploaden van afbeeldingen.
- **Afbeeldingen Directory** De directory met de afbeeldingsbestanden die worden vermeld ten opzichte van de standaard afbeeldingsmap (in Media > Opties ingesteld).
- **Entiteit Codering** Bepaalt hoe HTML-entiteiten worden gecodeerd. Aanbevolen instelling is `raw`. `named` = gebruikte named entity codering (bijvoorbeeld, `<`). `numeric` = gebruik numerieke HTML codering (bijvoorbeeld, `%03c`). raw = HTML-entiteiten niet coderen. Merk op dat het zoeken naar inhoud mogelijk niet correct werkt als de instelling niet `raw` is.
- **Automatische Taal Selectie** Als Ja, wordt de taal van de editor automatisch afgestemd op de geselecteerde UI-taal. Als de taal niet bestaat, wordt de editor-taal standaard Engels.
- **Tekstrichting** Of de taal leest *Links naar Rechts* of *Rechts naar Links* (bijvoorbeeld, zoals Arabisch). Standaard is *Links naar Rechts*.
- **Template CSS Klassen** Of het *editor.css* bestand moet worden geladen. Als een dergelijk bestand niet wordt gevonden voor de standaardtemplate, wordt het *editor.css* bestand van de systeemtemplate gebruikt. Standaard is *Ja*.
- **Aangepaste CSS Klassen** Optioneel volledige URL-pad naar een aangepaste CSS-bestand. Indien ingevuld, overschrijft dit de Template CSS klassen instelling.
- **URL's** Of Relatieve of Absolute URL's voor links moeten worden gebruikt. De standaard is *Relatief*.
- **Nieuwe Regels** Of nieuwe regels moeten worden geïnterpreteerd als *P Elementen* of *BR Elementen*. Standaard is *P Elementen*.
- **Gebruik Joomla Tekst Filter** Als ingeschakeld, wordt het tekstfilter uit de Joomla Globale Configuratie voor elke gebruikersgroep toegepast. Zo niet, dan worden de hier gedefinieerde filters voor alle gebruikersgroepen gebruikt.
- **Verboden Elementen** De elementen die uit de tekst worden verwijderd. Standaard is *applet*, wat applet-elementen uit de tekst verwijdert.
- **Geldige Elementen** Bepaalt welke elementen in de bewerkte tekst blijven wanneer de editor opslaat (de standaardregels voor deze optie zijn een mix van de volledige HTML5- en HTML4-specificaties).
- **Uitgebreide Geldige Elementen** Optioneel lijst van geldige HTML-elementen om toe te voegen aan de bestaande regelset.
- **Formaat Wijzigen** Sta het wijzigen van het formaat van het editor gebied toe (verticaal en ook horizontaal als *Horizontaal Formaat Wijzigen* is ingeschakeld).
- **Horizontaal Formaat Wijzigen** Sta horizontaal formaat wijzigen toe.
- **Element Pad** Als ingeschakeld, toont het de ingestelde klassen voor de gemarkeerde tekst.
- **Woorden Tellen** Zet woorden tellen aan/uit.
- **Markdown** Stelt het gebruik van Markdown-stijl syntaxis in om links, lijsten en andere stijlen te maken. Deze speciale syntaxis wordt geconverteerd en opgeslagen als reguliere html. Bijvoorbeeld kan de gebruiker # tekst typen om een kop te produceren of **tekst** om tekst vet te maken.
- **Geavanceerde Afbeelding** Zet een geavanceerder afbeeldingsdialoogvenster aan/uit.
- **Geavanceerde Lijst** Schakel in/uit de mogelijkheid om nummerformaten en bullet types in genummerde en niet-genummerde lijsten in te stellen.
- **Contextmenu** Zet het contextmenu aan/uit.
- **Aangepaste Plug-in** Voeg aangepaste TinyMCE-plug-ins toe aan de editor door ze hier op te geven.
- **Aangepaste Knop** Voeg aangepaste TinyMCE-knoppen toe aan de editor door ze hier op te geven.

#### TinyMCE Geavanceerde tab

![TinyMCE Geavanceerde Opties formulier](../../../en/images/plugins/plugin-group-editor-tinymce-advanced.png)

- **Aantal Sets** Het aantal sets dat kan worden aangemaakt. Minimaal 3.
- **HTML Hoogte** De hoogte, in pixels, van het HTML-modus pop-up venster.
- **HTML Breedte** De breedte, in pixels, van het HTML-modus pop-up venster.

*Vertaald door openai.com*

