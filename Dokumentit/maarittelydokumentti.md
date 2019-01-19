# Määrittelydokumentti

## Ongelma: onko annettu luku alkuluku ja kuinka tämän tehokkaasti selvitämme?

Suuret alkuluvut ovat oleellinen osa nykyaikaisia salausmetelmiä ja tällaisten löytäminen ja testaaminen tehokkaasti on eärs kryptografian peruspilareista. Vain raa'alla voimalla kokeilemalla jakaa lukua kaikkia mahdollisia tekijöihin neliöönsä asti ei saada realistisessa ajassa vastausta tähän kysymykseen kryptografian kannalta riittävien isojen lukujen osalta.

Ohjelmani alkulukutesteistä pyrkii toteuttamaan ja vertaamaan keskenään tehokkuuksissa kahta tunnettua alkulukutestiä, eli probabilistista Miller-Rabinin testiä sekä ensimmästä keksittyä determinististä AKS-testiä. Jälkimmäinen tunnistaa luvun alkuluvuksi tai yhdistelmäluvuksi täysin 100% varmuudella kun taas edellisen toiminta perustuu testin lukuisaan toistoon, jolloin päästään käytännössä kaikella merkittävällä tarkkuudella varmuuteen onko testattava luku alkuluku vai ei. Tämä todennäköisyyteen perustuva testi on näistä teoreettisesti tehokkaampi, joka siis on tarkoitus projektissa todentaa.

## Tutkittavat algoritmit

(tähän asiaa algojen teoreettisista tehokkuuksista ja toteutuksesta)

## Ohjelman toiminta

(asiaa käyttöliittymästä, ohjelman toiminnasta ja syötteistä sekä esitettävistä mittareista)

## Tavoitteet

(toimivuuden, tehokkuuden ja tilavaatimusten suhteen)

## Lähteet

*kirjat
*linkit
