# dual_sensor_lamp_controller
PCB and firmware for a smart lamp with light and motion sensor.
# Smart Motion-Activated Night Lamp PCB

This repository contains the PCB design files and firmware for a smart, energy-efficient lamp controller, designed by Ali Rajaee, an Electrical Engineering student at the University of Isfahan.

## Functionality

The lamp's operation is based on a two-stage sensor system to maximize energy savings:

1.  **Light Sensing (LDR):** The circuit uses a Light Dependent Resistor (LDR) to detect ambient light. It only allows the main circuit to be powered when the surroundings are dark, preventing daytime operation.

2.  **Motion Sensing (PIR):** Once enabled by the LDR, a Passive Infrared (PIR) sensor scans for movement. If motion is detected, it triggers the microcontroller to turn the lamp on.

The lamp automatically turns off after a set period of no motion, further conserving energy.

## Technologies Used

* **Hardware Design:** PCB and schematic designed in **Altium Designer**.
* **Core Controller:** An **AVR microcontroller**.
* **Firmware:** Written in C using the **CodeVisionAVR** compiler.
* **Sensors:** PIR sensor for motion and LDR for ambient light.

## About The Designer

This project was designed and developed by **Ali Rajai**, an undergraduate Electrical Engineering student with a passion for electronic circuit design, embedded systems, and board-level repair.
