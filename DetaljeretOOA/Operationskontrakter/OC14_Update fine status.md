# OC14_Update fine status

#### Operation:
Systemet matcher alle indbetalinger med modsvarende ubetalte bøder som er registreret i systemet.

#### Cross-reference:
UC04 Håndter betalingsinformationer

#### Pre-conditions:
- Der er modtaget indbetalinger fra Danske Bank
- Indbetalingerne er valideret og gemt
- Der findes ubetalte bøder i systemet

#### Post-conditions:
- Alle indbetalinger er matched med de korrekte udestående bøder
- Deres status er opdateret.
