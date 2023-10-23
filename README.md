# PCB-Power-60W-Single-Port-USB-C-Powerbank-5S2P

This is a 6-layer board designed to be a single USB-C Port power bank-like board, capable of having 5s lithium-ion battery packs, and supplying up to 60W. It can also report battery level over an FTDI (Serial communication). Additionally, it features a Power Delivery (PD) chip and a charger chip for USB-C PD power negotiation.

## Key Components
- TPS257550 PD Controller from Texas Instruments
- BQ25731 Charge Controller from Texas Instruments
- STM32F030F4 MCU from ST

## System Details
- Operating System: FreeRTOS Kernel

## Images

<p align='center'>
    <img src='https://user-images.githubusercontent.com/16338014/216881986-10af49a8-99d7-4047-870e-c918bf6c204b.png' width='700'>
    <img src='https://user-images.githubusercontent.com/16338014/216882013-40ec2971-13d7-4e2f-aa1f-d13dc1d679ed.png' width='700'>
</p>
