# UC05 Håndter bøde status

UseCase navn | Håndter bøde status | 
-------------| -------------------------------| 
Scope        | PBS
Primary Actor| Kontormedarbejder
Level        | User Goal
Beskrivelse  | Kontormedarbejderen skal udføre kontrol af om der er udestående betalinger som skal enten rykkes eller overdrages til inkasso.
Stakeholders and Interests | Kontormedarbejder (ønsker at lave opfølgning på registrerede  bøder samt behandle udstående bøder)
Preconditions | Der skal være registreret bøder i systemet.
Succes Guarantee | Kontormedarbejderen har fået overblik over alle bøder og har behandlet udestående bøder korrekt.
Main Succece Scenario | 1. Kontormedarbejderen åbner en oversigt over status på alle bøder.<br> 2. Systemet viser en opdeling af antallet af bøder i de forskellige statusser (Betalt, ubetalt, rykket eller inkasso)<br> 3. Kontormedarbejderen udsender rykkere på de bøder som har overskredet betalingsdato.<br> 4. Systemet udskriver rykkeren med originalt beløb samt rykkergebyr.<br> 5. Kontormedarbejderen overdrager rykkere som har overskredet betalingsdato til inkasso.<br> 6. Systemet udskriver original bøde, udsendte rykkere samt nødvendige personinformationer.<br> 7. Kontormedarbejderen overdrager informationer til eksternt inkassobureau	
Extensions | 4. a Systemet kan ikke udskrive rykkere og oplyser brugeren om dette.<br> 1. Brugeren løser print problemet. Processen fortsætter fra punkt 3.<br><br> 6. a Systemet kan ikke udskrive de nødvendige oplysninger til inkasso overdragelsen og oplyser brugeren om dette.<br> 1. Brugeren løser print problemet. Processen fortsætter fra punkt 5.
Special Requirements | --
Technology & Data Variations List | --
Frequency of Occurrence |  Use casen forekommer når kontormedarbejderen ønsker at arbejde med udestående bøder eller ønsker et overblik og de betalte bøder.
Miscellaneous | -- 



