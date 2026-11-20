## Components
 
(Most) parts on Tayda: [cart link](https://www.taydaelectronics.com/savecartpro/index/savenewquote/qid/60358194109), [quick-order CSV](tayda_bom.csv)
 
| | Reference | Qty | Part | Value | Source | Comment |
|---|---|---|---|---|---|---|
|  | U3 | 1 | OTA | LM13700 (SOIC-16) | [Tayda A-6171](https://www.taydaelectronics.com/lm13700-lm13700m-operational-amplifier-ic.html) |  |
|  | U2 | 1 | Quad op-amp | TL074 (SOIC-14) | [Tayda A-1137](https://www.taydaelectronics.com/tl074-quad-operational-amplifier-j-fet-soic-14-tl074cdt.html) | TL074CDT |
| 🔴 | U1 | 1 | Shunt reference | TL431 (SOT-23) | [Mouser](https://www.mouser.com/en/ProductDetail/Nexperia/TL431AIDBZR215?qs=LMSg3oBIm%2Fg5HlV5EGtYIg%3D%3D) | Nexperia TL431AIDBZR,215. Pinout matches the board (pin 1 cathode, pin 2 reference, pin 3 anode). Check the pinout before substituting another maker's TL431 |
|  | Q1 | 1 | PNP transistor | MMBT3906 (SOT-23) | [Tayda A-4666](https://www.taydaelectronics.com/mmbt3906lt1g-pnp-general-purpose-transistor-40v-0-2a.html) |  |
| 🔴 | D1, D2 | 2 | Diode | 1N4148W (SOD-123) | [Amazon](https://www.amazon.com/gp/product/B0HJ4PB2B6) | 100 pack. Leave D2 off if using a bipolar LED for D3 |
| 🔴 | D4, D5 | 2 | Schottky diode | SS14 (SMA), 1N5817 equivalent | [Amazon (assortment kit)](https://www.amazon.com/gp/product/B07BTXK1NG) | Reverse polarity protection. Use the SS14 strip from the kit |
|  | D3 | 1 | LED | 3mm red | [Tayda A-261](https://www.taydaelectronics.com/led-3mm-red.html) | Any color works. Optional: 2-lead bipolar (red/green) LED shows both signal polarities; leave D2 off if used |
| 🔴 | R17, R18 | 2 | Resistor | 10Ω (1206) | [Amazon](https://www.amazon.com/gp/product/B08R8G5JT9) | Power rail fuse resistors. Pick the "10 ohm" size option. 100 pack |
|  | R1, R14, R16 | 3 | Resistor | 1kΩ (0805) | [Tayda A-3065](https://www.taydaelectronics.com/50-x-smd-chip-resistors-1-0k-ohm-1-8w-1-0805.html) | Sold in packs of 50 |
| 🔴🔁 | R10, R12 | 2 | Resistor | 1.5kΩ (0805) | DigiKey | e.g. Yageo RC0805FR-071K5L. R10 and R12 are always the same value. Build 2: 330Ω |
|  | R2, R3, R11, R15 | 4 | Resistor | 10kΩ (0805) | [Tayda A-950](https://www.taydaelectronics.com/10k-ohm-smd-chip-resistors-1-8w-1-0805.html) | Sold in packs of 50 |
| 🔁 | R4–R9, R13 | 7 | Resistor | 100kΩ (0805) | [Tayda A-3113](https://www.taydaelectronics.com/50-x-smd-chip-resistors-100k-ohm-1-8w-1-0805.html) | Sold in packs of 50. Build 2: R9 is 47kΩ, R8 optionally 220kΩ |
|  | C5–C8 | 4 | Ceramic capacitor | 0.1µF (0805) | [Tayda A-3511](https://www.taydaelectronics.com/100nf-50v-smd-ceramic-chip-capacitor.html) | 50V. Sold in packs of 50 |
| 🔴 | C1, C2 | 2 | Ceramic capacitor | 10µF (1206) | [Amazon (assortment kit)](https://www.amazon.com/dp/B0G58VQWQL) | X7R, 25V or higher. Power rail filter. Use the 10µF strip from the kit |
|  | RV1, RV2 | 2 | Tall trimmer | B10K (linear), RV9012NO-PA25B7.0-B10K | [Tayda](https://www.taydaelectronics.com/catalogsearch/result/?q=RV9012NO-PA25B7.0-B10K) | Channel A and B level. 6mm shaft with 40-tooth knurl: use set-screw knobs or knobs made for fine-knurl shafts |
| 🔁 | RV3, RV4 | 2 | Potentiometer | B10K (linear), 9mm vertical | [Tayda A-1847](https://www.taydaelectronics.com/catalogsearch/result/?q=A-1847) | INIT and DIST. Round shaft. Build 2: DIST (RV4) is A10K |
|  | J1–J4 | 4 | 3.5mm jack | PJ-3001F (Thonkiconn style) | [Tayda A-2563](https://www.taydaelectronics.com/pj-3001f-3-5-mm-mono-phone-jack.html) | In A, In B, CV, Out |
| 🔴 | J5 | 1 | Power header | 2x5 shrouded, 2.54mm | [Amazon](https://www.amazon.com/dp/B0F9NSTWCV) | Eurorack power. 10 pack |
 
🔴 = Missing from Tayda BOM
🔁 = Value changes for Build 2 (see Build Variants)
 
All controls increase clockwise.
 
## Build Variants
 
The PCB is the same for both builds. The Components table lists Build 1, which matches the Super Synthesis values. Build 2 changes only these parts:
 
| Reference | Qty | Part | Build 1 (stock) | Build 2 (more grit) | Source |
|---|---|---|---|---|---|
| R9 | 1 | Resistor (0805) | 100kΩ | 47kΩ | |
| R10, R12 | 2 | Resistor (0805) | 1.5kΩ | 330Ω | |
| RV4 | 1 | Potentiometer, 9mm vertical | B10K (linear) | A10K (log) | [Tayda A-1856](https://www.taydaelectronics.com/10k-ohm-logarithmic-taper-potentiometer-round-shaft-pcb-9mm.html) |
| R8 (optional) | 1 | Resistor (0805) | 100kΩ | 220kΩ | |
 
**Build 1** adds a little grit even at the lowest DIST setting and squares off the signal at the top.
 
**Build 2** is nearly clean at the lowest DIST setting and drives the OTA about twice as hard at every setting, so it stays saturated even with quieter inputs. The A10K pot spreads the gritty range across more of the turn. Raising R8 to 220kΩ also lets loud inputs clip the mixer before the OTA, which is harsher and buzzier.
 