<h1 align="center">Welcome to Project: nrf54_promicro </br> (nRF54L1x Pro Micro inspired development board) </h1>
<div align="center">
  <a href="https://github.com/brendose/nrf54_promicro"></a>
  
  ![Alt text](/images/nrf54_promicro.png?raw=true)
  
<a href="#introduction">Introduction</a> &nbsp;&bull;&nbsp;
<a href="#directory">Directory</a> &nbsp;&bull;&nbsp;
<a href="#documentation">Documentation</a> &nbsp;&bull;&nbsp;
<a href="#notes">Notes</a>
</div>

# Introduction
The <b>nrf54_promicro</b> project revolutionizes nRF52840 based keyboard projects by utilizing the Nordic Semiconductors nRF54L10/L15 Bluetooth transceiver, achieving sub-100uA/MHz power draw!
<br>
<br>
We're challenging the status quo of limited wireless keyboard battery life with the nRF54L15/L10, achieving unprecedented power efficiency. Why? Because Bluetooth based keyboard designs require decent battery life.
The nRF52840 power draw limits the battery life of most keyboard based projects, however, moving to the nRF54 the power draw can be minimized to a under 100uA/MHz. This Pro Micro-inspired board, designed in KiCad 9, 
integrates optimized power circuitry such as; the use of a high efficiency switching power supply, carefully selected low quiescent current (Iq) load switch and meticulous RF antenna tuning, wasting no power and
offering a development platform for keyboards that redefines what it means to have "good battery life".


The board contains:

- A Nordic Semiconductors nRF54L10 / nRF54L15 (ARM Cortex M33 and RISC-V coprocessor)
- 2.45GHz Chip Antenna supporting Bluetooth LE
- Texas Instruments BQ24075 battery charger
- 2x 13 pin GPIO headers 
- USB-C connector, with bit-banged USB interface
- Charge Status indicator LED
- Bluetooth Status indicator LED

### Projects top-level directory

    .
    ├── bom                      # Bill of Materials
    ├── images                   # Images used on this GitHub page
    ├── libs                     # Local component library
    ├── plots                    # Assembly drawings of the design
    ├── schematics               # Schematics of the design      
    └── README.md

## Documentation

TBD

## Notes

This repository is not actively maintained, so if you spot any bugs, please <a href="hhttps://github.com/brendose/nrf54_promicro/issues/new">raise an issue</a> and I will try get to it.

This is not an officially supported Google product. 


