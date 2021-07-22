# Projekt bővítése első teszttel

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

## Feladatod
A projektedben készíts egy tesztet a locations endpoint-ra. A teszt kérdezze le az összes lokációt.

További feladatod, hogy leellenőrizzd, hogy a HTTP hívás sikeresen végződött-e. HTTP 200-as kóddal kell végződjön. Ehhez használd a megismert teszt funkciót a SoapUI-ban.