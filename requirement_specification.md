# Dokumentista

Tämä dokumentti on "elävä"-dokumentti, joka päivittyy jatkuvasti. Se on karkea vaatimusmäärittelydokumentin runko, jota voi käyttää projektien vaatimusmäärittelyn pohjana. Rakennetta saa ja pitää muokata! Tavoitteena on luoda dokumentti, joka yhdistää palvelumuotoilun ja ohjelmistosuunnittelun saumattomasti yhteen. Tekijä ei ota mitään vastuuta dokumentin sisällöstä.

tv:NarsuMan



## IOT CITY-palvelun vaatimusmäärittely

Dokumentin versionumero 0.1

### Materiaalin luokittelu

Julkinen

### Oikeudet

Marko "NarsuMan" Rintamäki


## Sisältö

Sisällysluettelo 

* Johdatus


## Johdatus

Tämän vaatimusmäärittelydokumentti sisältää tarvittavia tietoja IOT-haasteen toteuttamiseen.    
IOT-haaste (City IOT) on JAMKin Challenge Factory 2016-tiimille annettu tehtävä, joka ratkaistaan kesän aikana.
Voit lukea lisää Challenge Factorystä [täältä](jamk-it.github.io/challenge_factory).

Tavoitteena em. tehtävän annolla on kerätä yhteen IOT-ratkaisuista kiinnostuneet yhteisöt ja opiskelijat. Yhdessä rakentaen ja ongelmia ratkoen opimme mitä kuuluu IOT-palvelujen maailmaan. 

### Lyhyt tuote/palvelukuvaus/asiakastarina

City IOT-palvelu on lyhyesti referenssitoteutus IOT-järjestelmästä, jonka avulla voidaan kerätä erilaista mittaustietoa kuvitteellisen kaupungin alueelta. Lähtökohtaisesti on tavoite kerätä mittaustietoa liittyen viemärijärjestelmään.

Esimerkkeinä mitattavista parametereistä ovat virtausmäärä, vedenkorkeus ja eri hälytystasot. Palvelun toimiala on valittu mielivaltaisesti tilaajan omassa päässä, mutta pitäen mielessä todelliset ongelmat. Tehtäväannon on tarkoitus johdattaa opiskelijat tutustumaan IOT-ongelmakenttään kokonaisuutena, eikä pelkästään yksittäiseen osa-alueeseen. 


Palvelun toteuttaminen perustuu muutamien jo olemassa olevien ohjelmistojen yhteensovittamiseen. 


Karkea tavoite on luoda referenssitoteutus IOT-mittausjärjestelmästä, joka avulla voidaan kerätä mittaustietoa kuvitteellisesta kaupunginosasta ja siirtää kerätyn tiedon tietokantaan. Kerättyä tietoa pyritään visualisoimaan ja esittämään tilannehuoneen muodossa. 

Toteutettavan City IOT-mittauspalvelulla (Proof Of Concept) voidaan seurata yksittäisen kaupungin viemäriverkkoa, mutta tavoite on kyetä tarvittaessa skaalautua koko maata kattavavaan seurantaan.


### Tilaaja

Tilaajana ko. referenssi palvelulle toimivat N4S- ja Cyber Trust-tutkimusohjelmien yhteistyön innoittamana 
JAMKilla Marko "NarsuMan" Rintamäki 

  * Kuka on tilaaja, yhteistiedot ?
  
  
  * Jos tiedot on projektisuunnitelmassa, niin linkit tänne!

### Toimittaja

JAMK Challenge Factory 2016
Piippukatu 2, 40100 Jyväskylä
  
  * Kuka on toimittaja, yhteistiedot ?
  * Jos tiedot on projektisuunnitelmassa, niin linkit tänne!

### Aikataulu

Aikataulu on suuntaa antava ja tulee muuttumaan ajan kuluesa

  * Mitä alustavasti tullaan tekemään ja milloin ?
 



| Etappi | Alkaa | Loppuu | | | 
|:-----:|:-----:|:-----:|:-----:|:-----:|
| Challenge Factory ylösajo | 16.5.2016 | 17.5.2016 |  | P1 |
| Perehtyminen ongelmaan ja sidosryhmätapaaminen | 18.5.2017 | |  | P1 |
| Osa-alueisiin perehtyminen | 23.5.2017 |  |  | P1 |
|  28.2.2017 | 12.2.2017 |  | P1 |

