# KSP-controller-STAR266-dashboard

REPO UNDER CONSTRUCTION

This repository allows you to build a custom Kerbal Space Program controller based on the STAR 266 dashboard and Raspberry Pi Pico. You can modify it to your own design, though I recommend using similar hardware.

## RasPi Pico setup

CircuitPython 7.3.2 with the adafruit_hid library is used to simulate the controller.
1. Push the BOOTSEL button on RasPi Pico and then plug the USB cable.
2. Copy the .uf2 file to the RPI-RP2 disk to install CircuitPython.
3. Copy whole 'adafruit_hid' folder to the CIRCUITPY/lib to add necessary libraries.