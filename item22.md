---
layout: page
title: SV203 B/C Servo Motor Controller Board
menu: Servo Motor Controller
parent: xpctargetstuff.md
weight: 19
---
# SV203 B/C Servo Motor Controller Board

[User manual](https://globedrop.com/wiki/_media/products:sv203_v.1.20_webmanual.pdf)

<p align="center">
<img src="https://github.com/armlab-clemson/armlab_inventory/blob/gh-pages/images/SV203.jpg?raw=true" width="600px" >
</p>

## Description

RC servos operate using feedback to compare the current position to an input pulse width, which typically repeats every 14 to 20 ms (milliseconds). If the pulse width lasts for approximately 0.6 ms, the servo will rotate to a maximum position. If the pulse width is increased to approximately 2.4 ms, the servo will rotate to the opposite maximum position (Figure 1). A 1.5 ms pulse will set the servo in the middle (neutral) position.
The SV203 controller is designed to the specifications of a Futaba servo model FP-S148. These servos have a neutral position at 1.52 ms. -90 degrees at 0.6 ms, and 90 degrees at 2.4 ms. Other servos may have slightly different values for these positions.
