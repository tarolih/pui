# Predlog projekta

|                             |                                                                |
| :-------------------------- | :------------------------------------------------------------- |
| **Naziv projekta**          | eZdravnik                              |
| **Člani projektne skupine** | Vanessa Jačmenjak, Vasja Lev Kirn, Dejan Mandic, Ana Polančec in Tara Rolih|
| **Kraj in datum**           | 28.02.2022, Ljubljana                                   |

## Povzetek projekta

Vsak izmed nas si želi priti do svojega zdravnika hitro in enostavno. V realnosti pa je 
to lahko dolgotrajen proces, ki z nepotrebno birokracijo bremeni pacienta in zdravniško osebje ter
s tem močno vpliva na dolžino čakalnih vrst v slovenskem zdravstvu. Z uporabo spletne aplikacije eZdravnik, 
se lahko pacient, pri svojih zdravnikih (lahko gre za osebnega zdravika, ginekologa, psihiatra, zobozdravnika,...), v le nekaj trenutkih, naroči na želen prost termin za pregled ali pa
zaprosi za podaljšanje recepta. S tem se izogne napornemu čakanju med klicanjem zdravstvenega osebja
na telefonski liniji. Zdravnik lahko pacientov termin potrdi ali zavrne, lahko pa se odloči, da 
pacienta povabi na video pregled, če se želi prepričati o urgentnosti njegovega stanja ali pa gre za zdravstveno storitev, ki ne potrebuje fizičnega obiska (psiholog). Osebni zdravnik lahko na preprost način dodeli dostop do pacientovega zdravniškega kartona specialistu, če je obisk le-tega zanj potreben. 
Intuitiven uporabniški vmesnik in optimizacija zdravstvenih storitev, ki jih ponuja aplikacija, bosta pripomogla 
k hitrejšemu obravnavanju pacientov in tako izboljšala kakovost ter zmanjšala čakalne vrste v zdravstvu.

## 1. Projektna ideja

### 1.1 Ozadje

Slovensko zdravstvo je v veliki meri preobremenjeno. Dostop do osebnih zdravnikov in specialistov je sploh v času pandemije, ko je naročanje obvezno, močno omejeno z dosegljivostjo ambulant. Telefonske linije so pogosto zasedene ali pa so klici za naročanje sprejeti le ob določenih urah. V postopno digitalizacijo slovenskega zdravstva se že vključujejo ideje in tudi že konkretne implementacije naročanja preko spleta. Izkušnja epidemije in dela od doma je razkrila pravo vrednost videoklicev, ki so postali velik del našega vsakdana in nov način osebne komunikacije. 

### 1.2 Področje in motivacija

V zadnjih letih se je jasno pokazala preobremenitev slovenskega javnega zdravstva. Velik del zdravstva še vedno ni digitaliziran in zato neučinkovit. Ena izmed neučinkovitosti je zagotovo postopek naročanja. Medicinsko osebje mora poleg izvajanja zdravstvenih storitev prevzeti še breme naročanja, kar pa vodi v nezadovoljstvo iz obeh smeri komunikacije. Medicinsko osebje se ne more posvečati zdravstveni oskrbi in nujnim primerom, pacienti pa težko dosežejo zdravnika. Takšna celostna rešitev trenutno še ne obstaja, najbolj pa bi koristila ponudnikom zdravstvenih storitev ter uporabnikom le-teh. 

### 1.3 Namen

- Poenostaviti in optimizirati zdravstvene storitve,
- pacientom omogočiti pregled nad vsemi svojimi zdravniki v spletni aplikaciji,
- pacientom omogočiti naročanje, podaljševanje receptov in opravljanje pregleda preko spleta,
- z minimizacijo birokratskih obremenitev zdravnika, povečati hitrost sprejema pacientov in s tem zmanjšati čakalne dobe v zdravstvu,  
- omogočiti podaljšanje receptov pacienta z uporabo spletne aplikacije,
- zdravniku omogočiti enostavno dostopanje do pacientovega zdravniškega kartona,
- omogočiti lažje dostopanje do podatkov pacienta s strani različnih zdravnikov,
- minimizirati čas, ki ga zdravniško osebje porabi za telefonske pogovore s pacienti.

### 1.4 Cilji

Cilji projekta so sledeči:

- Spletna aplikacija za naročanje in komunikacijo med pacienti in zdravniki z intuitivnim uporabniškim vmesnikom,
- zmanjšanje porabljenega časa za naročanje pri zdravniku,
- hitrejši pretok informacij med pacientom in njegovim zdravnikom,
- tehnična dokumentacija (podatkovna baza),
- tehnična dokumentacija (aplikacija),
- navodila za uporabo uporabniškega vmesnika,
- delujoča podporna storitev za uporabnike aplikacije.

### 1.5 Smernice za rešitev

Razvit informacijski sistem mora izpolnjevati naslednje kriterije:

- Odziven in funkcionalen spletni uporabniški vmesnik,
- lahka prepoznavnost in odkrivanje,
- praviloma digitalno (sistem mora omogočati tudi uporabo na klasičen način, prijave v fizični obliki, vendar mora dajati prednost elektronskemu načinu),
- sistem mora biti povezan z večimi viri, ki vsebujejo informacije o urniku dela zdravnikov,
- za razvoj morajo biti uporabljene odprtokodne rešitve,
- zasebnost zdravstvenih kartotek uporabnikov in dejavnosti na platformi je treba spoštovati,
- varnosti uporabnikov in shranjenim podatkom dnevnika dejavnosti uporabnikov je potrebno dati prednost,
- sposobnost enostavnega zagotavljanja podatkov verodostojnim zunanjim zahtevam prek rešitev, kot so rest API ali skupne baze podatkov.

### 1.6 Končni uporabniki

Sistem bodo uporabljali zdravniško osebje in pacienti oziroma posamezniki, ki potrebujejo zdravstveno storitev. Sistem bo uporabljen v slovenskem zdravstvu, kar število uporabnikov enači s številom prebivalcev Republike Slovenije – okoli 2 milijona. Pričakuje se, da so uporabniki digitalno pismeni do te mere, da spletno storitev najdejo preko brskalnika, se v sistem registrirajo ali prijavijo in s pritiski na gumbe izberejo željeno storitev. Kljub temu, da tako naročanje izključuje digitalno nepismen del starejše generacije, bi tudi te posamezniki od take storitve imeli korist, saj bi bile telefonske linije ambulant razbremenjene in s tem zdravniki v večji meri dosegljivi. 

