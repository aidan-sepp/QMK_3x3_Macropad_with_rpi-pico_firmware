# seppopad

![seppopad](https://www.raspberrypi.com/documentation/microcontrollers/images/pico-2-r4-pinout.svg)

*A short description of the keyboard/project*

* Keyboard Maintainer: [aidan seppings](https://github.com/aidan-sepp)
* Hardware Supported: *The PCBs, controllers supported*
## Description
This is a 3 x 3 macropad made with a RPI PICO
It can be used with via but you will need ti import the custom layouts

Make example for this keyboard (after setting up your build environment):

    make seppopad:default

Flashing example for this keyboard:

    make seppopad:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
# Key 0,0 is the top left key
