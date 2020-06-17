# Configurations

Source firmware for Artillery Sidewinder X1, running stock mainboard, but fit with BL Touch. 
ABL (Bilinear) activated among other small tweaks. BL Touch should be wired up as per the Waggster method (into the Extruder LED Pins), and recomend using the Waggster files to flash the TFT. 

Pre-tested Configurations for Marlin Firmware 2.0.5

Marlin Firmware is configured using two files:

- `Configuration.h` contains core configuration options like machine geometry.
- `Configuration_adv.h` contains optional settings for advanced and low level features.

For Graphical LCD these files may also be included:

- `_Bootscreen.h` provides the bitmap for a custom Boot Screen.
- `_Statusscreen.h` provides bitmaps to customize the Status Screen.

See the [Configuration page](https://marlinfw.org/docs/configuration/configuration.html) for more information about configuration and individual configuration options.
