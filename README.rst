GEM Demo Board
==============

Copyright (c) 2020 `Antmicro <https://www.antmicro.com>`_

.. figure:: img/gem-demo-board.png

This repository contains PCB design files for a demo board compatible with the `GEM1 <https://github.com/antmicro/gem1-adapter>`_ and `GEM2 <https://github.com/antmicro/gem2-adapter>`_ adapter boards.

The board acts as an expansion hat for the Raspberry Pi platform.

It contains two FFC connectors supporting CSI input and output.
The FFC connectors are pin compatible with the Raspberry Pi camera interface.
It is possible to connect a Raspberry Pi camera module to the input connector on the board and provide processed CSI data from the output connector to a Rasbperry Pi platform. 
The board allows to configure the processing FPGA inside the GEM1 chip directly from the Raspberry Pi (using the SPI interface exposed on the expansion goldpin header).

It also contains a 4-channel FTDI USB/MPSSE converter that can be used for configuring selected GEM designs from an external host using a USB connection and the MPSSE bit-banging engine built into FTDI controller. 
For more details regarding possible connection scenarios please refer to the respective schematic sheets.
