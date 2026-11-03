# Experiment 4 – LED Blinking using Raspberry Pi Pico

## Aim
To interface an LED with a Raspberry Pi Pico and control it using MicroPython.

## Components Required
- Raspberry Pi Pico
- LED
- 220Ω resistor
- Jumper wires

## Connections

| LED | Raspberry Pi Pico |
|---|---|
| Anode | GP15 through 220Ω resistor |
| Cathode | GND |

## Program
The MicroPython program controls the LED using GPIO pin 15. It switches the LED ON and OFF at one-second intervals.

## Working
The Raspberry Pi Pico sends a HIGH signal to GPIO 15 to turn ON the LED and a LOW signal to turn it OFF. This process repeats continuously.

## Output
The LED blinks continuously with a one-second ON and OFF delay.

## Wokwi Simulation
https://wokwi.com/projects/new/pi-pico

## Circuit Diagram
![Circuit Diagram](Circuit(4).png)
