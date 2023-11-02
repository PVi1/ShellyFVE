# ShellyFVE
Sada skriptov pre pouzitie Shelly Pro 3EM spolu s Switch Addon ako ochrany posobiacej na HRM v zmysle kapitoly 9.1 a 10.1.5 ZSD_Technicke-podmienky-PDS_2301.pdf

## Instalacia
1. Shelly Addon Switch nastavenia: nastav Action on Power ON na Turn OFF
2. Nahraj oba skripty, uprav premenne v zahlavi skriptov podla aktualne platnej legislativy/poziadaviek DS
3. Enabluj oba skripty

## Pouzitie a princip cinnosti
- Shelly switch addon rele ovlada stykac, ktory pripaja FVI k sustave (GRIDU)
- Shelly_grid_check skript sluzi na kontrolu parametrov sustavy ako podpatie, prepatie a frekvencia
- Shelly_grid_check_state_checker sluzi na kontrolu cinnosti vyssie uvedeneho skriptu a v pripade, ze je dany skript z dovodu chyby pri vykonanvani zastaveny, dojde k vypnutiu Switch Addon rele a odpojeniu FVI(foto voltaickeho invertora) od sustavy.

