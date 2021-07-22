# Tesztek futtatása github actionnel

## Előfeltételek
A feladat elvégzéséhez az alábbi előfeltételekkel élünk
* a SoapUI community edition legújabb verizója telepítve van a gépeden
* telepítve van a gépeden a Docker Desktop és működik
* beszerezted a Locations-App forráskódját innen:
* elindítottad az applikációt az alábbi parancsal:
```
docker compose up -d
```
* létrehoztad a `locations app test projekt` nevű SoapUI projektet
* projektedet már kibővítetted egy teszttel
* projektedet már kibővítetted egy saop asserttel

## Feladatod
A projekted exportált változatát add hozzá és pushold be a github repódba. A reóhoz a vizsgaremekben és egyéb feladatokban ismertetett módon készíts Github action workflow-t. Futtasd a soapui testrunner segítségével a projekted tesztjeit. Ne feledd, hogy el kell indítanod a dockerizált locations appot mielőtt a testrunnert futtatod.
