# Kulutusseuranta

Tämä ohjelmointiprojekti on toteutettu Backend ohjelmointi-kurssin lopputyönä Haaga-Helia ammattikorkeakoulussa. Työn aiheena on kulutusseurantajärjestelmä, jossa käyttäjä
voi tarkastella omaa kulutustaan ja kulujen jakautumista eri kategorioihin.

## Toiminnallisuudet
- Käyttäjien hallinta ja todennus: rekisteröinti- ja kirjautumissivu.
- Peruskäyttäjä voi lisätä kuluja ja nähdä lisäämänsä kulut.
- Admin-käyttäjä voi lisätä, poistaa ja muokata kuluja sekä nähdä lisäämänsä kulut (CRUD).
- Käyttäjän tiedot tallennetaan ulkoiseen tietokantaan (PostgreSQL).
- Kulut on esitetty sekä taulukossa että ympyrädiagrammissa, josta käyttäjä voi tarkastella kulujen
  jakautumista kategorioittain.
- Jokainen käyttäjä voi nähdä vain omat tietonsa.

## Käytetyt teknologiat
- Spring Boot
- PostgreSQL
- Java
- HTML
- Thymeleaf

## Kuvia

![Rekisteröidy](images/rekisteroidy.PNG)
<p></p>
Käyttäjän tulee rekisteröityä voidakseen lisätä kuluja järjestelmään. Jokaisella käyttäjällä on oma uniikki käyttäjätunnus ja salasana. Käyttäjä saa
ilmoituksen, mikäli käyttäjätunnus on jo varattu.
<p></p>

![Rekisteröidy](images/kirjaudu.PNG)
<p></p>
Mikäli käyttäjä saa luotua itselleen tunnuksen ja salasanan, hänet ohjataan kirjautumissivulle. Käyttäjää pyydetään syöttämään kenttiin luotu käyttäjätunnus ja salasana.
<p></p>


![Rekisteröidy](images/home.PNG)
<p></p>
Kirjautumisen jälkeen käyttäjä pääsee etusivulle, josta hän voi siirtyä suoraan kulujen lisäykseen. Käyttäjä voi myös tarkastella aiemmin lisättyjä kuluja.
<p></p>


![Rekisteröidy](images/kuluttajakulut.PNG)
<p></p>
Kulunäkymässä käyttäjä voi tarkastella lisättyjä kuluja sekä taulukon että ympyrädiagrammin muodossa. Kuluista voidaan kirjata seuraavat tiedot: kulun nimi, summa,
päivämäärä, ostopaikka ja kategoria. Taulukon alapuolella olevasta ympyrädiagrammista käyttäjä voi tarkastella kulujen jakautumista kategorioittain. Kun käyttäjä vie hiiren 
ympyrädiagrammin eri sektoreiden päälle, näytölle ilmestyy kunkin kategorian kulutusmäärä sekä sen osuus kokonaiskulutuksesta.
<p></p>


![Rekisteröidy](images/lisätään.PNG)
<p></p>
Käyttäjä pääsee kulujen lisäysnäkymään sekä etusivulta että kulujen listaussivulta.
<p></p>


![Rekisteröidy](images/admininkulut.PNG)
<p></p>
Admin voi poistaa ja muokata omia kulujansa. Poista- ja muokkaa-painikkeet löytyvät taulukosta.
<p></p>


![Rekisteröidy](images/muokkaa.PNG)
<p></p>
Vain admin pystyy muokkaamaan omien kulujensa tietoja.
<p></p>





