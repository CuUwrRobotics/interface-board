# Robot Hardware Interface Board

This is a repository containing [@nichlock](https://github.com/nichlock)'s design for our hardware interfacing board. This is the board which the [board-interface](https://github.com/CuUwrRobotics/PiranhaBot-docs/blob/master/board_interface/README.md) package is designed to control. 

![Top of board, outside appearence](https://github.com/CuUwrRobotics/interface-board/blob/master/images/rev1-top-appearance.png)

# Capabilities

This board is designed for our underwater robot, and connects to the Raspebrry Pi through the 40-pin header on the right. It has the following dedicated capabilities:
- 32 GPIO pins
- 32 PWM outputs
- 16 Analog inputs
- 8 Individual leak sensors
- 4 MOSFETs capable of driving 17A (connector limited)
- 2 Current sensors capable of 17A (connector limited, sensors are capable of 50A)
- 1 Microcontroller for I/O that needs constant attention
- 1 Configuration chooser, with 4 switches, for changing any setting on the fly
