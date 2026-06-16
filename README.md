# IoT Smart Fan Control System (ESP32)

## Overview
ESP32-based IoT system that automates fan control using temperature and motion detection with web-based control.

## Features
- Temperature & humidity monitoring (DHT22)
- Motion detection (PIR sensor)
- Automatic fan control (hysteresis logic)
- Manual control via web interface
- OLED real-time display
- HTTP server + JSON API

## Technologies
- ESP32 (Arduino)
- C++
- Wi-Fi (Web Server)
- Sensors: DHT22, PIR
- OLED Display (SSD1306)
- Relay Module

## Control Modes
- AUTO mode (sensor-based control)
- MANUAL mode (web override)

## API Endpoints
- / → Dashboard
- /on → Turn ON fan
- /off → Turn OFF fan
- /auto → Auto mode
- /data → JSON sensor data

## System Idea
Smart energy-efficient fan that responds to environment conditions in real time.