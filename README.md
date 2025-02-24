<h1 align="center">Welcome to Project: nrf54_promicro </br> (an nRF54L1x Pro Micro inspired development board) </h1>
<div align="center">
  <a href="https://github.com/brendose/nrf54_promicro"></a>
  
<a href="#introduction">Introduction</a> &nbsp;&bull;&nbsp;
<a href="#directory">Directory</a> &nbsp;&bull;&nbsp;
<a href="#documentation">Documentation</a> &nbsp;&bull;&nbsp;
<a href="#notes">Notes</a>
</div>

# Introduction
The <b>nrf54_promicro</b> project is a Pro Micro inspired development board for the nRF54L15/L10 containing Bluetooth RFFE and battery charging, developed in KiCad 9. 
The purpose of this project is to provide a development platform for keyboard designs. Why? Because Bluetooth based keyboard designs require decent battery life.
The nRF52840 power draw limits the battery life of most keyboard based projects, however, when moving to the nRF54 the power draw can be minimized to a under 100uA/MHz. 
Further steps have been taken in the design to ensure minimal power draw can be achieve, including the use of high efficiency switching power supplies, low quiescent current (Iq) load switches and RF antenna tuning.

The board contains:

- A Nordic Semiconductors nRF54L10 / nRF54L15 (ARM Cortex M33 and RISC-V coprocessor)
- 2.45GHz Chip Antenna supporting Bluetooth LE
- Texas Instruments BQ24075 battery charger
- 2x 13 pin GPIO headers 
- USB-C connector, with bit-banged USB 1.1
- Charge Status indicator LED
- Bluetooth Status indicator LED

### Projects top-level directory

    .
    ├── libs                     # local library of components used in the project
    └── README.md

## Documentation

TBD

## Notes

This repository is not actively maintained, so if you spot any bugs, please <a href="hhttps://github.com/brendose/nrf54_promicro/issues/new">raise an issue</a> and I will try get to it.

This is not an officially supported Google product. 


