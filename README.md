# Statika HF1 kalkulátor

A BME GPK Statika 1. házi feladatához készült kalkulátor: térbeli erőrendszer redukálása az origóba, az M_f nyomaték és a centrális egyenes origóhoz legközelebbi G pontja.

Megnyitás után válaszd ki, melyik ábra van a lapodon, majd add meg az „Adatok” táblázat értékeit. Az oldal kiírja a Moodle-be beírandó értékeket (F, M_O, r_G), a teljes részeredmény-táblázatot és a lépésenkénti levezetést a megadott számokkal. Egy méretarányos axonometrikus vázlatot is rajzol.

Az oldal egyetlen statikus `index.html` fájl, a képleteket a KaTeX (jsDelivr CDN) jeleníti meg.

## Elrendezések

Az A–D változatot korábbi, kidolgozott feladatlapok eredményeivel ellenőriztük; az E változathoz még nincs ellenőrzött lap.

| | Pontok | F₁ | F₂ | F₃ | M₂ |
|---|---|---|---|---|---|
| A | A(a;0;c), B(a;0;0), C(a;b;0), D(0;b;0), E(0;b;c) | B | E, +y | C, +z | −z |
| B | A(a;0;0), B(a;b;0), C(a;b;c), D(0;b;c), E(0;b;0) | A | D, +z | C, −y | −x |
| C | A(a;0;0), B(a;0;c), C(a;b;c), D(a;b;0), E(0;b;0) | A | C, −x | D, −z | +y |
| D (hasáb) | A(a;0;0), B(a;b;0), C(0;b;0), D(a;0;c), E(a;b;c) | A | B, −x | E, −z | +y |
| E | A(a;0;0), B(a;0;c), C(a;b;c), D(0;b;c), E(0;b;0) | A | D, −y | C, +x | −z |

M₁ és M₂ szabad vektorok. Ha egy lap ábrája egyik változattal sem egyezik, az F₂, F₃ és M₂ komponensenként is megadható.

## 2. házi feladat

A [`hf2/`](hf2/) oldal a 2. házi feladathoz készült: síkbeli, két rúdból álló tartó reakcióerői egy csuklós és egy 45°-os sima támasz esetén. Kiszámolja a Moodle-be beírandó A₁ₓ, A₁ᵧ, B₁ₓ, B₁ᵧ (megadott M₀) és A₂ₓ, A₂ᵧ, B₂ₓ, B₂ᵧ (M₀ = 0) értékeket, megmutatja a szabadtest-ábrát, az egyensúlyi egyenleteket, valamint a három erő egyensúlyán alapuló szerkesztést méretarányos szerkezeti ábrával és erőábrával.

| | Csukló | Sima támasz | Megoszló terhelés |
|---|---|---|---|
| 1 | B, a vízszintes rúdon | A, a bal végi függőleges rúd alján | B-től jobbra csökken |
| 2 | B, a jobb végen | A, az F₁ alatti függőleges rúd alján | B felé nő |
| 3 | A, középen | B, a jobb végen | A felé nő |
| 4 | A, a falon (bal vég) | B, a jobb végen | jobbra nő |

Az elrendezéseket 2026/27-es lapokról vettük át; két független számítás egyezik, javított lappal még nem ellenőriztük.

## 3. házi feladat

A [`hf3/`](hf3/) oldal a 3. házi feladathoz készült: két csuklóval (A, B) megtámasztott, C-ben belső csuklós síkbeli rácsos tartó. Kiszámolja a Moodle-be beírandó Aₓ, Aᵧ, Bₓ, Bᵧ reakciókat és az N₁…N₁₀ rúderőket (húzás pozitív), és lépésenként megmutatja a részekre bontást a C csuklóban, a csomóponti módszert csomópontonként (kis csomóponti ábrákkal), valamint az 5-ös rúdon átmenő átmetszést Ritter-pontokkal. Méretarányos szerkezeti ábrát és rúderő-ábrát is rajzol.

| | A | B | C | F₁ | F₃, F₂ |
|---|---|---|---|---|---|
| 1 | bal felső sarok, falon | jobb alsó sarok | alsó öv | alsó öv, lefelé | felső öv, balra / jobbra |
| 2 | bal alsó sarok | jobb felső sarok, felfüggesztve | felső öv | felső öv, lefelé | alsó öv, balra / jobbra |

A csomópontok közül a lapon csak A, B és C van megnevezve; a kalkulátor a többit D, E, G, H betűvel jelöli. Az elrendezéseket 2026/27-es lapokról vettük át (1. változat: 4 lap, 2. változat: 1 lap); két független számítás egyezik, javított lappal még nem ellenőriztük.
