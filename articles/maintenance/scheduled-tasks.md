<!-- Filename: Help5.x:Scheduled_Tasks / Display title: Geplande Taken -->

## Beschrijving

Geplande taken worden gebruikt om routineonderhoudstaken van de site uit te voeren als een alternatief voor server cron-taken. De taken worden gedefinieerd in plugins in de taakgroep. Er wordt een aantal taakplugins geleverd die als voorbeelden kunnen worden gebruikt voor het maken van andere gespecialiseerde taken.

### Veelvoorkomende Elementen

Sommige aspecten van deze pagina worden behandeld in aparte Help-artikelen:

* [Werkbalken](jdocmanual?article=help/common-elements/toolbars).
* [Lijstfilters](jdocmanual?article=help/common-elements/list-filters).
* [Kolomkoppen van de lijst](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginering van de lijst](jdocmanual?article=help/common-elements/list-pagination).

## Hoe toegang te krijgen

Uitgaande van het Administrator-menu:

- Selecteer **Systeem → Beheer paneel → Geplande taken**

De aanvankelijke lijst met Geplande Taken bevat drie items.

## Screenshot

![scheduled tasks list](../../../nl/images/maintenance/scheduled-tasks-list.png)

## Kolomkoppen

Kolommen die uniek zijn voor Geplande taken:

- **Taaktype** Taken worden aangemaakt uit een beschikbare lijst van types.
- **Laatste Uitvoerdatum** De datum en tijd van de laatste taakuitvoering.
- **Volgende Uitvoerdatum** De datum en tijd van de volgende taakuitvoering.
- **Testtaak** Een knop om de taak handmatig uit te voeren.
- **Taakprioriteit** De prioriteit kan Laag, Normaal of Hoog zijn. Taken met een hogere prioriteit kunnen mogelijk taken met een lagere prioriteit blokkeren.

## Uitvoeringsgeschiedenis

Selecteer de knop in de werkbalk om een lijst met individuele taakuitvoeringen te zien.

![task execution history list](../../../nl/images/maintenance/scheduled-tasks-logs.png)

## Beschikbare Taken

De volgende schermafbeelding toont een lijst van beschikbare taken. Sommige zijn demonstraties, sommige zijn nuttig.

![Scheduled Tasks Available](../../../nl/images/maintenance/scheduled-tasks-types.png)

Elke taak heeft zijn eigen taakspecifieke parameters die vanzelfsprekend zouden moeten zijn. Bijvoorbeeld, de taak **Site Offline** heeft alleen zin als de **Taak Bewerken → Basisvelden → Uitvoeringsregel** is ingesteld op **Handmatige Uitvoering**.

## Geplande Taken Opties

Selecteer de knop Opties in de Werkbalk om geplande taken te configureren.

### Tabblad Taken configureren

![task timeout setting](../../../nl/images/maintenance/scheduled-tasks-options-configure-tasks.png)

- **Taak Time-out** De standaard is 300 seconden.

### Luie Planner-tabblad

![lazy schedule setting](../../../nl/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- **Ingeschakelde** Taken worden geactiveerd door sitebezoekers.
- **Uitgeschakelde** Taken moeten worden geactiveerd door een extern cron-job.
- **Verzoekinterval** De standaard is 300 seconden.

### Web Cron-tabblad

![web cron setting](../../../nl/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- **Web Cron** Uitgeschakeld is de standaardinstelling. Ingeschakeld vereist een hash om de taak te activeren. Voor de eerste keer opslaan is er een bericht dat een sleutel vereist is. Na het opslaan is er een veld met een Webcron-link url om te kopiëren.

*Vertaald door openai.com*