## 2. Projektni načrt

### 2.1 Povzetek razdelitve projekta na aktivnosti

Zajem zahtev:
- pridobitev zahtev od naročnika
- opredelitev specifikacij od naročnika o zahtevani rešitvi

Načrtovanje programske opreme:
- načrtovanje sistema
- oblikovanje uporabniškega vmesnika
- načrtovanje arhitekture
- izdelava podatkovnega modela
- izdelava načrta testiranja

Implementacija in napredni vidiki razvoja programske opreme:
- implementacija frontend komponent aplikacije
- implementacija podatkovnih baz
- implementacija API dostopa
- implementacija ostalih backend komponent aplikacije
- priprava navodil za uporabo uporabniškega vmesnika
- priprava dokumentacije
- testiranje frontend dela aplikacije
- testiranje backend dela aplikacije
- pregled programske rešitve z naročnikom

Aktivnosti, ki se bodo izvajale skozi trajanje projekta:
- vodenje projekta
- skupinski sestanki ekipe
- redna komunikacija z naročnikom
- nadzor upoštevanja dobre prakse razvoja programske opreme

### 2.2 Načrt posameznih aktivnosti

| **Oznaka aktivnosti**                               |    A1_PZN                                                                                                        |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  | 21.03.2022                                                                                                                     |
| **Predvideni datum zaključka izvajanja aktivnosti** | 28.03.2022                                                                                                                     |
| **Trajanje**                                        | 6 dni                                                                                                                          |
| **Naziv aktivnosti**                                | Pridobitev zahtev od naročnika                                                                                                 |
| **Obseg aktivnosti v ČM**                           |  1/8 ČM                                                                                                      |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Pridobitev jasnih in koherentnih zahtev in pričakovanja naročnika                                                              |
| **Opis aktivnosti**                                 | Komunikacija z naročnikom glede zahtev programske rešitve                                                                      |
| **Morebitne odvisnosti in omejitve**                | / , aktivnost je na kritični poti|
| **Pričakovani rezultati aktivnosti**                | Seznam zahtev delovanja rešitve                                                                                            |



| **Oznaka aktivnosti**                               |  A2_OSN                                                                                                         |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  | 29.03.2022                                                                                                                  |
| **Predvideni datum zaključka izvajanja aktivnosti** | 31.03.2022                                                                                                                  |
| **Trajanje**                                        |  3 dni                                                                                                                      |
| **Naziv aktivnosti**                                | Opredelitev specifikacij od naročnika o zahtevani rešitvi                                            |
| **Obseg aktivnosti v ČM**                           |  1/8 ČM                                                                                                     |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Pridobljene jasno določene specifikacije zahtevane rešitve                                                           |
| **Opis aktivnosti**                                 | Komunikacija z naročnikom in skupni dogovor o specifikacijah zahtevane rešitve                                            |
| **Morebitne odvisnosti in omejitve**                | A1_PZN, aktivnost je na kritični poti |
| **Pričakovani rezultati aktivnosti**                | Seznam točnih specifikacij sistema                                                                                             |



| **Oznaka aktivnosti**                               |   A3_NS                                                                                                        |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  | 01.04.2022                                                                                                           |
| **Predvideni datum zaključka izvajanja aktivnosti** | 12.04.2022                                                                                                             |
| **Trajanje**                                        | 8 dni                                                                                                                      |
| **Naziv aktivnosti**                                | Načrtovanje sistema                                                                                                             |
| **Obseg aktivnosti v ČM**                           | 1/3 ČM                                                                                                        |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Jasno določen načrt sistema, ki ustreza zahtevam in specifikacijam rešitve.                                           |
| **Opis aktivnosti**                                 | Dogovarjanje o najustreznejšem načrtu čelnega in zalednega sistema.                                                    |
| **Morebitne odvisnosti in omejitve**                | A2_OSN, aktivnost je na kritični poti |
| **Pričakovani rezultati aktivnosti**                |  Načrt sistema, kateremu lahko sledimo.                                                                                         |



| **Oznaka aktivnosti**                               |   A4_OUV                                                                                                     |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |   13.04.2022                                                                                                |
| **Predvideni datum zaključka izvajanja aktivnosti** |   19.04.2022                                                                                              |
| **Trajanje**                                        |   4 dni                                                                                                                   |
| **Naziv aktivnosti**                                |   Oblikovanje uporabniškega vmesnika                                                                                     |
| **Obseg aktivnosti v ČM**                           |   1/5 ČM                                                                                                   |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |  Jasno določen izgled in strukturo uporabniškega vmesnika                                                              |
| **Opis aktivnosti**                                 | Zasnova grafične podobe uporabniškega vmesnika, skladno s specifikacijami in zahtevami naročnika                  |
| **Morebitne odvisnosti in omejitve**                |  A3_NS |
| **Pričakovani rezultati aktivnosti**                |   Izdelana grafična podoba in struktura uporabniškega vmesnika                                                    |



| **Oznaka aktivnosti**                               |    A5_NA                                                                                                      |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |  13.04.2022                                                                                                              |
| **Predvideni datum zaključka izvajanja aktivnosti** |  20.04.2022                                                                                                          |
| **Trajanje**                                        | 5 dni                                                                                                                    |
| **Naziv aktivnosti**                                | Načrtovanje arhitekture                                                                                                 |
| **Obseg aktivnosti v ČM**                           |   1/3 ČM                                                                                                      |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Točen načrt povezovanja komponent sistema (strežniki)                                                                 |
| **Opis aktivnosti**                                 |  Dogovarjanje o najustreznejšem načrtu podatkovnih komponent sistema.                                         |
| **Morebitne odvisnosti in omejitve**                |A3_NS, aktivnost je na kritični poti  |
| **Pričakovani rezultati aktivnosti**                |  Jasna opredelitev povezav med strežniki in aplikacijo                                               |



