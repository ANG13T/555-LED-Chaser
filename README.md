![https://github.com/ANG13T/555-LED-Chaser/blob/main/assets/preview.png](https://github.com/ANG13T/555-LED-Chaser/blob/main/assets/preview.png)

# 555 LED Chaser
LED Chaser circuit based on the NE555 and the CD4017 created for a San Diego workshop sponsored by Hack Club!

### Circuit Explanation
This circuit creates a sequential flashing animation of 10 LEDs which is operated by the CD1017 and 555 integrated circuits. 
It requires a VCC and GND from a 9V battery and allows you to monitor the clock output with an auxiliary pin header.
The clock speed of the 555 can be altered using the trim potentiometer.

### Schematic 
![https://github.com/ANG13T/555-LED-Chaser/blob/main/assets/schematic_preview.png](https://github.com/ANG13T/555-LED-Chaser/blob/main/assets/schematic_preview.png)

### PCB
![https://github.com/ANG13T/555-LED-Chaser/blob/main/assets/pcb_preview.png](https://github.com/ANG13T/555-LED-Chaser/blob/main/assets/pcb_preview.png)

## Components
- 555 Timer IC
- CD4017 IC
- 10x LED Lights
- Resistors: 470ohm and 1K ohm
- 1uF Capacitor
- 9V Battery
- 50Kohm Trim Potentiometer

## EasyEDA Symbols
| Name               | Component Name | Footprint Name                    |
|--------------------|----------------|-----------------------------------|
| 555 Timer IC       | NE555P         | DIP-8_L9.8-W6.6-P2.54-LS7.6-BL    |
| CD4017 IC          | CD4017KIT      | DIL16-KIT                         |
| LED                | LED_5MM        | LED-TH_BD5.0-P2.54-FD_C9900023552 |
| 1uF Capacitor      | CD4017KIT      | DIL16-KIT                         |
| 470ohm Resistor    | 470Ω           | RES-TH_BD3.3-L9.0-P13.00-D0.6     |
| 1K ohm Resistor    | 1k             | AXIAL-0.3                         |
| Trim Potentiometer | 50k            | RES-ADJ_3296X                     |
| VCC and GND Pins   | Header         | HEADER-FEMALE-2.54_1X2            |
| CLK Pin            | C81276         | HDR-TH_1P-P2.54-V-M               |

### 555 IC Overview 
The 555 IC is configured to be in astable mode. This causes the IC to behave like an oscillator switching its output between HIGH and LOW states to generate a square wave signal which can be fed into the CD4051 IC.

### CD4017 Overview


### Support 
If you enjoyed this design, please consider [becoming a sponsor](https://github.com/sponsors/ANG13T) or donating on [Buy Me a Coffee](https://www.buymeacoffee.com/angelinatsuboi) in order to fund my future projects. 

To check out my other works, visit my [GitHub profile](https://github.com/ANG13T).
