# Arbejdsseddel beskrivelse

## Beskrivelse
Arbejdssedlen giver information til fejeren om, hvilke ejendomme der skal besøges.
Den fortæller også hvilke opgaver der skal løses på ejendomme, samt om der er nogle særlige ting der skal lægges mærke til.


Arbejdssedlen har gennemgået en udvikling i udseende igennem tiden og findes derfor i 3 forskellige verisoner

Version 1 er her kun nævnt her fordi den stadig findes i systemet. Den vil ikke bliver omtalt yderligere.

Version 2 er den version flest brugere, og er en lettere forbedring af version 1.

Version 3 er den mest moderne udgave af arbejdssedlen. Opdelingen af arbejdsedlen er noget anderledes og der er gjort forskellige sigende ikon for de forskellige funktioner på arbejdssedlen.

Under menu punktet "Arbejdssedler" kan der findes en oversigt over arbejdssedler

Beskrivelse af oversigten finder du her [Oversigt_over_Arbejdssedler](Oversigt_over_arbejdssedler.md)

## Arbejdssedlens udseende

### Hoved / toppen af arbejdssedlen

Toppen af arbejdssedlen er ens for både version 2 og version 3

![Hoved på arbejdsseddel][Arbejdssedlenshoved]

1. Her kan det ses, hvilke nummer arbejdssedlen har fået

2. Faner med forskellig indhold

3. Beskrivelse af arbejdssedlen
    - År - Hvilket år den gælder for
    - oprettelse dato
    - Hvem har oprettet arbejdssedlen
    - Beskrivelse af arbejdssedlen
        Beskrivelsen er taget fra beskrivelsen af turen.
        Ønskes det at give den en anden beskrivelse kan det trykkes på ![edit][blok ikon] og ændre på beskrivelsen

4. Tilsagte ejendomme
    Filter til visning af ejendomme på arbejdssedlen
    - Vis mine aftaler
       - Vis kun de aftaler, hvor du står på tilsigningen
            Hvis du ikke står på nogen af tilsigningerne som fejer, så vil listen være tom
    - Vis alle aftaler, hvis alle ejendomme på arbejdssedlen, der opfylder filter betingelserne
    - Alle besøg, viser alle besøg, og sletter filter til højre.

    - Farvede bokse til højre
        Sættes der markering i disse bokse, så vil det kun være ejendomme med disse tilsigninger  der vil bliver vist
      - Grøn    - Aftaler for i dag
      - Lilla   - Aftaler i morgen
      - Gul     - Aftaler længere ude i fremtiden
      - Hvid    - Ejendomme, hvor der endnu ikke er lavet tilsigning til eller tidspunktet for tilsigningen er overskredet
   - Til højre for de farvede bokse står antallet af aftaler der passer på dette filter

5. Knapper til forskellige funktioner.

    Disse knapper er kun til stede, hvis indstillinger for Firma og bruger tillader det.
    - "Tildel til mig"
        Vises ikke, hvis brugerindstillingen "Tillad ikke tildeling af ture" er sat
    - "Version 2" / "version 3"
        Vises kun, hvis brugerindstillingen "Brug arbejdseddel Version -> V2/V3" er sat
        Den skifter så mellem Version 2 og Version 3 af arbejdssedlen
    - "Opdater besøg"
        Vises kun når Firma indstillingen 'Vis "Opdatér"- knap'  er sat

        Opdaterer besøg med ændringer på ejendomme, der er lavet efter arbejdssedlen er blevet dannet
        Det er kun åbne besøg der bliver påvirket.

        Har en ejendom været besøgt, og den er helt eller delvist færdigmeldt (Rest) vil opdateringen ikke påvirke besøget


6. Ture inkluderet

    Her kan det ses hvilke ture arbejdssedlen er lavet ud fra

    Efter "Ture inkluderet" er der et "+"  ![plus][plus ikon].

    Når det trykkes på plusset så vil den udvide visningen, til det som ses på billedet.


7. Viser hvor mange ejendomme der vises pr. side. og om det skal vises detaljeret eller som liste.

    Det er muligt at ændre antallet af ejendomme der vises pr. side, ved at trykke på tallet.

    Her kommer så en liste frem med forskellige valg muligheder



8. Angivelse af hvilke status på ejendommene, der vises skal have

    Det er muligt at vælge flere forskellige status på samme tid.

    Ved åbning af arbejdssedlen vil den som standard stå med markering i åbne og resten vil være tomme.

    Er der ikke nogen ejendomme på arbejdssedlen med åbne besøg, så vil en af de andre status automatisk blive markeret.


### Version 2

Vedr. punkt 7 i "Hoved på arbejdsseddel" er der efter visning af antal ejendomme per side vist mulighed for at vælge hvordan arbejdssedlen skal vises
   - Detaljeret (standard)
    Her vises oplysning om ejendommen og alle opgaverne der skal udføres

   - Liste

       Er "liste" markeret, vil det kun være følgende oplysninger der vises
       - Adresse på ejendomme
       - Navn på beboer
       - Mobilnummer
       - Turnummer
       - Hvornår der er lavet tilsigning til ejendommen
       Det vil sige den markeret overskrift på besøget


