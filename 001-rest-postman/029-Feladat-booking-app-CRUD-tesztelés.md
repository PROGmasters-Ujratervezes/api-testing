# 029-Feladat-booking-app-CRUD-tesztelés

Feladatot, hogy készíts egy saját Github fork-ot a https://github.com/tjozsa/booking-app git repoból. Tetszőleges eszközzel clone-ozd ki a saját gépedre. Ebben fogod a következő feladatokat megoldani. Nem kell kódot írnod a repóba. 

A feladatokat egy darab `postman-collections` mappában kell be pusholnod a saját forkodba. Ezt a mappát már most hozzd lértre. Ha be akarod commitolni és pusholni akkor bele tehetsz egy üres text file-t. Emlékeztetőül, ezt `.gitkeep` névvel szoktuk ilyenkor létrehozni.

Feladataid:

* Hozz létre egy `hotels` kollekciót postmanben, és készíts az előzőekben tanultak alapján egy teljesértékű CRUD teszt kollekciót
  * Legyen benne GET, POST, PUT, DELETE hívás
  * Legyen benne environments használat
  * Legyen benne teszt eset
* Futtasd ezt a kollekciót `newman` segítségével lokálisan
* Készíts a forkodhoz Github Action workflow-t ami lefuttatja az applikációt és rá az összes tesztet a kollekcióból.
* Az eredményeket allure reportban kell jelentened egy Github Page branchen.
  * Használd ezt az allure kiegészítőt: https://www.npmjs.com/package/newman-reporter-allure