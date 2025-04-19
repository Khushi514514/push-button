# Push Button Counter

This is a simple embedded systems project that demonstrates a basic **Push Button Counter** using a microcontroller (e.g., Arduino, ESP32, etc.). Every time the button is pressed, the counter value increases and is displayed on the output device (e.g., serial monitor or LCD).

## Features

- Counts button presses in real-time
- Debouncing logic to avoid false triggering
- Displays current count
- Reset functionality (optional)

## Components Used

- Microcontroller (e.g., Arduino Uno)
- Push button
- Resistor (10kΩ pull-down)
- Breadboard and jumper wires
- (Optional) LCD display or LED

## How It Works

1. The push button is connected to a digital input pin.
2. When the button is pressed, a counter variable is incremented.
3. Debouncing is handled in code to ensure accurate counting.
4. The count is displayed either on the serial monitor or an LCD.

## Circuit Diagram

You can connect:
- One terminal of the button to a digital input pin (e.g., D2)
- The other terminal to GND
- A pull-down resistor (10kΩ) between the input pin and GND

