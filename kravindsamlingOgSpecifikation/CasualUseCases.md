# Casual UseCases

### UC01 Registrer information

- P-vagten udfylder dato, placering og registreringsnummer om ulovlig parkering.
- P-vagten tager billede af den ulovligt parkerede bil 
- P-vagten indsætter billedet på registreringen
       - P-vagten godkender at billedet skal gemmes, eller tager et nyt billede
- P-vagten tilknytter GPS information til registreringen 
       - Systemet henter GPS informationer og viser det på skærmen
       - P-vagten godkender informationen 
       - GPS koordinaterne bliver indsat i registreringen
- Systemet validerer at nødvendig information er indtastet
- Systemet gemmer informationen lokalt


### UC02 Sykroniser dagens bøder

- P-vagten forbinder den håndholdte computer til en arbejdsstation
- P-vagten aktiverer synkronisering af bøder
- De registrerede bøder bliver overført til det fælles system
- De vedhæftede billeder bliver overført til det fælles system

### UC03 Udskriv bøder

- Systemet henter personinformation fra motorregistret ud fra registreringsnummeret
- Systemet gemmer personinformationer og sørger for kryptering af disse for at overholde GDPR
- Systemet udskriver bødeforlæg på baggrund personinformationer og det som P-vagten har indsamlet

### UC04  Handl betalingsinformationer

- Systemet modtager betalingsinformationer fra Danske Bank
-	Systemet gemmer informationerne lokalt
-	Systemet opdaterer bøde status 
- Systemet matcher ubetalte bøder med indbetalingerne fra Danske Bank
-	Systemet markerer indbetalte bøder som betalt
-	Systemet gennemgår alle ubetalte bøder
- Systemet opdaterer alle ubetalte bøder hvis deres indbetalingsdato er overskredet som at der skal udsendes rykker
- Systemet opdaterer alle ubetalte rykkere hvis deres indbetalingsdato er overskredet som at de skal overdrages til inkasso

### UC05 Manage bøde status

- Kontormedarbejderen åbner en oversigt over status på alle bøder
- Systemet viser en opdeling af antallet af bøder i de forskellige statusser (Betalt, ubetalt, rykket eller inkasso)
- Kontormedarbejderen udsender rykkere på de bøder som har overskredet betalingsdato 
- Systemet udskriver rykkeren med originalt beløb samt rykkergebyr	
- Kontormedarbejderen overdrager rykkere som har overskredet betalingsdato til inkasso Systemet udskriver original bøde, udsendte rykkere samt nødvendige    personinformationer
- Kontormedarbejderen overdrager informationer til eksternt inkassobureau











