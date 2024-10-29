# R75

* Keyboard Maintainers:
  * Original Firmware - [sdk66](https://github.com/sdk66)
  * This port of iamdanielv's customization - [boa](https://github.com/boafur)
  * Original R65 customization - [iamdanielv](https://github.com/iamdanielv)
  * Another customization - [irfan](https://github.com/irfanjmdn/)
* Hardware Supported: R75
* Hardware Availability: [rk](http://www.rkgaming.com)

Make example for this keyboard (after setting up your build environment):

    make rk/r75:vial
        
Flashing example for this keyboard:

    make rk/r75:vial:flash

To reset the board into bootloader mode, do one of the following:

* Hold the Reset switch mounted on the bottom side of the PCB while connecting the USB cable
* Hold the Escape key while connecting the USB cable (also erases persistent settings)

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).