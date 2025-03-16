# Muistio kurssityö

## Sovelluksen tulevat toiminnot

* Käyttäjä pystyy luomaan tunnuksen ja kirjautumaan sisään sovellukseen.
* Käyttäjä pystyy lisäämään, muokkaamaan ja poistamaan muistoja.
* Käyttäjä pystyy hakemaan muistoja.
* Käyttäjilla on profiilit, joista näkee tilastoja ja muistot.
* Muistoja voi luokitella.

## Sovelluksen asennus

Asenna `flask`-kirjasto:

```
$ pip install flask
```

Luo tietokannan taulut ja lisää alkutiedot:

```
$ sqlite3 database.db < schema.sql
$ sqlite3 database.db < init.sql
```

Voit käynnistää sovelluksen näin:

```
$ flask run
```
