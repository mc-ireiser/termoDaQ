# termoDaQ

![3D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/3D_Render/Render_3.png)

termoDaQ is a development board based on the [Arduino](https://www.arduino.cc/) architecture, uses an [ATmega328-P](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42735-8-bit-AVR-Microcontroller-ATmega328-328P_Summary.pdf) and an [ATtiny85](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2586-AVR-8-bit-Microcontroller-ATtiny25-ATtiny45-ATtiny85_Datasheet-Summary.pdf) for its operation, this board was originally designed to help the work of oceanography students, by serving as an instrument for the acquisition of physical variables (temperature, pressure) at surface level in bodies of fresh or salt water, in order to detect changes that may affect the flora or fauna of ecosystems, automating the work of making measurements over time.

- But it can serve many purposes, since it has connection for GPS receiver, pressure sensor, multiple temperature sensors and SD card.

The function of the [ATtiny85](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2586-AVR-8-bit-Microcontroller-ATtiny25-ATtiny45-ATtiny85_Datasheet-Summary.pdf) is a timer server for programming the operation cycles of the equipment, reducing the energy consumption.

## Certified open source hardware

[OSHW] VE000001

![3D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/3D_Render/Render_2.png)

## Operation

- The board works under two operating blocks.

The first one consists of data acquisition in the study environment, these are date, time, latitude, longitude, pressure and temperature in each working cycle interval for example every 10 minutes (interval time is defined by the user) and store the information, the duration of the interval is modified with a potentiometer connected to [ATtiny85](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2586-AVR-8-bit-Microcontroller-ATtiny25-ATtiny45-ATtiny85_Datasheet-Summary.pdf) who has the task of activating and deactivating the sensor area managed by the [ATmega328-P](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42735-8-bit-AVR-Microcontroller-ATmega328-328P_Summary.pdf). In total it could take temperature data in a body of water at a maximum depth of 35 to 38 meters depth, adapting a temperature sensor to a UTP cable of maximum 40 meters.

![2D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/docs/img/Mockup.png)

The second block of operation consists of transmitting the data to the computer using serial communication, to carry out this task is included a switch on the board that allows to select the mode of operation.

## Pinout

![2D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/IMG/Pinout.png)

![2D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/2D_Render/HQ_Top.png)

## Board specifications

All the source files are in this repository

- Board Size: 99.212 mm X 72.542 mm (X = 99.21, Y = 72.54)
- Outline contour: 342.90 mm
- Number of layers: 2
- Number of drills: 390
- Number of components: 72
- Trace width: 1.016 mm
- Minimum trace width: 0.076 mm
- Consumption: ~ 80mAh (currently under test)

![2D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/IMG/Overall.png)

## PCB assembled

![Photo](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/Photographs/DSCF1042.JPG)

## Software

The firmware for the board will be included in this repository, but anyone can develop their own code to adapt the operation to their needs. In addition to this, another project will be created to manage the data on the computer.

## Pending

- ~~Fabricate the board in PCB~~
- Complete the firmware (in progress)
- Make the case

## Important update

- November 26, 2017, I start the manufacturing process in PCB, the gerber files were sent to the factory, the process lasts 5 working days and then wait for the shipment to Venezuela.

- January 17, 2018. Reception of package with the first 10 PCB boards from the factory in China.

- January 18, 2018. Assembly and welding of components in the first plate, my main goal has been met, now termoDaQ is real :)

## Translation

English translation using google translator, If you wish, you can help me translate the readme file correctly.

## License

Creative Commons Attribution-ShareAlike 4.0 International Public License

Please go to the License section for more information. [Link](https://github.com/mc-ireiser/termoDaQ/tree/master/License)

[![2D Render](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)
