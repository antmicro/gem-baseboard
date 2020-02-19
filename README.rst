GEM1 Demo Board
==============

.. figure:: img/gem-demo-board.png

This repository contains PCB design files for a demo board compatible with the `GEM1 <https://github.com/antmicro/gem1-adapter>`_ adapter board.
It has been developed as a carrier board for showcasing the rapid ASIC design using chiplet technology.
The board has been designed by `Antmicro <https://www.antmicro.com>`_ in cooperation with `zGlue <http://www.zglue.com>`_

Key features
------------

* expansion hat for Raspberry Pi platform
* MIPI CSI-2 Input and output connectors sharing Raspberry Pi Camera pinout
* SPI interface and GPIOs allowing the GEM1 chip to be re-configured from Raspberry
* debug console from GEM1 routed to UART port available on Raspberry Expansion pinheader
* on-board 4-channel FTDI chip with MPSSE support for programming the GEM from external host

For more details regarding possible connection scenarios please refer to the respective schematic sheets.
Please note that the actual functionality of the board depends on the chiplet configuration routing file uploaded to the GEM1 IC.
