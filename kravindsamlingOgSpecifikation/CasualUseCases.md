# Casual UseCases

### UC01 Registrer information

- P-vagten udfylder dato, placering og registreringsnummer om ulovlig parkering.
- P-vagten tager billede af den ulovligt parkerede bil (UC02 Tag billede)
- P-vagten indsætter billedet på registreringen
- P-vagten tilknytter GPS information til registreringen (UC03 Hent GPS infornation)
- Systemet validerer at nødvendig information er indtastet
- Systemet gemmer informationen lokalt


### UC02 Tag billede

- P-vagter tager billede af den ulovligt parkeret bil.
- P-vagten godkender at billedet skal gemmes, eller tager et nyt billede
- Systemet gemmer billedet lokalt


### UC03 Hent GPS information

- P-vagten aktiverer GPS funktionaliteten
- Systemet henter GPS informationer og viser det på skærmen
- P-vagten godkender informationen 
- GPS koordinaterne bliver indsat i registreringen

### UC04 Sykroniser dagens bøder

- P-vagten forbinder den håndholdte computer til en arbejdsstation
- P-vagten aktiverer synkronisering af bøder
- De registrerede bøder bliver overført til det fælles system
- De vedhæftede billeder bliver overført til det fælles system

### UC05 Udskriv bøder

- Systemet henter personinformation fra motorregistret ud fra registreringsnummeret
- Systemet gemmer personinformationer og sørger for kryptering af disse for at overholde GDPR
- Systemet udskriver bødeforlæg på baggrund personinformationer og det som P-vagten har indsamlet

### UC06 Modtag betalingsinformationer fra Dansk bank

- Systemet modtager betalingsinformationer fra Danske Bank
- Systemet gemmer informationerne lokalt
- Systemet opdaterer bøde status (UC07 Opdater bøde status efter betaling)

### UC07 Opdater bøde status efter betaling

- Systemet matcher ubetalte bøder med indbetalingerne fra Danske Bank
- Systemet markerer indbetalte bøder som betalt
- Systemet gennemgår alle ubetalte bøder
- Systemet opdaterer alle ubetalte bøder hvis deres indbetalingsdato er overskredet som at der skal udsendes rykker
- Systemet opdaterer alle ubetalte rykkere hvis deres indbetalingsdato er overskredet som at de skal overdrages til inkasso

### UC08 Se bøde status  ( betalt, ubetalt, rykket, inkasso)

- Kontormedarbejderen åbner en oversigt over status på alle bøder
- Systemet viser en opdeling af antallet af bøder i de forskellige statusser (Betalt, ubetalt, rykket eller inkasso)
- Kontormedarbejderen udsender rykkere på de bøder som har overskredet betalingsdato (UC09 Udsend rykker)
- Kontormedarbejderen overdrager rykkere som har overskredet betalingsdato til inkasso (UC10 Overfør til inkasso)

### UC09 Udsend rykker

- Kontormedarbejderen laver bøden om til en rykker
- Systemet udskriver rykkeren med originalt beløb samt rykkergebyr	

### UC10 Overfør til inkasso

- Kontormedarbejderen laver rykker om til en inkassosag
- Systemet udskriver original bøde, udsendte rykkere samt nødvendige personinformationer
- Kontormedarbejderen overdrager informationer til eksternt inkassobureau











