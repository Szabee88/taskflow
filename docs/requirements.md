# Követelmények

## Funkcionális követelmények

### FK-01 – Feladat létrehozása

**Leírás:**  
Felhasználóként szeretnék új feladatot létrehozni címmel és határidővel, hogy nyomon tudjam követni a teendőimet.

**Elfogadási kritérium:**  
Adott, hogy a felhasználó a feladatkezelő felületen van, amikor megadja a feladat adatait és elmenti, akkor az új feladat megjelenik a feladatlistában.

### FK-02 – Feladat teljesítettnek jelölése

**Leírás:**  
Felhasználóként szeretném a feladataimat teljesítettnek jelölni, hogy lássam, mely teendőimet végeztem már el.

**Elfogadási kritérium:**  
Adott, hogy létezik egy aktív feladat, amikor a felhasználó teljesítettnek jelöli, akkor a feladat állapota teljesítettre változik.

## Nem funkcionális követelmények

### NFK-01 – Teljesítmény

A rendszer a feladatlistát normál terhelés mellett legfeljebb 2 másodperc alatt töltse be.

### NFK-02 – Használhatóság

A felhasználó a fő funkciókat, például új feladat létrehozását és egy feladat teljesítettnek jelölését legfeljebb 3 felhasználói művelettel tudja elvégezni.