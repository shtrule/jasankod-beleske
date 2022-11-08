# Smislena imena

## Osnovna pravila

- Ime treba da otkrije nameru - zašto postoji, šta radi i kako se koristi
- Menjaj imena ukoliko smisliš bolja
- Izbegavaj dezinformacije: 
    - kratka imena bez smisla - `x`, `z`, `foo`
    - reči sa ukorenjenim značenjem - `list`, `win`, `hp`
    - jako slične reči za različite pojmove - TODO: dodaj primer
- Ukoliko imaš promenljive sličnog imena, daj im smislene razlike: 
    - ne koristi brojeve i prazne reči: 
        - `a1` i `a2` => umesto ovog možda možemo da iskoristimo `source` i `destination` (ili slično)
        - `accountInfo` i `accountData` => nema smislene razlike
- Koristi izgovorljiva imena: 
    - `vremeGenerisanja` je bolje od `genymdhms` 
- Koristi pretraživa imena: 
    - npr. `MAX_CLASSES_PER_STUDENT` je bolje od 7 (magic literal)
    - izbegavaj jednoslovna imena (pogotovo e - najčešže slovo u engleskom), osim u jako kratkim blokovima koda, npr. petljama 
- Izbegavaj dodavanje tipa u ime promenljive (npr. mađarska notacija), jer otežava menjanje imena ili tipa promenljive, a i suvišno je u modernim okruženjima
- Izbegavaj `_` prefiks (sa ovim se baš i ne slažem)
- Izbegavaj `I` pri imenovanju interfejsa, umesto ovoga dodaj `Impl(ementation)` u klasu koja implementira interfejs (ni sa ovim se ne slažem)

## Imena klasa

- Trebalo bi da bude imenica a ne glagol
- Izbegavaj `Manager`, `Data`, `Info`, `Processor` pri imenovanju klase - TODO: dodaj primer