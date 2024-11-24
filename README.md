
# Blink LED Code for Arduino

This code is an Arduino sketch that blinks an LED connected to pin 2 with a 1-second interval (500ms ON, 500ms OFF).

## How It Works

1. The `setup()` function initializes pin 2 as an output.
2. The `loop()` function repeatedly:
   - Turns the LED on.
   - Waits for 500 milliseconds.
   - Turns the LED off.
   - Waits for another 500 milliseconds.

## Usage

1. Connect an LED to pin 2 of your Arduino board:
   - The longer leg (anode) of the LED should be connected to pin 2 through a resistor (220Ω or 330Ω).
   - The shorter leg (cathode) should be connected to the ground (GND).
2. Upload this code to your Arduino using the Arduino IDE.
3. Observe the LED blinking on and off.

## File List

- **BlinkLED.ino**: The Arduino sketch file.
- **README.md**: This documentation file.

## Notes

- Ensure that the resistor is used to limit the current and protect the LED from damage.
- You can change the pin number or delay values as needed.
