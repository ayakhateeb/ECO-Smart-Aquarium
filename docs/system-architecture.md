# System Architecture

## Overview

The ESP32 acts as the central controller of the ECO Smart Aquarium prototype. It interfaces with sensors and actuators, processes readings and control conditions, and communicates with Firebase Realtime Database over Wi-Fi.

## High-Level Data Flow

```text
Sensors
  |
  v
ESP32 Controller <----> Wi-Fi <----> Firebase Realtime Database
  |
  +---- LCD status display
  +---- Servo fish feeder
  +---- Pump and relay control
  +---- Lighting control
  +---- Audible alerts
```

## Connected Components

| Component | Reported purpose |
|---|---|
| DS18B20 | Water temperature measurement |
| pH sensor | Water pH measurement |
| TDS sensor | Total dissolved solids measurement |
| Ultrasonic sensor | Water-level estimation |
| DS1307 RTC | Time-based scheduling |
| LCD 20x4 | Local status display |
| Servo motor | Fish-feeding mechanism |
| Pumps and relays | Selected water-management operations |
| Buzzer | Audible alerts |

## Communication

The controller uses Wi-Fi to exchange data and selected control commands with Firebase Realtime Database. The exact database schema and command definitions should be documented from the final application and firmware.

## Implementation Notes

This document describes the reported high-level design. Electrical wiring, power ratings, sensor calibration, safety interlocks, and detailed control logic must be verified against the team's final hardware and source code before being treated as definitive engineering specifications.
