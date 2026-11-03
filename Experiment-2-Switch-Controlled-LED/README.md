# Experiment 2: Switch-Controlled LED Using ESP32

## Aim
To interface a pushbutton switch and an LED with an ESP32 and control the LED using the pushbutton.

## Components Required
- ESP32 DevKit V1
- LED
- Pushbutton switch
- 220-ohm resistor
- Connecting wires

## Software Used
Wokwi Simulator

## Working Principle
The pushbutton is connected to GPIO 4 of the ESP32 using the internal pull-up resistor. When the button is pressed, the input reads LOW, and the ESP32 turns ON the LED connected to GPIO 2. When the button is released, the LED turns OFF.

## Result
The LED was successfully controlled using a pushbutton switch through the ESP32 in the Wokwi simulator.

## Circuit Diagram

![Circuit Diagram](Circuit(2).png)

## Wokwi Simulation
https://wokwi.com/projects/479686977127531521
