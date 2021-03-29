# UC04 Håndter betalingsinformationer

UseCase navn | Håndter betalingsinformationer | 
-------------| -------------------------------| 
Scope        | PBS
Primary Actor| Systemet
Level        | User Goal
Beskrivelse  | Systemet modtager informationer om modtagne betalinger fra Danske bank på daglig basis. Disse importeres og de registrerede bøder opdateres.
Stakeholders and Interests | Kontormedarbejder (ønsker at lave opfølgning på ubetalte bøder)
Preconditions | Der skal være bøder i systemet som endnu ikke er betalt.
Succes Guarantee | Betalingsinformationerne er modtaget og bøderne er opdateret med korrekt status.
Main Succece Scenario | 1. Systemet modtager betalingsinformationer fra Danske Bank.<br> 2. Systemet gemmer informationerne lokalt.<br> 3. Systemet opdaterer bøde status.<br> 4. Systemet matcher ubetalte bøder med indbetalingerne fra Danske Bank.<br> 5. Systemet markerer indbetalte bøder som betalt.<br> 6. Systemet gennemgår alle ubetalte bøder.<br> 7. Systemet opdaterer alle ubetalte bøder hvis deres indbetalingsdato er overskredet som at der skal udsendes rykker.<br> 8. Systemet opdaterer alle ubetalte rykkere hvis deres indbetalingsdato er overskredet som at de skal overdrages til inkasso.
Extensions | 2 a. Systemet kan ikke gemme informationerne fra Danske Bank.<br> 1. Systemet oplyser om fejl og afventer brugerinput. Processen fortsætter fra punkt 2.<br><br> 3 a. Systemet kan ikke opdatere bødestatus.<br> 1. Systemet oplyser om fejl og afventer brugerinput. Processen fortsætter fra punkt 3.<br><br> 4. a Systemet kan ikke finde nogle matchende bøder med indbetalingerne.<br> 1. Systemet oplyser om fejl og afventer brugerinput. Processen fortsætter fra punkt 4.
 Special Requirements | --
Technology & Data Variations List | --
Frequency of Occurrence |  Use casen forekommer når indbetalingerne bliver importeret fra Danske Bank.
Miscellaneous | -- 


