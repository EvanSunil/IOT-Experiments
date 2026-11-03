# Experiment 3 – OLED Display using ESP32

## Aim
To interface an OLED display with an ESP32 and display text using I2C communication.

## Components Required
- ESP32 Development Board
- SSD1306 OLED Display (128x64)
- Jumper Wires

## Connections

| OLED Pin | ESP32 Pin |
|---|---|
| VCC | 3V3 |
| GND | GND |
| SDA | GPIO 21 |
| SCL | GPIO 22 |

## Working
The ESP32 communicates with the OLED display using the I2C protocol. The program initializes the display and prints text on the OLED screen.

## Output
The OLED displays:
- Hello, ESP32!
- IoT Experiment 3
- OLED Display

## Wokwi Simulation
https://wokwi.com/projects/479688278360466433

## Circuit Diagram
![Circuit Diagram](Circuit(3).png)
