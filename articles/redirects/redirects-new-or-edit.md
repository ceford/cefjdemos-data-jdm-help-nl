<!-- Filename: Help4.x:Redirects:_New_or_Edit  / Display title: Omleidingen: Nieuw of Bewerken -->

## Beschrijving

De pagina *Omleidingen: Nieuw of Bewerken* wordt gebruikt om een nieuwe omleiding toe te voegen of een bestaande te bewerken. De URL waarvan je wilt omleiden, mag geen werkende URL zijn op je website die daadwerkelijk een webpagina laadt. Het kan de URL zijn naar een webpagina die je hebt uitgeschakeld in de Joomla! beheerdersinterface. De Bronnen-URL die je opgeeft wanneer je de omleiding maakt, moet de volledige URL zijn zoals je die in je webbrowser zou typen. De Bestemmings-URL die je opgeeft wanneer je een omleiding maakt, moet ook de volledige URL zijn.

### Algemene Elementen

Sommige elementen van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).

## Hoe te openen

- Selecteer **Systeem → Redirects** uit het Beheerdersmenu. Dan...
  - Om een nieuwe redirect aan te maken, klik op de knop **Nieuw** in de Toolbar. Of...
  - Om een bestaande redirect te bewerken, klik op de link in de kolom **Verlopen URL**.

## Screenshot

![Redirects links](../../../nl/images/redirects/redirects-edit.png)

## Formulieren

### Bewerken/Nieuwe Link \#1 tabblad

- **Verlopen URL** De URL waarnaar doorgestuurd moet worden.
- **Nieuwe URL** De URL waarnaar doorgestuurd wordt.
- **Status** Gepubliceerd status van het item. Mogelijke waarden zijn:
  - *Ingeschakeld* Het item is ingeschakeld. Dit is de enige status die
    reguliere websitebezoekers toestaat dit item te bekijken.
  - *Uitgeschakeld* Het item is uitgeschakeld.
  - *Gearchiveerd* Het item is gearchiveerd.
  - *Verwijderd* Het item is naar de prullenbak verplaatst.
- **Opmerking** Een opmerking die alleen door een beheerder zichtbaar is. Het is
  voornamelijk bedoeld voor de referentie van de beheerder.
- **ID** Dit is een uniek identificatienummer voor dit item, dat
  automatisch door Joomla wordt toegewezen. Het wordt intern gebruikt
  om het item te identificeren, en je kunt dit nummer niet wijzigen.
  Bij het aanmaken van een nieuw item geeft dit veld "0" weer totdat je
  de nieuwe invoer opslaat, waarna een nieuw ID wordt toegekend.
- **Aanmaakdatum** Datum waarop het item (Artikel, Categorie, enzovoort) werd aangemaakt.
- **Laatst bijgewerkte datum** Geeft de laatste datum weer waarop het item is aangepast.

## Hoe maak je een Redirect

1.  Zorg er eerst voor dat je de optie *URL-herschrijven gebruiken* hebt ingeschakeld in de Global Configuration-opties van je Joomla!-installatie. Let op dat alleen het inschakelen van de optie *URL-herschrijven gebruiken* niet voldoende is. Je moet ook de extra stap nemen om het `htaccess.txt` bestand in de webservermap waar je Joomla! hebt geïnstalleerd te hernoemen naar `.htaccess` of naar welke bestandsnaam je Apache-webserver vereist voor aanvullende configuratierichtlijnen. In het Apache-configuratiebestand wordt deze instelling `AccessFileName` genoemd en standaard is deze ingesteld op `.htaccess`.
2.  Open vervolgens de pagina *Redirect: Links* en selecteer de knop *Nieuw* in de werkbalk.
3.  Voer op de pagina *Redirects: Nieuw* de redirect-informatie in. Wanneer je URL's invoert in de velden *Verlopen URL* en *Nieuwe URL*, voer dan de volledige URL in zoals je deze in je webbrowser zou typen om deze te bekijken. De *Verlopen URL* moet een URL zijn die niet naar een geldige webpagina op je website leidt. Je kunt een bron-URL opgeven voor een Joomla!-webpagina die je in de beheerderbackend in een uitgeschakelde status hebt geplaatst. Zorg ervoor dat de optie *Status* is ingesteld op **Ingeschakeld**.
4.  Selecteer de knop **Opslaan & Sluiten** in de werkbalk om je nieuwe redirect op te slaan en in werking te laten treden.

## Tips

- Wanneer je URL's invoert in de velden *Verlopen/Bron URL* en *Nieuwe/Bestemmings URL*, voer dan de volledige URL in zoals je deze in je webbrowser zou typen om de webpagina te bekijken.

*Vertaald door openai.com*

