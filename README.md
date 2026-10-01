ECP 4-wire interface for Honeywell (Ademco) Alarm Panels such as Vista 20P

This circuit board allows you to connect an ESP32-WROOM-32 module or an ESP8266 D1 mini module
to a Honeywell Vista alarm system
using the ECP 12vdc serial interface and Alain Turbide's software at:
https://github.com/Dilbert66/esphome-vistaECP

Based on a modified (by Andrew Selle : eselle) version of Alain Turbide : Dilbert66's original interface circuit

I've been using it for several years to interface my Honeywell system to Home Assistant using esphome-vistaECP by Alain Turbide. (thanks Dilbert66)

I'm including all Kicad design files and the Gerber files to make the PCB,
as well as the FreeCAD design files and .stl models I used to make a 3d-printed case.

In the kicad directory there are pictures of the front and back of the board
and a PDF of the schematic if you don't want to install Kicad to view them.

There is a zip file with all gerbers inside. You can send this file to (probably) and good PCB fab shop to make your board(s).

This board uses opto-isolators on all lines to/from the Honeywell panel, and you can use either an ESP32-WROOM-32 module
or an ESP8266 D1 mini board. Both are shown on the schematic, and either one can be soldered to the board.

For all software information, refer to https://github.com/Dilbert66/esphome-vistaECP

I probably won't be maintaining this, just making it available for esphome-vistaECP users.
It's been very reliable for me for several years now, and I hope you find it useful.

Dan Baker
