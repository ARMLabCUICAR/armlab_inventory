---
layout: page
title: Diamond-MM Analog I/O Module
menu: Analog I/O Module
parent: xpctargetstuff.md
weight: 6
---

[12-bit Analog I/O PC/104 Module](http://www.diamondsystems.com/products/diamondmm#aor)

<p align="center">
<img src="https://github.com/armlab-clemson/armlab_inventory/blob/gh-pages/images/Diamond-MM Analog IO Module.PNG?raw=true" width="600px" >
</p>




### Description
Diamond-MM has all the primary features you expect in a high-performance analog I/O board at a reduced price. The analog input circuit uses a 12-bit A/D converte and can be configured for single-ended or differential input wiring, as well as unipolar or bipolar input ranges. It also offers 10 different input ranges, so it can work with a wide variety of input signals. The maximum A/D conversion rate is approximately 2,000-20,000 per second using interrupts (depending on the operating system) or 100,000 per second using DMA.
Two optional analog outputs provide 12-bit resolution over a 0-5V or user-adjustable output range with 8mA drive current and 4uS settling time. The D/A can also be used as a digital attenuator for an analog signal fed into one of the reference inputs.
The board contains 8 digital inputs and 8 digital outputs. It has an on-board 82C54 counter/timer chip to control the A/D sampling rate and provide general purpose counting functions.
Diamond-MM is available in four models: with or without analog outputs, and in commercial (0ºC-70ºC) or industrial (-40ºC to +85ºC) operating temperature range.
top


Analog Input Ranges
Diamond-MM supports multiple analog input voltage ranges, including both unipolar (+ only) and bipolar (+ and) ranges. In addition, a gain amplifier circuit allows you to reduce the input range to handle smaller signals.
To get the best resolution, select the smallest input range that is large enough to cover the entire range of your input signals. You can also install a resistor to customize the range exactly to your requirements. Note: On any A/D converter, the input range is the same as the full-scale A/D range divided by the gain. On Diamond-MM, the full-scale A/D range is 0-5V in unipolar mode and ±5V in bipolar mode.
