# termoDaQ

![3D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/3D%20Render/Render%203.png?token=AJS2yj0pG9qc0IsP0pAKQhiQk_DEYViaks5aHcU3wA%3D%3D)

termoDaQ is a development board based on the [Arduino](https://www.arduino.cc/) architecture, uses an [ATmega328-P](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42735-8-bit-AVR-Microcontroller-ATmega328-328P_Summary.pdf) and an [ATtiny85](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2586-AVR-8-bit-Microcontroller-ATtiny25-ATtiny45-ATtiny85_Datasheet-Summary.pdf) for its operation, this board was originally designed to help the work of oceanography students, by serving as an instrument for the acquisition of physical variables (temperature, pressure) at surface level in bodies of fresh or salt water, in order to detect changes that may affect the flora or fauna of ecosystems, automating the work of making measurements over time.

- But it can serve many purposes, since it has connection for GPS receiver, pressure sensor, multiple temperature sensors and SD card.

The function of the [ATtiny85](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2586-AVR-8-bit-Microcontroller-ATtiny25-ATtiny45-ATtiny85_Datasheet-Summary.pdf) is a timer server for programming the operation cycles of the equipment, reducing the energy consumption.

## Operation

- The board works under two operating blocks.

The first one consists of data acquisition in the study environment, these are date, time, latitude, longitude, pressure and temperature in each working cycle interval for example every 10 minutes (interval time is defined by the user) and store the information, the duration of the interval is modified with a potentiometer connected to [ATtiny85](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-2586-AVR-8-bit-Microcontroller-ATtiny25-ATtiny45-ATtiny85_Datasheet-Summary.pdf) who has the task of activating and deactivating the sensor area managed by the [ATmega328-P](http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42735-8-bit-AVR-Microcontroller-ATmega328-328P_Summary.pdf). In total it could take temperature data in a body of water at a maximum depth of 35 to 38 meters depth, adapting a temperature sensor to a UTP cable of maximum 40 meters.

![2D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/docs/img/mockup.png?token=AJS2ymGojnSCatxAPc8gW_jXVXe7j1cKks5aH4IgwA%3D%3D)

The second block of operation consists of transmitting the data to the computer using serial communication, to carry out this task is included a switch on the board that allows to select the mode of operation.

## Pinout

![2D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/IMG/Pinout.png)

## Board specifications

All the source files are in this repository

- Size: 99.212 mm X 72.542 mm (X = 99.21, Y = 72.54)
- Outline contour: 342.90 mm
- Number of drills: 518
- Number of layers: 2
- Consumption: ~ 80mAh (currently under test)

![2D Render](https://raw.githubusercontent.com/mc-ireiser/termoDaQ/master/IMG/Overall%201.png?token=AJS2yk9sYgyW8VRVaAOB3iB2HLssfOGZks5aHcYYwA%3D%3D)

## Software

The firmware for the board will be included in this repository, but anyone can develop their own code to adapt the operation to their needs. In addition to this, another project will be created to manage the data on the computer.

## Translation

English translation using google translator, If you wish, you can help me translate the readme file correctly.

## License

Creative Commons Attribution-ShareAlike 4.0 International Public License

Please go to the License section for more information. [Link](https://github.com/mc-ireiser/termoDaQ/tree/master/License)

[![2D Render](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)
