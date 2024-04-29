---
layout: default
title: Firmware
---
**Table of Contents**
- [Digital Compass](#digital-compass)
- [8051 Board Bring Up](#8051-board-bring-up)


## Digital Compass
![digital-compass-img](/public/img/digital-compass.jpg)
I designed and implemented a baremetal driver on the Arm Cortex M0+ based FRDMKL25z, for an SS1306 OLED display, enabling control over the displayed image, image polarity (positive/negative), mirroring, and orientation. The driver integrates seamlessly with a QMC5883L compass module, rendering compass heading data on the display. A built-in state machine facilitates switching between various display modes, while a frame rate calculation function aids in system testing and diagnostics. This project demonstrates my proficiency in embedded systems development, encompassing low-level driver programming, sensor integration, and state management. For more information [click here](https://github.com/krish0706/digital-compass).

## 8051 Board Bring Up
![placeholder](/public/img/8051-board-bringup.jpg)
Interfaced a 32KB NVRAM (using a 373 latch for multiplexing) with 8051 and a bit-banged an I2C interface achieving 100kHz communication with EEPROM and IO expanders on an AT89C51. Further streamlined development by establishing a toolchain utilizing make, SDCC, and batchisp.
