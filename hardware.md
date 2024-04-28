---
layout: default
title: Hardware
---
**Table of Contents**
- [PCB Design](#pcb-design)
  - [Instrument Driod](#instrument-driod)
  - [Golden Arduino](#golden-arduino)
  - [Good Vs. Bad Layout Board](#good-vs-bad-layout-board)
  - [Astable Multivibrator](#astable-multivibrator)
- [8051 Board Bring Up](#8051-board-bring-up)

## PCB Design
These boards were designed, manufactured and tested during the Practical PCB Design and Manufacture (ECEN 5730) course at the University of Colorado at Boulder.
This course solidified my ability to translate ideas into functional circuit boards. I built prototypes using solderless breadboards before moving to multilayer PCBs, while gaining a comprehensive understanding of industry best practices. This includes risk management, testing methodologies, signal/power integrity, and manufacturability, all while meeting cost and schedule targets. 
### Instrument Driod
![placeholder](/public/img/instrument-driod.png)
 This custom-built "Instrument Droid" is a 4-layer PCB housing a microcontroller and a dedicated data acquisition system. It can be used to characterize various voltage sources, including power supplies and digital output pins. Its core functionality lies in measuring the Thevenin equivalent resistance of these sources as the current load fluctuates. By plotting the resistance against the changing current, the instrument droid provides a comprehensive characterization of multiple voltage sources. For more information [Click Here, coming soon...]().
### Golden Arduino
![placeholder](/public/img/golden-arduino.png)
This custom-built "Golden Arduino," is a minimalist Arduino board designed to achieve core functionalities. It prioritizes essential features for uploading code via USB, running with the Arduino IDE, and ensuring full compatibility with most Arduino Uno R3 shields. While maintaining commercial Arduino connectivity specifications, the Golden Arduino boasts additional functionalities for enhanced noise control, simplified assembly, streamlined testing, and efficient startup procedures. For more information [Click Here](https://drive.google.com/file/d/1v7sLqAxz2TlS9UWMopKReOcbZpwJAusF/view?usp=sharing).
### Good Vs. Bad Layout Board
![placeholder](/public/img/good-v-bad-layout.png)
This PCB utilizes a 555 timer configured as an astable multivibrator to generate a 500Hz square wave with a 50% duty cycle. The output from the 555 timer triggers two SN74AHC14 hex inverters.  One inverter circuit includes a decoupling capacitor and a continuous ground return plane, while the other lacks these elements. By comparing the noise performance of these two layouts, we can observe the impact of proper design practices on PCB noise reduction. For more information [Click Here](https://drive.google.com/file/d/1vAGqYxZ14JId2595QzpmzcQCqJsF_GSF/view?usp=sharing).
### Astable Multivibrator
![placeholder](/public/img/555-timer-board.png)
I designed and fabricated a 500Hz astable vibrator circuit using an IC555 timer on a PCB to gain proficiency in the entire PCB design flow within Altium Designer. This project encompassed the POR (Plan of Record), prototyping, schematic capture, layout, assembly, and analysis, adhering to best practices in design and measurement. For more information [Click Here](https://drive.google.com/file/d/1vAIDYN3dhmb6S0dchkq_F6QjW78ltwsj/view?usp=sharing).


## 8051 Board Bring Up
![placeholder](/public/img/8051-board-bringup.jpg)
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. For more information [Click Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).




