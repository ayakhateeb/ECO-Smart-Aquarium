# ECO Smart Aquarium 🐠

**IoT-Based Smart Aquarium Monitoring and Control System**

ECO Smart Aquarium is a collaborative university graduation project that explores how Internet of Things (IoT) technology can support aquarium monitoring and selected automated operations.

The prototype is built around an ESP32 microcontroller connected to sensors and actuators. It collects aquarium readings, processes system conditions, controls connected components, and communicates with Firebase Realtime Database over Wi-Fi for remote monitoring and selected commands.

> **Project status:** Academic prototype. Detailed measurements, calibration data, and verified test results will be documented after review of the original project records.

## Project Objectives

- Monitor aquarium water temperature.
- Measure water pH and Total Dissolved Solids (TDS).
- Monitor the aquarium water level.
- Support scheduled and manual fish feeding.
- Control aquarium lighting.
- Automate selected water-management operations.
- Enable remote monitoring and selected controls through Firebase.

## Main Features

- Sensor data collection and status monitoring.
- Temperature-related control.
- Water-level monitoring and refill control.
- Water-quality monitoring (pH and TDS).
- Scheduled and manual feeding.
- Automatic and manual lighting.
- Scheduled water drainage.
- Remote monitoring and control.
- Audible/system alerts.

Feature behavior and operating limits should be interpreted in the context of the final hardware implementation and test records.

## Technologies

### Hardware
- ESP32
- DS18B20 temperature sensor
- pH sensor
- TDS sensor
- Ultrasonic distance sensor
- 20x4 LCD
- DS1307 RTC module
- Servo motor
- Water pumps
- Relay modules

### Software
- Arduino IDE
- C/C++
- Firebase Realtime Database
- Wi-Fi
- Arduino libraries

## System Architecture

The ESP32 is the central controller. It reads connected sensors, evaluates readings, operates selected actuators, and exchanges data with Firebase over Wi-Fi.

See [System Architecture](docs/system-architecture.md).

## Repository Structure

```text
ECO-Smart-Aquarium/
├── docs/
│   ├── ownership-and-attribution.md
│   ├── system-architecture.md
│   ├── hardware-and-components.md
│   └── testing-and-results.md
├── firmware/
│   └── README.md
├── images/
│   └── README.md
├── .gitignore
└── README.md
```

The firmware source and project photographs will be added after the original files have been reviewed and any credentials or private information have been removed.

## Testing and Results

Testing documentation is being prepared. Quantitative results, sensor calibration values, and performance claims will only be included when supported by the team's actual measurements and records.

See [Testing and Results](docs/testing-and-results.md).

## My Contribution

I participated in the development of ECO Smart Aquarium as a team leader, contributing to project coordination and technical implementation. The exact division of work among team members should be represented in the final team documentation.

## Project Team

Team members, academic supervisor, and institutional details will be added after confirmation.

## Ownership and Academic Attribution

ECO Smart Aquarium was developed collaboratively as a university graduation project. The project materials and intellectual property are subject to the applicable university policies and the rights of the participating students.

This repository is intended to document and present the academic project. No open-source license is applied in this repository. Reuse, modification, or redistribution should not be assumed to be permitted; interested parties should obtain authorization from the relevant rights holders.

See [Ownership and Attribution](docs/ownership-and-attribution.md).

## Project Gallery

Project photographs and implementation images will be added after they have been reviewed and approved for publication.

See the [images directory](images/).

---

*Academic project documentation. Please refer to the project team and relevant institution for authoritative information about ownership, implementation details, and validated results.*
