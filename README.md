# fpad KiCAD data

![fpad](images/fpad.png)

## Features

- Key switch (Cherry MX compatible) x16
- Rotary Encoder - Illuminated (RGB) x5
- JoyStick x1
- Display

## License

- MIT License

## Files

- fpad7.kicad_pcb: main board
- fpad_bottom.kicad_pcb: bottom plate
- fpad_top.kicad_pcb: top plate

## Versions

- latest (recommended)
  - in root directory
- rev1 (deprecated)
  - in [releases/rev1](releases/rev1)
  - [errata](releases/rev1/errata.md)

## BOM

| Component                             | Label        | LCSC     | remarks                                                     |
| ------------------------------------- | ------------ | -------- | ----------------------------------------------------------- |
| Capacitor 0.1u 0402                   | C1           | C307331  |                                                             |
| 1N4148WS Diode SOD-323 x 16           | D1 ~ D16     | C2128    |                                                             |
| SK6812MINI-E LED x 16                 | LED1 ~ LED16 | C5149201 |                                                             |
| SSD1306 OLED Display                  | OL1          |          |                                                             |
| Register 7.5kΩ 0402                   | R1           | C25918   |                                                             |
| Register 100kΩ 3216                   | R2           | C17900   |                                                             |
| Register 10kΩ 0402 x2                 | R3, R4       | C25744   |                                                             |
| Register 3.3kΩ 0402 x2                | R5, R6       | C25890   |                                                             |
| Rotary Encoder - Illuminated (RGB) x5 | S1 ~ S5      |          | https://www.sparkfun.com/products/15141                     |
| RKJXV122400R JoyStick                 | S6           |          | https://tech.alpsalpine.com/j/products/detail/RKJXV122400R/ |
| Kailh Switch Socket x16               | SW1 ~ SW16   | C2803348 | CherryMX Compatible                                         |
| Tactile Switch                        | SW17         |          | reset button for ProMicro                                   |
| Arduino ProMicro                      | U1           |          |                                                             |
| XL9555 I/O Expander                   | U2           | C609791  |                                                             |
| IS31FL3208A LED Driver                | U3           | C2940551 |                                                             |

## Issues

- [rev1/errata.md](releases/rev1/errata.md)

## External files

### 3D CONTENTCENTRAL

The following 3D models are obtained from [3D CONTENTCENTRAL](https://www.3dcontentcentral.com/).
They are not included in this repository due to license, so please obtain them on your own and place them in the following paths.

- [Keycap](https://www.3dcontentcentral.com/secure/download-model.aspx?catalogid=171&id=941483)
  - external/3dcontentcentral/Mx_Keycap.step
- [JoyStick](https://www.3dcontentcentral.com/secure/download-model.aspx?catalogid=171&id=1681961)
  - external/3dcontentcentral/User Library-RKJXV122400R.step
- [RotaryEncoder](https://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=630216)
  - external/3dcontentcentral/User Library-Rotary Encoder v21.STEP

### SnapEDA

SnapEDA files are provided under this license as described in the following [FAQ - SnapEDA](https://www.snapeda.com/about/FAQ/).

### kbd, SparkFun-KiCAD-Libraries

Comply with the original license
