# Welcome to mTX<sup>e</sup>!

**The MAVLink for EdgeTx open-source firmware for your R/C radio.**

The mTX project
- adds bi-directional, native MAVLink support to the EgdeTx firmware
- runs on EdgeTx radios with a color screen and a F4 or - better - a H7 processor
- is a fork of EdgeTx 2.12.4
- cooperates with the [mLRS](https://github.com/olliw42/mLRS) serial link and radio control system

## Installation

Installation largely follows the installation of EdgeTx. It involves three steps:

1. Flash the mTX firmware binary appropriate for your radio to the radio. You can follow the standard EgdeTx descriptions, except that you choose a different binary file. For radios with H7 processors the most convenient method for flashing is the "bootloader" method.
2. Copy the mTXMavW Lua widget script(s) to the radio's SD card. 
3. Install the widget(s) as usally. Use App mode.

## Acknowledgements
Sincere thanks go to the [EdgeTx project](https://github.com/edgetx/edgetx).
