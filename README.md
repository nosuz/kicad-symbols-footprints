# kicad-symbols-footprints

## Usage

1. Import this library under your KiCad project as submodule.

Note: the project to be import this library should be initialized by `git init` or `git clone`.

```
git submodule add https://github.com/nosuz/kicad-symbols-footprints.git nosuz-lib
```

2. Import symbols and footprints in project library from KiCad Preference menu.

## Component symbols and footprints

| Symbol                | Description                                                               | Footprint                   | Alias of           |
| --------------------- | ------------------------------------------------------------------------- | --------------------------- | ------------------ |
| **modules**           |                                                                           |                             |                    |
| ESP32-S3-WROOM-1      | ESP32-S3 module                                                           | ESP32-S3-WROOM-1            |                    |
| ESP32-S3-MINI-1       | ESP32-S3 module                                                           | ESP32-S3-MINI-1             |                    |
| ESP32-WROOM-32E       | ESP32 module                                                              | ESP32-WROOM-32E             |                    |
| EPS32-MINI-1          | ESP32 module                                                              | ESP32-MINI-1                |                    |
| ESP32-C3-WROOM-02     | ESP32-C3 module                                                           | ESP32-C3-WROOM-02           |                    |
| ESP32-C3-MINI-1       | ESP32-C3 module                                                           | ESP32-C3-MINI-1             |                    |
| Tang_Nano_9K          | Sipeed Tang Nano 9K FPGA module                                           | DIP-48_TangNano9K           |                    |
| Tang_Primer_20K       | Sipeed Tang Primer 20K FPGA module                                        | SODIMM_2013289-1_TYC        |                    |
| Tang_Primer_25K_J1    | Sipeed Tang Primer 25K FPGA module                                        | DF40C-60DS_HIROSE           |                    |
| Tang_Primer_25K_J2    | Sipeed Tang Primer 25K FPGA module                                        | DF40C-60DS_HIROSE           |                    |
| **cpu**               |                                                                           |                             |                    |
| RP2040                | ARM Microcontroller used for Raspberry Pi Pico                            | QFN-56_RP2040               |                    |
| CH32V203CxT6          | 32-bit Enhanced Low-Power RISC-V MCU - CH32V203                           | QFP-48_CH32Vx03CxT6         |                    |
| CH32V103Cx            | 32-bit Enhanced Low-Power RISC-V MCU - CH32V103                           | QFP-48_CH32Vx03CxT6         |                    |
| DCJ11                 | PDP-11 microprocessor J-11                                                | DIP-60_DCJ11                |                    |
| **memory**            |                                                                           |                             |                    |
| CY62167E              | 16-Mbit (1Mx16/2Mx8) Static RAM                                           | TSOP-48_12x18.4             |                    |
| AS6C3216A             | 32M Bits(2Mx16/4Mx8 Switchable) SRAM                                      | TSOP-I-48_AS6C3216A         |                    |
|                       | W25Q128, 128M bits SPI FLASH memory, SPI/QUAD, SOIC-8                     | SOIC-8_W25Q128JVS           |                    |
| **interface devices** |                                                                           |                             |                    |
| CH340N                | USB serial convertor                                                      | SOP-8_CH340N                |                    |
| FT231XS               | USB-Serial converter                                                      | SSOP-20_FT231X              |                    |
| FT245RN               | FTDI USB FIFO parallele interface                                         | SSOP-28_FTDI                |                    |
| FT245R                | FTDI USB FIFO parallele interface                                         | SSOP-28_FTDI                | FT245RN            |
| CH224K                | USB PD sink controller                                                    | ESSOP-10_CH224K             |                    |
| **sensors**           |                                                                           |                             |                    |
| SH4x                  | Relative Humidity and Temperature Sensor                                  | SHT4x                       |                    |
| SHT40                 | Relative Humidity and Temperature Sensor                                  | SHT4x                       | SH4x               |
| SHT41                 | Relative Humidity and Temperature Sensor                                  | SHT4x                       | SH4x               |
| SHT45                 | Relative Humidity and Temperature Sensor                                  | SHT4x                       | SH4x               |
| ADT7310               | SPI Temperature Sensor                                                    | SOIC_N-8                    |                    |
| ADT7410               | I2C Temperature Sensor                                                    | SOIC_N-8                    |                    |
| SHTC3                 | I2C Temperature Sensor                                                    | SHTC3                       |                    |
| S-5851A               | 2-wire digital temperature sensor                                         | SOT-23-6                    |                    |
| S-5851AAA-M6T1        | 2-wire digital temperature sensor                                         | SOT-23-6                    | S-5851A            |
| TouchPad              | Capacitance touch sensor                                                  | Touch-Pad_10mm              |                    |
| **logic ICs**         |                                                                           |                             |                    |
| 74HC04                | Hex Inverter                                                              |                             |                    |
| 74VHC04               | Hex Inverter                                                              |                             | 74HC04             |
| 74HC08                | Quad 2-input And                                                          |                             |                    |
| 74VHC08               | Quad 2-input And                                                          |                             | 74HC08             |
| 74HC21                | Dual 4-input AND                                                          |                             |                    |
| 74VHC21               | Dual 4-input AND                                                          |                             | 74HC21             |
| 74HC32                | Quad 2-input OR                                                           |                             |                    |
| 74VHC32               | Quad 2-input OR                                                           |                             | 74HC32             |
| 74LVC138              | 3-Line to 8-Line Decoders Demultiplexers                                  |                             |                    |
| SN74LVC138ADR         | 3-Line to 8-Line Decoders Demultiplexers                                  | SOIC-16_SN74LVC138ADR       | 74LVC138           |
| 74HC139               | Dual Decoder 1 of 4 Active low outputs                                    |                             |                    |
| 74VHC139              | Dual Decoder 1 of 4 Active low outputs                                    |                             | 74HC139            |
| SN74LVC245A           | Octal Bus Transceiver With 3-State Outputs                                |                             |                    |
| SN74LVC245APW         | Octal Bus Transceiver With 3-State Outputs                                | TSSOP-20_SN74LVC245APW      | SN74LVC245A        |
| SN74LVC245AN          | Octal Bus Transceiver With 3-State Outputs, DIP                           | DIP-20_TI-N                 | SN74LVC245A        |
| SN74LVC245ANS         | Octal Bus Transceiver With 3-State Outputs, SOIC                          | SOIC-20_TI-NS               | SN74LVC245A        |
| 74HC574               | 8-bit Latch 3-state outputs                                               |                             |                    |
| 74VHC574              | 8-bit Latch 3-state outputs                                               |                             | 74HC574            |
| SN74CB3T3245          | 8-Bit FET Bus Switch with 5V-Tolerant Level Shifter                       |                             |                    |
| SN74CB3T3245DW        | 8-Bit FET Bus Switch with 5V-Tolerant Level Shifter                       | SOIC-20_SN74CB3T3245        | SN74CB3T3245       |
| 74AHC1G04             | Single Inverter Gate                                                      |                             |                    |
| SN74AHC1G04DBVR       | Single Inverter Gate                                                      | SOT-23-5_TI                 | 74AHC1G04          |
| 74AHC1G07             | Buffer/Driver with Open Drain, single Gate                                |                             |                    |
| 74AHC1G07GV-P         | Buffer/Driver with Open Drain, single Gate                                | TSOT-23-5_74AHC1G07GV       | 74AHC1G07          |
| 74VLC1T45W            | Dual power supply Single bit Buffer                                       | SOT-26_74LVC1T45            |                    |
| TC7S32                | 2-Input OR Gate, Single gate                                              |                             |                    |
| TC7S32F               | 2-Input OR Gate, Single gate                                              | SSOP5_TC7S32F               | TC7S32             |
| TC7S32FU              | 2-Input OR Gate, Single gate                                              | SSOP5_TC7S32FU              | TC7S32             |
| TXB0104D              | 4-Bit Bidirectional Voltage-Level Translator, SOIC                        | SOIC-14_TXB0104             |                    |
| TXB0104PW             | 4-Bit Bidirectional Voltage-Level Translator, TSSOP                       | TSSOP-14_TXB0104            | TXB0104D           |
| **power devices**     |                                                                           |                             |                    |
| NJU7223DL1-xx         | Linear regulator                                                          | TO-252-3-L1                 |                    |
| NJU7223DL1-18         | Linear regulator                                                          | TO-252-3-L1                 | NJU7223DL1-xx      |
| NJU7223DL1-25         | Linear regulator                                                          | TO-252-3-L1                 | NJU7223DL1-xx      |
| NJU7223DL1-30         | Linear regulator                                                          | TO-252-3-L1                 | NJU7223DL1-xx      |
| NJU7223DL1-33         | Linear regulator                                                          | TO-252-3-L1                 | NJU7223DL1-xx      |
| NJU7223DL1-50         | Linear regulator                                                          | TO-252-3-L1                 | NJU7223DL1-xx      |
| LP38690DTx            | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, SOT-252 package         | TO-252-3-L1                 |                    |
| LP38690DTX-3.3/NOPB   | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, SOT-252 package         | TO-252-3-L1                 | LP38690DTx         |
| LP38690SDx            | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, WSON-6 package          | WSON-6                      |                    |
| LP38690SDX-3.3/NOPB   | Linear regulator, Vin max. 10V, Iout 1A, Iq 55uA, WSON-6 package          | WSON-6                      | LP38690SDx         |
| NJM2845DL1            | Linear regulator                                                          | TO-252-3-L1                 |                    |
| NJM2845DL1-05         | Linear regulator                                                          | TO-252-3-L1                 | NJM2845DL1         |
| NJM2845DL1-33         | Linear regulator                                                          | TO-252-3-L1                 | NJM2845DL1         |
| TPS740xx              | 600mA CMOS LDO Regulator                                                  | SOT-23-5L                   |                    |
| TPS74033SF5           | 600mA CMOS LDO Regulator                                                  | SOT-23-5L                   | TPS740xx           |
| AP2112M               | 600mA LDO Regulator                                                       | SO-8_AP2112M                |                    |
| AP2112M-3.3TRG1       | 600mA LDO Regulator                                                       | SO-8_AP2112M                | AP2112M            |
| AP2127N-xx            | 300mA LOD Regulator, SOT-23                                               | SOT-23_AP2127N              |                    |
| AP2127N-1.8           | 1.8V 300mA LOD Regulator, SOT-23                                          | SOT-23_AP2127N              | AP2127N-xx         |
| ME6217C33M5G          | 800mA Low Dropout Linear Regulator                                        | SOT-23-5L                   |                    |
| AP7333-XXSA           | 300mA, Low Quiescent Current, Fast Transient Low Dropout Linear Regulator | SOT23_AP7333                |                    |
| AP7333-33SA           | 300mA, Low Quiescent Current, Fast Transient Low Dropout Linear Regulator | SOT23_AP7333                | AP7333-XXSA        |
| HX4002                | Charge Pump DC/DC Converter                                               | SOT-23-6                    |                    |
|                       | AAx4 Battery Folder                                                       | BH-341-2P                   |                    |
| **MOS FETs**          |                                                                           |                             |                    |
| IRLML6402             | P-ch MOS FET                                                              | SOT-23_IRLML6402            |                    |
| SI3407                | P-ch MOS FET, Vgs(th -1.4V)                                               | SOT-23_SI3407               |                    |
| IRLML6344             | N-ch MOS FET                                                              | SOT-23_IRLML6402            |                    |
| **LEDs**              |                                                                           |                             |                    |
| OSxx1608              | 1608 LED                                                                  | 1608_OSxx1608               |                    |
| OSBL1608              | 1608 LED                                                                  | 1608_OSxx1608               | OSxx1608           |
| OSHR1608              | 1608 LED                                                                  | 1608_OSxx1608               | OSxx1608           |
| OSOR1608              | 1608 LED                                                                  | 1608_OSxx1608               | OSxx1608           |
| OSTG1608              | 1608 LED                                                                  | 1608_OSxx1608               | OSxx1608           |
| OSWT1608              | 1608 LED                                                                  | 1608_OSxx1608               | OSxx1608           |
| OSYG1608              | 1608 LED                                                                  | 1608_OSxx1608               | OSxx1608           |
| OSYL1608              | 1608 LED                                                                  | 1608_OSxx1608               | OSxx1608           |
| OSXXXX313XA-5V        | LED with R, 3 mm                                                          | OSXXXX313XA-5V              | LED_R              |
| AM23ESGW              | Two color (Red and Green) LED                                             | SOT-23_AM23ESGW             |                    |
| KM-23ESGC             | Two color (Red and Green) LED                                             | SOT-23_AM23ESGW             | AM23ESGW           |
| LTST-C195KGKFKT       | Two color (Orange and Green) LED                                          | LTST-C195KGKFKT             |                    |
| LED                   |                                                                           | LED_6mm                     |                    |
| LED                   |                                                                           | LED_4mm                     |                    |
| LED_R                 | LED with R                                                                |                             |                    |
| ORH-x36x              | LED, 1608                                                                 | ORH-x36x                    |                    |
| ORH-YG36A             | LED, 1608                                                                 | ORH-x36x                    | ORH-x36x           |
| ORH-R36A              | LED, 1608                                                                 | ORH-x36x                    | ORH-x36x           |
| SM412301N             | Red 7 segments LED display                                                | SM412301N                   |                    |
| **connectors**        |                                                                           |                             |                    |
| USB_Type-C            | USB Type-C socket                                                         | 5077CR-16SMC2-BK-TR         |                    |
| 5077CR-16SMC2-BK-TR   | USB Type-C socket                                                         | 5077CR-16SMC2-BK-TR         | USB_Type-C         |
| GT-USB-9047A          | USB Type-C socket                                                         | GT-USB-9047A                | USB_Type-C         |
| TYPEC-304-ACP16       | USB Type-C socket, 5077CR-16SMC2-BK-TR compatible?                        | TYPEC-304-ACP16             | USB_Type-C         |
| USB_Type-C_Power      | USB Type-C Power only socket                                              | UJC-HP-3-SMT-TR             |                    |
| A295-CTRPB-1          | USB Type-C Power only socket                                              | A295-CTRPB-1                |                    |
| USB-micro-B           | USB Micro B connector                                                     | ZX62R-B-5P                  | USB-micro-B        |
| ZX62R-B-5P            | USB Micro B connector                                                     | ZX62R-B-5P                  |                    |
|                       | XH terminal post 2P, Top type                                             | B2B-XH-A                    |                    |
|                       | XH terminal post 2P, Side type                                            | S2B-XH-A                    |                    |
|                       | XH terminal post 4P, Side type                                            | S4B-XH-A                    |                    |
| **tactile switches**  |                                                                           |                             |                    |
| Tactile_Switch_2P     | Tacticle switch 2P                                                        | TVAF06-A020B-R              |                    |
| TVAF06-A020B-R        | Tacticle switch 2P                                                        | TVAF06-A020B-R              | Tactile_Switch_2P  |
| GT-TC029x-Hxxx-L1N    | Tacticle switch 2P, 3.9mm x 2.9mm                                         | GT-TC029x-Hxxx-L1N          | Tactile_Switch_2P  |
| K2-1822SA             | Tacticle switch 2P, 3.0mm x 2.5mm                                         | K2-1822SA                   | Tactile_Switch_2P  |
| SKSTAAE010            | Tacticle switch 2P, 8.5mm x 8.5mm                                         | SKSTAXE010                  | Tactile_Switch_2P  |
| TAEF-25xx             | Tacticle switch 2P, 6.0mm x 3.8mm                                         | TAEF-25xx                   | Tactile_Switch_2P  |
| TVBP06-B043C          | Tacticle switch 2P, THT                                                   | TVBP06-B043C                | Tactile_Switch_2P  |
| Tactile_Switch_4P     | Tacticle switch 4P                                                        |                             |                    |
| TS-06104              | Tacticle switch 4P                                                        | TS-06104                    | Tactile_Switch_4P  |
| SKRPABE010            | Tacticle switch 4P                                                        | SKRPAxE010                  | Tactile_Switch_4P  |
| SKRPACE010            | Tacticle switch 4P                                                        | SKRPAxE010                  | Tactile_Switch_4P  |
| DTS-6x                | Tacticle switch 4P THT, 6.2mm x 6.2mm                                     | DTS-6-V                     | Tactile_Switch_4P  |
| DTSM-6x               | Tacticle switch 4P SMD, 6.2mm x 6.2mm                                     | DTSM-6x                     | Tactile_Switch_4P  |
| GT-TC149A-H090-L1     | Tacticle switch 4P, 12mm x 12mm                                           | GT-TC149X-HXXX-LX           | Tactile_Switch_4P  |
| K2-1809SN             | Tacticle switch 4P, 3.5mm x 3.0mm                                         | K2-1809SN                   | Tactile_Switch_4P  |
| TSC015x               | Tacticle switch 4P, 4.5mm x 4.5mm                                         | TSC015x                     | Tactile_Switch_4P  |
| **other switches**    |                                                                           |                             |                    |
| SLIDE_SWITCH_2x2      | Slide Switch 2x2                                                          | IS-2235-G                   |                    |
| IS-2235-G             | Slide Switch 2x2                                                          | IS-2235-G                   | SLIDE_SWITCH_2x2   |
| Toggle_Switch_2x3P    | Toggle switch 2 circuit                                                   |                             |                    |
| 2MD1-T2-B4-M2-Q-N     | Toggle switch 2 x 3P                                                      | 2MD1-T2-B4-M2-Q-N           | Toggle_Switch_2x3P |
| **Cap and Register**  |                                                                           |                             |                    |
|                       | capacitor                                                                 | C_2012                      |                    |
|                       | capacitor                                                                 | C_2012_Large                |                    |
|                       | capacitor                                                                 | C_1608                      |                    |
|                       | capacitor                                                                 | C_1005                      |                    |
|                       | capacitor                                                                 | C_1005_0402                 |                    |
|                       | capacitor                                                                 | C_1608_0603                 |                    |
|                       | Electric capacitor, D = 5 mm                                              | CP_THT_D5                   |                    |
|                       | register                                                                  | R_1608                      |                    |
|                       | register                                                                  | R_1005                      |                    |
|                       | register                                                                  | R_1005_0402                 |                    |
|                       | register                                                                  | R_1608_0603                 |                    |
|                       | THT Cement resistance SQP 5W                                              | R_THT_SQP5W                 |                    |
| **other devices**     |                                                                           |                             |                    |
|                       | Barrel Jack 2.1mm                                                         | BarrelJack_MJ-179PH         |                    |
|                       | Schottky diode                                                            | Diode_SS2040FL              |                    |
| TAXM12M4RLBDDT2T      | SMD Crystals 12MHz 20pF                                                   | SMD3225-4P_TAXM12M4RLBDDT2T |                    |
| FA-238V               | SMD Crystal                                                               | FA-238V                     |                    |
|                       | 3P IC socket for crystal unit                                             | Y_3P                        |                    |
|                       | SWPA inductor                                                             | SWPA6028Sxxx                |                    |
|                       | Jumper ジャン太                                                           | jumper_XX-2                 |                    |
|                       | Raspberry Pi HAT connector (40P) and mechanical holes                     | Raspberry_Pi_HAT_conn       |                    |
| Logo_image            | My logo image                                                             | Icon_Nosuz                  |                    |
