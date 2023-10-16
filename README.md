# GuudBox

_A custom hitbox for [GP2040-CE](https://github.com/OpenStickCommunity/GP2040-CE), built with Gateron low profile switches._

## Firmware Installation

1. Download the firmware (.uf2 file) in [release page](https://github.com/AkariiinMKII/GuudBox/releases).
2. Hold `BOOT` buttom on MCU board when plugging your controller into a PC. A new removable drive named `RPI-RP2` should appear in your file explorer.
3. Drag and drop the firmware into the removable drive.
4. Wait for the device to automatically disconnect.

## Key Map

_Default key map in firmware, you can change it in [__Web Configurator > Configuration > Pin Mapping__](https://gp2040-ce.info/#/web-configurator?id=pin-mapping)_

![Key Map](.doc/Key%20Map.png)

| Position | GPIO Pin | GP2040-CE  | XInput | Switch  | PS4          | PS3          | DirectInput  | Arcade |
| -------- | -------- | ---------- | ------ | ------- | ------------ | ------------ | ------------ | ------ |
| 1        | 14       | L3         | LS     | LS      | L3           | L3           | 11           | LS     |
| 2        | 15       | R3         | RS     | RS      | R3           | R3           | 12           | RS     |
| 3        | 26       | A1         | Guide  | Home    | PS           | PS           | 13           | Home   |
| 4        | 27       | A2         | -      | Capture | Touchpad     | -            | 14           | -      |
| 5        | 28       | S1         | Back   | Minus   | Share        | Select       | 9            | Coin   |
| 6        | 29       | S2         | Start  | Plus    | Options      | Start        | 10           | Start  |
| 7        | 13       | LEFT       | LEFT   | LEFT    | LEFT         | LEFT         | LEFT         | LEFT   |
| 8        | 12       | DOWN       | DOWN   | DOWN    | DOWN         | DOWN         | DOWN         | DOWN   |
| 9        | 11       | RIGHT      | RIGHT  | RIGHT   | RIGHT        | RIGHT        | RIGHT        | RIGHT  |
| 10       | 10       | UP         | UP     | UP      | UP           | UP           | UP           | UP     |
| 11       | 8        | B3         | X      | Y       | Square       | Square       | 1            | P1     |
| 12       | 6        | B4         | Y      | X       | Triangle     | Triangle     | 4            | P2     |
| 13       | 4        | R1         | RB     | R       | R1           | R1           | 6            | P3     |
| 14       | 2        | L1         | LB     | L       | L1           | L1           | 5            | P4     |
| 15       | 9        | B1         | A      | B       | Cross        | Cross        | 2            | K1     |
| 16       | 7        | B2         | B      | A       | Circle       | Circle       | 3            | K2     |
| 17       | 5        | R2         | RT     | ZR      | R2           | R2           | 8            | K3     |
| 18       | 3        | L2         | LT     | ZL      | L2           | L2           | 7            | K4     |
| 19       | 0        | Fn         | Fn     | Fn      | Fn           | Fn           | Fn           | Fn     |
| 20       | 1        | Turbo      | Turbo  | Turbo   | Turbo        | Turbo        | Turbo        | Turbo  |

## Custom settings

Hold `S2` (position 6 in default key map) when plugging your controller into a PC. Then visit <http://192.168.7.1> in a web browser to access [GP2040-CE Web Configurator](https://gp2040-ce.info/#/web-configurator).

__Visit [GP2040-CE home page](https://gp2040-ce.info/#/web-configurator) for full documentation.__
