# kicad-symbols-footprints

## Usage

1. Import this library under your KiCad project as submodule.

```
git submodule https://github.com/nosuz/kicad-symbols-footprints.git nosuz-lib
```

2. Import symbols and footprints in project library from KiCad Preference menu.

## Component symbols and footprints

| Symbol             | Description                                                               | aliases                                                                   | footprint                   |
| ------------------ | ------------------------------------------------------------------------- | ------------------------------------------------------------------------- | --------------------------- |
| ESP32-S3-WROOM-1   | ESP32-S3 module                                                           |                                                                           | ESP32-S3-WROOM-1            |
| ESP32-S3-MINI-1    | ESP32-S3 module                                                           |                                                                           | ESP32-S3-MINI-1             |
|                    | AAx4 Battery Folder                                                       |                                                                           | BH-341-2P                   |
| SHT4x              | Relative Humidity and Temperature Sensor                                  | SHT40, SHT41, SHT45                                                       | SHT4x                       |
| TouchPad           | Capacitance touch sensor                                                  |                                                                           | Touch-Pad_10mm              |
| ESP32-WROOM-32E    | ESP32 module                                                              |                                                                           | ESP32-WROOM-32E             |
| ESP32-MINI-1       | ESP32 module                                                              |                                                                           | ESP32-MINI-1                |
| NJU7223DL1-xx      | Linear regulator                                                          | NJU7223DL1-18, NJU7223DL1-25, NJU7223DL1-30, NJU7223DL1-33, NJU7223DL1-50 | TO-252-3-L1                 |
| LP38690DTx         | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, SOT-252 pacjage         | LP38690DTX-3.3/NOPB                                                       | TO-252-3-L1                 |
| LP38690SDx         | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, WSON-6 package          | LP38690SDX-3.3/NOPB                                                       | WSON-6                      |
| USB_Type-C         | USB Type-C socket                                                         |                                                                           | 5077CR-16SMC2-BK-TR         |
| USB_Type-C         | USB Type-C socket                                                         |                                                                           | GT-USB-9047A                |
| ESP32-C3-WROOM-02  | ESP32-C3 module                                                           |                                                                           | ESP32-C3-WROOM-02           |
| ESP32-C3-MINI-1    | ESP32-C3 module                                                           |                                                                           | ESP32-C3-MINI-1             |
| SLIDE_SWITCH_2x2   | Slide Switch 2x2                                                          | IS-2235-G                                                                 | IS-2235-G                   |
| Logo_image         | My logo image                                                             |                                                                           | Icon_Nosuz                  |
| NJM2845DL1         | Linear regulator                                                          | NJM2845DL1-33, NJM2845DL1-05                                              | TO-252-3-L1                 |
| FT231XS            | USB-Serial converter                                                      |                                                                           | SSOP-20_FT231X              |
| OSxx1608           | 1608 LED                                                                  | OSYG1608, OSYL1608, OSTG1608, OSHR1608, OSOR1608, OSBL1608, OSWT1608      | 1608_OSxx1608               |
| IRLML6402          | P-ch MOS FET                                                              |                                                                           | SOT-23_IRLML6402            |
|                    | Barrel Jack 2.1mm                                                         |                                                                           | BarrelJack_MJ-179PH         |
|                    | Schottky diode                                                            |                                                                           | Diode_SS2040FL              |
|                    | capacitor                                                                 |                                                                           | C_2012                      |
|                    | capacitor                                                                 |                                                                           | C_2012_Large                |
|                    | capacitor                                                                 |                                                                           | C_1608_0603                 |
|                    | capacitor                                                                 |                                                                           | C_1005_0402                 |
|                    | register                                                                  |                                                                           | R_1608                      |
|                    | capacitor                                                                 |                                                                           | R_1005_0402                 |
| ADT7410            | I2C Temperature Sensor                                                    |                                                                           | SOIC_N-8                    |
| ADT7310            | SPI Temperature Sensor                                                    |                                                                           | SOIC_N-8                    |
| SHTC3              | I2C Temperature Sensor                                                    |                                                                           | SHTC3                       |
|                    | XH terminal post 2P                                                       |                                                                           | B2B-XH-A                    |
| USB_Type-C_Power   | USB Type-C Power only socket                                              |                                                                           | UJC-HP-3-SMT-TR             |
|                    | THT Cement resistance SQP 5W                                              |                                                                           | R_THT_SQP5W                 |
| TPS740xx           | 600mA CMOS LDO Regulator                                                  | TPS74033SF5                                                               | SOT-23-5L                   |
| AP2112M            | 600mA LDO Regulator                                                       | AP2112M-3.3TRG1                                                           | SO-8_AP2112M                |
| S-5851A            | 2-wire digital temperature sensor                                         | S-5851AAA-M6T1                                                            | SOT-23-6                    |
| AM23ESGW           | Two color (Red and Green) LED                                             | KM-23ESGC                                                                 | SOT-23_AM23ESGW             |
| LTST-C195KGKFKT    | Two color (Orange and Green) LED                                          |                                                                           | LTST-C195KGKFKT             |
| FA-238V            | SMD Crystals                                                              |                                                                           | FA-238V                     |
| KM-23ESGC          | Two color (Red and Green) LED                                             |                                                                           |                             |
| RP2040             | ARM Microcontroller used for Raspberry Pi Pico                            |                                                                           | QFN-56_RP2040               |
| CH32V203CxT8       | 32-bit Enhanced Low-Power RISC-V MCU – CH32V203                           |                                                                           | QFP-48_CH32Vx03CxT6         |
| CH32V103Cx         | 32-bit Enhanced Low-Power RISC-V MCU – CH32V103                           |                                                                           | QFP-48_CH32Vx03CxT6         |
| AP7333-XXSA        | 300mA, Low Quiescent Current, Fast Transient Low Dropout Linear Regulator | AP7333-33SA                                                               | SOT23_AP7333                |
| ME6217C33M5G       | 800mA Low Dropout Linear Regulator                                        |                                                                           | SOT-23-5L                   |
| TAXM12M4RLBDDT2T   | SMD Crystals 12MHz 20pF                                                   |                                                                           | SMD3225-4P_TAXM12M4RLBDDT2T |
| TVAF06-A020B-R     | Tacticle switch 2P                                                        |                                                                           | TVAF06-A020B-R              |
| K2-1822SA          | Tacticle switch 2P, 3.0mm x 2.5mm                                         |                                                                           | K2-1822SA                   |
| GT-TC029x-Hxxx-L1N | Tacticle switch 2P, 3.9mm x 2.9mm                                         |                                                                           | GT-TC029x-Hxxx-L1N          |
| TAEF-25xx          | Tacticle switch 2P, 6.0mm x 3.8mm                                         |                                                                           | TAEF-25xx                   |
| TS-06104           | Tacticle switch 4P                                                        |                                                                           | TS-06104                    |
| SKRPAxE010         | Tacticle switch 4P                                                        | SKRPABE010, SKRPACE010                                                    | SKRPAxE010                  |
| K2-1809SN          | Tacticle switch 4P, 3.5mm x 3.0mm                                         |                                                                           | K2-1809SN                   |
| TSC015x            | Tacticle switch 4P, 4.5mm x 4.5mm                                         |                                                                           | TSC015x                     |
| DTSM-6x            | Tacticle switch 4P, 6.2mm x 6.2mm                                         |                                                                           | DTSM-6x                     |
| 2MD1-T2-B4-M2-Q-N  | Toggle switch 2 x 3P                                                      |                                                                           | 2MD1-T2-B4-M2-Q-N           |
| HX4003             | Charge pump 5V 2.7V~5.5V 250mA DC-DC Converters                           |                                                                           | SOT-23-6                    |
