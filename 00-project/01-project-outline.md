---
name: Rudics László
neptun: NDJ37A
id: 2026-ST-01
github: https://github.com/rudicslaszlo/NDJ37A-projekt
---

# Közúti forgalom automatikus elemzése videófelvételek alapján

A projekt célja rendszer megvalósítása, amely közúti videófelvételeken automatikusan detektálja és követi a járműveket, majd a járműtrajektóriákból forgalmi statisztikakat számít. A rendszer a járművek becsült mérete és mozgási sebessége alapján kategóriákat képez, és kategóriánkénti járműszámot, sebességi statisztikákat, valamint időegységre vetített forgalomintenzitást jelenít meg. A projekt része a merev határértékes és a fuzzy kategorizálás összehasonlítása, valamint a detektálás és követés eredményeinek referenciaadatokon történő kiértékelése.

## Célok

- **Elsődleges cél:** Működő, verziókezelt rendszer létrehozása közúti videófelvételek automatikus forgalomelemzésére.
- **Célfelhasználók / érintettek:** A közúti forgalmat elemző kutatók és fejlesztők, valamint a forgalmi adatok kiértékelésével foglalkozó szakemberek.
- **Mérhető sikerkritériumok:** A felhasználó videót tud betölteni a rendszer detektálja és követi a járművenként a trajektóriát, becsült méretet és sebességet határoz meg; kategóriánkénti járműszámot, átlagos és eloszlásalapú sebességi mutatókat, valamint forgalomintenzitást számít; a fuzzy és a merev kategorizálás eredményei reprodukálható módon összehasonlíthatók.
- **Korlátok:** A megoldásnak kezelnie kell a takarásokat, megszakadó trajektóriákat és nem feldolgozható bemeneteket. A detektálási és követési módszereket pontosság, identitáscsere, futási sebesség és erőforrásigény alapján kell összehasonlítani. A projekt nem terjed ki a közúti infrastruktúra valós idejű vezérlésére vagy hatósági célú járműazonosításra.

## Hatókör

### Benne van a hatókörben

- Járművek automatikus detektálása és időbeli követése.
- Járművenkénti trajektória előállítása, valamint a járműméret és sebesség becslése.
- Kategóriánkénti járműszámlálás, átlagos és eloszlásalapú sebességi statisztikák, valamint időegységre vetített forgalomintenzitás számítása.
- Méret- és sebességalapú járműkategóriák meghatározása, a kategóriaképzés dokumentálásával.
- Merev határértékes és fuzzy kategorizálási megközelítés megvalósítása, majd eredményeik összehasonlítása.
- Legalább két detektálási vagy követési megközelítés összehasonlítása pontosság, identitáscsere, futási sebesség és erőforrásigény szerint.
- Publikus, annotált közlekedési videó-adathalmazok felkutatása, hozzáférési és felhasználási feltételeik ellenőrzése, valamint a kiválasztott adatok dokumentált beszerzése.
- Referenciaadatokon végzett kiértékelés, különböző forgalomsűrűségű, takarásos különböző fényviszonyú jelenetek vizsgálatával.

### Nincs benne a hatókörben

- Közúti infrastruktúra valós idejű vezérlése.
- Járművek hatósági célú azonosítása.
- Torlódások automatikus felismerése az alapverzió kötelező részeként.
- Rendellenes közlekedési események detektálása az alapverzió kötelező részeként.
- Több kamera adatainak együttes feldolgozása az alapverzió kötelező részeként.

## Jegyzetek

Az első változat célja a teljes videófeldolgozási lánc megvalósítása a járműdetektálástól és -követéstől a forgalmi mutatók kiszámításáig. Legalább két detektálási módszer összehasonlítása reprodukálható kísérletekben.
