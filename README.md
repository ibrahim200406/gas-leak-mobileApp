# ESP32 Sensor Monitoring System with Firebase and MIT App Inventor

This project is an IoT-based sensor monitoring system using an ESP32 microcontroller, an MQ2 gas sensor, a DHT11 temperature and humidity sensor, and a buzzer. The sensor data is sent to Firebase Realtime Database, where it can be monitored through a mobile application built using MIT App Inventor. Additionally, the app provides real-time alerts when flammable gas is detected.

## Features

- Real-time sensor data monitoring: The ESP32 reads data from the MQ2 gas sensor and DHT11 sensor, then sends this data to Firebase.
- Mobile app integration: The MIT App Inventor app retrieves data from Firebase, displaying temperature, humidity, and gas levels.
- Buzzer alarm: The buzzer is activated if a hazardous gas concentration is sensed.

## Components Used

- ESP32: The microcontroller used for reading sensor data and communicating with Firebase.
- MQ2 Gas Sensor: Detects levels of flammable gas (e.g., LPG, propane, hydrogen).
- DHT11: Measures temperature and humidity.
- Firebase Realtime Database: Stores sensor data and sends updates to the mobile app.
- MIT App Inventor: Used to build the mobile app that displays sensor readings and warnings.

## Usage

The system continuously monitors the environment for temperature, humidity, and gas levels.
The mobile app displays real-time readings from the sensors.
If a dangerous level of flammable gas is detected, the app will display a warning, and the buzzer will sound an alarm.

## Screenshot
![](https://github.com/ibrahim200406/gas-leak-mobileApp/blob/main/mobilAppScreenShot.jpg)
![](https://github.com/ibrahim200406/gas-leak-mobileApp/blob/main/mobileAppScreenShot2.jpg)

## Diagram
![](https://github.com/ibrahim200406/gas-leak-mobileApp/blob/main/circuit%20diagram.png)

## Images
![](https://github.com/ibrahim200406/gas-leak-mobileApp/blob/main/1.jpg)
![](https://github.com/ibrahim200406/gas-leak-mobileApp/blob/main/2.jpg)

