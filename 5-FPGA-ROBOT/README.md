# FPGA-ROBOT

## Summary
- Degree project for Electronic Engineer in 2021
- 1 PCB with 2-layers for integration modules 
- FPGA based device with NodeMCU co-processor
- 

## Description
This was my degree project for the title of Electronic Engineer at the University. During my degree I was really interested in digital systems and FPGA design and this project is an example of that. With this project I wanted to apply a lot of knowledge in embedded systems and even robotics. The goal of this robot was to show the advantages of parallel hardware computing for high concurrent tasks, like in a robotics application, and compare them with a typical processor.



The project consisted of a complete electronic system with all subcircuits to perform tasks like controlling lights, opening doors, setting alarms, and even displaying information on a physical screen. The name of the project, MAFE, is an acronym in Spanish for Automation Model for Conventional Houses (Modelo de Automatización Para Casas Convencionales).

MAFE electronic systems interconnected before final installation:
![alt text](electronic-system.jpg "MAFE electronic systems")

This project was designed in PROTEUS 8 PROFESSIONAL with two PIC16F877A microcontrollers as the main controllers, programmed in C language using PIC C COMPILER and PICkit2. The five modules were designed to avoid having one large, complex PCB and to simplify wiring inside the model house. The five modules are as follows:

- Control: Microcontroller board with numerous IO for all the house peripherals. The top layer traces were essentially jumper wires.
![alt text](Control.png "Control board")

- Power: Relays for high-power loads. This board includes an 8-relay driver circuit with a logic control signal of 5VDC for 110-220VAC loads.
![alt text](Power.png "Power board")

- Sensors: Doors and windows switches. This circuit connects reed switches and IR sensors to detect events in the house.
![alt text](Sensors.png "Sensors board")

- Motors: For doors, windows, and garage actuators. This PCB contains H-bridges and servo drivers to control moving parts in the house.
![alt text](Motors.png "Motors board")

- Communication: Bluetooth and LCD circuits. Additionally, this module includes transistorized drivers for DC loads like ambient lighting and sirens.
![alt text](Communication.png "Cmmunication board")

The project was challenging enough for my younger self, and all of those boards were designed, programmed, and manufactured by me. The AC-DC converter was repurposed from an old printer to avoid the complexity of designing that power stage. Ultimately, the project worked well; I earned my Technician degree, and the model house turned out great.

![alt text](complete-project.jpg "MAFE project")