# ESP32 BLE Dactyl Manuform

I tried strapping ergodox dactyl-manuform to my chair's arm rests. Worked great if not for the cable. So now I'm abandoning QMK, Arduino Pro Micros and exploring wireless world!
![Chair-Keyboard](https://user-images.githubusercontent.com/56068621/175384516-79fcfe59-0c00-4817-a801-3e328d7c2a8e.jpg)


## Gist of it

1. I'm planning to start from an easy PoC
2. There will be more or lesss a keyboard
3. I will work on ease of setup.
4. TBD

### Hardware:
* 2 x ESP32 (each will be it's own separate keyboard)
* [Dactyl Manuform](https://github.com/tshort/dactyl-keyboard) 3d model
* rest is TBD


## How to build

1. Clone this repo
2. Make sure that you have PlatformioCLI installed
3. Run `pio run` to check if it builds
4. Run `pio run -t release` to flash it to ESP32
