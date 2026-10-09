# Stamkort og funktioner
- [Stamkort og funktioner](#stamkort-og-funktioner)
  - [Overblik](#overblik)
  - [Ny ejendom](#ny-ejendom)
    - [**Felter i Popup formular**](#felter-i-popup-formular)
  - [Ny lokation](#ny-lokation)
    - [**Felter  i popup formular**](#felter--i-popup-formular)
  - [Kanpperne ude til venstre](#kanpperne-ude-til-venstre)
  - [Resultat liste](#resultat-liste)
    - [Knapper](#knapper)
    - [Felter ( Overskrifter på kolone ) på listen](#felter--overskrifter-på-kolone--på-listen)

![Stamkort skærmbillede](<../../../../images/Stamkort - Skærmbillede.png>)

## Overblik

Når du vælger stamkort menupunktet i top menuen kommer der er en dropdown menu med følgende 2 punkter

- stamkort
- kommune login

Ved at vælge Stamkort så kommer du ind til en søge formular

Ude til højre findes der knapper med følgende funktioner

- find - Tekst felt indtastningsfelt
- Nulstil 
- Gem liste
- Vis kort

og nedenunder dem findes en blå knap "saldo list"

Ude til venstre er der to blå knapper

- Ny ejendom
- Ny lokation

Her udover er der en søge formular med følgende felter

Øverst oppe til højre under topmenuen
- søge felt - Tekst indtastningsfelt - mulighed for at indtaste turnummer og søge på det

**Fomular felter**

- Tur nummer - Tekst indtastningsfelt - efterfulgt af knap <+>
- Tur interval - Tekst indtastningsfelt - ( hvis der er trykket på <+> i ovenstående felt)
- Gade - Tekst indtastningsfelt
- Postnr./Sted -Tekst indtastningsfelt
- BBR - Tekst indtastningsfelt
- BFE - Tekst indtastningsfelt
- Husnr - Tekst indtastningsfelt
- Løbenr. - Tekst indtastningsfelt - Placeret ovre til højre mellem Dropdown valgfelterne
- Kommentar - Tekst indtastningsfelt

Plus følgende felter der kan klikkes af

- Rester - Checkbox
- Fristdato - Checkbox
- Nøglenr. - Checkbox
- Mangler email - Checkbox
- Åbne reg. - Checkbox
- Opfølgning - Checkbox
- Søg DAWA - Checkbox

og følgende felter med dropdown valg

- Status - Dropdown valgmenu - kan vælges mellem følgende værdier
  - Aktiv ( Standard)
  - Inaktiv
  - Vis alle 
- Antal fejn. - Dropdown valgmenu - kan vælges mellem følgende værdier
  - Vis alle ( Standard)
  - 0
  - 1
  - 2
  - 3
  - 4
  - 12
- Betalingstype - Dropdown valgmenu - kan vælges mellem følgende værdier
  - Vis alle ( Standard)
  - faktura
  - kommunal
  - gratis
- Fakturering - Dropdown valgmenu - kan vælges mellem følgende værdier
  - Vis alle ( Standard )
  - E-Boks
  - Brev
  - sms
  - Email
  - E-Faktura
  - Afleveres på adressen
- Tur gruppe - Dropdown valgmenu - kan vælges mellem følgende værdier
  - Vis alle
  - Ordinær
  - Industriel
  - Etageejendom
- Kom. dato - Dropdown valgmenu - kan vælges mellem følgende værdier
  - Vis alle ( standard) 
  - .... Række af årstal
- Kom. kategorier - Dropdown valgmenu - kan vælges mellem følgende værdier
  - Vis alle ( Standard )
  - AFM
  - ANM - ANMærkning
  - ANN
  - AOB - Anmærkning Om Arbejde
  - APV - ArbjedsPladsVurdering
  - ATT
  - FAK
  - NOT
  - SOD
  - TIL


Trykkes der på Find over til højre finder den alle Ture i systemet for den enkelte klient ( Mester ) med de angivne søge data. Er der ikke angivet nogen, så alle

## Ny ejendom

Ved tryk på <Ny ejendom> kommer der en popup formular op til at indtaste oplysninger om ejendommen

### **Felter i Popup formular**

- Fejes fra - Radio - her kan vælges årstal
- Kommune - Dropdown valgfelt - Kommunenummer liste over aktuelle kommunenumre for aktuelt distrikt
- BFE - Tekst indtastningsfelt - Ejendomsnummer ( Det nye som er erstatning for BBR)
- Adresse - Tekst indtastningsfelt - Adresse på ejendommen
- Hus nr. - Tekst Indtastningsfelt
- Etage - Tekst indtastningsfelt
- Dør - Tekst indtastningsfelt
- Sted - Tekst indtastningsfelt
- Postnr - Tekst indtastningsfelt
- Tur nummer - Dropdown valgmenu - der kun kan vælges eksisterende tur numre  efter fulgt af et felt hvor ejendommen får sit eget nummer på turen
- Tur gruppe - Dropdown valgmenu - følgende valgmuligheder ( de relevante er fed markeret. ) 
  - Ordinær ( default)
  - Sommerhus
  - Etageejendom
  - Industriel
  - Diverse
- Aktiv fra dato - Dato indtastningsfelt - Aktuel dato er standard , format dd/mm/ÅÅÅÅ , Vælg fra kalender eller dato skrives
- Kommunal - Checkbox - Angives om der er kommunal afregning
- Tilfoj brandsyn - Checkbox - Om Brandsyn skal tilføjes til ejendommen

## Ny lokation

Ved tryk på <Ny ejendom> kommer der en popup formular op til at indtaste oplysninger lokationen

### **Felter  i popup formular**

- Lokationsname - Tekst indtastningsfelt
- First position - Tekst indtastningsfel - første position
- Last position - Tekst indtastningsfel - Sidste position

## Kanpperne ude til venstre

- find - Knap - Ved tryk så laves en liste over ejendomme udfra felterne i formularen
- Nulstil - Knap - Sletter alle indtastninger i formularen
- Gem liste - Knap - Mulighed for at gemme listen, der kan vælges mellem følgende formater
  - CSV
  - PDF
  - Kommentar
- vis kort - Knap - Viser ejendommene på et kort

## Resultat liste

### Knapper

Lige over listen kommer 2 knapper frem, når der er informationer i listen

- Send Info SMS
- Send info e-mail

Ved tryk på disse kan der sendes en SMS eller mail til samlige betaler for ejendommene

### Felter ( Overskrifter på kolone ) på listen

- BBR 
- BFE - Det nye ejendomsnummer
- Tur nummer - Turens nummer
- Saldo - Skyldige beløb for ejendom
- Postnr. 
- Adresse
- Sted
- Tur gruppe  - Hvilken type tur er det
- Aktiv fra

Ved at trykke på feltes navn, så sorteres der på kolonen, ( 1. tryk stigene, 2. tryk faldende)
