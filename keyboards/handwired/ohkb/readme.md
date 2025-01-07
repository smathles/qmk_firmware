# ohkb

![ohkb](imgur.com image replace me!)

An open-source split keyboard, inspired by the [dygma raise](https://dygma.com/pages/dygma-raise-2), [Ultimate Hacking Keyboard](https://ultimatehackingkeyboard.com/), and the [Happy Hacking Keyboard](https://hhkeyboard.us/) (as well as a stubborn insistance that '6' should be typed with one's right hand).
Dev logs, useful information, and files are available here: [OHKB](https://github.com/smathles/ohkb)

* Keyboard Maintainer: [Cameron Smith](https://github.com/smathles)
* Hardware Supported: Pro Micro
* Hardware Availability: N/A (DIY keyboard project!). 3D print components from [Onshape](https://cad.onshape.com/documents/9e1f0d31a8394aa8d7623c60/w/c8f2cebee66fc5c32fb5229d/e/09752b9c4178eba7ffd03780).

Make example for this keyboard (after setting up your build environment):

    make handwired/ohkb:default

Flashing example for this keyboard:

    make handwired/ohkb:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (the top left key on the left keyboard) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the case (or short the pro micro connections)
