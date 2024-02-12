
# Raspberry Pi RGB LED Controller

This project allows you to control an RGB LED connected to a Raspberry Pi using sliders in a graphical user interface (GUI). The RGB LED can be adjusted to display various colors by changing the intensity of the red, green, and blue components.

## Components Used

- Raspberry Pi
- RGB LED
- Jumper wires

## Installation

1. Ensure you have Python installed on your Raspberry Pi.
2. Install the required Python libraries:
   - `gpiozero`
   - `guizero`
   - `colorzero`

You can install the libraries using the following commands:

```bash
pip install gpiozero guizero colorzero
```

## Usage

1. Connect the RGB LED to the GPIO pins of the Raspberry Pi.
2. Run the Python script `rgb_led_controller.py`.
3. Adjust the sliders in the GUI to change the intensity of the red, green, and blue components of the RGB LED.
4. Observe the RGB LED changing colors in real-time based on the slider values.

## Wiring

Connect the RGB LED to the following GPIO pins of the Raspberry Pi:

- Red pin: GPIO 18
- Green pin: GPIO 23
- Blue pin: GPIO 24

Ensure to use appropriate resistors to limit the current flowing through the RGB LED.

## GUI Controls

- Three sliders are provided to adjust the intensity of the red, green, and blue components of the RGB LED.
- Moving each slider will dynamically change the color of the RGB LED.

## License

This project is licensed under the [MIT License](LICENSE).
