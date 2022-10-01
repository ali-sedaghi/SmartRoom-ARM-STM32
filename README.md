# SmartRoom-ARM-STM32

A simulation of smart room (Heater, Cooler, Purifier, Lock) with ARM STM32 microprocessor.


## Technologies

- Proteus
- ARM
- STM32F103C6 microprocessor
- Keil uVision5
- STM32CubeMX
- C programming language


## Features

- LCD for showing data
- Heater will automatically turned on when the temperature exceed parameter p1
- Cooler will automatically turned on when the temperature is lower than parameter p2
- Air purifier will automatically turned on for a minute when time is equal to p3
- A red LED will turn on when density of Carbon monoxide is higher than 6 ppm
- All parameters (p1, p2, p3) can be modified by a keypad
- Authentication must occur in order to modify parameters (Password: 3421)


## Hardware
![Hardware](https://user-images.githubusercontent.com/45814362/193379988-6599ad84-6f66-4a39-8c30-54ddfcf81d0d.jpg)
