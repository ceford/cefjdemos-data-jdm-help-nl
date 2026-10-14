<!--
{
    "source": "https://docs.joomla.org/Help4.x:Joomla_Update:_Options",
    "title": "Joomla-update: opties",
    "description": " ",
    "author": ""
}
-->

## Beschrijving

De pagina Joomla-update: opties wordt gebruikt om parameters in te stellen voor het beheren van het 
updateproces van de Joomla-core.

### Algemene elementen

Sommige aspecten van deze pagina worden behandeld in afzonderlijke Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars)

## Toegang

- Selecteer **Systeem → Updatepaneel → Joomla** in het beheerdersmenu. Vervolgens...
  - Selecteer de knop **Opties** in de werkbalk.

## Schermafbeelding

![Opties voor Joomla-update: updatebron](../../../nl/images/joomla-update/joomla-update-options/01-update-source.png)

## Formuliervelden

### Tabblad Updatebron

- **Updatekanaal**
  - **Standaard** Met deze instelling geeft Joomla een melding weer wanneer er een nieuwe 
    minor- of patchversie beschikbaar is voor de huidige majorversie. 
  - **Joomla Next** Met deze instelling geeft Joomla een melding weer wanneer er een 
    nieuwe stabiele majorversie beschikbaar is en alle bestaande minorversies en
    extensies up-to-date zijn.
  - **Aangepaste URL** Voor Joomla-ontwikkelaars. Er verschijnen meer velden.
- **Minimale stabiliteit** De minimale stabiliteit van de extensie-updates die u wilt zien. Development is het minst stabiel, Stable heeft productiekwaliteit. Als een extensie geen niveau opgeeft, wordt deze beschouwd als Stable.
  - **Development** Voor sites van Joomla-ontwikkelaars.
  - **Alpha** Voor sites voor alfatests.
  - **Beta** Voor sites voor bètatests.
  - **Release Candidate** Voor sites voor Release Candidate-tests.
  - **Stable** Voor productiesites.
- **Aangepaste URL** Als er bij het updatekanaal een aangepaste URL is geselecteerd, verschijnt hier een veld om de URL in te voeren.
- **Selectievakje voor mogelijk incompatibele extensies** Toont het selectievakje bij de controle vóór de update als een van de op uw site geïnstalleerde extensies mogelijk incompatibel is met de Joomla-versie waarnaar u bijwerkt. 
  *Opmerking:* het selectievakje wordt weergegeven bij het bijwerken naar een nieuwe Joomla-versiefamilie (minor- of majorversie).
- **Selectievakje Back-up bevestigen** Toont het selectievakje om te bevestigen dat u een back-up hebt gemaakt en klaar bent om bij te werken in de laatste stap voordat de update daadwerkelijk wordt toegepast. 

### Tabblad Automatische updates

*Automatische updates zijn vanaf Joomla 5.4 beschikbaar voor sites die openbaar toegankelijk zijn op internet. Als uw site zich achter een firewall bevindt of niet openbaar toegankelijk is, zoals in een lokale testomgeving, moet u handmatig bijwerken.*

![Opties voor Joomla-update: updatebron](../../../nl/images/joomla-update/joomla-update-options/02-automated-updates.png)

- **Automatische update** Wanneer dit is ingesteld op *Ja*, wordt uw site automatisch bijgewerkt naar de nieuwste minor- of patchrelease (inclusief beveiligingspatches) zodra deze beschikbaar komt. Majorreleases zijn niet inbegrepen.
- **Updatetoken** Dit is een token waarmee deze site wordt geïdentificeerd. Het wordt aangemaakt door de externe Joomla-updateserver en kan niet door de gebruiker worden gewijzigd.
- **Laatst gecontroleerd** De meest recente datum waarop uw site contact heeft opgenomen met de updateserver.
- **E-mail naar gebruikersgroepen verzenden** Alle gebruikers in de geselecteerde groepen ontvangen e-mails over geslaagde of mislukte automatische updates. Als er geen gebruikers worden gevonden, worden de e-mails naar alle Super Users verzonden. Ontvangers moeten de optie Systeeme-mails ontvangen hebben ingeschakeld.

Gebruik de knop *Inline Help in-/uitschakelen* voor meer details.

*Vertaald door openai.com*