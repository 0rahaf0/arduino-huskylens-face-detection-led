
# Arduino HuskyLens Face Detection LED

This project demonstrates how to use an Arduino with a HuskyLens to turn on an LED when a face is detected. The HuskyLens is a machine vision sensor that is easy to use with Arduino. This repository contains the code and instructions for setting up the project.

## Components Needed

- Arduino Uno (or compatible)
- HuskyLens AI Camera
- LED
- Resistor (220Ω)
- Jumper wires
- Breadboard

## Wiring Diagram

[Include a wiring diagram here]

## Setup

1. Connect the HuskyLens to the Arduino using I2C (SDA to A4, SCL to A5).
2. Connect the LED to pin 7 on the Arduino with a resistor.
3. Load the provided code onto the Arduino.
4. Ensure that the HuskyLens is set to I2C protocol (General Settings >> Protocol Type >> I2C).

## Code

The code is provided in the `huskylens_face_detection.ino` file. It allows the Arduino to communicate with the HuskyLens, detect faces, and switch on the LED when a face is detected.

## Troubleshooting

- Make sure the HuskyLens is connected correctly.
- Ensure the protocol type is set to I2C on the HuskyLens.
- Check the serial monitor for debugging information.

## License

This project is licensed under the GNU Lesser General Public License.
