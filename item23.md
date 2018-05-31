---
layout: page
title: PAK-VIIIa Pulse Coprocessor
menu: PAK-VIII
parent: xpctargetstuff.md
weight: 20
---
# PAK-VIIIa Pulse Coprocessor

[User manual](https://cdn.instructables.com/ORIG/F38/GEEN/FBVHDZOK/F38GEENFBVHDZOK.pdf)

<p align="center">
<img src="https://github.com/armlab-clemson/armlab_inventory/blob/gh-pages/images/PAK8.jpg?raw=true" width="600px" >
</p>

## Description

The PAK-VIII is an 8 channel pulse output coprocessor. It can perform a variety of functions:

* Generate pulses continuously
* Generate a certain number of pulses and then stop
* Create pulses with varying duty cycles
* Count generated rising edges or falling edges
* Control servos
* Generate PWM
* Works with Basic Stamp's SHIFTIN and SHIFTOUT
* Easy to use

Like all PAKs, the PAK-VIII is simple to connect to a Stamp or any microcontroller. If your microcontroller can switch pins between input and output status, you can connect a single PAK with as few as 2 I/O lines. However, the PAK will allow you to use separate I/O pins (3 lines) if necessary. You can also connect multiple PAKs together using the same two or three lines if you provide an additional enable line for each PAK.

The PAK-VIII is a standard 28-pin IC. In order to operate, it must have a regulated supply of 5V and connection to a clock element. The PAK-VIII includes a 50MHz ceramic resonator that you can use to clock the chip. If you need more accuracy, a crystal or external oscillator may be used.
