# Klipper Screen Menus for use with AFC and Box Turtle
*not an official Armored Turtle project*

For official [Box Turtle](https://github.com/ArmoredTurtle/BoxTurtle) Software, check out [AFC-Klipper-Add-On](https://github.com/ArmoredTurtle/AFC-Klipper-Add-On)

## Instructions

*Use all settings and macros at your own risk*

1. Copy the `KlipperScreen Menus` folder into your `~/printer_data/config/`
2. Add `[include KlipperScreen Menus/*]` to your `Klipperscreen.conf`
3. Add `BTKS_Macros.cfg` to your macro folder or to `~/printer_data/config/`
   - Add `[include BTKS_Macros.cfg]` to your `printer.cfg` if it is not added to a folder that is included in your `printer.cfg`
4. Service restart Klipper
5. Restart Klipperscreen
