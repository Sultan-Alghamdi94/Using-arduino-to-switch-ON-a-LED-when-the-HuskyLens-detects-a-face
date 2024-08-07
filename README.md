# Using-arduino-to-switch-ON-a-LED-when-the-HuskyLens-detects-a-face
This project aims to create an interactive system using an Arduino board and the HuskyLens AI vision sensor. The system will illuminate an LED whenever the HuskyLens detects a face, providing a visual indication of face recognition.



## Introduction: 
This project aims to create an interactive system using an Arduino board and the HuskyLens AI vision sensor. The system will illuminate an LED whenever the HuskyLens detects a face, providing a visual indication of face recognition.


## Description:
The HuskyLens is an advanced AI vision sensor capable of recognizing faces. When it detects a face, it sends a signal to the connected Arduino board. The Arduino, programmed with specific instructions, will then activate an output pin to power the LED. This setup allows for real-time face detection and visual feedback.


## Tools and Components Needed:

# Arduino Board: Acts as the central processing unit for the project.
# HuskyLens: The AI vision sensor that detects faces.
# Connecting Wires: Facilitates connections between the components.
# Power Supply: Powers both the Arduino and HuskyLens.

Please ensure you have the appropriate libraries installed on your Arduino IDE for the HuskyLens, and the connections are made according to the HuskyLens documentation. Once everything is set up, you’ll need to upload the code to the Arduino to handle the face detection signal from the HuskyLens and turn on the LED accordingly.

## Pins Needed:

# Arduino Digital Pin (Output): A pin like D13 can be used to control the LED.
# Ground (GND) Pin: The LED’s negative leg will connect to the GND pin on the Arduino.
# HuskyLens Communication Pins: These will be used for data exchange between the HuskyLens and the Arduino, typically via I2C or UART interfaces.

![1](https://github.com/user-attachments/assets/e79d281a-a68b-4808-8609-284f4ecc3519)

![The output](https://github.com/user-attachments/assets/ef9f848c-ae6b-46fb-875c-6c579d49ca9b)


