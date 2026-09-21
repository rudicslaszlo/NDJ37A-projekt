---
name: Rudics László
neptun: NDJ37A
id: 2026-ST-01
---
# Közúti forgalom automatikus elemzése videófelvételek alapján

## A brief értelmezése

A projekt célja egy olyan rendszer létrehozása, amely közúti videófelvételek alapján automatikusan detektálja járműveket, majd különböző forgalmi mutatókat számít. A rendszernek képesnek kell lennie a járművek becsült méretük és mozgási sebességük alapján történő kategorizálására, valamint kategóriánkénti járműszám, sebességi statisztikák és forgalomintenzitási mutatók előállítására. A projekt fontos része a határértékeken alapuló kategorizálás és a fuzzy logikát alkalmazó besorolás összehasonlítása.

## Miért én lennék alkalmas erre a projektre?

Érdekelnek számítógépes látás és a valós környezetből származó adatok feldolgozásosán alapuló problémák. A közúti forgalom automatikus elemzése jó lehetőséget biztosít arra, hogy egy összetett, gyakorlati problémán keresztül fejlesszem a képfeldolgozással és adatelemzéssel kapcsolatos tudásomat. Emellett a merev és fuzzy kategorizálás összehasonlítása kutatási szempontból is izgalmas feladat, mivel lehetőséget ad a különböző megközelítések objektív vizsgálatára.

## Releváns tapasztalat és előzmények

Kurzusfeladatokban és saját projektekben dolgoztam már programozással, webes technológiákkal és adatbázisokkal. Magabiztosan használom a Gitet, és egy nagyobb feladatot kisebb, jól elkülöníthető és tesztelhető funkciókra bontok. A meglévő Python skilljeimet szeretném kibővíteni a képfeldolgozás és a számítógépes látás területeire is.

## Tervezett megközelítés

Első lépésként megvizsgálnám a feladathoz használható detektálási és követési módszereket, majd kiválasztanám a megfelelő tesztadatokat. Ezután kialakítanám a videófeldolgozás teljes folyamatát, amely magában foglalná a járművek detektálását, időbeli követését, a trajektóriák előállítását, valamint a járművek méretének és sebességének becslését. Legalább két detektálási vagy követési megközelítést hasonlítanék össze pontosság, identitáscserék, futási sebesség és erőforrásigény alapján. A következő lépésben megvalósítanám a járművek méretalapú és sebességalapú kategorizálását. A hagyományos, merev határértékes módszer mellett fuzzy tagsági függvényeken alapuló megközelítést is kidolgoznék. A két módszer eredményeit összehasonlítanám, különös tekintettel a határesetekre és a végső forgalmi mutatókra gyakorolt hatásukra. Végül elkészíteném a felhasználó számára a feldolgozott videók, a detektált és követett járművek, valamint a számított forgalmi statisztikák megjelenítését. A rendszer tesztelése során külön figyelmet fordítanék a takarások, a megszakadó trajektóriák, a változó fényviszonyok kezelésére.

## Kezdeti terv

1. A közlekedési videó-adathalmazok felkutatása, kiválasztása
2. Legalább két detektálási vagy követési megközelítés prototipizálása és összehasonlítása.
3. A járműdetektálás, követés, trajektória-előállítás, méret- és sebességbecslés megvalósítása.
4. A merev határértékes és a fuzzy kategorizálási módszer kidolgozása.
5. A kategóriánkénti számlálás, sebességi statisztikák és forgalomintenzitási mutatók elkészítése.

## További információ

A projektet a kezdetektől Git repóban vezetném, a fejlesztési feladatokat kisebb issue-kra bontva.
