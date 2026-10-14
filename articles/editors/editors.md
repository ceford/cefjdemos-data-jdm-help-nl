<!--
{
    "source": "https://docs.joomla.org/Help4.x:Editors",
    "title": "Editors: Inleiding",
    "description": " ",
    "author": ""
}
-->

## TinyMCE

TinyMCE is de standaardeditor voor frontend- en backendgebruikers. De editor
biedt gebruikers een vertrouwde tekstverwerkingsinterface voor het bewerken
van content.

TinyMCE kan worden geconfigureerd met 3 verschillende sets werkbalkknoppen. Dit
wordt ingesteld in de plug-in Editor - TinyMCE.

### Werkbalken

#### Eenvoudige voorinstelling

De werkbalkset 2 biedt één rij knoppen, zoals hieronder weergegeven. De set is
standaard toegewezen aan de gebruikersgroep Public.

![TinyMCE-werkbalkset 2](../../../nl/images/editors/editors/01-set-2.png)

- Met de knoppen kunt u tekst vet, onderstreept of doorgestreept maken.
- Ongedaan maken en Opnieuw uitvoeren.
- Ongeordende lijst, Geordende lijst.
- Plakken als tekst: Vaak bevat de geselecteerde tekst bij het kopiëren en plakken van tekst uit andere bronnen,
  zoals pdf-bestanden, tekstdocumenten of webpagina's, opmaakinformatie die niet nodig of gewenst is. Met
  'Plakken als tekst' wordt alle opmaak uit de tekst verwijderd.

#### Gemiddelde voorinstelling

De werkbalkset 1 biedt twee rijen knoppen, zoals hieronder weergegeven. De set
is standaard toegewezen aan de gebruikersgroepen Manager en Registered.

![TinyMCE-werkbalkset 1](../../../nl/images/editors/editors/02-set-1.png)

Deze optie biedt alle dezelfde knoppen als hierboven beschreven voor werkbalkset 2.
Daarnaast zijn de volgende opties beschikbaar.

#### Gemiddeld: bovenste rij

- CMS-content: De vervolgkeuzelijst biedt toegang tot het koppelen van een Artikel,
  Contact, Veld, Media, Menu of Module.

Artikel: Het voorbeeld laat zien hoe u eenvoudig een link naar een artikel op
de huidige site kunt maken.

![TinyMCE-modal voor linkselectie](../../../nl/images/editors/editors/03-link-button.png)

Een link naar het gewenste artikel maken:

- Plaats de cursor op de plek in het artikel waar u de titel van het gekoppelde
  artikel wilt invoegen.
- Klik op de knop Artikel om het venster te openen.
- Klik op de titel om het gewenste artikel in het venster te selecteren. U
  kunt de zoekfunctie en filters gebruiken om het gewenste artikel te vinden.
- Er wordt op de huidige cursorlocatie een link met de titel van het artikel
  ingevoegd.
- Indien nodig kunt u de linktekst bewerken.

Op dezelfde manier kunt u andere items koppelen, zoals Media, Modules enzovoort.

Pagina-einde: Met deze knop kunt u een pagina-einde in een
artikel invoegen. Met een pagina-einde is paginanavigatie mogelijk wanneer het artikel
in een lay-out wordt weergegeven. Dit is handig voor lange artikelen. Wanneer deze
knop wordt ingedrukt, wordt een venster weergegeven zoals hieronder:

![TinyMCE-formulier voor pagina-einde](../../../nl/images/editors/editors/04-pagebreak-button.png)

- **Paginatitel**. Voer de titel in die voor de nieuwe pagina moet worden weergegeven (bijvoorbeeld
  'Pagina 2').
- **Alias van inhoudsopgave**. Optioneel veld dat in de inhoudsopgave voor deze pagina wordt weergegeven. In een artikel met meerdere pagina's geeft Joomla een
  'inhoudsopgave' voor de pagina weer, waarmee de gebruiker elke pagina kan selecteren. Als dit veld leeg is,
  wordt de paginatitel gebruikt. Als u een andere titel in de inhoudsopgave wilt, voert u deze hier in.
