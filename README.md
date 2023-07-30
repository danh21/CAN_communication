# Description:
    - The system includes 4 devices which connect each other by CAN bus. 
    - When pressing the built-in button of one of devices, monitors of all devices display information about which device whose button is pressed.
    - Each device can transmit commands to control built-in led of other devices, monitors of all devices display information about those commands.

# Hardware:
    - 4 boards STM32F407
    - 4 Modules TJA1050 CAN Bus
    - 4 Modules USB UART CP2102 (connected to 4 personal computers)

# Software:
    - STM32CubeIDE (config and programming for microcontroller)
    - Hercules (monitoring operation of system)
    - Fritzing (design schematic)

# Source:
    - CAN1: Source code of board 1
    - CAN2: Source code of board 2
    - CAN3: Source code of board 3
    - CAN4: Source code of board 4
    - Design: schematic of system

# Bonus:
    - Demo: https://youtu.be/9fTRTqMTrdw