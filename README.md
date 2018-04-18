# ZUMCore
BQ ZUM Core integration on Arduino IDE

## Getting Started

### Prerequisites

You need to install latest [Arduino IDE](https://www.arduino.cc/en/Main/Software).

This package has been tested on Arduino IDE 1.8.5.

### Installing

To use the integration with Arduino IDE follow these steps:
1. Open Arduino IDE and go into File -> Preferences.
1. On "Additional Boards Manager URLs:" enter the link to [package_zumcore_1_8_x_index.json](https://raw.githubusercontent.com/bq/ZUMCore/master/package_zumcore_1_8_x_index.json) [right click here and copy link] and press OK.
1. Go to Tools -> Boards -> Board Manager and you will find "ZUM Core for Arduino 1.8.x" ready to be installed. Install latest version.

Now you can choose your Board **BQ ZUM Core**.

You can also find some usefull examples for the board available on the IDE.

### Examples



## Flashing Bootloader

The bootloader can be flashed on ZUM Junior using another Arduino board as ISP or any other supported ISP programmer.
For further support check this [link](https://www.arduino.cc/en/Tutorial/ArduinoISP).

## License

This project is licensed under the GPL v3 license.

## Credits

This project relies on Arduino IDE to work.

The project is based on [Elektor UNO R4](https://github.com/ElektorLabs/Arduino/) 