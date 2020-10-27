# ATEM-Tally-Camera-Light
## License: MIT License

Part 2 of a RFM69-based BlackMagic ATEM Tally Light system - On Camera Light

Part 1 is the SDI-connected controller
Part 2 is the on-camera tally light display

The controller uses the BMD SDI-Shield as an I2C interface to the control signals embedded in the SDI video stream emitted by the ATEM switchers, connected to an AdaFruit RadioFeather AVR 32u4 RFM69 controller and an AdaFruit neopixel strip.  

The Tally light receivers use the same AdaFruit RadioFeather RFM68 AVR 32U4 sticks with a NeoPixel strip that displays Red (LIVE), Green (PREVIEW) or dim Blue (operational, but not currently selected).

The Arduino IDE sketch is available on GitHub (... TBD URL ...)



