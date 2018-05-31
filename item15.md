---
layout: page
title: Stamp Stack II-SX Microcontroller Kit
menu: Stamp Stack II
parent: xpctargetstuff.md
weight: 13
---
# Stamp Stack 2

<p align="center">
<img src="https://github.com/armlab-clemson/armlab_inventory/blob/gh-pages/images/stamp_stack_2.jpg?raw=true" width="600px" >
</p>

## Description
Designed to plug into any solderless breadboard, this 100%-compatible Basic Stamp 2 microcontroller is reverse-polarity protected, has a built-on serial programming connector and reset switch, and has an easily replaced interpreter & EEPROM.

Although somewhat larger, it's substantially less expensive than a true Parallax BS2 module, but still interfaces with our Sumovore Mini-sumo through the BS2-brainboard add-on.

## Initial Configuration And Setup

Stamp Stacks behave exactly like BASIC Stamps. The same commands, programming (editor) software, cables etc. are used.
1. Mount your Stamp Stack to a breadboard and apply power (+5 to 12 Volts DC –we recommend 6 VDC as being ideal). The LED on the Stamp Stack should be green.
2. Connect a standard (straight-through) serial cable between the Stamp Stack and an available serial port on your PC. If your PC does not have a serial port, HVW Tech. Has USB to RS-232 converters (Item# USB-001). Run the BASIC Stamp Editor software (available from the HVW Technologies website). The following instructions assume you are using the Windows editor software v2.1 Beta1.
3. Under the Run menu, select Identify, or simply click on the small “ID Card” icon in the toolbar. The editor software will scan all the available serial ports and identify all BASIC Stamps that it finds. A small window will list the COM
Port, the Device Type, the Firmware Version, Loopback Status, and Echo Status for each COM port. If all is well, it will say “BASIC Stamp 2” ; Version “v1.0”; Loopback “Yes”; Echo “Yes”.

4. If you do not see your Stamp Stack listed on any port, then see the Troubleshooting section of this manual. NOTE: When the software scans the ports, it is communicating with the Stamp Interpreter Chip on the Stamp Stack board. Since this is the same chip as the BS2 module, it will report that it has found a “BASIC Stamp 2” and NOT a “Stamp Stack 2”. This is normal.


[Stamp Stack II User manual](https://cdn.solarbotics.com/products/documentation/stamp%20stack%20ii%20v5.4.pdf)
