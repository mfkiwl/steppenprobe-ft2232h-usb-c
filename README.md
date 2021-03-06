Steppenprobe
============
Open Source Hardware JTAG/SWD/UART/SWO interface board

https://github.com/diegoherranz/steppenprobe

Basic specs:
-----------

- Open Source Hardware and designed in [KiCad](https://kicad-pcb.org/).
- FT2232H-based
- Simultaneous operation of JTAG/SWD and UART/SWO.
- STDC14 connector: standard Arm Cortex debug connector (1.27 mm pitch) with extra pins for UART. JTAG/SWD and UART on a single connector while being compatible with the standard Arm Cortex debug connector (middle 10 pins).
- USB powered: no power supply needed.
- USB type-C receptacle: more convenient (reversible) and future-proof (it should be the most common connector in the near future even if it isn't now, as of late 2019).
- OpenOCD compatible.
- JTAG or SWD use without any jumper or switch operation required (configured from OpenOCD).
- Switch-selectable UART RX or SWO operation.
- Signals also available on 2.54 mm pin header.
- 4 GPIO.
- System Reset tactile switch.
- I/O buffers for protection and to be able to use a wide voltage range (1.65 V to 5.5 V).
- Descriptive LED indicators.

Schematic PDF, Gerbers and other generated files:
---------------------------------------------
See [releases](https://github.com/diegoherranz/steppenprobe/releases).

3D renders
----------
![PCB top view](images/PCB_render_top.png) ![PCB bottom view](images/PCB_render_bottom.png)
