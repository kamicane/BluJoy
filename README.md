# BluJoy

A common joystick interface for [ESP32-BLE-Gamepad](https://github.com/lemmingDev/ESP32-BLE-Gamepad).

Used in my [NeoGeo Mini Bluetooth Gamepad](https://github.com/kamicane/neogeo-mini-bluetooth-gamepad) and [Wii Classic Bluetooth Gamepad](https://github.com/kamicane/wii-classic-bluetooth-gamepad).

## Features

- XBOX 360 layout based common joystick interface
- Calibration helpers with eeprom save support
- [Scaled radial deadzone](https://github.com/Minimuino/thumbstick-deadzones) algorithm for analog inputs
- [Eight symmetric angular zones](https://gamingprojects.wordpress.com/2017/08/04/converting-analog-joystick-to-digital-joystick-signals/) for optional, accurate ADC
