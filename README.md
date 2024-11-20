# Motion-sensor
# Intro
This GitHub page details a project done by Daniel Arinze as part of the completion of GPGN590A at the Colorado School of Mines, Fall 2024. Herein I discuss the creation of a low-cost, motion sensor using Arduino boards and code. Code is found in Sensor.ino. May this page be a reference to those who come after.
# Why make a motion sensor ?
Asides from being cool, motion sensors are applicable in field surveys that involve leaving equipment in the field and at the mercy of criters such as field mice and birds. This motion sensor is equiped with a buzzer to scare off creatures that come too close to the set up. The set up is relatively affordable and the challenge of assembling the pieces together is entertaining.
# Sensor components
The sensor components utilized in this project include a breadboard, Arduino uno R3 board, LED light, a 220 ohm resistor, A buzzer, Hcsr04 sonic emitter and receiver and a handful of jumper wires.
# Sensor wiring
Arduino Uno 5v - HCSR VCC
Arduino Uno GND - HCSR GND
Arduino Uno 10 - HCSR Echo
Arduino Uno 9 - HCSR Trig
Arduino Uno 11 - Buzzer positive node in breadboard
Arduino Uno GND - Buzzer negative node in breadboard
Arduino Uno GND - Negative end of LED and resistor
Arduino Uno 13 - Other end of resistor
Resistor is placed in between negative end of LED and Arduino Uno GND

![Image (1)](https://github.com/user-attachments/assets/17bb7ff4-ae45-4b30-a60c-810397d9fd8a)
![Image (2)](https://github.com/user-attachments/assets/77b5a643-2f36-4690-9a66-cb6748ca8883)
![Image (3)](https://github.com/user-attachments/assets/4b0aaf3a-89be-4e20-bf80-14e3f1b97908)
![Image (4)](https://github.com/user-attachments/assets/5c4e75e3-ff8a-4bb0-8ea5-8442a1731479)
![Image (5)](https://github.com/user-attachments/assets/37bbfc08-5c59-4de0-8ba2-7d930e410ff1)
