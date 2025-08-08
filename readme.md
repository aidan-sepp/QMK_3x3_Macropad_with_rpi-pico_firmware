## Macropad 3 x 3

![RPI pico pinout image](https://www.raspberrypi.com/documentation/microcontrollers/images/pico-2-r4-pinout.svg)


* Keyboard Maintainer: [aidan seppings](https://github.com/aidan-sepp)
## Description
This is a 3 x 3 macropad made with a RPI PICO
It can be used with via but you will need to import the custom layouts

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb macropad_main -km via

Flashing example for this keyboard:

    qmk flash -kb macropad_main -km via

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader using the set bootloader key :

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
Key 0,0 is the top left key

This firmware configuration supports via but you will need to use the design tab to import the layout as the ## via.json
see: https://youtu.be/7d5yzBOup9U
