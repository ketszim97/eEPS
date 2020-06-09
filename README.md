# eEPS
### emulatedEPS for the UBC Orbit Canadian Satellite Design Competition

Original design to test and verify the UBC Orbit ASPECTU satellite

A PC/104 based power supply for a 1U cubesat. Provides:
- 3V3
- 5V0
- 12V0
- CAN peripheral to act as CAN Bus debugger
- STM32H743ZIT6 480MHz Microcontroller
- USB/Banana/Screw Terminal Inputs

Allows 8 channels of independent current sense and load switching. The shared bus/header is specific to the Orbit Satellite design, but can be easily modified to fit other uses.

![Fusion Render](https://github.com/ketszim97/eEPS/blob/master/Renders/Fusion%20Render%201.png)
![Front View](https://github.com/ketszim97/eEPS/blob/master/Renders/Altium%20Front%20View.png)