## Palvelun/ohjelmiston tunnistetut sidosryhmät ja asiakkaat (Stakeholders and customers) 


### Sidosryhmät (Stakeholders)

* https://en.wikipedia.org/wiki/Stakeholder_analysis
* [Mikä ihmeen sidosryhmä?](https://fi.wikipedia.org/wiki/Sidosryhm%C3%A4)
* Kuka on kiinnostunut tuotteesta tai kenellä on sanansa sanottavana liittyen tuotteen kehittämiseen ?

Sidosryhmät (esimerkkejä)

* JAMK ohjelmisto-, verkko-, media- ja kybertekniikan osastot 
* Digia 
* Digile N4S-tutkimusohjelma
* Digile Cyber Trust-tutkimusohjelma
* Tekes
* Challenge Factory 2016-ryhmä 
* Muut alan yritykset

## Persoonat (Personanas)

Tunnistetut asiakasprofiilit, joiden avulla palvelua kehitetään.  


  * [Asiakas 1](), Mauno Mainio, 67, eläkeläinen, , kotosin Pohjois-Savosta (Matematiikan opettaja)
  * [Asiakas 2](), Riku Rikas, 30, IT Yrittäjä, asuinpaikka tuntematon, kotoisin nomands land 
  * [Asiakas 3](), Siiri Koikkalainen 99, suurmummo, Hankasalmi, (Sokea)
  * [Asiakas 4](), John Rambu, 55, tuntematon, Helsinki, (Bad Man)
  * [Asentaja 1](), Mauno Teräs, 29, Helsinki (Serviceman)
  * [Asentaja 2](), Mauno Teräs, 29, Helsinki (Serviceman)
  * [Ylläpito 1](), Jamppa Jauhola, 35, Helsinki ()
  * [Ylläpito 2](), Jaana Simola, 31, Joensuu ()
  * [Verkkoasiantuntija 1](), Kalle Kajaus, 26 ()
  * [ 
  


## Sidosryhmäkartta (Stakeholder map)

![](https://www.lucidchart.com/publicSegments/view/afbaa205-0924-40f8-a0a1-96e281aafcf5/image.png)

## Yleinen palvelun asiakaspolku (General Customer Journey)

![](https://camo.githubusercontent.com/1429ec848bc406a1bc7f38874188e4af03d3ee46/68747470733a2f2f7777772e64726f70626f782e636f6d2f732f6c6f7076357a6a6a337076676261392f757365725f6a6f75726e6579732d30322e706e673f646c3d31)

Käydään läpi asiakaspolku, jossa käytetään nimettyjä sidosryhmien edustajia

  *  Kuva seurantapalvelun toiminnasta


## Palvelun osa-aluejako (Service Domain areas)

Millaisiin osa-alueiseiin voidaan ohjelmisto/palvelu voidaan jakaa.

* Tietokanta
* Visualisointi
* Luenta
* SDN-luentaverkko
* Mittalaite
* Luentapalvelu
* Asentaja-applikaatio
* Valtuutuskanta
* Ajoympäristö
* Orkestrointi

## Tärkeimmät asiakaspolut (Customer Journey Maps) valituiden asiakasprofiilien näkökulmasta

* Tarkennetaan kuvausta tehtävän mukaisesti ?

* Mittarin asentaminen
* Mittariluennan valtuuttaminen
* Mittaustiedon kerääminen
* Mittaustiedon analysointi
* Mittaustiedon visualisointi
* Mittarin ohjelmistopäivitys
* Ison mittauksen tekeminen


### Asiakaspolku mittarin asennus [asentaja_1] näkökulmasta

* lorem ipsum
* Blue Print-kuva ?


### Mittaustiedon kerääminen [asiakas_1] näkökulmasta

* lorem ipsum
* Blue Print-kuva ?

### Asiakaspolku tuotten uudelleenasennus [asiakasprofiili_3] näkökulmasta

* lorem ipsum
* Blue Print-kuva ?


## Tärkeimmät piirteet/ominaisuudet (Features)


* Mittariohjelmisto
* Mittausohjelmiston jakelupalvelu
* Luentajärjestelmä
* SDN-verkko
* Mittalaitteen hyväksyntä luentaan


* [Tsekkaa MVP - Minimum Viable Product Features](https://en.wikipedia.org/wiki/Minimum_viable_product)


### Ominaisuus 2

  * [Linkki ominaisuuskuvaukseen](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/ominaisuuskuvaus.md)

  * Kuvaus
  * Ominaisuuteen liittyvät vaatimukset ?
  * UI-Näkymä ?
  * Testauksessa huomioitavaa

### Ominaisuus 3

  * Kuvaus
  * Ominaisuuteen liittyvät vaatimukset ?
  * UI-Näkymä ?
  * Prototyyppi näkymä?
  * Testauksessa huomioitavaa

### Ominaisuus 4

  * Kuvaus
  * Ominaisuuteen liittyvät vaatimukset ?
  * UI-Näkymä ?
  * Prototyyppi näkymä?
  * Testauksessa huomioitavaa

## Käyttötapaukset

### Tärkeimmät käyttötapaukset kuvana

![](https://www.lucidchart.com/publicSegments/view/6994e113-aa9d-4eeb-ab5d-edc605b604ef/image.png)

### Käyttötapaus 1

   * [Asentaminen](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/kayttotapauskuvauksen-pohja.md)

### Käyttötapaus 2

   * [Ohjelmiston päivitys mittarissa](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/kayttotapauskuvauksen-pohja.md)

### Käyttötapaus 3

   * [Mittaustiedon luenta](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/kayttotapauskuvauksen-pohja.md)

### Käyttötapaus 4

   * [Esimerkki4](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/kayttotapauskuvauksen-pohja.md)

## Riskit  (Risks)

   * Tunnistetaan ohjelmistoon/palveluun liittyviä riskejä..
   * [Riskienhallinta](https://fi.wikipedia.org/wiki/Riskienhallinta)

| Riski ID | Kuvaus | Tyyppi | Osa-alue | Vastuullinen | Prioriteetti | 
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|RISK001| Teknologiat eivät toimi | - | P1 |
|RISK002|  | Toiminnnallinen |  | P5 |
|RISK003| Heikon verkkoyhteyden vaikutus palvelun käyttöön | Toiminnnallinen | - | P3 |

  * Miten taulukoita luetaan: P1 = Erittäin tärkeä, P3 = Oleellinen, P5 = Triviaali

## Yleiset vaatimukset (Functional Requirements)

  * Tässä osiossa voidaan nostaa esiin huomioitavia tärkeitä vaatimuksia, jotka on hyvä pitää mielessä!

| Vaatimus ID | Kuvaus | Tyyppi | Osa-alue | Vastuullinen | Prioriteetti | 
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|YVA0001| Palvelun täytyy toimia Android versiosssa 4.x alkaen | Tekninen | "ASAP"-tuotantotiimi | P1 |
|YVA0002| Palvelun täytyy toimia Windows Phonessa | totetutus |  "ASAP"-tuotantotiimi | P2 |
|YVA0003| Palvelun täytyy toimia Windows 95:ssa, koska johtajalla on moinen koneessaan! | totetuts |  "ASAP"-tuotantotiimi | P5 |

## Tunnistetut toiminnnalliset vaatimukset (Functional Requirements)

| Vaatimus ID | Kuvaus | Tyyppi | Osa-alue | Vastuullinen | Prioriteetti | 
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|VAT0001|  | Toiminnnallinen | "ASAP"-tuotantotiimi | P1 |
|VAT0002| Käyttäjä voi tarvittaessa vaihtaa salasanansa | Toiminnnallinen |  "ASAP"-tuotantotiimi | P5 |
|VAT0003| Salasanan vaihdon jälkeen ei käyttäjän tarvitse kirjautua uudestaan | Toiminnnallinen |  "ASAP"-tuotantotiimi | P3 |

  * Miten taulukoita luetaan: P1 = Erittäin tärkeä, P3 = Oleellinen, P5 = Triviaali


## Tunnistetut laadulliset /ei-toiminnalliset vaatimukset (Non-Functional Requirements)

  * [Esimerkkejä tietoturvavaatimuksista](https://confluence.csc.fi/display/oppija/10.+Tietoturvavaatimukset)

| Vaatimus ID | Kuvaus | Tyyppi | Osa-alue | Vastuullinen | Prioriteetti | 
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|VAL0201| Palvelun pitää skaalatua hetkellisesti 1000 käyttäjälle | Skaalautuvuus | "ASAP"-tuotantotiimi | P1 |
|VAL0202| Palvelun saatavuus on oltava 99.1 % | Stabiilisuus |  "ASAP"-tuotantotiimi | P5 |
|VAL0203| Käyttäjän tiedot on salattavat | Tietoturva |  "ASAP"-tuotantotiimi | P3 |

  * Miten taulukoita luetaan: P1 = Erittäin tärkeä, P3 = Oleellinen, P5 = Triviaali

### Käytettävyys

  * Mitä on otettava huomioon ?
  * Asiakkaan toiveet ?
  * Teknologiset osa-alueet/asiat, jotka vaikuttavat käytettävyyteen?

# Käyttöliittymä prototyyppi


### Prototyypin esittely

   * Linkit prototyyppi ympäristöön
   * Tarvittavat tiedot prototyypin tarkasteluun


## Palvelun/ohjelmiston arkkitehtuuri

  * Tämä osio voidaan sisällyttää osaksi teknistä suunnittelua. 
  * Vaatimusmäärittelyssä voi kuitenkin olla  hyvä tarvittaessa kuvata yleistä totetutusta ja siihen liittyviä ongelmakohtia
  

![](https://camo.githubusercontent.com/5c169deb4debb278bb6219208f577843075ddab3/68747470733a2f2f7777772e64726f70626f782e636f6d2f732f6179707170797376726831316133312f636f6e747269626f6172642d6172636869746563747572652e706e673f646c3d31)

   * [Esimerkki elävästä elämästä](https://confluence.csc.fi/display/OPHPALV/Koodistopalvelun+tekninen+dokumentaatio)




### Luokkaehdokkaat (Class proposal)

  * Yleensä osa tarkempaa suunnittelua
  * Voidaan viitata linkeillä...

  * Tunnistetut luokkaehdokkaat

![](https://www.lucidchart.com/publicSegments/view/16b2b5a7-f349-48bf-8efb-594521131e09/image.png)

### Luokkamalli (Class Diagram)

  * Ainoastaan karkea kuvaus tarpeen ?

![](https://www.lucidchart.com/publicSegments/view/c680dd6c-6e68-43b7-bf6c-421bbe21a17c/image.png)

### Toiminta kuvaus (Sequence Diagram)

  * Sekvenssikuvalla on aika kätevä esittää muutakin

![](https://en.wikipedia.org/wiki/File:CheckEmail.svg)

### Sijoittelunäkymä (Deployment diagram

  * Vaatimusmäärittelyssä tämä saattaa olla yksi hyödyllisimpiä UML-kuvauksia ?
  * Miten ohjelmisto/palvelu tulee karkeasti toimimaan osana vanhaa totetutusta..
  * Miten olemassa oleva järjestelmä tulee karkeasti toimimaan

![](https://www.lucidchart.com/publicSegments/view/6f727a36-f880-4dca-b5ac-133f6f860697/image.png)


## Riskiperustainen esi-testaussuunnitelma

### Tunnistetut riskit ja testikohtee

  * Riski -> Testaustarve
  * Vaatimus -> Testaustarve


##  Julkaisusuunnitelma ja priorisointi

Julkaisujärjestys ei aina ole lineaarinen. [Ks. Kriittinen polku](https://fi.wikipedia.org/wiki/Kriittinen_polku)
Joskus se saattaa tuntua siltä: [Release Plan](https://wiki.documentfoundation.org/ReleasePlan)


Toiminnallisuudet ja toteuttamisjärjestys

  * Ominaisuus 1 - Maaliskuu 2019
  * Ominaisuus 3 - Huhtikuu 2019
  * Ominaisuus 5 - Toukokuu 2019
  * Ominaisuus 2 - Syyskuu 2019
  *     


### Priorisointi 


  * Miten taulukoita luetaan: P1 = Erittäin tärkeä, P3 = Oleellinen, P5 = Triviaali


## Standardit ja lähteet

  * ISTQB
  * IPMA
  * etc..



# Lähteet

# Lähteitä
