# Budapest-Keleti Forgalmi Szimulátor

Telepíthető, internet nélkül is működő webes változat.

Elérhető: https://csovestom.github.io/keleti-palyaudvar/

## Közzététel GitHub Pages-en

**Settings → Pages**: Source = **Deploy from a branch**, Branch = `main`, mappa = `/ (root)`, **Save**. Egy-két perc múlva elérhető a fenti címen.

## Telepítés

- **Android (Chrome):** nyisd meg a címet, menü (⋮) → **Alkalmazás telepítése** / **Hozzáadás a kezdőképernyőhöz**.
- **iPhone, iPad (Safari):** Megosztás gomb → **Főképernyőhöz adás**.
- **Számítógép (Chrome, Edge):** a címsor jobb szélén a telepítés ikon, vagy menü → **Telepítés**.

Az első megnyitás után internet nélkül is indul.

## Frissítés

Cseréld le a fájlt a repóban. Az `index.html` változását a játék a következő online indításkor magától átveszi. Ha más fájl is változik, írd át a `sw.js` elején a `keleti-v1` értéket (pl. `keleti-v2`-re).
