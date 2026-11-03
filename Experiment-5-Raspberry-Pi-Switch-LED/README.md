# Experiment 5 – Switch-Controlled LED using Raspberry Pi Pico

## Aim
To interface a pushbutton and LED with a Raspberry Pi Pico and control the LED using MicroPython.

## Components Required
- Raspberry Pi Pico
- LED
- Pushbutton
- 220Ω resistor
- Jumper wires

## Connections

| Component | Pico Pin |
|---|---|
| LED anode | GP15 through 220Ω resistor |
| LED cathode | GND |
| Pushbutton pin 1 | GP14 |
| Pushbutton pin 2 | GND |

## Program
The program uses GPIO 14 as input for the pushbutton and GPIO 15 as output for the LED. The internal pull-up resistor is enabled for the button.

## Working
When the pushbutton is pressed, the input becomes LOW and the LED turns ON. When the button is released, the LED turns OFF.

## Output
The LED glows while the pushbutton is pressed and turns OFF when released.

## Wokwi Simulation
https://wokwi.com/projects/479690544411431937

## Circuit Diagram
![Circuit Diagram](Circuit(5).png)