- **Pagina-einde invoegen**. Klik op deze knop om het pagina-einde met de ingevoerde velden in te voegen. Het pagina-einde wordt weergegeven als een grijze stippellijn
  over het artikel. Houd er rekening mee dat een pagina-einde niet kan worden bewerkt. Als u een veld in het pagina-einde
  wilt wijzigen, klikt u in het artikel net na het pagina-einde, drukt u op Backspace totdat het pagina-einde is verwijderd
  en voegt u vervolgens een nieuw pagina-einde met de gewenste informatie in.
- De configuratie wordt ingesteld in de plug-in Content - Page Break.

Lees meer: Met deze knop wordt een Lees meer-einde in het artikel ingevoegd. Dit
wordt weergegeven als een rode stippellijn over het artikel.

- Als een artikel een Lees meer-einde bevat, wordt aanvankelijk alleen de tekst vóór het einde,
  de Introductietekst genoemd, weergegeven, samen met een link Lees meer. Als de gebruiker op deze link klikt, wordt
  het volledige artikel of alleen het gedeelte na de link Lees meer weergegeven. Dit is afhankelijk van de instelling van de parameters voor de
  Introductietekst
  van het artikel.
- Met het Lees meer-einde kunt u ruimte op pagina's besparen door alleen de Introductietekst weer te geven.
- Als u einden wilt invoegen voor een artikel dat in een Artikelindeling wordt weergegeven, gebruikt u de knop Pagina-einde.

De knoppen in de vervolgkeuzelijst CMS-content kunnen worden uitgeschakeld in
Plugins - editors-xtd.

- Met de knoppen linksboven kunt u tekst cursief maken. Daarnaast staan
  knoppen voor links, rechts, gecentreerd en uitgevuld uitlijnen.
- Opmaakprofielen: Selecteer vooraf gedefinieerde opmaakprofielen voor Koppen, Inline, Blokken enzovoort.
- Inspringing verkleinen (naar links verplaatsen) en Inspringing vergroten (naar rechts inspringen).
- 3 puntjes: Tweede rij van de werkbalk weergeven.

#### Gemiddeld: tweede rij

- Link invoegen/bewerken: Selecteer de gekoppelde tekst en druk op deze
  knop om een link in te voegen of te bewerken. Er verschijnt een
  pop-upvenster waarin u gegevens over de link kunt invoeren.
- Link verwijderen: Markeer de gekoppelde tekst en druk op deze knop om
  een link te verwijderen.
- Anker: Een anker is een bladwijzer in een artikel waarmee u rechtstreeks
  naar dat punt in het artikel kunt linken.
- Broncode: Er verschijnt een pop-up met de HTML-broncode, zodat u de
  HTML-broncode kunt bewerken.
- Horizontale lijn invoegen: Verplaats de cursor naar de gewenste locatie
  in het artikel en klik op deze knop om een horizontale lijn in te voegen.
- Tabel: Nieuwe tabel invoegen, eigenschappen van tabelrij, eigenschappen
  van tabelcel, rij ervoor invoegen, rij erna invoegen, rij verwijderen,
  kolom ervoor invoegen, kolom erna invoegen, kolom verwijderen,
  samengevoegde tabelcellen splitsen, tabelcellen samenvoegen.
- Subscript, superscript, speciaal teken.
- Tekst bekijken in pop-up.

#### Geavanceerde preset

De werkbalkset 0 biedt de meest uitgebreide bewerkingsopties, zoals
hieronder weergegeven. De set is standaard toegewezen aan de gebruikersgroepen
Beheerder, Editor en Supergebruikers.

![TinyMCE-gegevensset 0](../../../nl/images/editors/editors/05-set-0.png)

Deze optie biedt alle knoppen die hierboven zijn beschreven voor de werkbalk
van set 1. Daarnaast zijn de volgende opties beschikbaar.

#### Geavanceerd: bovenste rij

- Blokken: alinea, koppen, voorgeformatteerd.
- Lettertypen: Selecteer het gewenste lettertype.
- Tekengrootte: Selecteer de gewenste tekengrootte.
- Zoeken en vervangen.
- Afbeelding invoegen/bewerken: Plaats de cursor op de gewenste locatie
  en druk op deze knop om een afbeelding in te voegen. Er verschijnt een
  pop-upvenster waarin u de bron, breedte of hoogte en andere informatie
  over de afbeelding kunt invoeren.

#### Geavanceerd: tweede rij

- Tekstkleur of achtergrondkleur selecteren.
- Volledig scherm.
- Emoticons.
- Media invoegen: Plaats de cursor op de gewenste locatie en druk op deze
  knop om media in te voegen. Er verschijnt een pop-upvenster waarin u het
  type, bestand of URL en andere informatie over de media kunt invoeren.
