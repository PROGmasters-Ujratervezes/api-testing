# Első SoapUI projekt

## Előfeltételek
A feladat elvégzéséhez az alábbi előfeltételekkel élünk
* a SoapUI community edition legújabb verizója telepítve van a gépeden
* telepítve van a gépeden a Docker Desktop és működik
* beszerezted a Locations-App forráskódját innen: https://github.com/Training360/locations-app
* elindítottad az applikációt az alábbi parancsal:
```
docker compose up -d
```

## Feladatod
Készíts egy új SoapUI projektet. Legyen a neve Locations App test projekt. A típusa legyen SOAP webservice. Használd a lokálisan futó alkalmazás WSDL fálját a projektben: 
`http://localhost:8080/services/locations?wsdl`

A projektben felajánlott test és sandbox generálás fogadd el és tekintsd át a projektet.

Az elkészült projektet exportáld ki SOAPUIból és kommitold be a gitrepo gyökerébe locations_app_test_projekt.xml néven.
