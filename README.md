# CM4 Baseboard

Copyright (c) 2024 [Antmicro](https://www.antmicro.com)

## Overview

This project contains open hardware design files for a baseboard supporting System on Modules (SoMs) supporting Raspberry Pi Compute Module rev. 4.0 (CM4) pinout.
The design files were prepared in KiCad 7.x.

### Visualisation of the CM4 Baseboard with the CM4 LVDS Adapter

| ![CM4 baseboard with LVDS-adapter- top view](img/assembly_top_iso_black.png) | ![CM4 baseboard with LVDS-adapter- bottom view](img/assembly_bottom_iso_black.png) |
| :--------------------------------------------------------------------------: | :--------------------------------------------------------------------------------: |
|                                   Top view                                   |                                    Bottom view                                     |

## Key features

- Compatible with `Raspberry Pi CM4` (and `RPi CM4` compatible modules)
- Extended features for [Antmicro PolarFire SoM](https://github.com/antmicro/polarfire-som)
- Compact size (`107mm x 68mm`)
- Multiple power supply options (`USB-PD`, `PoE`, `9-15V DC Input Connector`) with automatic switching between sources
- `m.2 2280 PCIe 2.0 x4` slot for fast storage (`RPi CM4` supports `PCIe 2.0 x1` only)
- `USB-C 2.0 DRP` with `5V@1.5A` output
- `USB-C UFP` with `Power Delivery 15V@3A` input, used to expose 4 `UARTs`over the USB port
- `Gigabit Ethernet` with `PoE` input
- `DSI Adapter Connector` exposing with touchscreen control over `I2C` and power `5V@2A` to connect adapters for different displays
- `Antmicro Dual CSI` (4-line + 2-line) to connect external cameras
- `HDMI 2.0b` output
- `microSD` slot
- 2x `QWIIC` expansion connectors to connect external sensors or peripherals
- `NFC`(`PN7160`) with an external antenna connector
- All `GPIOs` are exposed through a dedicated connector

## Project structure

The main project directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* `lib` - contains the component libraries
* `img` - contains board visualization for this README
* `doc` - contains project realated pdf's (eg. schematics)
* `assets` - contains visual assets for showcasing the board on Antmicro [Open Hardware Portal](https://openhardware.antmicro.com)

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
