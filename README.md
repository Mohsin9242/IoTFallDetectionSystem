# IoT Fall Detection System

## Overview

The IoT Fall Detection System is a smart healthcare monitoring solution designed to detect falls in real-time using the Arduino Nano 33 BLE Sense Rev2 and a Flutter-based Android application. The system continuously monitors motion data from onboard sensors and alerts caregivers or emergency contacts when a fall is detected.

This project combines IoT, Bluetooth Low Energy (BLE), mobile application development, and cloud messaging to improve safety for elderly individuals and patients requiring continuous monitoring.

---

## Features

* Real-time fall detection using accelerometer and gyroscope data
* Bluetooth Low Energy (BLE) communication
* Flutter-based Android application
* Automatic emergency alerts through Telegram Bot
* User information and emergency contact management
* Sensor data logging in CSV format
* Customizable fall detection settings
* Live Bluetooth device scanning and connection
* Portable and battery-powered solution

---

## System Architecture

Arduino Nano 33 BLE Sense Rev2

↓

Motion Sensors (Accelerometer + Gyroscope)

↓

BLE Communication

↓

Flutter Mobile Application

↓

Fall Detection Algorithm

↓

Telegram Alert System

↓

Emergency Contact Notification

---

## Hardware Components

* Arduino Nano 33 BLE Sense Rev2
* 3.7V LiPo Battery
* USB Cable
* Android Smartphone
* BLE Communication Module (Built-in)

---

## Software Technologies

### Mobile Application

* Flutter
* Dart

### Embedded System

* Arduino IDE
* C/C++

### Communication

* Bluetooth Low Energy (BLE)

### Notification Service

* Telegram Bot API

---

## How It Works

1. The Arduino continuously collects accelerometer and gyroscope readings.
2. Sensor data is transmitted to the Flutter application via BLE.
3. The application processes motion patterns using a fall detection algorithm.
4. If a fall is detected, an emergency alert is generated.
5. User details and location information can be included in the alert.
6. The Telegram Bot automatically sends notifications to predefined contacts.

---

## Project Structure

```text
IoTFallDetectionSystem/
│
├── Arduino_Code/
├── Flutter_App/
├── Assets/
├── Documentation/
├── Screenshots/
└── README.md
```

## Installation

### Arduino Setup

1. Install Arduino IDE.
2. Install Arduino Nano 33 BLE board package.
3. Install required sensor libraries.
4. Upload the Arduino firmware.

### Flutter Application Setup

```bash
git clone https://github.com/Mohsin9242/IoTFallDetectionSystem.git

cd IoTFallDetectionSystem

flutter pub get

flutter run
```

## Telegram Bot Configuration

1. Create a Telegram Bot using BotFather.
2. Obtain the Bot Token.
3. Enter the Bot Token in the application settings.
4. Configure the Chat ID for receiving alerts.

## Future Enhancements

* GPS-based location tracking
* Cloud database integration
* AI-powered activity recognition
* Multi-user monitoring dashboard
* Wearable device support
* Healthcare provider integration

## Research Applications

* Elderly care systems
* Smart healthcare monitoring
* Patient safety solutions
* IoT-based emergency response systems
* Remote healthcare monitoring

## Author

Mohsin Ali

### Connect

GitHub: https://github.com/Mohsin9242

---

## License

This project is developed for educational, research, and healthcare monitoring purposes.
