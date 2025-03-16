![zilpzalp](https://github.com/kilipan/zilpzalp/blob/main/img/zilpzalp_photo.jpg?raw=true)

Alternate QMK Firmware for the [zilpzalp](https://github.com/kilipan/zilpzalp) keyboard. 

Original QMK firmware repository: [here](https://github.com/kilipan/qmk-config-zilpzalp)

# zilpzalp QMK firmware
*A wonky 28-key split-unibody column-stagger keyboard.*  
**IMPORTANT: This firmware is only suitable for the Seeed Xiao RP2040 MCU!**
If you would like to use the BLE version of the XIAO, please consider using [ZMK firmware](https://github.com/kilipan/zmk-config-zilpzalp) (currently only tested for the RP2040 version).

* Keyboard Maintainer: [kilipan](https://github.com/kilipan)
* Hardware Supported: *zilpzalp keyboard with Seeed Studio Xiao RP2040 Controller*
* Hardware Availability: [*production files*](https://github.com/kilipan/zilpzalp)

Building this firmware (after setting up your build environment, and checking out this repository in the `keyboards/` folder):

    qmk compile -kb zilpzalp -km default

Flashing for this firmware:

    Drop the uf2 file onto the Seeed Xiao RP2040 after connecting with the "B" button held down, or if connected hold down the "B" button and press the "R" button.

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Default keymap
The `default` keymap is set to QWERTY with the `Q`, `Z`, `B`, and `N` keys missing.
They are reacheable via combos.
