# ProgramiranjeKorisnickihInterfejsaVezbe

Ovaj repozitorijum poseduje izvorni kod aplikacije obradjene na vezbama iz predmeta PRogramiranje korisnickih interfejsa na smeru Racunarske Nauke, Fakulteta za  Informatiku i Racunarstvo Univerziteta Singidunum

## Tehnologije

Aplikcacija je razvijena upotrebom frontend okruzenja Angular 18. Pored toga koriscene su sledece biblioteke:

-[Angular MAterial](https://material.angular.io/)
-[SweetAlert2](https://sweetalert2.github.io/)

### Struktura Aplikacije

Izvorni kod koristi standardnu strukturu Angular projekta bez `app.modules.ts` datoteke koja nije potrebna upravo od verzije 18. Svi potrebni moduli se uvoze direktno u komponentama koje ih upotrebljavaju.

Prikaz svih direktorijuma :

-`src/app`- Glavni direktorijum koji sadrzi sve komponente 
-`src/models`- Direktorijum u kojem skladistimo definicije tipova/interfejsa potrebnih za brzi razvoj apliakcije
-`src/services`- Direktorijum koji sadrzi definicije servisa neophodnih za rad aplikacije

## Dodatne informacije

Aplikacija koristi Angular Router koji zahteva da prilikom pustanja aplikacije u produkciju svaka putanja redirektovana na `index.html` datoteku jer su rute definisane programski u javascriptu-u a ne fizicki postojanjem fajlova.