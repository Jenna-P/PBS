# Risiko analyse
|  Risiko | Sandsynlighed | Konsekvens | Prioritet | Revideret sandsynlighed | Revideret konsekvens |
| ------------------------------------ | ---------------------------------------------------- | --------- | --------- | ------------------ |--------- |
| Sygdom blandt udviklerne | 5/10 | Forsinkelse af projektet(10/10)      | 50 | 2/10 | Mindre risiko for forsinkelse (1/10) |

**Imødekommelses strategi**
Der er kun 1 udvikler på projektet hvilket gør forsinkelser sandsynlige.
Projekter bør have mere end 1 udvikler tilkoblet, som kan tage over i forbindelse med sygdom, ferie og lignende.


|  Risiko | Sandsynlighed | Konsekvens | Prioritet | Revideret sandsynlighed | Revideret konsekvens |
| ------------------------------------ | ---------------------------------------------------- | --------- | --------- | ------------------ |--------- |
| Fejlestimater | 8/10 | Forsinkelse af projektet(7/10)      | 56   | 2/10 | Godkendelse af estimater sikrer projektforløbet (2/10) |

**Imødekommelses strategi**
Fejlestimater grundet manglende erfaring gør det usandsynligt at projektet kan færdiggøres til tiden.
Estimater skal revideres og godkendes af en udvikler/projektleder med mere erfaring, og eventuelt tilrettes, inden det sendes til kunden.


|  Risiko | Sandsynlighed | Konsekvens | Prioritet | Revideret sandsynlighed | Revideret konsekvens |
| ------------------------------------ | ---------------------------------------------------- | --------- | --------- | ------------------ |--------- |
| Svartid hos lærerne | 5/10 | Forsinkelse af projektet(3/10)      | 15    | 2/10 | Det er forudsigeligt hvornår man får svar (2/10) |

**Imødekommelses strategi**
Det forventes at eventuelle tvivlsspørgsmål stillet til læreren også bliver besvaret med en hvis forsinkelse.
Der kan eventuelt specifikke tidsrum hvor kan man stille spørgsmål/forvente svar. For eksempel kan man samle spørgsmål sammen 1-2 gange om ugen, og aftale at svar modtages senest dagen efter.


|  Risiko | Sandsynlighed | Konsekvens | Prioritet | Revideret sandsynlighed | Revideret konsekvens |
| ------------------------------------ | ---------------------------------------------------- | --------- | --------- | ------------------ |--------- |
| Data afleveres kun en gang i døgnet | 10/10 | Fejl i data(5/10)      | 50    | 1/10 | Valideringen sikrer at alle data er modtaget (1/10) |

**Imødekommelses strategi**
De håndholdte terminaler skal kun aflevere data en gang i døgnet når medarbejderne er tilbage på kontoret. 
Der skal indbygges kontrol der sikrer at al data er korrekt opsamlet i løbet af dagen og at alt er afleveret, eventuelt i form af hash validering


|  Risiko | Sandsynlighed | Konsekvens | Prioritet | Revideret sandsynlighed | Revideret konsekvens |
| ------------------------------------ | ---------------------------------------------------- | --------- | --------- | ------------------ |--------- |
| Data integreres mod Danske Bank | 10/10 | Fejl i data(5/10)      | 50   | 1/10 | Valideringen sikrer at alle data er modtaget (1/10) |

**Imødekommelses strategi**
Der bygges integration mod Danske Bank.
Det skal sikres at al data er sendt/modtaget korrekt, da det ellers ikke er sikkert at der forefindes korrekte data om betalinger. Dette kan eventuelt løses ved udveksling af hash key som der valideres i mod.


|  Risiko | Sandsynlighed | Konsekvens | Prioritet | Revideret sandsynlighed | Revideret konsekvens |
| ------------------------------------ | ---------------------------------------------------- | --------- | --------- | ------------------ |--------- |
| Der opsamles persondata | 10/10 | Persondata ikke opbevaret korrekt(10/10)      | 100   | 3/10 | Kryptering samt oversigt over gemte data sikrer at GDPR er overholdt(4/10) |

**Imødekommelses strategi**
Ved opsamling af personlige data skal det sikres at GDPR overholdes.
Persondata skal krypteres når det ligger gemt/samt når det flyttes. Derudover bør virksomheden etablere et datakatalog hvor det registreres at der findes persondata i denne applikation


|  Risiko | Sandsynlighed | Konsekvens | Prioritet | Revideret sandsynlighed | Revideret konsekvens |
| ------------------------------------ | ---------------------------------------------------- | --------- | --------- | ------------------ |--------- |
| Der skal bygges 2 UI | 10/10 | Ekstra uddannelse(5/10)      | 50    | 1/10 | Den samme UI gør det nemt at anvende systemet (3/10) |

**Imødekommelses strategi**
Der skal bygges separate brugerflader til hhv. den håndholdte samt til arbejdsstationerne.
Det skal sikres at der er en lignende brugerflade og arbejdsmetode for det håndholdte system og på arbejdsstationerne


|  Risiko | Sandsynlighed | Konsekvens | Prioritet | Revideret sandsynlighed | Revideret konsekvens |
| ------------------------------------ | ---------------------------------------------------- | --------- | --------- | ------------------ |--------- |
| Der udsendes forkert rykkere og inkassoskrivelser | 10/10 | Forkert udsendelse af rykkere/inkasso(10/10)      | 100   | 3/10 | En validering formindsker risikoen for forkerte udsendelser (3/10) |

**Imødekommelses strategi**
Ubetalte regninger skal valideres inden de overføres til inkasso da det ellers stillet firmaet sårbart juridisk.
Der bør etableres enten en manuel eller automatisk validering af data inden der udsendes rykkere/inkasso skrivelser.


|  Risiko | Sandsynlighed | Konsekvens | Prioritet | Revideret sandsynlighed | Revideret konsekvens |
| ------------------------------------ | ---------------------------------------------------- | --------- | --------- | ------------------ |--------- |
| Mangler bilejers informationer | 10/10 | Udsendelse af bøder ikke mulig(6/10)      | 60    | 1/10 | En validering sørger for at al data indsamles (1/10) |

**Imødekommelses strategi**
Den håndholdte terminal bør validere at al nødvendig information er indhentet for at kunne sende en parkeringsbøde