| **Oznaka aktivnosti**                               |    A6_IPM                                                                                                       |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |  21.04.2022                                                                                    |
| **Predvideni datum zaključka izvajanja aktivnosti** |  26.04.2022                                                                                                   |
| **Trajanje**                                        |  4 dni                                                                                                                     |
| **Naziv aktivnosti**                                | Izdelava podatkovnega modela                                                                                             |
| **Obseg aktivnosti v ČM**                           |  1/5 ČM                                                                                                       |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Jasno opredelitit podatkovni model za uporabljene podatkovne baze                                                       |
| **Opis aktivnosti**                                 | Načrtovanje podatkovnega modela, ki ustreza načrtovani arhitekturi                                         |
| **Morebitne odvisnosti in omejitve**                | A5_NA, aktivnost je na kritični poti |
| **Pričakovani rezultati aktivnosti**                | Izdelan podatkovni model (opredeljene vse povezave med podatki)                            |



| **Oznaka aktivnosti**                               |     A7_INT                                                                                                      |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |   28.04.2022   |
| **Predvideni datum zaključka izvajanja aktivnosti** |   03.05.2022                                                                                    |
| **Trajanje**                                        |   3 dni                                                                                                                   |
| **Naziv aktivnosti**                                |  Izdelava načrta testiranja                                                                                             |
| **Obseg aktivnosti v ČM**                           |  3/8 ČM                                                                                                    |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Določitev področij, ki potrebujejo testiranje ter določiti njihovo prioriteto                                   |
| **Opis aktivnosti**                                 | Pregled načrta sistema, uporabniškega vmesnika in podatkovnega modela ter glede na njih določanje prioritet testiranja     |
| **Morebitne odvisnosti in omejitve**                | A6_IPM |
| **Pričakovani rezultati aktivnosti**                | Seznam področij potrebnih testiranja, po padajoči prioriteti                                                         |

| **Oznaka aktivnosti**                               |    A8_IFK                                                                                                       |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |  20.04.2022                                                                                                                   |
| **Predvideni datum zaključka izvajanja aktivnosti** |  06.05.2022                                                                                                                            |
| **Trajanje**                                        |  11 dni                                                                                                                     |
| **Naziv aktivnosti**                                |  Implementacija frontend komponent aplikacije                                                                                                            |
| **Obseg aktivnosti v ČM**                           |   5/4 ČM                                                                                                      |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |  Delujoči frontend aplikacije torej uporabniški vmesnik za uporabnike paciente in zdravnike                                                                                                        |
| **Opis aktivnosti**                                 |  Implementacije frontend komponent aplikacije                                                                                   |
| **Morebitne odvisnosti in omejitve**                |  A4_OUV |
| **Pričakovani rezultati aktivnosti**                |  Delujoč in intuitiven uporabniški vmesnik za aplikacijo                                                                                             |

| **Oznaka aktivnosti**                               |      A9_IPB                                                                                                      |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |  28.04.2022                                                                                                                           |
| **Predvideni datum zaključka izvajanja aktivnosti** |  13.05.2022                                                                                                                            |
| **Trajanje**                                        |  11 dni                                                                                                                      |
| **Naziv aktivnosti**                                |  Implementacija podatkovnih baz                                                                                                            |
| **Obseg aktivnosti v ČM**                           |  5/4 ČM                                                                                                       |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |  Delujoča implementacija in povezava podatkovnih baz med seboj in z aplikacijo                                                                                                         |
| **Opis aktivnosti**                                 |  Implementacija podatkovnih baz                                                                                    |
| **Morebitne odvisnosti in omejitve**                |  A6_IPM, aktivnost je na kritični poti|
| **Pričakovani rezultati aktivnosti**                |  Delujoča integracija podatkovnih baz, ki omogoča efektivni prenos informacijskih podatkov (o zdravnikih in pacientih) v aplikaciji                                                                                             |

| **Oznaka aktivnosti**                               |      A10_IAPI                                                                                                    |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |   28.04.2022                                                                                                                        |
| **Predvideni datum zaključka izvajanja aktivnosti** |   05.05.2022                                                                                                                          |
| **Trajanje**                                        |   5 dni                                                                                                                   |
| **Naziv aktivnosti**                                | Implementacija API dostopa                                                                                                          |
| **Obseg aktivnosti v ČM**                           |     5/8 ČM                                                                                                 |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |   Delujoč API klic med aplikacijo in informacijsko bazo zdravstvenega sistema                                                                                                        |
| **Opis aktivnosti**                                 |  Definiranje oblike API klicev in implementacija potrebnih funkcionalnosti                                                                                   |
| **Morebitne odvisnosti in omejitve**                | A6_IPM |
| **Pričakovani rezultati aktivnosti**                |  Delujoč API klic                                                                                            |


| **Oznaka aktivnosti**                               |      A11_IBK                                                                                                     |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |   21.04.2022|
| **Predvideni datum zaključka izvajanja aktivnosti** |   11.05.2022                                                                                                                          |
| **Trajanje**                                        |   13 dni                                                                                                                    |
| **Naziv aktivnosti**                                | Implementacija ostalih backend komponent aplikacije                                                                                                              |
| **Obseg aktivnosti v ČM**                           | 7/4 ČM                                                                                                        |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |  Delujoč backend aplikacije, ki podpira vse zahtevane funckionalnosti                                                                                                         |
| **Opis aktivnosti**                                 | Izdelava in implementacija celotne backend strukture                                                                                     |
| **Morebitne odvisnosti in omejitve**                | A5_NA |
| **Pričakovani rezultati aktivnosti**                |  Delujoč backend                                                                                             |

| **Oznaka aktivnosti**                               |      A12_NVV                                                                                                      |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  | 09.05.2022                                                                                                                            |
| **Predvideni datum zaključka izvajanja aktivnosti** | 12.05.2022                                                                                                                            |
| **Trajanje**                                        |  4 dni                                                                                                                      |
| **Naziv aktivnosti**                                | Priprava navodil za uporabo uporabniškega vmesnika                                                                                                             |
| **Obseg aktivnosti v ČM**                           |  1/4 ČM                                                                                                       |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Zapisati navodila, ki bodo uporabnikom razumljiva in v pomoč pri uporabi uporabniškega vmesnika                                                                                                       |
| **Opis aktivnosti**                                 | Pregled možnih uporab uporabniškega vmesnika in zapis navodil za dosego posameznih funkcionalnosti                                                                                      |
| **Morebitne odvisnosti in omejitve**                | A8_IFK |
| **Pričakovani rezultati aktivnosti**                | Jasna in razumljiva navodila za uporabo uporabniškega vmesnika namenjena                                                                                               |

