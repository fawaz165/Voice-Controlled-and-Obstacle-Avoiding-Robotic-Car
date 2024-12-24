# Voice-Controlled and Obstacle-Avoiding Robotic Car

## Project Description
This project focuses on designing and developing a robotic car that integrates voice recognition and obstacle detection capabilities. Users can control the car's movements (forward, backward, left, right, and stop) using voice commands transmitted via a smartphone app. Additionally, the car autonomously detects and avoids obstacles using ultrasonic sensors.

![Architecture Diagram](https://github.com/fawaz165/Voice-Controlled-and-Obstacle-Avoiding-Robotic-Car/blob/main/images/architecture.png)

---

## Features
- **Voice Command Control**: Supports voice commands using Google’s speech recognition technology.
- **Obstacle Avoidance**: Ultrasonic sensors detect obstacles and enable safe navigation.
- **Hands-Free Operation**: Designed for accessibility and safety, allowing control without physical interaction.

---

## Hardware Requirements
- **Arduino Uno**: Microcontroller for processing commands.
- **HC-05 Bluetooth Module**: Wireless communication module.
- **L298N Motor Driver**: Controls the DC motors.
- **Ultrasonic Sensor**: Detects obstacles.
- **DC Motors**: Drives the wheels.
- **12V Rechargeable Battery**: Powers the system.

---

## Software Requirements
- **Arduino IDE**: To program the microcontroller.
- **MIT App Inventor**: For developing the Android application.

---

## Methodology
1. **Voice Command Interpretation**:
   - Pair the HC-05 Bluetooth module with the smartphone using the security key ("1234" or "0000").
   - Use the smartphone app’s microphone to issue voice commands.
   - Convert voice commands into text using Google’s speech recognition technology.
   - Transmit text commands to the robotic car via Bluetooth.

2. **Command Processing**:
   - The Bluetooth module receives the commands and sends them to the Arduino Uno.
   - The Arduino interprets commands and controls the motor driver to move the car accordingly.

3. **Obstacle Detection**:
   - Ultrasonic sensors continuously monitor the path for obstacles.
   - If an obstacle is detected, the Arduino initiates evasive actions (stop, turn, or reverse).

![Flowchart](https://github.com/fawaz165/Voice-Controlled-and-Obstacle-Avoiding-Robotic-Car/blob/main/images/flowchart.png)
---

## Installation and Setup
1. **Arduino Code**:
   - Download and install the Arduino IDE.
   - Connect the Arduino Uno to your computer via USB.
   - Upload the provided sketch to the Arduino.

2. **Mobile App**:
   - Use MIT App Inventor to create the Android application.
   - Ensure the app supports Google speech recognition and Bluetooth communication.
   - Pair your smartphone with the HC-05 module.
![Mobile App](https://github.com/fawaz165/Voice-Controlled-and-Obstacle-Avoiding-Robotic-Car/blob/main/images/bluetooth%20app.jpg)

3. **Hardware Assembly**:
   - Connect the HC-05 Bluetooth module, ultrasonic sensors, and motor driver to the Arduino Uno.
   - Attach the DC motors to the motor driver.
   - Power the system using a 12V rechargeable battery.

---

## Usage
1. Turn on the robotic car by powering the Arduino and peripherals.
2. Open the mobile app and pair it with the HC-05 module.
3. Use the app’s microphone button to issue commands such as:
   - **"Move forward"**: Move the car forward.
   - **"Move backward"**: Reverse the car.
   - **"Turn left"**: Turn the car to the left.
   - **"Turn right"**: Turn the car to the right.
   - **"Stop"**: Halt all movement.

![Command Function](https://github.com/fawaz165/Voice-Controlled-and-Obstacle-Avoiding-Robotic-Car/blob/main/images/command%20function.png)

4. The ultrasonic sensors will detect and avoid obstacles autonomously.
---
