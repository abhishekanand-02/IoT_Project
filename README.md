# IoT Clap-Activated Home Automation Project

## Overview

This project implements a clap-activated home automation system using an Arduino Uno, ultrasonic sensor, and relay. The system turns a light bulb on with two claps and off with another set of two claps.

## Code Structure

The C++ code for this project (found in `clap_automation.ino`) is structured as follows:

### Global Variables

- `sound_sensor`: Pin connected to the ultrasonic sensor (A0).
- `relay`: Pin connected to the relay (13).
- `clap`: Variable to track the number of claps.
- `detection_range_start` and `detection_range`: Variables to track the time between claps.
- `status_lights`: Boolean variable to store the state of the lights.

### Setup

Initializes the pins (`sound_sensor` and `relay`) as INPUT and OUTPUT, respectively.

### Loop

- Reads the status of the ultrasonic sensor.
- Tracks the number and timing of claps.
- Controls the state of the lights based on the claps.

## Usage

1. Connect the ultrasonic sensor and relay according to the provided wiring diagram.
2. Open the `clap_automation.ino` file in the Arduino IDE.
3. Upload the code to the Arduino Uno.
4. Power up the system.
5. Clap twice to turn the light on and clap twice again to turn it off.


## Contributing

This project welcomes contributions and improvements. Feel free to fork and submit pull requests.


## Acknowledgments

- First prize winner in the IoT based project competition at SIRT College, Bopal.
