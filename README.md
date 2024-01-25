# streamdeck

This is a simple arduino project that allows you to control your computer by using the F13-F24 keys. The arduino is connected to the computer via USB and the computer will recognize it as a keyboard. The F13-F24 keys are mapped to the pins on the ardunio and when a pin is grounded, the arduino will then send the key presses to the computer. The computer will recognize it as a key press. This is useful in applications such as OBS where you can map the F13-F24 keys to different scenes.

### Prerequisites

You will need the following:

- Arduino (32u4 and SAMD based board like Leonardo, Micro, Zero, ...)
- 10x 10k Ohm Resistors
- 10x Push Buttons
- 20x Wires
- Arduino IDE
- 3D printed case

### Getting started

1. Clone this repository
2. Open the `streamdeck.ino` file in the Arduino IDE
3. Upload the code to the Arduino
4. Wire up the Arduino to the push buttons
5. Connect the Arduino to the computer
6. Enjoy!
