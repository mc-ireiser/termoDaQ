# termoDaQ

![Header](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/Photographs/termoDaQ_header.jpg)

termoDaQ is a development board based on the [Arduino](https://www.arduino.cc/) architecture, uses an [ATmega328-P](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42735-8-bit-AVR-Microcontroller-ATmega328-328P_Summary.pdf) and an [ATtiny85](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2586-AVR-8-bit-Microcontroller-ATtiny25-ATtiny45-ATtiny85_Datasheet-Summary.pdf) for its operation, this board was originally designed to help the work of oceanography students, by serving as an instrument for the acquisition of physical variables (temperature, pressure) at surface level in bodies of fresh or salt water, in order to detect changes that may affect the flora or fauna of ecosystems, automating the work of making measurements over time.

- But it can serve many purposes since it has a connection to a GPS receiver, pressure sensor, temperature sensors, and SD card.

The function of the [ATtiny85](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2586-AVR-8-bit-Microcontroller-ATtiny25-ATtiny45-ATtiny85_Datasheet-Summary.pdf) is work as a timer to program the operation cycles of the equipment, reducing the energy consumption.

## Operation

- The board works under two operating blocks.

The first involves the acquisition of data in the study environment; these are date, time, latitude, longitude, pressure, and temperature in each working cycle interval, for example, every 10 minutes (the user defines the interval time) and stores the information, the duration of the interval is modified with a potentiometer connected to [ATtiny85](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2586-AVR-8-bit-Microcontroller-ATtiny25-ATtiny45-ATtiny85_Datasheet-Summary.pdf) which has the task of activating and deactivating the sensor area managed by the [ATmega328-P](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42735-8-bit-AVR-Microcontroller-ATmega328-328P_Summary.pdf).

![Operation](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/IMG/Mockup.png)

The second block of operation consists of stopping the acquisition and transmitting the data to the computer through serial communication.

To carry out these tasks, a switch is included on the board that allows selecting the operating mode.

## Board specifications

All the source files are in this repository

- Board Size: 99.82 mm X 73.41 mm (X = 99.82, Y = 73.41)
- Area: 11.36 in2
- Number of layers: 2
- Number of drills: 311
- Number of vias: 47
- Number of signals: 146
- Minimum copper trace width: 0.41 mm
- Consumption: ~ 80mAh (currently under test)

## Pinout

![Pinout](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/IMG/Pinout.png)

## Pending

| Goal | Date |
| ---------- | ---------- |
| ~~Full test in breadboard~~   | November 11, 2017   |
| ~~FAB: First prototype in PCB~~   | November 26, 2017   |
|~~Feedback and modifications~~| February to March, 2018 |
|~~Fab: Second prototype in PCB~~| Abril 4, 2018 |
|~~Funcionality test~~| May to June, 2018 |
|FAB: Final PCB circuit| N/A |
|~~Print first 3D case~~| February 28 to March 9, 2018 |

## Important update

- November 26, 2017, I start the manufacturing process in PCB, the gerber files were sent to the factory, the process lasts 5 working days and then wait for the shipment to Venezuela.

- January 17, 2018. Reception of package with the first 10 PCB boards from the factory in China.

- January 18, 2018. Assembly and welding of components in the first plate, my main goal has been met, now termoDaQ is real :)

- April 4, 2018 begins the process of manufacturing the second prototype in PCB with updates and corrections of the feedback applied.

## Translation

English translation using google translator, If you wish, you can help me translate the readme file correctly.

## License

Creative Commons Attribution-ShareAlike 4.0 International Public License

Please go to the License section for more information. [Link](https://github.com/mc-ireiser/termoDaQ/tree/master/License)

[![2D Render](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)
