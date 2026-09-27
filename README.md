# Statika HF1 kalkulátor

A BME GPK Statika 1. házi feladatához készült kalkulátor: térbeli erőrendszer redukálása az origóba, az M_f nyomaték és a centrális egyenes origóhoz legközelebbi G pontja.

Megnyitás után válaszd ki, melyik ábra van a lapodon, majd add meg az „Adatok” táblázat értékeit. Az oldal kiírja a Moodle-be beírandó értékeket (F, M_O, r_G), a teljes részeredmény-táblázatot és a lépésenkénti levezetést a megadott számokkal. Egy méretarányos axonometrikus vázlatot is rajzol.

Az oldal egyetlen statikus `index.html` fájl, a képleteket a KaTeX (jsDelivr CDN) jeleníti meg.

## Elrendezések

Mind a négy változatot korábbi, kidolgozott feladatlapok eredményeivel ellenőriztük.

| | Pontok | F₁ | F₂ | F₃ | M₂ |
|---|---|---|---|---|---|
| A | A(a;0;c), B(a;0;0), C(a;b;0), D(0;b;0), E(0;b;c) | B | E, +y | C, +z | −z |
| B | A(a;0;0), B(a;b;0), C(a;b;c), D(0;b;c), E(0;b;0) | A | D, +z | C, −y | −x |
| C | A(a;0;0), B(a;0;c), C(a;b;c), D(a;b;0), E(0;b;0) | A | C, −x | D, −z | +y |
| D (hasáb) | A(a;0;0), B(a;b;0), C(0;b;0), D(a;0;c), E(a;b;c) | A | B, −x | E, −z | +y |

M₁ és M₂ szabad vektorok. Ha egy lap ábrája egyik változattal sem egyezik, az F₂, F₃ és M₂ komponensenként is megadható.