![Ejendom detaljevisning ][Ejdendomsvisning-version2]


#### Detaljeret visning

1. Overskriftet på de forskellige kolonner
2. Oplysninger om ejendommen
    - Adresse
    - Navn på beboer
    - Evt. telefonnr
    - Afsluttet besøg
    - Fejet / besøgt
    - Ejendoms turnummer
    - Faktura og levering af faktura
    - Tilsigning ( hvis ingen så vises kalender ikon ![Kalender ikon][kalender ikon])
3. Viser opgaver på ejendommen
    - her er det muligt at markerer hvilke opgaver der er udført
4. Spørgsmål
   - Vises kun hvis det er sat i firmaindstillingerne
   - Kan ignores hvis bruger indstillinger tillader det
5. Bemærkning på på ejendommen

   Oplysninger om dato og fejer for oprettelse af bemærkningen vises kun hvis det er sat i indstillinger for firmaet

   - Mulighed for at tilføje en anmærkning
   - mulighed for at tilføje en ny kommentar
   - Muligheden for at redigere sager ( Hvis bruger indstillinger tillader det)
6. Knapper til angive om besøget er udført eller gået forgæves
7. Vises kun hvis Ejer og beboer ikke er den samme

#### Liste visning

Vælges liste som visning (pkt 7. i hoved på arbejdsseddel) så vil det kun være pkt. 1. og pkt. 2. i ovenstående der vises


### Version 3

Arbejdsseddel version 3 findes kun i en detaljeret version

![Ejendomsvisning version 3][Ejendomsvisning-version3]

Det er de samme ting der står på de versioner af arbejdssedler, hvorfor jeg har forsøgt at bevare nummergivingen af de forskellige områder.

I udseende, er der dog nogle få ændringer, der gør beskrivelserne vil afvige lidt fra ovenstående i nogle af beskrivelserne

1. Overskriftet på de forskellige kolonner
2. Oplysninger om ejendommen
    - Adresse
    - Navn på beboer
    - Evt. telefonnr
    - Afsluttet besøg
    - Fejet / besøgt
    - Ejendoms turnummer
    - Faktura og levering af faktura
    - Tilsigning ( hvis ingen så vises kalender ikon ![Kalender ikon][kalender ikon])
3. Viser opgaver på ejendommen
    - her er det muligt at markerer hvilke opgaver der er udført
4. Spørgsmål
   - Vises kun hvis det er sat i firmaindstillingerne
   - Kan ignores hvis bruger indstillinger tillader det
5. Bemærkning på på ejendommen

   Oplysninger om dato og fejer for oprettelse af bemærkningen vises kun hvis det er sat i indstillinger for firmaet

6. Ikoner for forskellige handlinger på ejendommen

    I modsætning til arbejdssedlen version 2, så er alle handlinger samlet til dette område ( Undtaget faktura)

    Alt efter hvad firma- og bruger indstillinger angiver, så vil der her være følgende muligheder
    - Anmærkninger ( findes under pkt. 5. i Version 2)
    - Ny kommentar ( findes under pkt. 5. i version 2)
    - tilsigning ( findes under pkt. 2. i version 2)
    - Forgæves ( findes under pkt. 6. i version 2 )
    - Annulleret (Kun hvis bruger indstillinger tillader det, findes under pkt. 2. i version 2)
    - Redigere sager ( findes under pkt. 5. i version 2 )
    - Besøgsrapport (Kun hvis firma indstillinger er sat,  findes under pkt. 6. i version 2, kommer denne først frem, når der er udført arbejde på ejendommen)
    - Udført ( findes under pkt. 6. i version 6)
7. Vises kun hvis Ejer og beboer ikke er den samme
8. Faktura (findes under pkt. 2. i version 2) ( kun hvis firma- og bruger indstillinger tillader det)
9.  Egen noter Kommentar af typen "Egen Note" vises her i stedet for under pkt. 5 bemærkninger







[Reference til billeder]: <# oversigt over billeder der henvises til>
[Arbejdssedlenshoved]: <images/Arbejdsseddel beskrivelse/image.png>
[Kuvert icon]: <images/Arbejdsseddel beskrivelse/Kuvert.ico>
[Kort ikon]: <images/Arbejdsseddel beskrivelse/kort.ico>
[Printer ikon]: <images/Arbejdsseddel beskrivelse/printer.ico>
[Skorstensfejer ikon]: <images/Arbejdsseddel beskrivelse/skorstensfejer.ico>
[blok ikon]: <images/Arbejdsseddel beskrivelse/blok.ico>
[plus ikon]: <images/Arbejdsseddel beskrivelse/plus.ico>
[kalender ikon]: <images/Arbejdsseddel beskrivelse/kalender.ico>
[Ejendomsvisning-version3]: <images/Arbejdsseddel beskrivelse/image-7.png>
[Ejdendomsvisning-version2]: <images/Arbejdsseddel beskrivelse/image-6.png>
