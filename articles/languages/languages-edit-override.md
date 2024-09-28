<!-- Filename: Help4.x:Languages:_Edit_Override  / Display title: Talen: Override Bewerken -->

## Beschrijving

In de Joomla-code worden tekstreeksen die in de Gebruikersinterface moeten verschijnen, of dit nu de Site-interface of de Beheerder-interface is, uitgedrukt als string-constanten. Bijvoorbeeld, de string *Uw sessie is verlopen. Gelieve opnieuw in te loggen.* wordt uitgedrukt als `JLIB_ENVIRONMENT_SESSION_EXPIRED`. De tekstreeks kan in elke taal worden vertaald. De standaardtaal is Brits Engels. Er zijn duizenden van dergelijke reeksen in een Joomla-installatie.

Als een string niet geschikt is voor uw site, kunt u de Taaloverschrijvingsfunctie gebruiken om het origineel te vervangen. De pagina *Talen: Overschrijvingen* toont een lijst van bestaande overschrijvingen, dus deze is aanvankelijk leeg.

### Gemeenschappelijke elementen

Sommige aspecten van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).

## Hoe Toegang te Krijgen

- Selecteer **Systeem → Beheer Paneel → Taal Overschrijvingen**. Dan...
  - Selecteer een **Taal en Client** uit de keuzelijst. Dan...
    - Selecteer de **Nieuw** knop in de Werkbalk om een nieuwe overschrijving te maken.
      Of...
    - Selecteer de constante link in de **Constante** kolom om een bestaande overschrijving te bewerken.

## Screenshot

![Talen Bewerken Overschrijven](../../../nl/images/languages/languages-edit-override.png)

## Formuliervelden

### Rechterpaneel: Zoek naar de tekst die je wilt wijzigen

- **Zoeken Naar** Begin hier! Je kent waarschijnlijk eerder de Waarde
  (verlopen) dan de Constante (`_VERLOPEN`). In beide gevallen is de zoekopdracht
  niet hoofdlettergevoelig voor een deel van de string.
- **Zoektekst** Voer de tekst in om naar te zoeken en selecteer de knop *Zoeken*.
- **Zoekresultaten** Een lijst met strings die de zoekterm bevatten
  verschijnt in een apart Resultatenpaneel onder het Rechter paneel. Selecteer de 
  gewenste tekst. De constante en tekst worden gekopieerd naar het 
  *linkerpaneel* om bijgewerkt en opgeslagen te worden.

### Linker paneel: Maak een Nieuwe Override of Bewerk deze Override

- **Taal** en **Locatie** Deze werden geselecteerd voordat dit
  bewerkingsformulier werd geopend en kunnen niet worden gewijzigd.
- **Taal Constante** Dit is de string die door de
  ontwikkelaar in de code wordt gebruikt. Als de waarde niet in de code bestaat, zal de string
  nooit worden gebruikt.
- **Tekst** Dit is waar je de standaardterm overschrijft met jouw
  versie.
- **Voor Beide Locaties** Selecteer om de override toe te passen op zowel de front-end als
  back-end.
- **Bestand** Dit toont waar het override-bestand zich bevindt in het bestands-
  systeem. Dit kan nodig zijn voor probleemoplossingen.

*Vertaald door openai.com*

