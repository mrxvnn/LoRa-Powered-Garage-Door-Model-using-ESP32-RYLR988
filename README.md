# LoRa-Powered-Garage-Door-Model-using-ESP32-RYLR988
A wireless garage door control system using two ESP32 nodes communicating over LoRa with RYLR988 modules. The remote unit sends commands via a push button, and the receiver unit activates a servo motor to open/close the garage door. Demonstrates long-range wireless communication, embedded systems, and actuator control, with applications in home automation and industrial control systems.

**Components & Supplies**
2 × ESP32-WROOM-32
2 × RYLR988 LoRa Modules
1 × SG90 Micro-Servo Motor
Breadboard & Jumper Wires
2 × SparkFun Breadboard Power Supply (5V/3.3V)

**Apps & Platforms**
Arduino IDE

**Features**
Long-range wireless communication using LoRa
Servo-driven garage door mechanism
Simple push-button remote control
Demonstrates practical use of LoRa for automation

**How It Works**
Remote Unit: ESP32 + RYLR988 + push button. Sends LoRa commands when the button is pressed.
Garage Receiver: ESP32 + RYLR988 + servo. Receives LoRa messages and moves the servo to open/close the garage door.
Commands are transmitted wirelessly over LoRa, providing reliable long-range control.

**Challenges & Solutions**
LoRa reliability: Configured correct network ID and addressing for consistent communication
Servo precision: Implemented smooth movement using incremental position updates
Power management: Ensured stable supply to ESP32 and RYLR988 modules for uninterrupted operation



