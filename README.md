# Tiny-Tetris

Tetris Clone with OLED SSD1306(I2C) for Arduino Nano / Uno and ESP32.

ESP32 pins:
Analog joystick uses pin 2 for Rx, 4 for Ry and 5 for push button on joystick.
I2C connection to OLED via pins 21 (SDA) and 22 (SCK/SCL).
Indicator LED on pin 13 (unchanged from original implementation).


TODO:
The code is not finished, there is still lots to be done.

Things that need to be added:

High score functionality.

Decent random number generator.

Create a letter font, create a proper system for rendering numbers and letters.

Tidy up code and optimize for memory, sort out the globals and types.

Create defines for all the magic numbers but they are useful for now.



