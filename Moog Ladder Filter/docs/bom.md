# Mogg Ladder BOM
 
[Back to Mogg Ladder](../README.md)
 
## Components
 
(Most) parts on Tayda: cart link TBD, [quick-order CSV](tayda_bom.csv)
 
| | Reference | Qty | Part | Value | Source | Comment |
|---|---|---|---|---|---|---|
|  | U1 | 1 | Quad op-amp | TL074 (SOIC-14) | [Tayda A-1137](https://www.taydaelectronics.com/tl074-quad-operational-amplifier-j-fet-soic-14-tl074cdt.html) | TL074CDT |
| ❓ | U2 | 1 | Dual op-amp | TL072 (SOIC-8) | Tayda (SKU to confirm) |  |
| 🔴 | Q1, Q6 | 2 | Transistor array | AS3046 (SOIC-14), CA3046 replacement | [Electric Druid](https://electricdruid.net/product/as3046-matched-transistor-array/), [Tubes and More](https://www.tubesandmore.com/products/soic-14) | The CA3046 is obsolete. The Alfa AS3046 is the drop-in SOIC-14 replacement |
| 🔴 | Q2, Q3, Q5 | 3 | Matched NPN pair | BCM847DS (SOT-457 / SOT-23-6) | DigiKey, Mouser | Nexperia matched pair |
| 🔴 | Q4 | 1 | PNP transistor | BC857 (SOT-23) | DigiKey, Mouser |  |
| 🔴 | D1–D4 | 4 | LED | 3mm bicolor red/green, 2 leads | [Jameco 94553](https://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_94553_-1) | Bipolar 2-lead type, not common anode or cathode |
| 🔴 | D5, D6 | 2 | Schottky diode | SS14 (SMA), 1N5817 equivalent | [Amazon (assortment kit)](https://www.amazon.com/gp/product/B07BTXK1NG) | Reverse polarity protection. Use the SS14 strip from the kit |
|  | R7, R14, R20, R25 | 4 | Resistor | 150Ω (0805) | [Tayda A-3360](https://www.taydaelectronics.com/catalogsearch/result/?q=A-3360) | Sold in packs of 50 |
|  | R23, R33, R35, R38 | 4 | Resistor | 1kΩ (0805) | [Tayda A-3065](https://www.taydaelectronics.com/50-x-smd-chip-resistors-1-0k-ohm-1-8w-1-0805.html) | Sold in packs of 50 |
|  | R2, R3, R5, R19, R28 | 5 | Resistor | 10kΩ (0805) | [Tayda A-950](https://www.taydaelectronics.com/10k-ohm-smd-chip-resistors-1-8w-1-0805.html) | Sold in packs of 50 |
|  | R10, R16, R17, R24 | 4 | Resistor | 100kΩ (0805) | [Tayda A-3113](https://www.taydaelectronics.com/50-x-smd-chip-resistors-100k-ohm-1-8w-1-0805.html) | Sold in packs of 50 |
|  | R30 | 1 | Resistor | 22Ω (0805) | [Tayda A-3025](https://www.taydaelectronics.com/catalogsearch/result/?q=A-3025) | Sold in packs of 50 |
| ❓ | R26 | 1 | Resistor | 220Ω (0805) | Tayda (SKU to confirm) |  |
| ❓ | R34 | 1 | Resistor | 180Ω (0805) | Tayda (SKU to confirm) |  |
| ❓ | R1, R27 | 2 | Resistor | 330Ω (0805) | Tayda (SKU to confirm) |  |
| ❓ | R21, R22 | 2 | Resistor | 470Ω (0805) | Tayda (SKU to confirm) |  |
| ❓ | R4 | 1 | Resistor | 680Ω (0805) | Tayda (SKU to confirm) |  |
| ❓ | R18 | 1 | Resistor | 1.8kΩ (0805) | Tayda (SKU to confirm) |  |
| ❓ | R8, R11, R13, R32 | 4 | Resistor | 4.7kΩ (0805) | Tayda (SKU to confirm) |  |
| ❓ | R15, R41 | 2 | Resistor | 22kΩ (0805) | Tayda (SKU to confirm) |  |
| ❓ | R29, R37 | 2 | Resistor | 47kΩ (0805) | Tayda (SKU to confirm) |  |
| ❓ | R40 | 1 | Resistor | 56kΩ (0805) | Tayda (SKU to confirm) |  |
| ❓ | R6, R9, R12 | 3 | Resistor | 120kΩ (0805) | Tayda (SKU to confirm) |  |
| ❓ | R31, R36 | 2 | Resistor | 220kΩ (0805) | Tayda (SKU to confirm) |  |
| 🔴 | R39, R42 | 2 | Resistor | 10Ω (1206) | [Amazon](https://www.amazon.com/gp/product/B08R8G5JT9) | Power rail fuse resistors. Pick the "10 ohm" size option |
|  | C1, C4, C6, C9, C10, C14, C15, C16 | 8 | Ceramic capacitor | 0.1µF (0805) | [Tayda A-3511](https://www.taydaelectronics.com/100nf-50v-smd-ceramic-chip-capacitor.html) | 50V. Sold in packs of 50 |
| ❓ | C5 | 1 | Ceramic capacitor | 100pF (0805) | Tayda (SKU to confirm) | C0G/NP0 |
| 🔴 | C2, C3, C7, C11 | 4 | Ceramic capacitor | 47nF (1206) | DigiKey, Mouser | Ladder capacitors: use C0G/NP0 (or film) for stable cutoff. The X7R kit works but drifts with temperature |
| 🔴 | C8, C18, C19 | 3 | Ceramic capacitor | 10µF (1206) | [Amazon (1206 kit)](https://www.amazon.com/dp/B0G58VQWQL) | X7R, 25V or higher. Use the 10µF strip from the kit |
| 🔴 | C20, C21 | 2 | Ceramic capacitor | 10µF (1210) | DigiKey, Mouser | X7R, 25V or higher. Power rail filter |
| 🔴 | C13, C17 | 2 | Ceramic capacitor | 220nF (1210) | DigiKey, Mouser |  |
| ❓ | C12 | 1 | Electrolytic capacitor | 220µF, 8x10mm | Tayda (SKU to confirm) | Check voltage rating against its rail |
|  | RV2 | 1 | Potentiometer | B10K (linear), 9mm vertical | [Tayda A-1847](https://www.taydaelectronics.com/catalogsearch/result/?q=A-1847) | CUTOFF (frequency). Round shaft |
|  | RV9 | 1 | Potentiometer | C50K (anti-log), 9mm vertical | [Tayda A-8406](https://www.taydaelectronics.com/c50k-ohm-taper-potentiometer-round-shaft-pcb-9mm.html) | RESONANCE (emphasis). Round shaft |
|  | RV3, RV4 | 2 | Potentiometer | A50K (log), 9mm vertical | [Tayda A-1660](https://www.taydaelectronics.com/50k-ohm-logarithmic-taper-potentiometer-round-shaft-pcb-9mm.html) | Audio 1 and 2 LEVEL. Footprint is Bourns PTV09A: check the Alpha pins fit |
|  | RV1, RV5 | 2 | Potentiometer | B50K (linear), 9mm vertical | [Tayda A-1858](https://www.taydaelectronics.com/50k-ohm-linear-taper-potentiometer-round-shaft-pcb-9mm.html) | CV 1 and CV 2 attenuators. Footprint is Bourns PTV09A: check the Alpha pins fit |
| 🔴 | RV7 | 1 | Trimmer | 500Ω, Bourns 3214W (4mm SMD) | DigiKey, Mouser | Calibration |
| 🔴 | RV10 | 1 | Trimmer | 1kΩ, Bourns 3214W (4mm SMD) | DigiKey, Mouser | Calibration |
| 🔴 | RV8 | 1 | Trimmer | 10kΩ, Bourns 3214W (4mm SMD) | DigiKey, Mouser | Calibration |
| 🔴 | RV6 | 1 | Trimmer | 100kΩ, Bourns 3214W (4mm SMD) | DigiKey, Mouser | Calibration |
| 🔴 | RV11 | 1 | Trimmer | 200kΩ, Bourns 3214W (4mm SMD) | DigiKey, Mouser | Calibration |
|  | J1–J5, J7 | 6 | 3.5mm jack | PJ-3001F (Thonkiconn style) | [Tayda A-2563](https://www.taydaelectronics.com/pj-3001f-3-5-mm-mono-phone-jack.html) | IN 1, IN 2, CV 1, CV 2, CV 3, OUT |
| 🔴 | J6 | 1 | Power header | 2x5 shrouded, 2.54mm | [Amazon](https://www.amazon.com/dp/B0F9NSTWCV) | Eurorack power |
| ❓ | J8, J9 | 2 pairs | Board-to-board header | 1x3, 2.54mm, male + female | Tayda (SKU to confirm) | Joins the front and main boards |
| ❓ | J10, J11 | 2 pairs | Board-to-board header | 1x6, 2.54mm, male + female | Tayda (SKU to confirm) | Joins the front and main boards |
 
🔴 = Missing from Tayda BOM
❓ = Probably at Tayda, SKU not confirmed yet
 
TP1–TP10 are test pads on the board. No part needed.
 
All controls increase clockwise.
 