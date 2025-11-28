# Datubase

**burdinola\_kalkulatu\_beza funtzioa**

* Helburua: produktu baten prezioari %21eko BEZa gehitzea.
* Sarrera: `prezioa` (DECIMAL(10,2)).
* Irteera: prezioa BEZa gehituta (DECIMAL(10,2)).
* Erabilera-adibidea:\
  `SELECT burdinola_kalkulatu_beza(100);` → `121.00`

<figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>



**burdinola\_kontatu\_erregistroak funtzioa**

* Helburua: emandako taulan dauden erregistro-kopurua zenbatzea.
* Sarrera: `taula_izena` (VARCHAR(64)).
* Irteera: erregistro-kopurua (INT).
* Erabilera-adibidea:\
  `SELECT burdinola_kontatu_erregistroak('wp_burdinolausers');`

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>



**burdinola\_osatu\_izena funtzioa**

* **Helburua:** izen eta abizena jasota, erabiltzailearen izen osoa kate bakarrean itzultzea (adibidez, “Ane Lopez”).
* **Sarrera:**
  * `izena` – erabiltzailearen izena (`VARCHAR(50)`)
  * `abizena` – erabiltzailearen abizena (`VARCHAR(50)`)
* **Irteera:** `VARCHAR(120)` motako testu-katea, formatuan: `izena + espazioa + abizena`.

<figure><img src=".gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