| **Oznaka aktivnosti**                               |      A13_PD                                                                                                      |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  | 16.05.2022                                                                                                                          |
| **Predvideni datum zaključka izvajanja aktivnosti** | 18.05.2022                                                                                                                           |
| **Trajanje**                                        | 3 dni                                                                                                                     |
| **Naziv aktivnosti**                                | Priprava dokumentacije                                                                                                              |
| **Obseg aktivnosti v ČM**                           | 4/9 ČM                                                                                                      |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |  Dokumentirati opravljeno delo po stnadardih stroke                                                                                                         |
| **Opis aktivnosti**                                 | Pregled opravljenega dela in opis le-tega                                                                                     |
| **Morebitne odvisnosti in omejitve**                | A8_IFK, A9_IPB, A10_IAPI, A11_IBK, aktivnost je na kritični poti|
| **Pričakovani rezultati aktivnosti**                | Pregledna in celostna dokumentacija celotnega projekta                                                                                              |

| **Oznaka aktivnosti**                               |      A14_TF                                                                                                     |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |   09.05.2022                                                                                                                         |
| **Predvideni datum zaključka izvajanja aktivnosti** |   17.05.2022                                                                                                                       |
| **Trajanje**                                        |  7 dni                                                                                                                    |
| **Naziv aktivnosti**                                |  Testiranje frontend dela aplikacije                                                                                                            |
| **Obseg aktivnosti v ČM**                           |    5/8 ČM                                                                                                   |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |  Informacija o pravilnem delovanju frontend dela programske rešitve                                                                                                        |
| **Opis aktivnosti**                                 | Delovanje posameznih frontend komponent preizkusimo na testnih primerih uporabe. Pri tem sledimo načrtu testiranja.                                                                                      |
| **Morebitne odvisnosti in omejitve**                | A7_INT, A8_IFK |
| **Pričakovani rezultati aktivnosti**                |  Informacija o tem, koliko testnih primerov programska rešitev pravilno reši, ter informacija o potrebnih popravkih.                                                                                             |

| **Oznaka aktivnosti**                               |       A15_TB                                                                                                   |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |   16.05.2022|
| **Predvideni datum zaključka izvajanja aktivnosti** |   18.05.2022                                                                                                                       |
| **Trajanje**                                        |  3 dni                                                                                                                   |
| **Naziv aktivnosti**                                | Testiranje backend dela aplikacije                                                                                                            |
| **Obseg aktivnosti v ČM**                           |     5/8 ČM                                                                                                   |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |   Informacija o pravilnem delovanju backend dela programske rešitve                                                                                                       |
| **Opis aktivnosti**                                 |   Delovanje posameznih backend komponent preizkusimo na testnih primerih uporabe. Pri tem sledimo načrtu testiranja.                                                                                |
| **Morebitne odvisnosti in omejitve**                |  A7_INT, A9_IPB, A10_IAPI, A11_IBK |
| **Pričakovani rezultati aktivnosti**                |   Informacija o tem, koliko testnih primerov programska rešitev pravilno reši, ter informacija o potrebnih popravkih.                                                                                           |

| **Oznaka aktivnosti**                               |       A16_PPR                                                                                                  |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |  19.05.2022                                                                                                                     |
| **Predvideni datum zaključka izvajanja aktivnosti** |  20.05.2022                                                                                                                            |
| **Trajanje**                                        |  2 dni                                                                                                                      |
| **Naziv aktivnosti**                                | Pregled programske rešitve z naročnikom                                                                                                              |
| **Obseg aktivnosti v ČM**                           | 1/5 ČM                                                                                            |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Pridobitev povratne informacije od naročnika o programski rešitvi in pridobiti celosten pogled aplikacije s strani uporabnika                                                                                                       |
| **Opis aktivnosti**                                 |  Z naročnikom pregledamo vse funkcionalnosti programske rešitve in primer vsakodnevne uporabe aplikacije                                                                                    |
| **Morebitne odvisnosti in omejitve**                | A12_NVV, A13_PD, A14_TF, A15_TB, aktivnost je na kritični poti |
| **Pričakovani rezultati aktivnosti**                | Potrditev ustreznosti programske rešitve s strani naročnika                                                                                             |



| **Oznaka aktivnosti**                               |       A17_VP                                                                                                   |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |  21.03.2022                                                                                                                        |
| **Predvideni datum zaključka izvajanja aktivnosti** |  22.05.2022                                                                                                                            |
| **Trajanje**                                        |   42 dni                                                                                                                      |
| **Naziv aktivnosti**                                | Vodenje projekta                                                                                                             |
| **Obseg aktivnosti v ČM**                           |  1/5 ČM                                                                                                       |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Zaključek projekta v predvidenem časovnem in finančnem okvirju                                                                                                          |
| **Opis aktivnosti**                                 | Skrb za nemoten potek projekta, usklajevanje članov skupine, skrb za tedenske sestanke in obveščanje ekipe                                                                                     |
| **Morebitne odvisnosti in omejitve**                | /  |
| **Pričakovani rezultati aktivnosti**                | Programska rešitev v predvidenem časovnem in finančnem okvirju                                                                                              |

