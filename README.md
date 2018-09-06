Lakduino is a series of devices manufactured by [Aptinex (Pvt) Ltd](https://aptinex.com). This aims at making improved compatibles of Arduino.

# Table of contents
* [Boards](#boards)
  - [Dwee - 1284 Mini Pro](#dwee---1284-mini-pro)
* [How to install](#how-to-install)

# Boards
## Dwee - 1284 Mini Pro 

<img src="https://user-images.githubusercontent.com/6365607/45154613-c2e9b480-b1f5-11e8-872f-5280fbeb1542.jpg" width="400"/>

The new “Lakduino Dwee 1284 Mini Pro” is Arduino compatible hardware with the ATmega 1284P AVR, in place of the common 328p that is used in current Arduino hardware. The 1284P is the perfect mix of features, program space, and more features.

Extra space for extra code: With 4x the flash memory (program space), 4x the EEPROM, and 8x the RAM versus the 328p, your programs will never be limited by space constraints. You will be free to code without worrying about a data cap looming over you.

Create more developed projects with the extra pins: Supplying 32 I/O pins, you will never have to make the tough choice of which peripheral to keep in your project, and which to toss out. The “Lakduino Dwee 1284 Mini Pro” is designed to fit them all! It can also source up to 40 mA of current per pin compared to 25 mA capabilities of ARM based boards.

In a compact package:
The “Lakduino Dwee 1284 Mini Pro” is the breadboard Pluggable 40 pin design.

Get more data in and out (digital and analog):

### Other features

- 2 UARTs,
- 8 Analog Input pins,
- 8 PWM (Pulse Width Modulation) enabled pins,
- 3 External Interrupt pins.
- The “Lakduino Dwee 1284 Mini Pro” also has SPI and I2C capabilities.

How to use the “Lakduino Dwee 1284 Mini Pro”:
All you need to upload a sketch via Micro USB cable to the “Lakduino Dwee 1284 Mini Pro”. USB-to-Serial adapter based on the CH340G is include to easy to use and plug and play.

### Full Specification

- Built around the Atmel AVR ATmega1284P (TQFP 44 Package)
- Support for the Arduino IDE 1.0+ (OSX/Windows/Linux)
- 100% Open-source
- Uses Mighty 1284P Platform Bootloader
- On-board 5v and 3.3v regulator
- 32 I/O pins
- Communication includes 2 UARTs, 1 I2C, and 1 SPI
- 8 Analog In (ADC) pins
- 8 PWM pins
- Power Indicator LED
- Onboard LED

## Pinout
<img src="https://user-images.githubusercontent.com/6365607/45154427-350dc980-b1f5-11e8-8921-11acd38bdc23.jpg" width="500"/>



# How to install
This installation method requires Arduino IDE version 1.6.4 or greater.
* Open the Arduino IDE.
* Open the **File > Preferences** menu item.
* Enter the following URL in **Additional Boards Manager URLs**: `https://aptinex.github.io/lakduino/package_Aptinex_Lakduino_index.json`
  * Separate the URLs using a comma ( **,** ) if you have more than one URL
* Open the **Tools > Board > Boards Manager...** menu item.
* Wait for the platform indexes to finish downloading.
* Scroll down until you see the **Lakduino** entry and click on it.
* Click **Install**.
* After installation is complete close the **Boards Manager** window.


