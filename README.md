

# Clap-On Light Project

This project demonstrates how to control a light using sound (claps) with the help of a microphone sensor, Arduino, and simple electronic components. It provides an affordable and innovative solution for sound-activated automation.

## Features

- Turn lights on/off with the sound of claps.
- Adjustable sensitivity of the microphone sensor.
- Low-cost and easy to set up with minimal components.
- Suitable for beginner-level Arduino enthusiasts.

## Components Used

- **Hardware**:
  - Arduino Uno
  - Microphone sensor module
  - Relay module
  - Light bulb or LED
  - Jumper wires
  - Resistors
  - Breadboard
- **Software**:
  - Arduino IDE

## Project Structure

```
Clap-On-Light/
├── .gitignore                  # Git ignore rules (optional)
├── README.md                   # Project documentation
├── circuit_diagram.png         # Circuit schematic for the project
├── clap_on_light.ino           # Arduino sketch (main code)
└── images/
    ├── demo_image_1.png        # Example: Light turning ON
    └── demo_image_2.png        # Example: Light turning OFF
```

## Circuit Diagram

![Circuit Diagram](circuit_diagram.png)

## How It Works

1. **Microphone Sensor**: Detects sound waves (claps) and converts them into an electrical signal.
2. **Arduino Uno**: Processes the signal from the microphone sensor and determines if it matches the desired pattern (e.g., two quick claps).
3. **Relay Module**: Acts as a switch to turn the connected light ON or OFF based on Arduino's instructions.

## Getting Started

### Prerequisites

1. Install the [Arduino IDE](https://www.arduino.cc/en/software/).
2. Gather all the required components listed above.

### Setup Instructions

1. **Hardware Setup**:
   - Connect the microphone sensor, relay module, and light as per the provided circuit diagram.
   - Use the `circuit_diagram.png` file for reference.

2. **Software Setup**:
   - Clone this repository:
     ```bash
     git clone https://github.com/yourusername/Clap-On-Light.git
     cd Clap-On-Light
     ```
   - Open the `clap_on_light.ino` file in the Arduino IDE.
   - Select the correct board (`Arduino Uno`) and port in the Arduino IDE.
   - Upload the code to your Arduino.

### Code Overview

- The Arduino sketch (`clap_on_light.ino`) processes the sound input from the microphone sensor.
- It detects patterns of claps (e.g., two quick claps) to toggle the relay module, controlling the light.

## Demo

![Light Turning On]"C:\Users\VIC\Downloads\on.jpg"
![Light Turning Off]"C:\Users\VIC\Downloads\off.jpg"

## Customization

- Adjust the sensitivity of the microphone sensor using the onboard potentiometer.
- Modify the code to change the number or pattern of claps required to toggle the light.

## Contributing

Contributions are welcome! Feel free to fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Would you like me to adjust this README for any specific details or add additional sections?
