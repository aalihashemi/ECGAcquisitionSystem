# ECGAcquisitionSystem
This repository contains the PCB, Schematics, and simulation files for an ECG acquisition system.
The system includes two different circuits for measuring ECG signals, one of them is based on AD8232 IC and the other one is the circuit that has been designed by us, which includes HPF, LPF, Nothch Filter, and Pre-amp (for RLD) circuits. For reading the output signals, you can use Test Points or the provided MCU (STM32F030F4P6 microcontroller). You can connect a micro-USB cable to the board from your PC, to power up the board and receive the data of measured signals on your PC (A CP2104 IC has been provided for USB-to-Serial conversion).

- The schematic and PCB have been designed on Altium Designer 22 software.
- Simulations have been done on LTspice software.

![image](https://github.com/aalihashemi/ECGAcquisitionSystem/assets/65431605/681e7b85-4a0e-4017-a7d6-c56f5303a5cd)
