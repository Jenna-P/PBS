# UC02 Synkroniser dagens bøder

UseCase navn | Sykroniser dagens bøder | 
-------------| -------------------------------| 
Scope        | PBS
Primary Actor| P-vagter
Level        | User Goal
Beskrivelse  | P-vagten skal efter dagens arbejde sørge for, at alle de registrerede bøder bliver indsat i det fælles system.
Stakeholders and Interests | P-vagt  (ønsker at aflevere dagens bøder)
Preconditions | Der skal være registreret bøder på den håndholdte computer som ikke er synkroniseret med det fælles system endnu.
Succes Guarantee | Bøderne er synkroniseret korrekt fra den håndholdte enhed til det fælles system.
Main Succece Scenario |   1. P-vagten forbinder den håndholdte computer til en arbejdsstation.<br> 2. P-vagten aktiverer synkronisering af bøder. <br> 3. De registrerede bøder bliver overført til det fælles system.<br> 4. De vedhæftede billeder bliver overført til det fælles system. <br> 5. Systemet henter personinformation fra motorregistret ud fra registreringsnummeret. <br> 6. Systemet gemmer personinformationer og sørger for kryptering af disse for at overholde GDPR. <br> 7. Bøden oprettes i det fælles system.
Extensions |1.a Forbindelsen til det fælles system fejler. <br> 1. Systemet oplyser P-vagten at han skal forsøge at forbinde det håndholdte enhed igen. Processen fortsætter fra punkt 1.<br><br> 2 a. Synkronisering af informationerne til det fælles system fejler.<br> 1. Systemet oplyser P-vagten at han skal forsøge at synkronisere igen. Processen fortsætter fra punkt 2.<br><br> 5 a. Forbindelsen til motorregistret fejler og det er ikke muligt at hente informationer på den pågældende bøde.<br> 1. Systemet markerer bøden som ikke importeret og oplyser P-vagten at han skal synkronisere igen. Processen fortsætter fra punkt 2.<br> <br> 7 a. Oprettelsen af bøden fejler.<br>  1. Systemet markerer bøden som ikke importeret og oplyser P-vagten at han skal synkronisere igen. Processen fortsætter fra punkt 2.
Special Requirements | --
Technology & Data Variations List | --
Frequency of Occurrence | Use casen forekommer når bøderne skal synkroniserer til det fælles system.
Miscellaneous | -- 