| **Oznaka aktivnosti**                               |       A18_SE                                                                                                     |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |  21.03.2022                                                                                                                         |
| **Predvideni datum zaključka izvajanja aktivnosti** |  22.05.2022                                                                                                                           |
| **Trajanje**                                        |  42 dni                                                                                                                     |
| **Naziv aktivnosti**                                | Skupinski sestanki ekipe                                                                                                             |
| **Obseg aktivnosti v ČM**                           |  4/7 ČM                                                                                                      |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |  Informiranost celotne ekipe o napredku na različnih delih programske rešitve, reševanje nesporazumov in napetosti v skupini       |
| **Opis aktivnosti**                                 | Sestanki na tedenski ravni, kjer vsak član ekipe opiše svoj napredek v preteklem tednu ter načrt za prihodnji teden, v primeru nejasnosti se podrobneje razdeli naloge posameznim članom                                                                                     |
| **Morebitne odvisnosti in omejitve**                | / |
| **Pričakovani rezultati aktivnosti**                | Dobra ekipna dinamika in skladnost s časovnim načrtom                                                                                              |

| **Oznaka aktivnosti**                               |        A19_KN                                                                                                   |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |  21.03.2022                                                                                                                           |
| **Predvideni datum zaključka izvajanja aktivnosti** |  22.05.2022                                                                                                                          |
| **Trajanje**                                        |  42 dni                                                                                                                   |
| **Naziv aktivnosti**                                |  Redna komunikacija z naročnikom                                                                                                            |
| **Obseg aktivnosti v ČM**                           |   3/8 ČM                                                                                                      |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    |  Aktivna in tekoča komunikacija z naročnikom                                                                                                      |
| **Opis aktivnosti**                                 | Preprečevanje nesporazumov, redno obveščanje naročnika o napredku in doseganju ciljev, preverjanje ustreznosti implementacije                                                                                 |
| **Morebitne odvisnosti in omejitve**                | /  |
| **Pričakovani rezultati aktivnosti**                |  Programska rešitev v skladu z zahtevami in zadovoljen naročnik                                                                                            |

| **Oznaka aktivnosti**                               |     A20_DP                                                                                                       |
| :-------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Predvideni datum pričetka izvajanja aktivnosti**  |   21.03.2022                                                                                                                         |
| **Predvideni datum zaključka izvajanja aktivnosti** |   22.05.2022                                                                                                                           |
| **Trajanje**                                        |   42 dni                                                                                                                    |
| **Naziv aktivnosti**                                | Nadzor upoštevanja dobre prakse razvoja programske opreme                                                                                                             |
| **Obseg aktivnosti v ČM**                           |     1/4 ČM                                                                                                    |
| **Seznam ciljev aktivnosti (kaj želite doseči)**    | Jasen, strukturiran, opredeljen  in dokumentiran razvoj programske opreme skozi celotno trajanje projekta                                                                                                         |
| **Opis aktivnosti**                                 |  Skrb za preglednost in dokumentiranost kode na vseh področjih implementacije                                                                                    |
| **Morebitne odvisnosti in omejitve**                | / |
| **Pričakovani rezultati aktivnosti**                |  Dokumentirana in sturkturirana implementacija, ki lahko novi ekipi služi kot osnova za uporabo in vzdrževanje sistema                                                                                             |






### 2.3 Seznam izdelkov

Izdelki vseh aktivnosti so prikazani v spodnji tabeli:

| Oznaka izdelka   | Ime izdelka      | Datum izdaje     |
| :--------------- | :--------------- | :--------------- |
| I1               | Seznam zahtev delovanja rešitve              | 28.03.2022              |
| I2               | Seznam točnih specifikacij sistema              | 31.03.2022              |
| I3               | Načrt sistema              | 12.04.2022              |
| I4               | Grafična podoba uporabniškega vmesnika              | 19.04.2022              |
| I5               | Načrt arhitekture              | 20.04.2022              |
| I6               | Navodila za uporabo uporabniškega vmesnika              | 12.05.2022              |
| I7               | Podatkovni model              | 26.04.2022              |
| I8               | Prioritetno urejen načrt testiranja              | 03.05.2022              |
| I9               | Frontend del aplikacije              | 06.05.2022              |
| I10              | Backend del aplikacije              | 11.05.2022              |
| I11              | Dokumentacija za aplikacijo              | 18.05.2022              |


### 2.4 Časovni potek projekta - Ganttov diagram


