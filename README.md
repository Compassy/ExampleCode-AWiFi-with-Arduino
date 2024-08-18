# ExampleCode-AWiFi-with-Arduino

This repository contains a collection of example codes demonstrating how to use WiFi with Arduino, focusing primarily on ESP8266 and ESP32 modules. These examples are designed to help users explore and implement various IoT (Internet of Things) projects, integrating sensors, displays, and communication protocols.

## Table of Contents

- [ExampleCode-AWiFi-with-Arduino](#examplecode-awifi-with-arduino)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Examples](#examples)
    - [Sensor Integrations](#sensor-integrations)
    - [WiFi Communication](#wifi-communication)
    - [Display Control](#display-control)
    - [IoT Protocols (MQTT)](#iot-protocols-mqtt)

## Introduction

The ExampleCode-AWiFi-with-Arduino repository is designed to help developers understand and implement WiFi-based IoT solutions using Arduino. Each example in this repository is crafted to demonstrate a specific use case, such as reading sensor data, controlling devices remotely, or displaying information on an OLED screen. The examples are easy to follow and can be used as a foundation for more complex projects.

## Installation

To use the examples in this repository, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/Compassy/ExampleCode-AWiFi-with-Arduino.git
   ```

2. **Open in Arduino IDE:**
   - Open the Arduino IDE.
   - Navigate to `File > Open...` and select the `.ino` file from the desired example directory.

3. **Install Required Libraries:**
   Some examples may require additional libraries. Make sure to install them via the Arduino Library Manager (`Sketch > Include Library > Manage Libraries...`).

4. **Upload to Your Device:**
   - Connect your ESP8266/ESP32 module to your computer.
   - Select the correct board and port from `Tools > Board` and `Tools > Port`.
   - Click the upload button.

## Examples
### Sensor Integrations

- **AWiFi_BH1750-OLED**: Measures light intensity using the BH1750 sensor and displays it on an OLED screen while sending data over WiFi.
- **AWiFi_DHT11OLED / AWiFi_DHT22OLED**: Reads temperature and humidity data from DHT11/DHT22 sensors and displays it on an OLED display.
- **AWiFi_HCSR04OLED**: Measures distance using an ultrasonic sensor (HC-SR04) and shows it on an OLED screen.

### WiFi Communication

- **WIFI_CLIENT / WIFI_SERVER**: Basic examples showing how to set up a WiFi client or server using the ESP8266/ESP32.
- **WIFI_DIRECT_SERVER**: Demonstrates setting up a WiFi Direct server for peer-to-peer communication.
- **WIFI_SCAN**: Scans available WiFi networks and displays the results.

### Display Control

- **AWiFi_AnalogOLED**: Displays analog sensor values on an OLED screen while sending data over WiFi.
- **AWiFi_TestOLED**: General example for testing OLED display with WiFi functionality.

### IoT Protocols (MQTT)

- **MQTT_PUBLISHER / MQTT_SUBSCRIBER**: Shows how to use MQTT for publishing and subscribing to topics, enabling real-time IoT communication.