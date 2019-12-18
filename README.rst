GEM Demo Board
==============

.. figure:: img/gem-demo-board.png

This repository contains PCB design files for demo board compatible with `GEM1 <https://github.com/antmicro/gem1-adapter>`_ and `GEM2 <https://github.com/antmicro/gem2-adapter>`_ adapter boards.
The board acts as an expansion hat for Raspberry Pi platform.
It contains two FFC connectors supporting supporting CSI input and output.
The FFC connectors are pin compatible with Raspberry Pi Camera interface.
It is possible to connect Raspberry Pi Camera module to input connector on board and provide processed CSI data from output connector to Rasbperry Pi platform. 
The board allows to configure processing FPGA inside the GEM1 chip directly from Raspberry Pi (using SPI interface exposed on expansion goldpin header).
It also contains a 4-channel FTDI USB/MPSSE converter that can be used for configuring selected GEM designs from external host using USB connection and MPSSE bit-banging engine built into FTDI controller. 
For more details regarding possible connection scenarios please refer to the respective schematic sheets.
