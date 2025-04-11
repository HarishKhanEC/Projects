Smart Stethoscope – Real-Time Health Monitoring System

This project is a compact and cost-effective Smart Stethoscope designed to digitally monitor and visualize heart and lung sounds using an ESP8266 (NodeMCU) microcontroller, an electret microphone module, and an optional LCD display or IoT dashboard (Blynk).

Features

Real-time monitoring of heartbeat and respiratory sounds

Analog signal capture via microphone sensor

Data visualization on 16x2 LCD (I2C) display

Optional wireless transmission to smartphone via Blynk IoT

Battery-powered for portable use

Easy-to-build and open-source


Hardware Used

ESP8266 (NodeMCU)

Electret Microphone Module (KY-038)

16x2 LCD with I2C module

Jumper Wires, Breadboard

Battery Pack or USB Power Supply


How It Works

1. The electret microphone captures heart/lung sounds as analog signals.


2. The ESP8266 reads the signals and:

Displays them on the LCD

(Optional) Sends the data to the Blynk app over Wi-Fi



3. Real-time values are updated every second.



Use Cases

Remote and rural health screening

Educational tool for auscultation practice

DIY home health monitoring

Prototype for IoT-based medical diagnostics


Getting Started

Upload the Arduino code via Arduino IDE

Connect components as per the schematic

Power the device with a USB or battery source

View mic values on the LCD and/or mobile app


License

This project is open-source and free to use for educational and non-commercial purposes.
