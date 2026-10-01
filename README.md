ECP 4-wire interface for Honeywell (Ademco) Alarm Panels such as Vista 20P

This circuit board allows you to connect an ESP8266 D1 mini module
to a Honeywell Vista alarm system
using the ECP 12vdc serial interface and Alain Turbide's software at:
https://github.com/Dilbert66/esphome-vistaECP.

<img width="3472" height="4624" alt="vistaECP-mounted-on-honeywell-panel" src="https://github.com/user-attachments/assets/5f68194e-ff8e-4aae-89a2-4b584fec887d" />

This involves soldering parts to a printed circuit board, so be very careful how you pronounce the word solder.
Either the 'l' is silent and the 'r' is pronounced, or maybe it's the other way around. One is the good way, and the other way is stupid and evil.
It's like those mindless jerks who insist on breaking their eggs on the wrong end. Gulliver can tell you more about that.

Where was I????? Oh, yeah...

This circuit is based on a modified (by Andrew Selle : eselle) version of Alain Turbide : Dilbert66's original interface circuit

I've been using it for several years to interface my Honeywell system to Home Assistant using esphome-vistaECP by Alain Turbide. (thanks Dilbert66)

I'm including all Kicad design files and the Gerber files to make the PCB,
as well as the FreeCAD design files and .stl models I used to make a 3d-printed case and a bushing to connect it through a knockout on the alarm panel.

In the kicad directory there are pictures of the front and back of the board
and a PDF of the schematic if you don't want to install Kicad to view them.

There is a zip file with all gerbers inside. You can send this file to (probably) and good PCB fab shop to make your board(s).

This board uses opto-isolators on all lines to/from the Honeywell panel, and soldered through-hole components.

For all software information, refer to https://github.com/Dilbert66/esphome-vistaECP

I probably won't be maintaining this, just making it available for esphome-vistaECP users.
It's been very reliable for me for several years now, and I hope you find it useful.

I started work on a board supporting either a D1 mini board or an ESP32-WROOM-32 module, but never finished it because
this version works so well for me.

Dan Baker

<img width="1083" height="603" alt="vistaECP-Front-2026-09-30" src="https://github.com/user-attachments/assets/60171222-cd28-4099-a38c-352ac4db4ef4" />

<img width="1083" height="603" alt="vistaECP-Back-2026-09-30" src="https://github.com/user-attachments/assets/afc639b5-ee32-4044-aa6d-d97f4734e7b6" />


[vistaECP-Schematic.pdf](https://github.com/user-attachments/files/32884098/vistaECP-Schematic.pdf)


