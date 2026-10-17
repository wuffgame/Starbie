# wuff's Starbie

A homemade portable Tamagotchi. Built using the Half-Life guide from Hack Club.

![alt text](<imgs/Zrzut ekranu_20261010_125132.png>)

## Why this?

I decided it was time to build something other than just another software project, so I joined YSWS Half-Life, where I was able to build the project from scratch using a guide.

## Features

- XIAO ESP32 C3
- OLED 0.96
- MPU6050
- DHT11
- Custom PCB

## Repository Structure

```
Starbie/
├── Starbie_firmware/
   ├── Starbie.ino     # Firmware file
├── Starbie_PCB        # Schematic file from PCB
├── imgs               # Images for README
├── BOM.md             # Bill of materials
├── JOURNAL.md         # Log of every hour of time spent building
├── LICENSE            # File with license
├── README             # File that you read now
```

## BOM

| Part | What it's for | Qty | Unit | Total | Vendor |
| --- | --- | --- | --- | --- | --- |
| [PCB](https://jlcpcb.com/) | PCB | 1 | $4.00 | $4.00 | [JLCPCB](https://jlcpcb.com/) |
| [XIAO ESP32-C3](https://botland.com.pl/xiao/21859-seeed-xiao-esp32-c3-wifibluetooth-seeedstudio-113991054.html) | ESP32 | 1 | $6.63 | $6.63 | [botland](https://botland.com.pl/xiao/21859-seeed-xiao-esp32-c3-wifibluetooth-seeedstudio-113991054.html) |
| [DHT11](https://pl.aliexpress.com/item/1005009268179353.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) | Temperature and Humidity Sensor | 1 | $1.39 | $1.39 | [aliexpress](https://pl.aliexpress.com/item/1005009268179353.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) |
| [Switches](https://pl.aliexpress.com/item/1005007135709029.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) | For pressing buttons | 2 | $0.82 | $1.64 | [aliexpress](https://pl.aliexpress.com/item/1005007135709029.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) |
| [OLED 0,96](https://pl.aliexpress.com/item/1005006141235306.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) | For display | 1 | $2.87 | $2.87 | [aliexpress](https://pl.aliexpress.com/item/1005006141235306.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) |
| [Resistor 10K](https://pl.aliexpress.com/item/1005007539842999.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) | limiting current intensity | 1 | $1.32 | $1.32 | [aliexpress](https://pl.aliexpress.com/item/1005007539842999.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) |
| [Keycaps](https://pl.aliexpress.com/item/1005009364428646.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) | Switch caps | 1 | $3.20 | $3.20 | [aliexpress](https://pl.aliexpress.com/item/1005009364428646.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) |
| [MPU6050](https://pl.aliexpress.com/item/1005009227671615.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) | Shake detection | 1 | $2.74 | $2.74 | [aliexpress](https://pl.aliexpress.com/item/1005009227671615.html?spm=a2g0o.cart.0.0.1cc9452ct3C8RJ&mp=1&gatewayAdapt=glo2pol) |
| **Parts subtotal** | — | — | — | **$23.79** | — |
| **Tax & shipping** | — | — | — | **$7.78** | — |
| **Total** | — | — | — | **$31.57** | — |

## Credits

Thanks Hack Club and Half Life for giving me the motivation to start with hardware projects.

## License

The project is licensed under the GNU General Public License v3.0. See the LICENSE file for details.

## Contact

- Discord \_anik2010\_
- Email: wuff@wuffdev.pl or kacper5555544444@gmail.com
- Hack Club Slack: wuff
