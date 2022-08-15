# KSP-controller-STAR266-dashboard

REPO UNDER CONSTRUCTION

This repository allows you to build a custom Kerbal Space Program controller based on the STAR 266 dashboard and Raspberry Pi Pico. You can modify it to your own design, though I recommend using similar hardware. Tested only with Windows 10 machine.

## RasPi Pico setup

CircuitPython 7.3.2 with the adafruit_hid library is used to simulate the controller.
1. Push the BOOTSEL button on RasPi Pico and then plug the USB cable.
2. Copy the .uf2 file from 'firmware' to the RPI-RP2 disk to install CircuitPython.
3. Copy whole 'lib' folder to the CIRCUITPY to add necessary libraries.
4. Copy boot.py, hid_gampepad.py and main.py to the CIRCUITPY.

## Communicating with the board

I am using Visual Studio Code. To set up the IDE properly - install Python and then the three VS Code extensions: Python, Pico-Go and CircuitPython. Remember to choose proper board in the lower right corner. All necessary files should be downloaded by VS Code as a bundle.
If you want to check the installation - simply connect button (tactswitch or sth) to GP2 and some potentiometer to GP26_A0 and check the 'Game Controller Settings'. See if you can make actions.