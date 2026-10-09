# Hvordan oprettes der statestik for vare på prislisten


## Beskrivelse

Det kan være en god ting nemt at kunne se hvor tit en vare eller varegruppe er blevet brugt, og hvor meget omsætning den har givet.

Det er ikke direkte muligt at lave statistik på en enkelt vare.

Det er derimod muligt at få en oversigt over hvor meget en varegruppe har omsat for.

Der er ingen regler for hvor mange eller hvor få vare der skal være i en varegruppe, eller hvor mange varegrupper der kan oprettes.
Er ønsket at holde øje med en vares omsætning, kan der oprettes en varegruppe, som kun indeholder denne vare.

En varegruppe der oprettes, vil automatisk komme med på fremtidige faktura.
Tidligere faktura bliver ikke påvirket.

Ønskes det at statistik på varegruppen også skal gælde for tidligere faktura, så skal du ind på hver enkelt faktura og rette varegruppen for varen

En varegruppe der er blevet oprettet kan ikke slettes igen.

En varegruppen omdøbes. Denne omdøbning kommer automatisk til at gælde alle vare der tilhøre varegruppen ved omdøbningen.


### Forudsætning

    At du har rollen en af rollerne
    -  kontor
    -  Mester/Firma admin


## Fremgangsmåde

1. opret en varegruppe
   1. Topmenu "Administration"
   2. Vælg "Varegrupper"

   ![Menu varegruppe][Menu Varegruppe]

   3. Tryk på "Opret"

    ![Opret varegruppe][Opret varegruppe]

   4. Angiv kode (1) og navn (2) for  Varegruppen

   ![Navngiv Varegruppe][Navngiv Varegruppe]

   5. Den nye varegruppe optræder nu i listen over varegrupper

    ![Ny varegruppe oprettet][Ny varegruppe oprettet]

2. Tilføj de ønskede vare til varegruppen
   1. Under menu "Profil" vælges "Prisliste"

   ![Menu prisliste][Menu prisliste]

   2.  Vælg Varen der ønskes tilføjet

        Tryk på ![Blok ikon][blok ikon] ude til højre for varen

        ![Vare tilføjes varegruppe][Vare tilføjes varegruppe]

   3.  Vælg varegruppen som varen skal hører under (1)

        ![Vælg varegruppe til vare][Liste over mulige valg af varegruppe]

   4. Når varegruppen er valgt, tryk på "Gæm ændringer" (2)


   5. I Prislisten vil det nu kunne ses, hvilken vare gruppe varen tilhører

        ![Prisliste se varegruppe for vare][Prisliste se varegruppe for vare]

3. Når varen nu tilføjes nye faktura, så vil varegruppen automatisk fremgå

    ![Vare på ny faktura][Vare på ny faktura]

Varegruppen vil kun optræde på nye faktura.
Det vil derfor kun være faktura der er lavet efter dette tidspunkt der vil være med i optællingen.

Ønskes det, at også tidligere faktura, hvor varen fremgår skal indgå i opgørelsen for varegruppen, skal hver enkelt af disse faktura tilrettes, så varegruppen fremgår af fakturaen.

- Det gøres på følgende måde
    - Gå ind på fakturaen
    - ret varegruppen for den pågældende vare
      - Når der trykker på feltet for varegruppen (1) kommer listen over varegrupper (2) frem

    ![Ret varegruppe på faktura][Ret varegruppe på faktura]

    - Vælg den varegruppe der ønskes at varen skal være en del af
    - Herefter vil varen fremgå af sammentælling under Administration -> Varegrupper








[Billede reference]: < Reference til billeder>

[Menu Varegruppe]: <images/Statistik for vare/image.png>

[Opret varegruppe]: <images/Statistik for vare/image-1.png>

[Navngiv Varegruppe]: <images/Statistik for vare/image-2.png>

[Ny varegruppe oprettet]: <images/Statistik for vare/image-3.png>

[Menu prisliste]: <images/Statistik for vare/image-4.png>

[Vare tilføjes varegruppe]: <images/Statistik for vare/image-5.png>

[Vælg varegruppe til vare]: <images/Statistik for vare/image-6.png>

[Liste over mulige valg af varegruppe]: <images/Statistik for vare/image-7.png>

[Valgt varegruppe]: <images/Statistik for vare/image-8.png>

[Prisliste se varegruppe for vare]: <images/Statistik for vare/image-9.png>
[blok ikon]: <images/Statistik for vare/blok.ico>
[Vare på ny faktura]: <images/Statistik for vare/image-10.png>
[ret varegruppe på faktura]: <images/Statistik for vare/image-11.png>