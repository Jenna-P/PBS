# UC03 Udskriv bøder

UseCase navn | Udskriv bøder | 
-------------| -------------------------------| 
Scope        | PBS
Primary Actor| Systemet
Level        | User Goal
Beskrivelse  | Systemet udskriver automatisk alle dagens registrerede bøder i løbet af natten, så de er klar til udsendelse næste dag
Stakeholders and Interests | Kontormedarbejder (ønsker at bøderne er udskrevet og klar til behandling næste dag)
Preconditions | Dagens registrerede bøder skal være synkroniseret til det fælles system.
Succes Guarantee | Alle de registrerede bøder som er oprettet i løbet af dagen er udskrevet korrekt.
Main Succece Scenario | 1. Systemet henter automatisk alle nyoprettede bøder på et defineret tidspunkt.<br> 2. Systemet validerer at al nødvendig information er tilstede.<br> 3. Bøder med manglende information sættes på fejlliste til manuel opfølgning.<br> 4. Systemet udskriver valide bødeforlæg på baggrund personinformationer og det som P-vagten har indsamlet.
Extensions | 1 a. Systemet kan ikke hente bøderne.<br> 1. Systemet oplyser om fejl og afventer manuelt brugerinput. Processen fortsætter ved punkt 1.<br><br> 4 a. Systemet kan ikke printe bøderne grundet printerfejl.<br> 1. Systemet oplyser om fejl og afventer manuelt brugerinput. Processen fortsætter ved punkt 4.
Special Requirements | --
Technology & Data Variations List | --
Frequency of Occurrence | Use casen forekommer når bøderne bliver printet i løbet af natten.
Miscellaneous | -- 


