# Smart Solenoid Door Lock System using RFID, Matrix Keypad, Fingerprint Sensor, and Serial Monitor Commands

## Overview

This project implements a smart embedded security-based solenoid door lock system using multiple authentication methods. The system provides secure access control using RFID card authentication, matrix keypad password verification, fingerprint recognition, and serial monitor command control.

The project is built using the ESP8266 NodeMCU platform and demonstrates embedded systems concepts such as sensor interfacing, serial communication, relay control, and access automation.

The solenoid lock activates only when valid authentication credentials are verified successfully.

---

# Features

* RFID card-based authentication
* Matrix keypad password entry system
* Fingerprint sensor verification
* Serial monitor command-based control
* Solenoid lock control using relay module
* Multi-authentication security system
* Embedded access automation
* Secure door unlocking mechanism
* Real-time authentication monitoring
* Serial communication debugging support

---

# Authentication Methods

## 1. RFID Authentication

The RC522 RFID module reads RFID cards/tags and verifies authorized IDs before unlocking the solenoid lock.

## 2. Matrix Keypad Password Entry

Users can enter a predefined password through the matrix keypad. Correct password entry grants access.

## 3. Fingerprint Verification

The fingerprint sensor stores and verifies fingerprints for secure biometric authentication.

## 4. Serial Monitor Commands

Commands can be sent through the serial monitor for manual testing and debugging operations.

---

# Components Used

| Component          | Quantity  |
| ------------------ | --------- |
| ESP8266 NodeMCU    | 1         |
| RC522 RFID Module  | 1         |
| RFID Cards/Tags    | 1 or more |
| Matrix Keypad      | 1         |
| Fingerprint Sensor | 1         |
| Solenoid Door Lock | 1         |
| Relay Module       | 1         |
| Jumper Wires       | Multiple  |
| Breadboard         | 1         |
| Power Supply       | 1         |

---

# Working Principle

The system continuously monitors all authentication modules.

1. RFID cards are scanned using the RC522 module.
2. Password input is accepted from the matrix keypad.
3. Fingerprints are verified using the fingerprint sensor.
4. Commands can also be sent via serial monitor.

If any authentication method successfully validates authorized credentials:

* The relay module activates
* The solenoid lock unlocks the door
* Access status is displayed on serial monitor

Invalid authentication attempts deny access.

---

# Circuit Diagram

## Circuit Diagram

![Circuit Diagram](circuit-diagram/circuit-diagram.png)

## Wiring Connections

![Wiring Connections](circuit-diagram/wiring-connections.jpg)

---

# Setup Images

## Hardware Setup

![Setup Overview](setup/setup-overview.jpg)

## RFID Authentication

![RFID Authentication](setup/rfid-authentication.jpg)

## Fingerprint Authentication

![Fingerprint Authentication](setup/fingerprint-authentication.jpg)

## Keypad Authentication

![Keypad Authentication](setup/keypad-authentication.jpg)

---

# Project Structure

```txt
smart-solenoid-door-lock-system/
│
├── README.md
├── code/
├── setup/
├── circuit-diagram/
└── docs/
```

---

# Output Example

```txt
System Initialized

Waiting for Authentication...

RFID Card Detected
Access Granted
Door Unlocked

Fingerprint Matched
Access Granted

Password Correct
Door Unlocked

Serial Command Received
Door Activated
```

---

# Technical Concepts Used

* Embedded Systems
* IoT Security
* Sensor Interfacing
* RFID Communication
* Biometric Authentication
* Relay Control
* Serial Communication
* Access Automation
* Embedded C/C++
* Firmware Development

---

# Applications

* Smart Door Security Systems
* Home Automation
* Office Access Control
* Smart Locks
* Embedded Security Systems
* Industrial Security Automation
* IoT-based Authentication Systems

---

# Future Scope

* Mobile App Integration
* WiFi-based Remote Access
* Cloud Monitoring
* OTP-based Authentication
* Face Recognition Support
* Firebase Integration
* Access Log Storage
* GSM Alert Notifications
* IoT Dashboard Integration

---

# Advantages

* High security using multiple authentication methods
* Real-time access control
* Easy hardware integration
* Scalable security architecture
* Reliable embedded automation system

---

# Conclusion

This project demonstrates a complete embedded security automation system using multiple authentication techniques. It combines RFID technology, biometric authentication, keypad verification, and serial communication to provide secure and reliable smart door access control.

The project is highly suitable for learning embedded systems, IoT security, firmware development, and sensor interfacing concepts.

---

# Author

Pilla Naga Adinarayana

ECE Student | Embedded Systems Enthusiast | IEEE Volunteer
