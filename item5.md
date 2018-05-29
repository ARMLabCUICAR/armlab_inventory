---
layout: page
title: DM5605
menu: DM5605
parent: xpctargetstuff.md
weight: 4
---


# DM5605

<p align="center">
<img src="https://github.com/armlab-clemson/armlab_inventory/blob/gh-pages/images/DM6505.jpeg?raw=true" width="600px" >
</p>

## Description
The DM5604 dataModule analog output board turns your IBM PC-compatible cpuModule or other PC/104
computer into a high-performance testing and control system. Ultra-compact for embedded and portable applications,
the DM5604 features:
Eight fast-settling 12-bit analog output channels,
±5, ±10, 0 to +5, or 0 to +10 volt analog output range,
Simultaneous updating of all output channels,
24 TTL/CMOS 8255 based programmable digital I/O lines,
Software enabled interrupts IRQ2-IRQ7, IRQ9-IRQ15 (DM6604)
+5 volt only operation, 2.35W power consumption,
BASIC and Turbo C source code; diagnostics program

## Digital-Analog Conversion
The digital-to-analog (D/A) circuitry features two 12-bit converter channels in each AD7237 D/A converter IC for a total of eight output channels. The two channels in each AD7237 are internally double buffered and all channels are simultaneously updated by issuing a single command. Each channel can be jumped to one of four output voltage ranges, ±5, ±10, 0 to +5, or 0 to +10 volts


## Installation Guide

Before installing the module in your system, check the jumper and switch settings.
The DM5604 comes with a stack through P1 connector. The stack through connector lets you stack another board
on top of your DM5604, plugging it into the data bus through the pins on the non-component side of the board.
To install the module, follow the procedures described in the computer manual and the steps below:
1. Turn OFF the power to your system.
2. Touch a metal frame or to discharge any static buildup and then remove the module from its antistatic bag.
3. Select the appropriate standoffs for your application to secure the board when you install it in your system
(two sizes are included with the board).
4. Holding the module by its edges, orient it so that the P1 bus connectors pin 1 lines up with pin 1 of the
expansion connector onto which you are installing the module.
5. After carefully positioning the module so that the card edge connector is resting on the expansion connector,
gently and evenly press down until it is secured on the connector.
NOTE: Do not force the module onto the connector. If the module does not slide into place, remove it and
try again. Wiggling the module or exerting too much pressure can result in damage to the DM5604 or to the
computer board.
6. After the module is installed, connect the cable to I/O connector P2 on the module. When making this
connection, note that there is no keying to guide you in orientation. You must make sure that pin 1 of the
cable is connected to pin 1 of P2 (pin 1 is marked on the module with a small square). For twisted pair
cables, pin 1 is the dark brown wire; for standard single wire cables, pin 1 is the red wire.
7. Make sure all connections are secure.
