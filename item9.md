---
layout: page
title: GPIO-MM Digital I/O Module
menu: GPIO Digital I/O
parent: xpctargetstuff.md
weight: 7
---
# GPIO-MM Digital I/O Module
#### Reconfigurable 48-line Digital I/O + Counter/Timer PC/104 Module
#### GIPO-MM-XT Rev C, 10 Ctr/Timers, 40DIO

[GPIO-MM Digital I/O Module](http://www.diamondsystems.com/products/gpiomm)


<p align="center">
<img src="https://github.com/armlab-clemson/armlab_inventory/blob/gh-pages/images/GPIO-MM-Digital-IO-Module.png?raw=true" width="600px" >
</p>

## Description

GPIO-MM is a PC/104 digital I/O module based on an FPGA, allowing multiple feature sets to be implemented on the same hardware platform. The FPGA is a Xilinx Spartan 2 RAM-based device with 200K gates (XC2S200). An on-board configuraton flash memory device stores the FPGA code for automatic loading on power-up, and new code can be downloaded using a JTAG cable connected to a PC. Several standard off the shelf personalities are available, and custom ones can be developed either by users with Xilinx tools or by Diamond as a customization service. 
The right side I/O connector includes ESD protection circuitry for increased reliability, while the left side I/O connector offers high-drive logic buffers for increased load compatibility, along with jumper-configured pull-up / pull-down resistors. All digital I/O pins are set to input on power-up to avoid conflicts with external circuitry. 
Hardware configuration options include jumper-selectable base address and DMA level, plus a 10-position jumper lock for user-definable field configurability when used with custom designs. A 256-byte EEPROM provides convenient non-volatile storage for user-defined functionality. The board also includes the layout for an optional RS-232/422/485 serial port, so that a multi-protocol serial port can be integrated into custom designs. 
GPIO-MM contains 8 diagnostic LEDs located in the lower left corner. Off-the-shelf configurations use these LEDs to identify the personality programmed onto the board, while custom designs can use them for any purpose. An additional programmable LED in the lower right corner offers a simple way to verify successful FPGA programming.

## Standard feature sets 

* 10 "9513" style 16-bit counter/timers + 8 fixed digital inputs + 8 fixed digital outputs + 48 buffered programmable digital I/O
* 48 programmable digital I/O + 48 buffered programmable digital I/O
