<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Authentication_Group  / Display title: Authenticatie Groep -->

## Groepsbeschrijving

De plugins in deze groep worden gebruikt voor standaard gebruikerslogin naar de Site- of Beheerderinterfaces. De standaard is Joomla Authenticatie. De *Cookie* methode wordt gebruikt in combinatie met de *Onthoud mij* functie voor alleen Site login. De cookie wordt ingesteld na de eerste login met een van de andere methoden.

## Authenticatie - Cookie

![cookie authenticatie plugin](../../../en/images/plugins/plugin-group-authentication-cookie.png)

- **Levensduur van Cookie** Het aantal dagen totdat de authenticatiecookie verloopt. Andere factoren kunnen ervoor zorgen dat het eerder verloopt. Langere tijdsduur is minder veilig.
- **Sleutel Lengte** De lengte van de sleutel die wordt gebruikt om de cookie te versleutelen. Langere lengtes zijn veiliger, maar ze vertragen de prestaties.

## Authenticatie - Joomla

Deze plugin verwerkt de standaard gebruikersauthenticatiemethode in Joomla. Het heeft geen opties.

## Authenticatie - LDAP

Deze plugin verwerkt gebruikersauthenticatie tegen een LDAP-server.

![ldap authenticatie plugin](../../../en/images/plugins/plugin-group-authentication-ldap.png)

- **Host** De host-URL. Bijvoorbeeld, `openldap.mijnbedrijf.org`.
- **Port** Het poortnummer. De standaard is 389.
- **LDAP V3** Of deze host LDAP versie 3 gebruikt. De standaard is LDAP v2.
- **Onderhandel TLS** Of je TLS-encryptie met deze host wilt gebruiken. Als ingesteld op *Ja*, moet al het verkeer van en naar deze server versleuteld zijn.
- **Volg Verwijzingen** Of de LDAP_OPT_REFERRALS-vlag op Ja of Nee moet worden ingesteld. Voor Windows 2003 hosts moet dit op Nee worden ingesteld.
- **Autorisatiemethode** *Direct binden als gebruiker* of *Binden en zoeken*.
- **Basis DN** De basis DN van je LDAP-server.
- **Zoekstring** Een querystring die wordt gebruikt om naar een bepaalde gebruiker te zoeken. Het `[search]` trefwoord wordt vervangen door de inlognaam die door de gebruiker is getypt. Bijvoorbeeld: `uid=[search]`. Er kan meer dan één zoekstring worden ingevoerd. Scheid elke door een puntkomma `;` teken. Dit wordt alleen gebruikt bij het zoeken.
- **DN van de gebruiker** Het [gebruikersnaam] trefwoord wordt dynamisch vervangen door de inlognaam die door de gebruiker is getypt. Een voorbeeldstring is: `uid=[gebruikersnaam], dc=[mijn-domein], dc=[com]`. Er kan meer dan één string worden ingevoerd. Scheid elke door een puntkomma `;` teken. Dit wordt alleen gebruikt als de hierboven genoemde autorisatiemethode is ingesteld op *Direct binden als gebruiker*.
- **Verbindingsgebruikersnaam en verbindingswachtwoord** Deze definiëren verbindingsparameters voor de DN-zoekfase. Voor anonieme zoekopdrachten, laat je beide velden leeg. Voor een administratieve verbinding is de *Verbindingsgebruikersnaam* de gebruikersnaam van een administratief account (bijvoorbeeld, *Administrator*). In dit geval is het *Verbindingswachtwoord* het daadwerkelijke wachtwoord van dit administratieve account.
- **Kaart: Volledige naam** Het LDAP-attribuut dat de volledige naam van de gebruiker bevat.
- **Kaart: E-mail** Het LDAP-attribuut dat het e-mailadres van de gebruiker bevat.
- **Kaart: Gebruikers-ID** Het LDAP-attribuut dat het inlog-ID van de gebruiker bevat. Voor Active Directory is dit `sAMAccountName`.
- **Debug** Hiermee wordt debuggen op hardcoded niveau 7 ingeschakeld.

*Vertaald door openai.com*

