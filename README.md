# Arduino LM35 Temperature Sensor Interface

This project involves interfacing an LM35 temperature sensor with an Arduino Uno and controlling the onboard LED based on temperature readings. The Arduino code is developed using the FreeRTOS library and not using any funtion like delay, millis to blink the led.

## Project Structure

The project consists of two tasks:

1. **TaskBlink:** Controls the onboard LED based on temperature readings.
2. **TaskAnalogRead:** Reads temperature values from the LM35 sensor.

## Setup

### Hardware Requirements

- Arduino Uno
- LM35 Temperature Sensor
- LED (onboard)

### Connections

- LM35 Analog Pin --> A0 on Arduino
- LED Pin --> BUILTIN_LED (Pin 13 on Arduino)

## Arduino Code

The Arduino code is organized into two tasks:

# Running the Code

1. Open the Arduino IDE.
2. Install the FreeRTOS library if not already installed.
3. Load the provided code (`main.ino`) onto the Arduino Uno.
4. Monitor the serial output for temperature readings and state changes.

# Proteus Circuit Simulation

The Proteus circuit simulation file (`assign1_arduino.pdsprj`) is included in the repository. This file can be opened in Proteus to simulate the circuit and observe the behavior of the temperature sensor and LED based on the Arduino code.

## Proteus Simulation Steps

1. Open Proteus.
2. Load the circuit simulation file (`assign1_arduino.pdsprj`).
3. Run the simulation to observe LED behavior based on temperature changes.

# Repository Structure

- **Arduino_Code:** Contains the Arduino code (`main.ino`).
- **Proteus_Circuit:** Contains the Proteus circuit simulation file (`assign1_arduino.pdsprj`).

# Evaluation Criteria

## Working Code:

- The code should be functional in the Arduino IDE.
- LED blinking should be appropriately controlled based on temperature conditions.
