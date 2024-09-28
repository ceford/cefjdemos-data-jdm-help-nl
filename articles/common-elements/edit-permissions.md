<!-- Filename: Help4.x:Edit_Permissions  / Display title: Machtigingen Bewerken -->

## Doel

Veel extensies hebben bewerkingsschermen met een tabblad Machtigingen dat wordt gebruikt om de machtigingen toe te wijzen aan gebruikersgroepen. Het aantal gebruikersgroepen kan variëren omdat aangepaste gebruikersgroepen kunnen worden toegevoegd voor speciale doeleinden. Het aantal acties dat kan worden gewijzigd, varieert ook per extensie. Dit artikel is een korte beschrijving van de machtigingenschermen voor dergelijke speciale doeleinden.

Stel je voor dat er een gebruiker is die zorgt voor media (afbeeldingen en bestanden) maar verder geen andere verantwoordelijkheden heeft. Een groep genaamd Oddjob is aangemaakt en toegewezen aan het Toegangsniveau Special. Ook is een gebruiker genaamd Oddjob aangemaakt en toegewezen aan de groep Oddjob.

Voor meer gedetailleerde informatie over gebruikersgroepen, toegangsniveaus en machtigingen is er een apart tutorial over [Toegangscontrole](jdocmanual?article=user/users/access-control).

## Globale Configuratie Rechten

In dit voorbeeld hebben gebruikers in de Oddjob-groep globale rechten gekregen om in te loggen op de Beheerinterface, maar niets anders.

![Screenshot van Rechten](../../../nl/images/common-elements/global-configuration-permissions-tab.png)

## Componentconfiguratie Permissies

Om toegang te krijgen tot een specifieke component moeten de rechten worden ingesteld in de componentopties.
In dit voorbeeld de Media-componentopties.

![Media Screenshot](../../../nl/images/common-elements/media-options-permissions-tab.png)

Je zult merken dat deze component minder Acties beschikbaar heeft en de Oddjob
groep net genoeg permissies heeft om het werk te doen.

Om de permissies voor deze component te wijzigen:

* Selecteer de Groep door op de titel aan de linkerkant te klikken.<br>
    Zoek de gewenste Actie.
    * Verwijderen. Gebruikers kunnen dit artikel verwijderen.
    * Bewerken. Gebruikers kunnen dit artikel bewerken.
    * Status Bewerken. Gebruikers kunnen de gepubliceerde status en gerelateerde informatie voor dit artikel wijzigen.
* Selecteer de gewenste permissie voor de actie die je wilt wijzigen.
    * Overgenomen. Overgenomen voor gebruikers in deze Groep uit de Globale Configuratie, Artikelopties, of Artikelcategorie.
    * Toegestaan. Toegestaan voor gebruikers in deze Groep. Let op: Als deze actie op een van de hogere niveaus is Geweigerd, zal de Toegestane permissie hier niet van kracht worden. Een Geweigerde instelling kan niet worden overschreven.
    * Geweigerd. Geweigerd voor gebruikers in deze Groep.
* Klik op Opslaan in de Toolbar bovenaan. Wanneer het scherm wordt vernieuwd, zal de kolom Berekende Instelling de effectieve permissie voor deze Groep en Actie tonen.

## De Gebruikerservaring

Na inloggen zal een gebruiker in de Oddjob-groep de modules zien die **Speciale** toegang hebben ingesteld op het Startdashboard, en een Menu-item link naar de Media-component.

![Startdashboard voor Oddjob](../../../nl/images/common-elements/home-dashboard-for-oddjob.png)

En het Mediascherm voor gebruiker Oddjob is zoals verwacht:

![Mediascherm voor Oddjob](../../../nl/images/common-elements/media-screen-for-oddjob.png)

*Vertaald door openai.com*

