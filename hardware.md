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
  - [Lab Experiments](#lab-experiments)

## PCB Design
These boards were designed, manufactured and tested during the Practical PCB Design and Manufacture (ECEN 5730) course at the University of Colorado at Boulder.
This course solidified my ability to translate ideas into functional circuit boards. I built prototypes using solderless breadboards before moving to multilayer PCBs, while gaining a comprehensive understanding of industry best practices. This includes risk management, testing methodologies, signal/power integrity, and manufacturability, all while meeting cost and schedule targets. 
### Instrument Driod
![instrument-driod-img](/public/img/instrument-driod.png)
 This custom-built "Instrument Droid" is a 4-layer PCB housing a microcontroller and a dedicated data acquisition system. It can be used to characterize various voltage sources, including power supplies and digital output pins. Its core functionality lies in measuring the Thevenin equivalent resistance of these sources as the current load fluctuates. By plotting the resistance against the changing current, the instrument droid provides a comprehensive characterization of multiple voltage sources. For more information [Click Here, coming soon...]().
### Golden Arduino
![golden-arduino-img](/public/img/golden-arduino.png)
This custom-built "Golden Arduino," is a minimalist Arduino board designed to achieve core functionalities. It prioritizes essential features for uploading code via USB, running with the Arduino IDE, and ensuring full compatibility with most Arduino Uno R3 shields. While maintaining commercial Arduino connectivity specifications, the Golden Arduino boasts additional functionalities for enhanced noise control, simplified assembly, streamlined testing, and efficient startup procedures. For more information [Click Here](https://drive.google.com/file/d/1v7sLqAxz2TlS9UWMopKReOcbZpwJAusF/view?usp=sharing).
### Good Vs. Bad Layout Board
![goood-v-bad-img](/public/img/good-v-bad-layout.png)
This PCB utilizes a 555 timer configured as an astable multivibrator to generate a 500Hz square wave with a 50% duty cycle. The output from the 555 timer triggers two SN74AHC14 hex inverters.  One inverter circuit includes a decoupling capacitor and a continuous ground return plane, while the other lacks these elements. By comparing the noise performance of these two layouts, we can observe the impact of proper design practices on PCB noise reduction. For more information [Click Here](https://drive.google.com/file/d/1vAGqYxZ14JId2595QzpmzcQCqJsF_GSF/view?usp=sharing).
### Astable Multivibrator
![555-timer-img](/public/img/555-timer-board.png)
I designed and fabricated a 500Hz astable vibrator circuit using an IC555 timer on a PCB to gain proficiency in the entire PCB design flow within Altium Designer. This project encompassed the POR (Plan of Record), prototyping, schematic capture, layout, assembly, and analysis, adhering to best practices in design and measurement. For more information [Click Here](https://drive.google.com/file/d/1vAIDYN3dhmb6S0dchkq_F6QjW78ltwsj/view?usp=sharing).

### Lab Experiments
Here are some of the imporant Lab experiments I performed in ECEN 5730: Practical PCB Design and Manufacture
- PDN Noise and Role of the Decoupling Capacitor [link](https://drive.google.com/file/d/1vnG7VLyzaD1nYsuLZARYHTnpzdUfR2JF/view?usp=sharing).
- Trace to Trace crosstalk and Importance of Return Paths [link](https://drive.google.com/file/d/1vypCbqzBD7SkqityPE9_jZgvobrkLoU8/view?usp=sharing).
- Trace Current Carrying Capacity [link](https://drive.google.com/file/d/1vpXw37XTkxrg3Y3JYRWyNuRssKsGYiN5/view?usp=sharing).
- Single Vs. Differentail Measurment Methods [link](https://drive.google.com/file/d/1wLDV93ogB_ZK4a2LnXl1ROMpf64mT7Ww/view?usp=sharing).
- Inrush and Operational Current Measurment [link](https://drive.google.com/file/d/1wDVcCmcssbPXKAFiuZtN6i98hIQldicP/view?usp=sharing).







