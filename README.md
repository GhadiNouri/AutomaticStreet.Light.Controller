**# Automatic Street Light Controller

## Video Demonstration  
Short demo of the project:  
https://bit.ly/AutomaticStreetLightController

## Overview
A simple hardware project demonstrating an automatic street-light system that turns ON in darkness and OFF in daylight.  
The entire system is built using electronic components only —no programming, no microcontroller— and relies entirely on a light sensor (LDR) to control the LED lights.

## How It Works
The behavior depends on the amount of light detected by the LDR sensor:
- **When the sun rises (bright environment):**  
  The LDR detects light → LEDs turn OFF automatically.
- **When the sun sets (dark environment):**  
  The LDR detects darkness → LEDs turn ON automatically.
A transistor (2N2222 NPN) acts as a switch to control the LED based on the signal coming from the LDR.

## Hardware Components
- LDR (Light Dependent Resistor)
- 9V Battery
- Battery Connector
- Resistors (1kΩ)
- Transistor (2N2222 NPN)
- White LED
- Wires (soldered connections)

## Build Method
The project was assembled using soldering, not a breadboard.  
All connections were created manually to simulate a real-world hardware build and ensure stability.

## Circuit Diagram
Below is the main circuit schematic used in this project:
![Circuit Diagram](Circuit%20Design.png)

## Features
1. Fully automated ON/OFF control  
2. No programming or microcontroller  
3. Simple and reliable electronics design  
4. Real hardware implementation  

## Future Improvements
1. Replace LED with a high-power lighting module  
2. Add a solar charging system  
3. Add motion detection for better energy saving  
