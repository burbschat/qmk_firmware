# hmkb65_alps_mx_hybrid

![hmkb65_alps_mx_hybrid](imgur.com image replace me!)

*A short description of the keyboard/project*

* Keyboard Maintainer: [Bela Urbschat](https://github.com/burbschat)
* Hardware Supported: My custom alps pcb for the hmkb65 case
* Hardware Availability: Design files not (yet) public

Make example for this keyboard (after setting up your build environment):

    make hmkb65_alps_mx_hybrid:default

Flashing example for this keyboard:

    make hmkb65_alps_mx_hybrid:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
