# Boardoza TPS63030 Buck-Boost Converter Breakout Board
The TPS63030 High-Efficiency Buck-Boost Converter Breakout Board is a versatile power solution designed for battery-operated devices. It leverages the TPS63030 IC to efficiently convert input voltages from a wide range of battery chemistries, including two-cell or three-cell alkaline, NiCd, NiMH, or single-cell Li-ion/Li-polymer batteries. This board ensures a stable and adjustable power supply, supporting output currents up to 600 mA, even when the battery discharges to as low as 2.5V. With its high efficiency, compact design, and low quiescent current, the TPS63030 breakout board is ideal for portable electronics, wearable devices, and other applications requiring consistent performance regardless of battery charge state.

### [Click here to purchase!](https://www.ozdisan.com/maker-and-iot-products/boardoza/boardoza-modules/BOARDOZA-TPS63030/1206513)

|Front Side|Back Side|
|:---:|:---:|
| ![ TPS63030 Front](./assets/TPS63030%20Front.png)| ![ TPS63030 Back](./assets/TPS63030%20Back.png)|

---
## Key Features
- High Efficiency: Provides efficient power conversion, achieving up to 96% efficiency for extended battery life.
- Buck-Boost Capability: Supports both step-up and step-down voltage conversion for versatile power management.
- Adjustable Output Voltage: Allows for precise voltage control to match various device requirements.
- Automatic Mode Transition: Seamlessly transitions between step-down and boost modes based on input voltage.
- Safety Features: Includes overtemperature protection and load disconnect during shutdown for enhanced device safety.
- Compact Design: Small form factor for easy integration into portable applications and battery-operated devices.
- Low Quiescent Current: Consumes less than 50 μA in standby mode, optimizing power efficiency.

---

## Technical Specifications
**Input Voltage:**	1.8V ~ 5.5V

**Power Input Type:** Molex 2 pin 2.50 header

**Output Voltage:** 3.3V	

**Output Current:** 
- Up to 800 mA in Step-Down Mode (VIN = 3.6V to 5.5V)  
- Up to 500 mA in Boost Mode (VIN > 2.4V)  
 
**Functions:**	Buck-Boost Converter

**Efficiency:** Up to 96%

**Quiescent Current:** Less than 50 μA  

**Operating Temperature:**	-40°C ~ +85°C

**Board Dimensions:**	40mm x 60mm

---

## Board Pinout
| ( J1 ) Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | GND | Ground |
| 2 | VIN | Voltage Input Pin (1.8V ~ 5.5V) |

| ( J2 ) Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | GND | Ground |
| 2 | VIN SENSE | Can be used to measure the input voltage directly on the input capacitor. |

| ( J3 ) Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | HIGH | Power Supply |
| 2 | EN | Shorting jumper between the center pin EN and HIGH turns on the unit. Shorting jumper between the center pin EN and LOW turns the unit off. (Default: Pulled up to VIN in circuit) |
| 3 | LOW | Ground |

| ( J4 ) Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | GND | Ground |
| 2 | VOUT SENSE | Can be used to measure the output voltage directly on the output capacitor. |

| ( J5 ) Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | HIGH | Power Supply |
| 2 | PS/SYNC | The center pin of this jumpers is connected to the SYNC pin of the TPS63030 and is used to synchronize the unit with an external clock.This jumper also enables/disables the power-saving mode at light loads. To enable power-save, PS/SYNC must  shorting  to LOW. (Default: Pulled up to VIN in circuit) |
| 3 | LOW | Ground |

| ( J6 ) Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | GND | Ground |
| 2 | VOUT | Buck-boost converter output (3.3V) |

---
## Board Dimensions

<img src="./assets/TPS63030 Dimension.png" alt=" TPS63030 Dimension" width="450"/>

---
## Step Files

[Boardoza TPS63030.step](./assets/TPS63030%20Step.step)

---
## Datasheet

[Boardoza TPS63030 Datasheet.pdf](./assets/TPS63030%20Datasheet.pdf)

---
## Version History
- V1.0.0 - Initial Release

---
## Support
- If you have any questions or need support, please contact support@boardoza.com

---
## License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
