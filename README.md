# Wisconsin Oscillator

Small, inexpensive, low power device for powering ion guiding devices.

The Wisconsin Oscillator has been published in the Journal of the American Society for Mass Spectrometry. Please read our article to learn more about the motivation behind the Wisconsin Oscillator and to see examples the circuit being used to guide ions through a custom spectrometer.

> [The Wisconsin Oscillator: A Low-Cost Circuit for Powering Ion Guides, Funnels, and Traps](https://doi.org/10.1021/jasms.1c00247) Kregel, S. J.; Thompson, B. J.; Nathanson, G. M.; and Bertram, T. H. _Journal of the Americian Socieity for Mass Spectrometry_ (2021)

## PCB

Printed circuit board fabrication files can be found in the gerber directory.
PCB images generated with [tracespace](https://github.com/tracespace/tracespace) follow.

<img src="./Wisconsin Oscillator-.top.svg" width="100%"/>
<img src="./Wisconsin Oscillator-.bottom.svg" width="100%"/>

## Bill of Materials

C1 and L1/L2 can be changed to control the amplitude and frequency of the oscillator, as described in the next section.
All other parts are listed below.

| reference         | manufacturer | part number                       |  vendors |
| :---------------- | :----------- | :-------------------------------- | :------- |
| C2                | various      | 2.2 pF ceramic, 1kV, 1206 package | [Mouser](https://www.mouser.com/ProductDetail/Walsin/1206N2R2C102CT?qs=ZrPdAQfJ6DMo6D%2FvZxBqfw%3D%3D) |
| C3, C4            | various      | 4.7 nF ceramic, 1kV, 1206 package | [Mouser](https://www.mouser.com/ProductDetail/Kyocera-AVX/1206AC472MAT1A?qs=%2Fha2pyFaduhzfYpjb5v9%2FX3y5jlWBFFWEQhcr6uCzhXR56xULseKBA%3D%3D) |
| C5                | various      | 100 uF electrolytic               | [Mouser](https://www.mouser.com/ProductDetail/CDE-Illinois-Capacitor/107CKE025MEM?qs=3tP%252BN51vMXeOVuB%252BkBNQFQ%3D%3D) |
| C6                | various      | 330 nF ceramic, 1206 package      | [Mouser](https://www.mouser.com/ProductDetail/Samsung-Electro-Mechanics/CL31C332JBFNNNE?qs=%2Fha2pyFaduhPzWFCM51KQEWJ40%252BY2tgediDfDzBWCkuVgZGDNgIATFe5%252BxLhkX0v) |
| J1, J2, J3, J4    | Molex        | 22-23-2021                        | [Mouser](https://www.mouser.com/ProductDetail/Molex/22-23-2021?qs=%2Fha2pyFaduiHQLs56YZXs3AkvtRoBprDw5MnVZuMKr8%3D) |
| R1                | various      | 6.8 kOhm, 1206 package            | [Mouser](https://www.mouser.com/ProductDetail/Panasonic/ERJ-8ENF6801V?qs=%2Fha2pyFaduh7VP2GfmkMxHOCEV8rtbSgRKUNEyrhBWx1%252BvfOW9YFPw%3D%3D) |
| R2, R3            | varous       | 1 Mohm, 1206 package              | [Mouser](https://www.mouser.com/ProductDetail/Vishay-Dale/CRCW12061M00FKEAC?qs=%2Fha2pyFaduh62bXGafpVtEasjFvzCXuSdredFavJVIq3S3FLHV7HVu%2Fl5Mz9wsE3) |
| U1, U2, U3, U4    | TI           | CD74AC04M96                       | [Mouser](https://www.mouser.com/ProductDetail/Texas-Instruments/CD74AC04M96?qs=5BZzbFV4k2sxVMcJXGEnkA%3D%3D) |
| U5                | RECOM        | R-78B6.5-1.0                      | [Mouser](https://www.mouser.com/ProductDetail/RECOM-Power/R-78B65-10?qs=YWgezujkI1Jcc6KIi%2FUXSQ%3D%3D) |

## Choice of Inductor, Capacitor

### Capacitor C1

### Inductors L1/L2
