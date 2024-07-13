# ESP32_Noise_Detector_WebServer

This project demonstrates an ESP32-based noise detection system that uses an LM393 sound sensor to monitor noise levels. When the noise exceeds a defined threshold, an LED is activated for a specified duration. The ESP32 also hosts a web server to display the real-time noise status, refreshing every 5 seconds. This setup is ideal for real-time noise monitoring applications with visual and web-based alerts.

## Features
- Detects noise levels using the LM393 sound sensor.
- Activates an LED when noise exceeds the threshold.
- Hosts a web server on the ESP32 to display noise status.
- Web interface refreshes every 5 seconds to show real-time updates.

## Components
- ESP32
- LM393 sound sensor
- LED
- Resistor (220 ohm)

## Circuit Diagram
1. Connect the positive leg (anode) of the LED to pin 25 on the ESP32.
2. Connect the negative leg (cathode) of the LED to a 220 ohm resistor.
3. Connect the other end of the resistor to ground (GND) on the ESP32.
4. Connect the output of the LM393 sound sensor to pin 33 on the ESP32.