- Richting van links naar rechts of richting van rechts naar links: Met
  deze knoppen kunt u de tekstrichting invoeren of wijzigen, bijvoorbeeld
  voor talen die van rechts naar links worden gelezen.
- Knippen, kopiëren, plakken.
- Onzichtbare tekens weergeven (zoals alineamarkeringen).
- Blokken weergeven.
- Harde spatie.
- Citaatblok.
- Sjabloon invoegen.

#### Geavanceerd: derde rij

- De artikeltekst afdrukken.
- Codevoorbeeld invoegen/bewerken.
- Datum/tijd invoegen.
- Opmaak wissen.

### Toegankelijkheid

TinyMCE is compatibel met schermlezers zoals
<a href="https://www.freedomscientific.com/products/software/jaws/"
rel="nofollow noreferrer noopener">JAWS</a> en
<a href="https://www.nvaccess.org/"
rel="nofollow noreferrer noopener">NVDA</a>. U kunt het
effectief gebruiken, zelfs als u de muis niet gebruikt.

#### Sneltoetsen

| Taak                                      | PC                     | macOS                  |
|-------------------------------------------|------------------------|------------------------|
| Focus naar/naar menubalk springen         | Alt+F9                 | ⌥+F9                 |
| Focus naar/naar werkbalk springen         | Alt+F10                | ⌥+F10                |
| Focus naar/naar elementpad springen        | Alt+F11                | ⌥+F11                |
| Menu/submenu/venster sluiten              | Esc                    | esc                    |
| Terugkeren naar het inhoudsgebied van de editor | Esc                    | esc                    |
| Links/rechts door menu/werkbalk navigeren | Tab en de pijltoetsen  | Tab en de pijltoetsen  |

Zie voor meer informatie:

- <a href="https://www.tiny.cloud/docs/advanced/accessibility/"
  rel="nofollow noreferrer noopener">TinyMCE - Toegankelijkheid</a>
- Een lijst met beschikbare
  <a href="https://www.tiny.cloud/docs/advanced/keyboard-shortcuts/"
  rel="nofollow noreferrer noopener">sneltoetsen</a> (pc, mac)
  binnen het hoofdgedeelte van de editor.

## CodeMirror

De 'Editor - CodeMirror' is ontworpen om het invoeren van HTML-code in
een artikel of beschrijving eenvoudig te maken. CodeMirror ondersteunt
syntaxisaccentuering en automatische aanvulling, zoals in deze schermafbeelding
wordt weergegeven.

![CodeMirror-bewerkingsformulier](../../../nl/images/editors/editors/06-codemirror.png)

- De hieronder weergegeven knoppen bieden toegang tot links naar elk
  onderdeel van de site.
- CodeMirror biedt enkele van dezelfde voordelen als het gebruik van 'Editor -
  Geen', maar maakt het werken met onbewerkte HTML-code iets eenvoudiger.
- De configuratie is ingesteld in de plug-in Editor -
  CodeMirror.

## Geen

Als 'Editor - Geen' voor een gebruiker is geselecteerd, wordt een eenvoudige teksteditor weergegeven. Hiermee kunt u onbewerkte, niet-opgemaakte HTML invoeren. U kunt de werkbalkknop 'Voorbeeld' gebruiken om een voorbeeld te bekijken van hoe de HTML wordt weergegeven.

Houd er rekening mee dat de optie 'Geen' handig kan zijn wanneer u 'standaardtekst' of aangepaste HTML invoert, bijvoorbeeld om een PayPal-link te maken. TinyMCE maakt automatisch opnieuw op en verwijdert bepaalde HTML wanneer een bestand wordt opgeslagen. Hierdoor kan complexe HTML niet correct werken.

Als dit gebeurt, kunt u de editor tijdelijk wijzigen in 'Geen' en de gewenste inhoud maken. Houd er rekening mee dat u, als u deze inhoud in de toekomst wilt bewerken, voorzichtig moet zijn en uw editor moet wijzigen in 'Geen'. Als u de inhoud anders met TinyMCE opent en opslaat, kunt u uw aangepaste HTML kwijtraken.

De plug-in 'Editor - Geen' heeft geen configuratie.

*Vertaald door openai.com*