![Ganttov diagram](https://teaching.lavbic.net/plantuml/png/dLJRRjem6BxFKrYgj0Ct44CWbQf9K8g4Ej9eC2vM8SiZ1ZBI1CMkAZJrtHVRCJYn8TlK6_hv_mx_0UW-JWyuno_W9rxljtdscaRtMPBbWEKufSKJIPdZt55sJCWNPujJniOntdB6RmS05h-G94w9-0U0hyL7IR_PGFudq4cMCeaMl6C1lNCcflkIDQfPtn1_ussYkg8t6VaFzoKTvtdsPhfMQbxYX52MdTBzZyywoIY9BWbOcqpYxOwTEdrtxjhbz9n3dlqYQmOempcZWEq8W2xRWMm3PZXVxm3iGEXGp5xp21zfqIGf0pYqCAr1lBZTwRLT7yIq3iA10Nhj3jH0vxdL6hee_16qMk1J7qHf_7a5C0NF4bs11DCYPV5I6CjoY9xcehohLGjGLNU1Z9b6galCJeeVAI2fT9wvXKmRo0Vm0IWLhZXpLs273mUIsjZ_IfPlclMmYu8vRyBNU-QWQiAtDs4gzT3JzoMNwkbI0bLQFRkMi3jtDFHGCEH2dYx4GQNZDUi8eJwQXZCZaa0R8WatNMg0fi52R5kN4cZ3kgMTQazHz0ev8ztDHzF98tTpNTrEmCgEFzdyJBNR8i78L1DmareblVoQTD1q64wD1PLumuuiUYwQZcIpbTbA_9Il-vUBSY4AbkOTIhXXwtA-sYMwNHIEZQqBj67hLIb5qIla-AzLg8bUhP5JqZFtq6B2CmygcJcgCW_icULfdjqavM9NvRmzj1YP8-9emuZgTf9oRKHcXJaYIqrbH6NgFWh3RpmshCGMiCeDB_n-orCwMvQaIesOtVKIiSph9QAPodKFq38KnrtDpU7JSPUv9S57ymSBWSDsmYrw32m43bi9i8F6baW2hX7-0000)

**Ganttov diagram** (izvorna koda :bar_chart: [PlantUML](../gradivo/plantuml/Gantt.puml))

### 2.5 Odvisnosti med aktivnosti - Graf PERT


![Graf PERT](https://teaching.lavbic.net/plantuml/png/fLLTJzim57tthx3WRO8HEz-igjJo8LLi9Lex7iQG5HgtgmZ9b0Pjq-2_xzfnd8ycQ1aFRQwEVS-vz_Z6sJrianzX5ZxY-t3riCdIfoGwI-CqmtaM9ZjOuacEOhxESPxYRBlvdkDec_5LlaqJX7QhCEROUEyXDDhblsC-HhiypFdvDjm8qZy8up3BqfyomlZZDk45_NqCUe2ze1SqEb6vQAVBMGWQcJLj5NR8lRMzZiHAcaKyKwXzEVKkpe2jHXBnTVWKvql-Av_4sqto2CtW5Vpn31M5ueFHIkIVHc7saF5eF24i-3eVdKXqV8337PuGVBXUSuSx7sAelzoAJ_58uKVgENw67XtyZ0tumVDR8W2Z0lf4ARjUj4Jf854J-AKozkko6keJDjbyqTGr1-bwYXyJjw5RGgNkn6BNNsuA1KkI5QTuf9wIp599c9AIZ0X8Y53QtuJDvfDc4_QW9cojI-jDQAXFrs6pu5DJs1aaR2a1J1l3eY7jdijcysMXuFQvPweaJFK827vJC9fcZSnZiykhWiph9YD47G8sQVqaP65rhhOZFZWoRJhY3t2aq1Kzc8rnqf3kWHXiDWbcwlqq-ZonTRAUA4TrrU8ZR3PLfa0LtQwOvL08JmisEIBM7XjbynirxOI-Dkv59KxZm4I5bj5lCZ5PSDwweSp1juKeMCfKDckeQiHYoqibqVlQkheFlpuiOavQR3PRJXMR_TeO_qjjUwuuB0W-jsmPzZfI9O6jnZsWeQeHbzq4IgBdVHJxLNg33E-JUMnneSYyDvFvx6gkoFotab63dQisgV6_P0ZTlhl3nxU7oloZ-pIExex7K222BslN0aNmzUjQC15ydev5PCceOukDuFBlMd0GV7XahelWcYuZXNaIwqZpzMPYI6ePGkcU2caLGdb-TwUm0fUKtWKtZ8vT5LeLZrMXjgGiGyrXrpX437Q947eagY4PTriab-pQjixEuTIAavFRm2bIrDJ4mJVYTU1W6_7tSGeUKgF4_m80)

**Graf PERT** (izvorna koda :bar_chart: [PlantUML](../gradivo/plantuml/PERT.puml))

## 3. Obvladovanje tveganj

### 3.1 Identifikacija in analiza tveganj


| Naziv tveganja   | Vpliva na        | Opis tveganja    | Tip tveganja     | Verjetnost nastopa tveganja | Posledice nastopa tveganja |
| :--------------- | ---------------- | :--------------- | :--------------- | :-------------------------- | :------------------------- |
| Slabo planiranje (T1) | projekt | Celoten plan dela smo podcenili in bo prišlo do zamude | ocenjevanje | zmerna            | usodne           |
| Odsotnost člana (T2)           | projekt  | Zaradi različnih razlogov član ekipe ni dosegljiv in ne more nadaljevati dela na projektu| ljudje              | zmerna                         | resne                        |
| Okvara strojne opreme (T3)              | projekt in produkt              | Kritična napaka strojne opreme              | orodja              | majhna                       | usodne                        |
| Konkurenčen produkt (T4)              | posel              | Na trg pride konkurenčen produkt              | organizacijsko              | zmerna                         | sprejemljive                        |
| Počasna podatkovne baza ali premalo zmogljiv strežnik (T5)              | projekt in produkt              | Strežnik ki servira aplikacijo ni prilagojen za večje število uporabnikov, oziroma izbrana podatkovna baza ni dobro prilagojena na operacije, ki se bodo na njej pogosto izvajale              | tehnologija              | majhna                         | majhna                        |
| Spremembe zahtev (T6)              | projekt in produkt              | Klient zahteva nove funkcionalnosti, ki zahtevajo obsežno spremembo kode              | zahteve              | zmerna                         | resne                        |
| Odpoved zunanjih virov (T7)              | projekt in produkt              | Zunanji viri informacij prenehajo pretakati podatke              | tehnologija              | nizka                         | resne                        |
| Finanče težave zaradi napačne razporeditve sredstev (T8)              | projekt              | Finance niso pravilno razporejene, kar ima za posledico finančno pomanjkanje              | organizacijsko              | nizka                         | usodne                        |
| Razdelitev dela (T9)              | projekt            | Slaba organizacija znotraj ekipe je privedla do neučinkovite in počasne proizvodnje              | organizacijsko              | visoka                         | resne                        |
| Nepredvidena epidemija (T10)              | projekt              | Nepredvidena pandemija je vplivala na trg in delovno sposobnost              | organizacijsko              | nizka                         | resne                        |

### 3.2 Načrtovanje tveganj


| Tveganje         | Strategija       |
| :--------------- | :--------------- |
| Okvara strojne opreme (T3) | Kodna baza je shranjena v več razčlenjenih bazah podatkov, okolje izvajanja pa je pripravljeno v vsebniku za hitro in varno nastavitev, tako da ga lahko v primeru kritične napake hitro in zanesljivo identificiramo in odpravimo |
| Slabo planiranje (T1)              | Uporabljamo že uspešno metodo načrtovanja s poudarkom na lokalnih izboljšavah, ki ustrezajo našim zaposlenim              |
| Finanče težave zaradi napačne razporeditve sredstev (T8)              | Odgovorno in objektivno ustvarjanje skupinskih skladov strokovno pregledano in zabeleženo za letno analizo              |
| Počasna podatkovna baza ali premalo zmogljiv strežnik (T5)              | Nameravamo uporabiti najnovejši sklad, pogosto preverjati zanesljivost in potiskati posodobitve, ki temeljijo na zmogljivosti              |
| Spremembe zahtev (T6)              | Posvetujemo se z vodjo projekta o zahtevani posodobitvi funkcij, načrtujemo najustreznejši časovni okvir in se posvetujemo z našo ekipo razvijalcev o načinih razvoja              |
| Odpoved zunanjih virov (T7)              | Dodajanje le preverjenih zanesljivih zunanjih virov. V primeru odpovedi, imamo že pripravljeno podporo za alternative              |
| Razdelitev dela (T9)              | Vodja projekta bo imel odgovornost, da ekipo pogosto opomni o spremembah urnika in prihajajočih rokih              |
| Odsotnost člana (T2)              | V primeru načrtovanega ali nenačrtovanega dopusta enega od naših članov, bo vodja projekta odgovoren za iskanje zamenjave za dano nalogo              |
| Konkurenčen produkt (T4)              | Z nenehnimi izboljšavami in dodajanjem novih funkcij poskušamo ostati relevantni na trgu              |
| Nepredvidena epidemija (T10)              | Možnosti za to so majhne. Ker imamo izkušnje z delom v takšnih razmerah, bi tudi takšnih težkih časih uspeli z nadaljevanjem projekta              |


## 4. Upravljanje projekta

Pri projektu bo delitev dela sledeča: 

|Aktivnost| Vanessa Jačmenjak| Vasja Lev Kirn| Dejan Mandic| Ana Polančec| Tara Rolih| 
|:--------|:-----------------|:--------------|:------------|:------------|:----------|
|Pridobitev zahtev od naročnika | | | |50% | 50%|
|Opredelitev specifikacij od naročnika o zahtevani rešitvi | | | |50% |50% |
|Načrtovanje sistema |20% |20% |20% |20% |20% |
|Oblikovanje uporabniškega vmesnika |70% |30% | | | |
|Načrtovanje arhitekture |20% |20% |20% |20% |20% |
|Izdelava podatkovnega modela| | | |50% | 50%|
|Izdelava načrta testiranja | | |33% | 33%| 34% |
|Implementacija frontend dela aplikacije | | |80% | | 20%|
|Implementacija podatkovnih baz | | 20%||80%| |
|Implementacija API dostopa |80%| | |20%| |
|Implementacija ostalih backend komponent aplikacije | |80% || | 20%|
|Priprava navodil za uporabo uporabniškega vmesnika |50% | | |50% | |
|Priprava dokumentacije |20% |20% |20% |20% |20% |
|Testiranje frontend dela aplikacije|30% | |70% || |
|Testiranje backend dela aplikacije| | | | | 100%|
|Pregled programske rešitve z naročnikom|50% | | || 50%|
|Vodenje projekta |100% | | | | |
|Skupinski sestanki članov ekipe, ki delajo na aplikaciji |20% |20% |20% |20% |20% |
|Redna komunikacija z naročnikom |100% || | | |
|Nadzor upoštevanja dobre prakse razvoja programske opreme |20% |20% |20% |20% |20% |


## 5. Predstavitev skupine


Ana Polančec, starost 24 let, študentka univerzitetnega študija računalništva in informatike na Univerzi v Ljubljani, na dodiplomski stopnji. V večji meri pozna delo s programskimi jeziki Java, Python, C, Matlab, HTML, SQL, CSS in Javascript. Zaradi svojih znanj bo v večji meri sodelovala pri oblikovanju podatkovnega modela, načrtovanju testiranja in implementaciji podatkovnih baz ter komunikaciji z naročnikom. 

Dejan Mandic, starost 22 let, študent univerzitetnega študija računalništva in informatike na Univerzi v Ljubljani, na dodiplomski stopnji. Širok nabor izkušenj na področju različnih tehnologij, od sistemske in omrežne arhitekture do razvoja in avtomatizacije. Na projektu bom odgovoren za funkcionalnosti, implementacijo in vzdrževanje platforme in njenih podpornih elementov (baze podatkov, API-ji itd.)

Vasja Lev Kirn, starost 21 let, študent univerzitetnega študija računalništva in informatike na Univerzi v Ljubljani, na dodiplomski stopnji. Pozna delo s programskimi jeziki HTML, CSS, JavaScript, Java, Python, C, Matlab in tudi delo v Android sistemu. Zaradi svojih znanj in izkušenj bo sodeloval pri komunikaciji z naročnikom, izdelavi načrtov, implementaciji podatkovnih baz in v kasnejših fazah razvoja pri izdelavi mobilne aplikacije za platformo Android.

Tara Rolih, starost 21 let, študentka Univerzitetnega študija računalništva in informatike na Univerzi v Ljubljani, na dodiplomski stopnji. Pozna delo s programskimi jeziki HTML, CSS, JavaScript, Java, Python, C, Matlab, Racket, Prolog, Scala. Je kreativna in ima dobre komunikacijske veščine, zato bo skupaj z Ano poskrbela, da od naročnika dobi vse potrebne informacije za nadaljevanje projekta in ob koncu projekta skupaj z naročnikom pregledala programske rešitve. V celotnem obsegu ji bo prepuščeno tudi testiranje backend dela aplikacije, saj ima s tem že nekaj izkušenj, ki jih želi še dodatno izpopolniti. K projektu bo pripomogla tudi pri ostalih aktivnostih kot so opredelitev specifikacij, načrtovanje sistema, testiranja, arhitekture, implementacija frontend-a, implementacija backend-a, priprava dokumentacije in tudi pri nadzorovanju upoštevanja dobre prakse razvoja programske opreme.

Vanessa Jačmenjak, starost 24 let, študentka Univerzitetnega študija računalništva in informatike na Univerzi v Ljubljani, na dodiplomski stopnji. Pozna delo s programskimi jeziki HTML, CSS, JavaScript, Java, Python, C, Matlab, C#, Kotlin. Zaradi izkušenj kot razvijalka programske opreme v poslovnem svetu bo prevzela vlogo vodenja projekta ter redno komunikacijo z naročniki. Poleg tega pa bo poskrbela še za implementacijo API dostopa in oblikovanje uporabniškega vmesnika s pomočjo Ane ter Vasje. Zaradi svojih izkušenj pa bo ostalim priskočila na pomoč tudi pri načrtovanju, pripravi navodil in dokumentacije, ter testiranju.

## 6. Finančni načrt - COCOMO II ocena

|Tip funkcionalnosti|Naziv funkcionalnosti|Obseg|Utež|
|:-----|:-----|:------|:-----|
|EI|prijava v sistem|L|3|
|EI|registracija v sistem|L|3|
|EI|uredi profil|L|3|
|EI|zaprosi zdravnika za nov recept|L|3|
|EI|iskalnik zdravnikov|L|3|
|EI|iskalnik pacientov|L|3|
|EQ|prikaz mojih zdravnikov (osebni zdravnik, zobozdravnik, ginekolog,...)|L|4|
|EQ|prikaz podatkov in urnika izbranega zdravnika|L|3|
|EQ|prikaz pacientovih pregledov (že opravljeni, čakajo na zdravnikovo potrditev in potrjeni a neopravljeni)|L|4|
|EQ|izpis zdravnikov|L|3|
|EQ|prikaz urnika za ambulanto|L|3|
|EQ|prikaz prošenj pacientov za recepte|L|3|
|EQ|prikaz prošenj pacientov za pregled (video ali v živo)|L|3|
|EQ|podatki izbranega pacienta in njegov zdravniški karton|L|4|
|ILF|podatkovna baza uporabnikov|H|15|
|ILF|podatkovna baza statistike|L|7|
|EIF|naročanje na pregled (video ali v živo)|L|5|

Ker bi uporabljali programski jezik JavaScript, je naše pričakovano število vrstic enako:
72 x 47 = 3384 SLOC


--------------------------------------------------------------------------------------------------------

Po metodi COCOMO II napor izračunamo po formuli Napor = A x obseg^B x M. Parametri izračuna so določeni v nadaljevanju. 

A = 2.94

Obseg = 3.384 KSLOC

B = 1.01 + 1.01 x Σwi = 1.01 + 0.01 x 13 = 1.14


|Dejavnost| Vrednost | Utež |
|:-----|:----|:-----|
|PREC|nominalna|3|
|FLEX|nominalna|3|
|RESL|zelo visoka|1|
|TEAM|visoka|2|
|PMAT|nizka|4|


Zgornje uteži so določene po kriteriju : zelo nizka (5), nizka (4), nominalna (3), visoka (2), zelo visoka (1) in izjemno visoka (0). 

M = PERS X PREX X RCPX X RUSE X PDIF X SCED X FCIL = 1.2 x 1.0 x 1.0 x 0.8 x 1.0 x 1.0 x 0.8 = 0.768

|Dejavnik|Ocena|Razpon uteži|Utež|
|:-----|:------|:------|:-----|
|PERS|nizka|1.5 - 0.5|1.2|
|PREX|nominalna|1.5 - 0.5|1.0|
|RCPX|nominalna|0.5 - 1.5|1.0|
|RUSE|nizka|0.5 - 1.5|0.8|
|PDIF|nominalna|0.5 - 1.5|1.0|
|SCED||0.5 - 1.5|1.0|
|FCIL|visoka|1.5 - 0.5|0.8|

Napor = A x Obseg^B x M = 2.94 x 3.384^1.14 x 0.768 = 9.062


Finančni načrt za aktivnosti

| Aktivnost | obseg dela [ČM] | predvideni stroški dela[€] | predvideni stroški investicij[€] | predvideni potni stroški[€] | drugi predvideni posredni stroški[€] 
|---|---|---|---|---|---|
| Pridobitev zahtev od naročnika | 0.125 | 300 | 62.5 | 0 | 0 
| Opredelitev specifikacij od naročnika o zahtevani rešitvi | 0.125 | 300 | 62.5 | 0 | 0 
| Načrtovanje sistema | 0.3333 | 800 | 166.67 | 0 | 0
| Oblikovanje uporabniškega vmesnika | 0.2 | 480 | 100 | 0 | 0
| Načrtovanje arhitekture | 0.3333 | 800 | 166.67 | 0 | 0 
| Izdelava podatkovnega modela | 0.2 | 480 | 100 | 0 | 0 
| Izdelava načrta testiranja | 0.375 | 900 | 187.5 | 0 | 0
| Implementacija frontend komponent aplikacije | 1.25 | 3000 | 625 | 0 | 0 
| Implementacija podatkovnih baz | 1.25 | 3000 | 625 | 0 | 0
| Implementacija API dostopa | 0.625 | 1500 | 312.5 | 0 | 0
| Implementacija ostalih backend komponent aplikacije | 1.75 | 4200 | 875 | 0 | 0
| Priprava navodil za uporabo uporabniškega vmesnika | 0.25 | 600 | 125 | 0 | 0
| Priprava dokumentacije | 0.4444 | 1066.6667 | 222.222 | 0 | 0 
| Testiranje frontend dela aplikacije | 0.625 | 1500 | 312.5 | 0 | 0
| Testiranje backend dela aplikacije | 0.625 | 1500 | 312.5 | 0 | 0 
| Pregled programske rešitve z naročnikom | 0.2 | 480 | 100 | 0 | 0 
| Vodenje projekta | 0.2 | 480 | 100 | 0 | 0 
| Skupinski sestanki ekipe | 0.5714 | 1371.4285 | 285.7142 | 0 | 0 
| Redna komunikacija z naročnikom | 0.375 | 900 | 187.5 | 0 | 0
| Nadzor upoštevanja dobre prakse razvoja programske opreme | 0.25 | 600 | 125 | 0 | 0 |
| Skupaj | **10.1075** | **24258** | **5054** | 0 | 0 |  

Urna postavka je 30€. Urna postavka vklučuje tudi malico. Začetna investicija je približno 1000€ na osebo (računalnik), kar je približno 500€/ČM. Investicija se razporedi čez vse aktivnosti, saj se računalniki uporabljajo pri vseh. Potnih stroškov in stroškov najema pisarne ni, saj delamo na daljavo. Upoštevamo tudi, da je število ur, ki jih človek dela na mesec enako 80.

Skupna ocena stroškov dela je 24258€ in stroškov investicij 5054€. Skupna oocena vseh stroškov znaša **29312€**.


## Reference


[1]: D. Lavbič, https://teaching.lavbic.net/TPO/2021-2022/, 2022.
