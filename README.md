# Changelog

## Verzia 3.10.3 (NEW)
- Fix inicializacia dat - pri novej instalacii chyba v init databazy

## Verzia 3.10.2
- Prepojenie váh pomocou protokolu CAS

## Verzia 3.10.1
- Opravy komunikácie na Fiskal Pro protokol v prípade zaokrúhlenia
- pridane PRSK05

## Verzia 3.10.0
- Nová funkcia pre eKasa na 5c zaokrúhlovanie
- Rôzne opravy stability
- Rôzne opravy a úpravy komunikácie na eKasa Pay (storno, zaokrúhlenie)
- Bez PRSK05

## Verzia 3.9.1 (NEW)
- Fix inicializacia dat - pri novej instalacii chyba v init databazy

## Verzia 3.9.0
- prepojenie na PRSK05 protokol (TB/Verifone)

## Verzia 3.8.8.3 (NEW)
- Fix inicializacia dat - pri novej instalacii chyba v init databazy

## Verzia 3.8.8.2 
- oprava pridavania bonovacich tlaciarni, ktore nie su USB

## Verzia 3.8.8.1
- opravuje nespravne volanie predaja na kartu aj ked bol volany navrat na kartu. Dialo sa pri nastaveni eKasaPay protokol z Papaya na Nexgo alebo Pax
- Verzia je kompatibilna z 3.8.8 server verziou alebo 3.8.8-b1

## Verzia 3.8.8
- nove jadro s kontrolou pripravenosti tlace pre Nexgo
- fix pri opakovani dotlace - v pripade ked platba presla ale doklad sa nepodarilo vytlacit, bola zle zavolana platba znova.
- fix bonovania na ekasa tlaciarni v pripade pouzitia alternativneho drivera. v takomto pripade sa nedalo vybrat bonovacku na ekasa tlaciaren
