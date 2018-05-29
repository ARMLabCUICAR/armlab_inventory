---
layout: page
title: Diamond-MM Analog I/O Module
menu: Analog I/O Module
parent: xpctargetstuff.md
weight: 6
---

[12-bit Analog I/O PC/104 Module](http://www.diamondsystems.com/products/diamondmm#aor)

<p align="center">
<img src="https://github.com/armlab-clemson/armlab_inventory/blob/gh-pages/images/ESC629.PNG?raw=true" width="600px" >
</p>




## Description
Diamond-MM has all the primary features you expect in a high-performance analog I/O board at a reduced price. The analog input circuit uses a 12-bit A/D converte and can be configured for single-ended or differential input wiring, as well as unipolar or bipolar input ranges. It also offers 10 different input ranges, so it can work with a wide variety of input signals. The maximum A/D conversion rate is approximately 2,000-20,000 per second using interrupts (depending on the operating system) or 100,000 per second using DMA.
Two optional analog outputs provide 12-bit resolution over a 0-5V or user-adjustable output range with 8mA drive current and 4uS settling time. The D/A can also be used as a digital attenuator for an analog signal fed into one of the reference inputs.
The board contains 8 digital inputs and 8 digital outputs. It has an on-board 82C54 counter/timer chip to control the A/D sampling rate and provide general purpose counting functions.
Diamond-MM is available in four models: with or without analog outputs, and in commercial (0ºC-70ºC) or industrial (-40ºC to +85ºC) operating temperature range.
top


Analog Input Ranges
Diamond-MM supports multiple analog input voltage ranges, including both unipolar (+ only) and bipolar (+ and) ranges. In addition, a gain amplifier circuit allows you to reduce the input range to handle smaller signals.
To get the best resolution, select the smallest input range that is large enough to cover the entire range of your input signals. You can also install a resistor to customize the range exactly to your requirements. Note: On any A/D converter, the input range is the same as the full-scale A/D range divided by the gain. On Diamond-MM, the full-scale A/D range is 0-5V in unipolar mode and ±5V in bipolar mode.
Unipolar
Input Range    Resolution
0 - 10V    2.44mV
0 - 5V    1.22mV
0 - 2.5V    0.61mV
0 - 1V    0.244mV
0 - 0.5V    0.122mV
Custom    (10KΩ /R)/4096)V
Bipolar
Input Range    Resolution
>±10V    4.88mV
±5V    2.44mV
±2.5V    1.22mV
>±1V    .488mV
±0.5    .244mV
Custom    (10KΩ /R)/2048)V

top


Analog Output Ranges
The full-scale analog output voltage range is unipolar and is preset to 0 - 5V. However, you can adjust this range anywhere from 0 - 4V to 0 - 10V by adjusting a potentiometer on the board. You can also supply an external reference signal to each DAC individually to select unique ranges for each output channel. If the reference signal is an AC waveform (e.g. an audio signal), then the DAC can be used as an attenuator (volume control).
Note: The -NA versions of Diamond-MM do not have analog outputs.
top


A/D Conversion Methods and Rates
To provide flexibility in integrating with your application, Diamond-MM offers several methods of controlling A/D conversions. An A/D conversion can be triggered in 3 different ways: software command, external trigger, or on-board pacer clock. After the conversion is done, the data can be transferred from the board to system memory in 3 ways: software command, interrupt routine, or DMA transfer. Different conversion rates require the use of different transfer methods:
Software command    2,000/sec max (approx.)
Interrupt routine    20,000/sec max (approx.)
DMA transfer    100,000/sec max (board limit)
top


Free Software
Diamond-MM comes with free driver software compatible with C and Basic languages. Example programs are included to get you started quickly. Some examples of the supported board operations are:
•    A/D conversion on single channel
•    A/D conversion scan on multiple channels
•    Interrupt-based A/D conversions
•    DMA A/D conversions
•    Analog output on single channel
•    Analog output on both channels
•    Program counter/timers
•    Digital input, bit and byte
•    Digital output, bit and byte
top


I/O Header Pinout
Vin 15 / 7-    1    2    Vin 7 / 7+
Vin 14 / 6-    3    4    Vin 6 / 6+
Vin 13 / 5-    5    6    Vin 5 / 5+
Vin 12 / 4-    7    8    Vin 4 / 4+
Vin 11 / 3-    9    10    Vin 3 / 3+
Vin 10 / 2-    11    12    Vin 2 / 2+
Vin 9 / 1-    13    14    Vin 1 / 1+
Vin 8 / 0-    15    16    Vin 0 / 0+
Analog Ground    17    18    VRef Out (+5V/-5V)
Analog Ground    19    20    Vout 0
Analog Ground    21    22    Vout 1
Analog Ground    23    24    +15V Output
-15V Output    25    26    VRef In 0
Analog Ground    27    28    VRef In 1
Counter 0 in-    29    30    Digital Ground
Counter 0 Out    31    32    Counter 2 Out
Digital Out 7    33    34    Digital Out 6
Digital Out 5    35    36    Digital Out 4
Digital Out 3    37    38    Digital Out 2
Digital Out 1    39    40    Digital Out 0
Digital In 7    41    42    Digital In 6
Digital In 5    43    44    Digital In 4
Digital In 3    45    46    Digital In 2
Digital In 1    47    48    Digital In 0
+5V    49    50    Digital Ground





top


Specifications
Analog Inputs
Number of inputs    8 differential or 16 single-ended (user selectable)
A/D resolution    12 bits (1/4096 of full scale)
Bipolar ranges    ±10V, ±5V, ±2.5V, ±1V, ±0.5V, Custom
Unipolar ranges    0-10V, 0-5V, 0-2.5V, 0-1V, 0-.5V, Custom
Input bias current    50nA max
Max. input voltage    ±10V for linear operation
Overvoltage protection    ±35V on any analog input
Input Impedance    10^13 ohms
Conversion trigger    software trigger, internal pacer clock, or external TTL signal
Analog Outputs
Number of outputs    2
D/A resolution    12 bits (1/4096 of full scale)
Output ranges    0-5V, adjustable, or external reference input
Output current    ±8mA max per channel
Settling time    4µS max to ±2/2 LSB
Relative accuracy    ±1 LSB
Nonlinearity    ±1 LSB, monotonic
Reset    All channels reset to OV
Digital I/O
Number of inputs    8, HCT/TTL compatible
Input voltage    
Logic 0:    0.0V min, 0.85 max
Logic 1:    2.0V min, 5.0V max
Input current    ±1µA max
Number of outputs    8, HCT/TTL compatible
Output voltage    
Logic 0:    0.0V min, 0.33 max
Logic 1:    3.8V min, 5.0 max
Output current    ±4mA max per line
Counter/Timers
A/D Pacer clock    32-bit down counter (2 82C54 counters cascaded)
Clock source    10MHz on-board source or external signal
General purpose    16-bit down counter (1 82C54 counter)
Interrupt/DMA trigger    End of A/D conversion
General
Power supply    +5VD±10%@165mA typical
±15V output current    ±10mA max with DACs unloaded
Operating temperature    0°C to +70°C Standard, -40°C to +85°C Extended
Weight    3.3oz/93g
MTBF    DMM-XT 372,809 hours
RoHS    Compliant


