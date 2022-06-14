# Changelog

## Verzia 3.10.1
- Prepojenie váh pomocou protokolu CAS
- Opravy komunikácie na Fiskal Pro protokol v prípade zaokrúhlenia

## Verzia 3.10.0
- Nová funkcia pre eKasa na 5c zaokrúhlovanie
- Rôzne opravy stability
- Rôzne opravy a úpravy komunikácie na eKasa Pay (storno, zaokrúhlenie)

## Verzia 3.9.0
- prepojenie na PRSK05 protokol (TB/Verifone)

## Verzia 3.8.8.1
- opravuje nespravne volanie predaja na kartu aj ked bol volany navrat na kartu. Dialo sa pri nastaveni eKasaPay protokol z Papaya na Nexgo alebo Pax
- Verzia je kompatibilna z 3.8.8 server verziou alebo 3.8.8-b1

## Verzia 3.8.8
- nove jadro s kontrolou pripravenosti tlace pre Nexgo
- fix pri opakovani dotlace - v pripade ked platba presla ale doklad sa nepodarilo vytlacit, bola zle zavolana platba znova.
- fix bonovania na ekasa tlaciarni v pripade pouzitia alternativneho drivera. v takomto pripade sa nedalo vybrat bonovacku na ekasa tlaciaren
