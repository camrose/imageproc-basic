imageproc-basic
===============

Basic IDE project for an ImageProc 2.5 board.

Only the bare minimum of chip setup is done is done:
- Core clock and PLL to 40 Mhz Xtal
- Set GPIO modes and defaults on pins
- Start microsecond timer (sclock)

Example
-------

An example is provided in this template, which should indicate if your board is "alive":
- LED_1 is turned on after setup
- In the main loop, LED_2 is toggled at 1Hz

Note that LED_1 should be RED, and LED_2 should be GREEN, but this varies greatly between boards.

Using this template
--------------------
Follow examples of where to make further includes and setup calls. Examples are provided in comment lines.

Future
======
Further refinements will be made to this template in the future. Some of these must be kept in sync with imageproc-lib.

Planned:
- A single setup() function, akin to Arduino; yields a cleaner main()
- A single 'imageproc.h' header that encapsulates chip support and board support packages
- More stock examples
- Considerations for future portability (ARM Cortex M)