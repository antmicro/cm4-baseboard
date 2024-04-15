# CM4 Baseboard

Copyright (c) 2024 [Antmicro](https://www.antmicro.com)

![CM4 Baseboard render](img/cm4-baseboard-render.png)

## Overview

This project contains open hardware design files for a baseboard supporting System on Modules (SoMs) with Raspberry Pi Compute Module rev. 4.0 (CM4) pinout.
The design files were prepared in KiCad 7.x.

## Key features

* Compatible with `Raspberry Pi CM4` (and `RPi CM4` compatible modules)
* Extended features to support [Antmicro PolarFire SoM](https://github.com/antmicro/polarfire-som)
* Compact size (107mm x 68mm)
* Multiple power supply options (USB-PD, PoE, 9-15V DC Input Connector) with automatic switching between sources
* M.2 (key-M) 2280 PCIe 2.0 x4 slot for NVMe storage
* USB-C 2.0 DRP (5V with 1.5A) output
* USB-C UFP with Power Delivery (15V with 3A) input
* Gigabit Ethernet with PoE
* DSI Adapter Connector for customized display adapters
* Antmicro's 50-pin FFC camera connector for external camera modules and video accessories
* HDMI 2.0 output
* microSD slot
* 2x QWIIC expansion connectors for external sensors and peripherals
* NFC transceiver (PN7160) with an external antenna connector
* Expansion connector

## Project structure

The main project directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* `img` - contains graphics for this README
* `doc` - contains pdf schematics
* `assets` - contains visual assets for showcasing this design on [Open Hardware Portal](https://openhardware.antmicro.com)

## License

This project is published under the [Apache-2.0](LICENSE) license.
