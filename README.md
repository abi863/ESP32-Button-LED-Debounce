# Button-Controlled LED with Debouncing

## Objective
Read a push-button and toggle an external LED using basic software debouncing.

## Components
- ESP32
- Push Button
- LED
- 220Ω Resistor

## Pin Connections
- Push Button → GPIO 4
- LED → GPIO 2
- Button → GND
- LED → GND through 220Ω resistor

## Software Debouncing
A 50 ms debounce delay is used to prevent multiple detections caused by mechanical button bouncing.

## Working
Each button press toggles the external LED.

- First press → LED ON
- Second press → LED OFF
- Third press → LED ON

## Simulation
The project was simulated using Wokwi before hardware testing.

## Wokwi Simulation
Paste your Wokwi project link here.
