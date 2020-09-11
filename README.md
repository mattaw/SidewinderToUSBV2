# SidewinderToUSBV2
Integrated Sidewinder adaptor with assembly files for various manufacturers.  This project originated as a combination of [the adapt-ffb-joy project](https://github.com/tloimu/adapt-ffb-joy) (minus the trim pots) with the [Teensy 2.0](https://www.pjrc.com/teensy/schematic.html) in order to remove the requirement for a comparatively expensive Teensy module and to make manufacture by a professional facility easier, with the intent of providing an open-source board that people can use to send off to have adaptors made.

Source code for the below hexes can be found at [the adapt-ffb-joy project](https://github.com/tloimu/adapt-ffb-joy) and [the sw3dprousb project](https://code.google.com/archive/p/sw3dprousb/).  Programming can be done using a [Tag-Connect TC2030-IDC-NL](https://www.tag-connect.com/product/tc2030-idc-nl) and an AVR programmer such as the [Pololu AVR Programmer v2.1](https://www.pololu.com/product/3172).

Licensing for the board is Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0).

To use with various Sidewinder devices, there are three .hex files provided.  Only one of them can be flashed to the microcontroller at a time, so which one to use depends on which device you'll be using the adaptor with:

- 3DPro32u4-10.hex - Sidewinder Precision Pro, 3D Pro, 3D Pro Plus, or Force Feedback Pro (without force feedback support)
- adaptffbjoy-r54.hex - Sidewinder Force Feedback Pro (with force feedback support)
- Wheel.hex - Sidewinder Force Feedback Wheel

Schematic and PCB files are provided in KiCad format.

Gerbers and POS files (for component placement) are included in the Production directory.

BOMs for various assembly houses are also included in the Production directory.

Note: I'm currently awaiting an initial run of assembled boards from PCBWay for testing to make sure I did the board layout properly.