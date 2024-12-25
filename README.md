# kicad-symbols-footprints

## Usage

1. Import this library under your KiCad project as submodule.

```
git submodule https://github.com/nosuz/kicad-symbols-footprints.git nosuz-lib
```

2. Import symbols and footprints in project library from KiCad Preference menu.

## Component symbols and footprints

| Symbol              | Description                                                       | Footprint            | Alias of          |
| ------------------- | ----------------------------------------------------------------- | -------------------- | ----------------- |
| ESP32-S3-WROOM-1    | ESP32-S3 module                                                   | ESP32-S3-WROOM-1     |                   |
| ESP32-S3-MINI-1     | ESP32-S3 module                                                   | ESP32-S3-MINI-1      |                   |
|                     | AAx4 Battery Folder                                               | BH-341-2P            |                   |
| SH4x                | Relative Humidity and Temperature Sensor                          | SHT4x                |                   |
| SHT40               | Relative Humidity and Temperature Sensor                          | SHT4x                | SH4x              |
| SHT41               | Relative Humidity and Temperature Sensor                          | SHT4x                | SH4x              |
| SHT45               | Relative Humidity and Temperature Sensor                          | SHT4x                | SH4x              |
| TouchPad            | Capacitance touch sensor                                          | Touch-Pad_10mm       |                   |
| ESP32-WROOM-32E     | ESP32 module                                                      | ESP32-WROOM-32E      |                   |
| EPS32-MINI-1        | ESP32 module                                                      | ESP32-MINI-1         |                   |
| NJU7223DL1-xx       | Linear regulator                                                  | TO-252-3-L1          |                   |
| NJU7223DL1-18       | Linear regulator                                                  | TO-252-3-L1          | NJU7223DL1-xx     |
| NJU7223DL1-25       | Linear regulator                                                  | TO-252-3-L1          | NJU7223DL1-xx     |
| NJU7223DL1-30       | Linear regulator                                                  | TO-252-3-L1          | NJU7223DL1-xx     |
| NJU7223DL1-33       | Linear regulator                                                  | TO-252-3-L1          | NJU7223DL1-xx     |
| NJU7223DL1-50       | Linear regulator                                                  | TO-252-3-L1          | NJU7223DL1-xx     |
| LP38690DTx          | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, SOT-252 package | TO-252-3-L1          |                   |
| LP38690DTX-3.3/NOPB | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, SOT-252 package | TO-252-3-L1          | LP38690DTx        |
| LP38690SDx          | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, WSON-6 package  | WSON-6               |                   |
| LP38690SDX-3.3/NOPB | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, WSON-6 package  | WSON-6               | LP38690SDx        |
| USB_Type-C          | USB Type-C socket                                                 | 5077CR-16SMC2-BK-TR  |                   |
| 5077CR-16SMC2-BK-TR | USB Type-C socket                                                 | 5077CR-16SMC2-BK-TR  | USB_Type-C        |
| ESP32-C3-WROOM-02   | ESP32-C3 module                                                   | ESP32-C3-WROOM-02    |                   |
| ESP32-C3-MINI-1     | ESP32-C3 module                                                   | ESP32-C3-MINI-1      |                   |
| SLIDE_SWITCH_2x2    | Slide Switch 2x2                                                  | IS-2235-G            |                   |
| IS-2235-G           | Slide Switch 2x2                                                  | IS-2235-G            | SLIDE_SWITCH_2x2  |
| Tactile_Switch_2P   | Tacticle switch 2P                                                | TVAF06-A020B-R       |                   |
| TVAF06-A020B-R      | Tacticle switch 2P                                                | TVAF06-A020B-R       | actile_Switch_2P  |
| Tactile_Switch_4P   | Tacticle switch 4P                                                |                      |                   |
| TS-06104            | Tacticle switch 4P                                                | TS-06104             | Tactile_Switch_4P |
| SKRPABE010          | Tacticle switch 4P                                                | SKRPAxE010           | Tactile_Switch_4P |
| SKRPACE010          | Tacticle switch 4P                                                | SKRPAxE010           | Tactile_Switch_4P |
| DTS-6x              | Tacticle switch 4P                                                | DTS-6-V              | Tactile_Switch_4P |
| Logo_image          | My logo image                                                     | Icon_Nosuz           |                   |
| NJM2845DL1          | Linear regulator                                                  | TO-252-3-L1          |                   |
| NJM2845DL1-05       | Linear regulator                                                  | TO-252-3-L1          | NJM2845DL1        |
| NJM2845DL1-33       | Linear regulator                                                  | TO-252-3-L1          | NJM2845DL1        |
| FT231XS             | USB-Serial converter                                              | SSOP-20_FT231X       |                   |
| OSxx1608            | 1608 LED                                                          | 1608_OSxx1608        |                   |
| OSBL1608            | 1608 LED                                                          | 1608_OSxx1608        | OSxx1608          |
| OSHR1608            | 1608 LED                                                          | 1608_OSxx1608        | OSxx1608          |
| OSOR1608            | 1608 LED                                                          | 1608_OSxx1608        | OSxx1608          |
| OSTG1608            | 1608 LED                                                          | 1608_OSxx1608        | OSxx1608          |
| OSWT1608            | 1608 LED                                                          | 1608_OSxx1608        | OSxx1608          |
| OSYG1608            | 1608 LED                                                          | 1608_OSxx1608        | OSxx1608          |
| OSYL1608            | 1608 LED                                                          | 1608_OSxx1608        | OSxx1608          |
| IRLML6402           | P-ch MOS FET                                                      | SOT-23_IRLML6402     |                   |
| SI3407              | P-ch MOS FET, Vgs(th -1.4V)                                       | SOT-23_SI3407        |                   |
|                     | Barrel Jack 2.1mm                                                 | BarrelJack_MJ-179PH  |                   |
|                     | Schottky diode                                                    | Diode_SS2040FL       |                   |
|                     | capacitor                                                         | C_2012               |                   |
|                     | capacitor                                                         | C_2012_Large         |                   |
|                     | capacitor                                                         | C_1608               |                   |
|                     | capacitor                                                         | C_1005               |                   |
|                     | register                                                          | R_1608               |                   |
|                     | register                                                          | R_1005               |                   |
| ADT7310             | SPI Temperature Sensor                                            | SOIC_N-8             |                   |
| ADT7410             | I2C Temperature Sensor                                            | SOIC_N-8             |                   |
| SHTC3               | I2C Temperature Sensor                                            | SHTC3                |                   |
|                     | XH terminal post 2P                                               | B2B-XH-A             |                   |
| USB_Type-C_Power    | USB Type-C Power only socket                                      | UJC-HP-3-SMT-TR      |                   |
|                     | THT Cement resistance SQP 5W                                      | R_THT_SQP5W          |                   |
| TPS740xx            | 600mA CMOS LDO Regulator                                          | SOT-23-5L            |                   |
| TPS74033SF5         | 600mA CMOS LDO Regulator                                          | SOT-23-5L            | TPS740xx          |
| AP2112M             | 600mA LDO Regulator                                               | SO-8_AP2112M         |                   |
| AP2112M-3.3TRG1     | 600mA LDO Regulator                                               | SO-8_AP2112M         | AP2112M           |
| S-5851A             | 2-wire digital temperature sensor                                 | SOT-23-6             |                   |
| S-5851AAA-M6T1      | 2-wire digital temperature sensor                                 | SOT-23-6             | S-5851A           |
| AM23ESGW            | Two color (Red and Green) LED                                     | SOT-23_AM23ESGW      |                   |
| KM-23ESGC           | Two color (Red and Green) LED                                     | SOT-23_AM23ESGW      | AM23ESGW          |
| LTST-C195KGKFKT     | Two color (Orange and Green) LED                                  | LTST-C195KGKFKT      |                   |
| FA-238V             | SMD Crystal                                                       | FA-238V              |                   |
| RP2040              | ARM Microcontroller used for Raspberry Pi Pico                    | QFN-56_RP2040        |                   |
| USB-micro-B         | USB Micro B connector                                             | ZX62R-B-5P           | USB-micro-B       |
| ZX62R-B-5P          | USB Micro B connector                                             | ZX62R-B-5P           |                   |
| DCJ11               | PDP-11 microprocessor J-11                                        | DIP-60_DCJ11         |                   |
| CY62167E            | 16-Mbit (1Mx16/2Mx8) Static RAM                                   | TSOP-48_12x18.4      |                   |
| LED                 |                                                                   | LED_6mm              |                   |
| 74HC04              | Hex Inverter                                                      |                      |                   |
| 74VHC04             | Hex Inverter                                                      |                      | 74HC04            |
| 74HC08              | Quad 2-input And                                                  |                      |                   |
| 74VHC08             | Quad 2-input And                                                  |                      | 74HC08            |
| 74HC139             | Dual Decoder 1 of 4 Active low outputs                            |                      |                   |
| 74VHC139            | Dual Decoder 1 of 4 Active low outputs                            |                      | 74HC139           |
| 74HC21              | Dual 4-input AND                                                  |                      |                   |
| 74VHC21             | Dual 4-input AND                                                  |                      | 74HC21            |
| 74HC32              | Quad 2-input OR                                                   |                      |                   |
| 74VHC32             | Quad 2-input OR                                                   |                      | 74HC32            |
| 74HC574             | 8-bit Latch 3-state outputs                                       |                      |                   |
| 74VHC574            | 8-bit Latch 3-state outputs                                       |                      | 74HC574           |
| Tang_Primer_20K     | Sipeed Tang Primer 20K FPGA module                                | SODIMM_2013289-1_TYC |                   |
| Tang_Primer_25K_J1  | Sipeed Tang Primer 25K FPGA module                                | DF40C-60DS_HIROSE    |                   |
| Tang_Primer_25K_J2  | Sipeed Tang Primer 25K FPGA module                                | DF40C-60DS_HIROSE    |                   |
| FT245RN             | FTDI USB FIFO parallele interface                                 | SSOP-28_FTDI         |                   |
| AS6C3216A           | 32M Bits(2Mx16/4Mx8 Switchable) SRAM                              | TSOP-I-48_AS6C3216A  |                   |
| SN74CB3T3245        | 8-Bit FET Bus Switch with 5V-Tolerant Level Shifter               |                      |                   |
| SN74CB3T3245DW      | 8-Bit FET Bus Switch with 5V-Tolerant Level Shifter               | SOIC-20_SN74CB3T3245 | SN74CB3T3245      |
| TC7S32              | 2-Input OR Gate, Single gate                                      |                      |                   |
| TC7S32F             | 2-Input OR Gate, Single gate                                      | SSOP5_TC7S32F        | TC7S32            |
| TC7S32FU            | 2-Input OR Gate, Single gate                                      | SSOP5_TC7S32FU       | TC7S32            |
|                     | Electric capacitor, D = 5 mm                                      | CP_THT_D5            |                   |
|                     | 3P IC socket for crystal unit                                     | Y_3P                 |                   |
|                     |                                                                   |                      |                   |
