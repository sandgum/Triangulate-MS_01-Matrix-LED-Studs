# MatrixStuds

## Description
Tiny 10x10mm ear studs (inspired by Mitxela) with 16 LEDs on each, arranged in a 4x4 matrix. Each matrix is controlled by an Analog Devices MAX32660 microcontroller paired with a Bosch BMA530 accelerometer to react to orientation changes. Each stud features a tiny 3.7v-3.3v step-down converter to accept rechargeable Li-ion cells. All tied up together in a CNC'd steel enclosure.

<img width="811" height="785" alt="Screenshot 2026-04-04 at 11 23 14 am" src="https://github.com/user-attachments/assets/c3880b61-a608-47b6-987e-57b682025fe8" />

## PCB (Studs)
### Overview
* 4-layer double-stacked rigid PCB (8 layers when assembled)
* Matrix on one "part" of PCB, other electronics on other "part"
* Features interconnect pads on back of each PCB to interface between the two "parts"
* 0.4mm thickness, 0.8mm total stacked thickness
* Features 1mm pads for programming, power pins

### Schematic
<img width="1377" height="977" alt="Screenshot 2026-04-04 at 11 30 57 am" src="https://github.com/user-attachments/assets/be50bc5f-8143-44bf-8060-85f74ffda779" />

### PCB Layout
<img width="807" height="506" alt="Screenshot 2026-04-04 at 11 31 59 am" src="https://github.com/user-attachments/assets/d1f7e6fc-dc4a-4f62-be1b-58509b80d32c" />

*Top Layer*

<img width="812" height="513" alt="Screenshot 2026-04-04 at 11 32 11 am" src="https://github.com/user-attachments/assets/7f0cbec6-f238-480c-a0aa-7fb607eeb215" />

*Bottom Layer*

<img width="468" height="391" alt="Screenshot 2026-04-04 at 11 38 30 am" src="https://github.com/user-attachments/assets/263422a2-e5f3-44bc-82fd-c1df3f55eaad" />

*3D Model (Bottom Side)*

<img width="482" height="346" alt="Screenshot 2026-04-04 at 11 38 48 am" src="https://github.com/user-attachments/assets/d0cf7c53-3b8e-4a1b-912b-16f272e0ead0" />

*3D Model (Top Side)*

## PCB (Charging Board)
## Overview
* 4-layer double-stacked rigid PCB (8 layers when assembled)
* Side 1:
*   Battery charging circuitry for two batteries (fuel gauge and charger)
*   USB-C Port
*   ATMega328P microcontroller for controlling lights
* Side 2:
*   9x WS2812B 2mm NeoPixel Lights
*   Reset SPDT switch for MCU

### Schematic
<img width="1223" height="841" alt="Screenshot 2026-05-03 at 11 30 13 am" src="https://github.com/user-attachments/assets/ff812b4c-9c57-48fc-9fc4-8ad9123b0731" />

### PCB Layout
<img width="923" height="904" alt="Screenshot 2026-05-03 at 11 30 37 am" src="https://github.com/user-attachments/assets/020b6ab2-662d-4689-9d53-8e2b851e41a3" />

*Top Layer*

<img width="915" height="902" alt="Screenshot 2026-05-03 at 11 31 29 am" src="https://github.com/user-attachments/assets/eb95296c-172b-4c65-8fe0-f0c2ff354feb" />

*Bottom Layer*

<img width="899" height="584" alt="Screenshot 2026-05-03 at 12 21 00 pm" src="https://github.com/user-attachments/assets/4bc29ef1-356e-4a64-96c2-4679cf67813a" />

*3D Model (Top Side)*

<img width="783" height="559" alt="Screenshot 2026-05-03 at 12 21 12 pm" src="https://github.com/user-attachments/assets/1c1fd2a4-d0b9-454c-ac09-a778edeec776" />

*3D Model (Bottom Side)*

## Enclosure
### Overview (Studs)
* CNC stainless steel construction
* Two-part design, one for battery side, one for top side
* Translucent PP diffuser over LED matrix
* Push-lock mechanism two secure both sides
* Permanent power wire going from battery side to top side in accent colour
* Points on back of top side for rotational stability while on ear

### Overview (Charging Dock)
* CNC steel upper construction, 3D-printed plastic lower construction
* Battery charging GND connection made through upper case, positive connection made through insulated copper springs
* Magnets to secure studs
* USB-C charging, SoC indication through adressable RGB strip

### Images (Studs)
<img width="612" height="696" alt="Screenshot 2026-04-04 at 11 36 01 am" src="https://github.com/user-attachments/assets/fa327f75-bff2-49ac-ae74-bd1219aa985a" />
<img width="623" height="658" alt="Screenshot 2026-04-04 at 11 36 17 am" src="https://github.com/user-attachments/assets/edc9808b-fe49-4375-b50c-51c7dd21a559" />
<img width="416" height="454" alt="Screenshot 2026-04-04 at 11 36 41 am" src="https://github.com/user-attachments/assets/fbdad625-be97-4f9e-9be2-0c793f9924e7" />
<img width="599" height="633" alt="Screenshot 2026-04-04 at 11 36 59 am" src="https://github.com/user-attachments/assets/05d7dde4-ab0c-4fc0-9761-213678e0bd49" />

### Images (Charging Dock)
<img width="767" height="590" alt="Screenshot 2026-05-03 at 12 22 40 pm" src="https://github.com/user-attachments/assets/5d49c6d4-0234-4c71-9019-87d99dd921d6" />
<img width="783" height="629" alt="Screenshot 2026-05-03 at 12 23 12 pm" src="https://github.com/user-attachments/assets/b34ec335-1c4e-4ab9-b8f1-6681ee0bde60" />
<img width="726" height="627" alt="Screenshot 2026-05-03 at 12 23 26 pm" src="https://github.com/user-attachments/assets/28aec886-8f76-46b0-9ff2-7645bc1b156b" />
<img width="699" height="672" alt="Screenshot 2026-05-03 at 12 23 36 pm" src="https://github.com/user-attachments/assets/24175558-b038-4cfe-aca8-500618cab05d" />
<img width="677" height="621" alt="Screenshot 2026-05-03 at 12 23 51 pm" src="https://github.com/user-attachments/assets/4f59ebe4-4606-49e2-8848-0e6da7fc3268" />

## Bill of Materials (Coming soon)
