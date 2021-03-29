# UC01 Registrer information

UseCase navn | Registrer information | 
-------------| -------------------------------| 
Scope        | PBS
Primary Actor| P-vagter
Level        | User Goal
Beskrivelse  | Systemet skal kunne registrere dato, placering og registreringsnummer om ulovlig parkering.Samtidig kan systemet tage billede af bil og hent GPS information.
Stakeholders and Interests | P-vagt (ønsker at kunne registrere en ulovligt parkeret bil)
Preconditions | Der holder en ulovligt parkeret bil
Succes Guarantee | Bøden skal være gemt i systemet med den nødvendige information.
Main Succece Scenario |   1. P-vagter udfylder dato, placering og registreringsnummer om ulovlig parkering.<br> 2. P-vagten tager billede af den ulovligt parkerede           bil.<br> 3. P-vagten indsætter billedet på registreringen.<br> 4. P-vagten godkender at billedet skal gemmes, eller tager et nyt billede.<br> 5. P-vagten tilknytter GPS information til registreringen.<br> 6.  Systemet henter GPS informationer og viser det på skærmen. <br> 7. P-vagten godkender informationen.<br> 8. GPS koordinaterne bliver indsat i registreringen.<br> 9. Systemet validerer at nødvendig information er indtastet.<br> 10. Systemet gemmer informationen lokalt.
Extensions |1.a P-vagten indtaster mangelfuld information om dato, placering eller registreringsnummer.<br> 1. Systemet oplyser om den manglende/forkert indtastede information og beder om en korrekt indtastning. Processen fortsætter fra punkt 1.<br><br> 3 a. P-vagten forsøger at indsætte et billede på registreringen men der er en fejl ved billedet.<br> 1. Systemet oplyser at P-vagten skal tage et nyt billede og processen fortsætter fra punkt 2.<br><br> 5 a. P-vagten henter GPS koordinater, men GPS opslaget fejler og returnerer invalide data.<br> 1. Systemet oplyser at P-vagten skal tilknytte GPS data igen. Processen fortsætter fra punkt 5.<br><br> 9 a. Systemet forsøger at gemme bøden men opdager en fejl ved valideringen af data.<br> 1. P-vagten oplyses om fejlen og om hvilket felt det drejer sig om. Processen fortsætter fra indsættelsen af det data som er fejlet.
Special Requirements | --
Technology & Data Variations List | --
Frequency of Occurrence | Use casen forekommer ved oprettelse af en bøde.
Miscellaneous | -- 

