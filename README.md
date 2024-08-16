# BIOMETRIC VOTING System with Fingerprint Authentication

This project implements a BIOMETRIC VOTING system using fingerprint authentication. The system integrates with Firebase to manage voter data and voting results, utilizing an `Adafruit Fingerprint Sensor`, an `LCD Display`, and an `ESP8266 Module` for Wi-Fi connectivity.

## Features

- **Fingerprint Enrollment**: Enroll voters by capturing their fingerprints.
- **Voting Functionality**: Allow enrolled voters to cast their votes.
- **Results Management**: Update and manage voting results.
- **Firebase Integration**: Store and retrieve voter data and voting results from Firebase.

## Components

- **Adafruit Fingerprint Sensor**: Captures and verifies fingerprints.
- **LiquidCrystal I2C Display**: Displays messages and prompts.
- **ESP8266 Module**: Provides Wi-Fi connectivity and Firebase communication.
- **Arduino Board**: Manages the system’s logic.

## Getting Started

### Prerequisites

1. **Arduino IDE**: Ensure you have the Arduino IDE installed on your computer. You can download it from [Arduino’s official website](https://www.arduino.cc/en/software).

2. **Libraries**:
   - `Adafruit Fingerprint Sensor Library`
   - `LiquidCrystal I2C`
   - `FirebaseESP8266`
   - `WiFi` (for ESP8266 connectivity)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/VisheshDixit22/BIOMETRIC-VOTING-system.git
