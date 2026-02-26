# Automatic-Street-Light-System

Project Overview
The Automatic Street Light System is a smart embedded system designed to automatically control street lighting based on environmental light conditions and motion detection.
The system improves energy efficiency, reduces power wastage, and minimizes manual operation of street lights.
This project was developed as part of the ICT 215 – Robotics and Embedded Systems Course.

Project Objectives
1. Design an intelligent street lighting system.
2. Automatically switch street lights ON at night and OFF during the day.
3. Reduce energy consumption using sensor-based automation.
4. Simulate the system before hardware implementation.
5. Design and implement a custom Printed Circuit Board (PCB).
6. Develop Arduino-based control logic.

System Components
Hardware Components:
1. Arduino Uno (Microcontroller)
2. Light Dependent Resistor (LDR)
3. Passive Infrared (PIR) Motion Sensor
4. LED Street Light
5. Resistors and Capacitors
6. Transistor / Relay Module
7. Solar Panel (Power Source)
8. Power Supply Unit

Software & Tools Used
1. Arduino IDE – Programming and firmware development
2. Proteus – Circuit simulation
3. Tinkercad – 3D circuit visualization and testing
4. KiCad – PCB schematic and layout design
5. GitHub – Project documentation and version control

System Working Principle
1. The LDR sensor detects ambient light intensity.
2. During daylight, the street light remains OFF.
3. When darkness is detected, the system automatically turns the light ON.
4. The PIR sensor detects motion at night.
5. Light brightness increases only when movement is detected, helping to conserve energy.
6. The Arduino microcontroller processes sensor data and controls the lighting system.

System Block Diagram

LDR Sensor + PIR Sensor
          ↓
     Arduino Uno
          ↓
   Switching Circuit
          ↓
      LED Street Light

Simulation
The circuit was first tested using:
1. Proteus simulation environment
2. Tinkercad virtual prototyping
This helped verify system functionality before hardware implementation.

PCB Design
A custom PCB was designed using KiCad to:
1. Improve circuit reliability
2. Reduce wiring complexity
3. Create a compact and professional hardware layout

Results
1. Reliable automatic switching achieved.
2. Response time: approximately 3–4 seconds.
3. Stable operation during repeated ON/OFF cycles.
4. Significant reduction in unnecessary energy usage.

Future Improvements
1. IoT-based remote monitoring
2. GSM/WiFi fault reporting
3. Smart city integration
4. Adaptive brightness control
5. Weather-resistant outdoor deployment
