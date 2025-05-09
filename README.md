# LiPo Charger & Protection Board with 5V Output

PLACEHOLDER FOR IMAGE

## Overview

This project is a custom-designed Lithium Polymer battery charging and protection circuit with a regulated 5V output. Perfect for powering your portable electronics projects, this board offers a complete power management solution in a compact form factor.

## Features

- **LiPo Battery Charging**: Safe charging circuit for single-cell LiPo batteries
- **Battery Protection**: Overcharge, over-discharge, and short-circuit protection
- **5V Regulated Output**: Clean, stable 5V output regardless of battery voltage
- **Compact Design**: Minimized footprint for easy integration into projects
- **Status Indicators**: LED indicators for charging/full charge
- **USB Input**: Standard USB-C connector for charging and power input

## Technical Specifications

- **Input Voltage**: 5V DC via USB
- **Battery**: Single-cell 3.7V Lithium Polymer
- **Charging Current**: 500mA (configurable)
- **Output Voltage**: 5V ±0.1V
- **Maximum Output Current**: 2A continuous
- **Protection Features**:
  - Overcharge cutoff: 4.2V
  - Over-discharge cutoff: 2.8V
  - Short-circuit protection

## PCB Details

- **Dimensions**: XX mm × XX mm
- **Layers**: 2-layer PCB
- **Designed with**: KiCad 9.0

## Getting Started

### Bill of Materials

| Designator |                Footprint                | Quantity |      Value      | LCSC Part # |
|------------|-----------------------------------------|----------|-----------------|-------------|
| C1, C2     |0603                                     |2         |10uF             |C19702       |
| C3         |0603                                     |1         |0.1uF            |C14663       |
| C4, C5     |0603                                     |2         |22uF             |C59461       |
| D1         |0603                                     |1         |RED              |C965799      |
| D2         |0603                                     |1         |GREEN            |C19171301    |
| D3         |D_SMA-SMB_Universal_Handsoldering        |1         |SS34             |C908680      |
| D4, D5     |D_SMA-SMB_Universal_Handsoldering        |2         |B340A            |C85098       |
| D6         |Nexperia_CFP3_SOD-123W                   |1         |5.1v             |C19077401    |
| J1         |JST_S2B-XH-A                             |1         |S2B-XH-A         |C157931      |
| J2         |Usb-C                                    |1         |USB_C_USB2.0_14P |C2988369     |
| L1         |WE-PD2_1054                              |1         |22uH             |C436465      |
| Q1, Q2     |SOT-23_Handsoldering                     |2         |SI2300A          |C347480      |
| R1, R5     |0603                                     |2         |2k               |C2907022     |
| R10        |0603                                     |1         |73.2k            |C2933257     |
| R11, R7    |0603                                     |2         |10k              |C98220       |
| R2, R3     |0603                                     |2         |1k               |C103198      |
| R4         |0603                                     |1         |100              |C3016239     |
| R6         |0603                                     |1         |0.4              |C5126047     |
| R8, R9     |0603                                     |2         |5.1k             |C3016319     |
| SW1        |SlideSwitch                              |1         |SK12D07VG4       |C393937      |
| U1         |SOIC-8                                   |1         |TP4056-42-ESOP8  |C725790      |
| U2         |SOT-23-6                                 |1         |MT3608           |C84817       |
| U3         |TSOT-23-6_HandSoldering                  |1         |FM2113           |C2832124     |


## Usage

1. Connect a LiPo battery to the BAT+ and BAT- terminals
2. Power the board via the USB connector
3. Connect your load to the 5V and GND output terminals
4. The charging indicator LED will illuminate red during charging and turn green when complete

## License

This project is released under the [MIT License](LICENSE).

## Contributing

Contributions to improve the design are welcome! Please feel free to submit issues or pull requests.

## Contact

If you have any questions or suggestions about this project, please open an issue on GitHub or contact me at Devin.Marx3@gmail.com.

---

*This is my first KiCad project! I appreciate any feedback or suggestions for improvement.*
