# Ortho 48 v2

A 4x12 Ortholinear keyboard powered by an onboard RP2040

* Keyboard Maintainer: [Andrew Kannan](https://github.com/awkannan)  
* Hardware Supported: RP2040 
* Hardware Availability: [CannonKeys](https://cannonkeys.com) 

Make example for this keyboard (after setting up your build environment):

    make cannonkeys/ortho48v2:default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).


## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Swap the boot switch on the back of the PCB to "1" and hit the reset button. Or double tap the reset button quickly while the boot switch is set to "0".
* **Keycode in layout**: Press the key mapped to `RESET` if it is available
