# ESP32 BLE Keyboard

I tried strapping ergodox dactyl-manuform to my chair arm rests. Worked great if not for the cable. So now I'm abandoning QMK, Arduino Pro Micro and exploring wireless world!
![IMG_20220623_213324490](https://user-images.githubusercontent.com/56068621/175382546-4b53f73c-7cf9-409f-9d90-ab06b41b0c33.jpg)

## Gist of it

I'm planning to start from an easy PoC, than there will be more or lesss a keyboard and than I will work on easy of setup.

### Hardware:
* 2 x ESP32 (each will be it's own separate keyboard)
* [Dactyl Manuform](https://github.com/tshort/dactyl-keyboard) 3d model
* rest is TBD


## How to build

1. Clone this repo
2. Make sure that you have PlatformioCLI installed
3. Run `pio run` to check if it builds
4. Run `pio run -t release` to flash it to ESP32
