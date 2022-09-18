## T120B165-saityno-taikomuju-programu-projektavimas

## Projeckto pavadinimas -

## Sprendžiamo uždavinio aprašymas

### Sistemos paskirtis

Projekto tikslas - sukurti paslaugų tiekimo / naudojimo platfomą, kuri leidžią:

- versliui reklamuoti savo teikiamas paslaugas, valdyti užsakymus.
- vartotojui ieškoti jį dominačių paslaugų, užsakyti jas bei palikti atsiliepimus

Verslas, norintis naudotis šia platforma ir reklamuoti savo teikiamas paslaugas turi susikurti verslo profilį, užregistruoti savo teikiamas paslaugas užpildant, paslaugos registravimo formą. Po administratoriaus patvirtinimo, paslauga tampa viešai prieinama ir klientai/vartotojai gali peržiūrėti paslaugos informaciją (įkainius, aprašymą, atsiliepimus, užimtumą) bei atlikti rezervaciją.

### Funkciniai reikalavimai

Neregistruotas sistemos vartotojas galės:

1. Peržiūrėti visas viešai prieinamas (patvirtintas) paslaugas.
2. Peržiūrėti paslaugų tiekėjus.
3. Sukurti naują paskyrą / prisijungti prie esamos paskyros.

Paslaugų tiekėjas galės:

1. Sukurti/redaguoti paslaugą.
2. Peržiūrėti ir valdyti savo užsakymus ir dienotvarkę.

Klientas galės:

1. Užsakyti paslaugą.
2. Palikti atsiliepimą apie užsakytą paslaugą.
3. Peržiūrėti ir valdyti savo užsakymus.

## Pasirinktų technologijų aprašymas

Kliento pusei (angl. front-end) programuoti buvo pasirinktas `SvelteKit` karkasas. Šis karkasas

Serverio daliai (angl. back-end) programuoti buvo pasirinktas `.NET6 API` karkasas. Duomenų bazei buvo pasirinkta naudoti `MariaDB`. Serverio bendravimui su duomenų baze pasirinktas `Entitiy Framework` karkasas, kuris leidžia lengvai manipuliuoti duomenimis

## Sistemos architektūra
