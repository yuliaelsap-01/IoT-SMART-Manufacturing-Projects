# IoT-SMART-Manufacturing-Projects
This repository contains past project of IoT SMART Manufacturing

## Predictive Maintenance IoT System
Wokwi Simulation + Node-Red Dashboard + MQTT Notifications

### Project Overview

![DHT22 Wiring-Predictive Maintenance](https://github.com/user-attachments/assets/7ad4b4d3-162a-4f2c-9f1a-889bad58f8ef)

This project demonstrates a Predictive Maintenance IoT System that monitors environmental conditions (temperature and humidity) using DHT22 sensor.

The system is built using :
- Wokwi for hardware wiring simulation
- ESP32 for real-time dashboard monitoring
- MQTT protocol for data communication
- MQTTx for notification monitoring

The goal of this project is to simulate how industrial equipment can be monitored in real-time to prevent overheating, excessive humidity exposure, and potential system failures.

### Technologies used
- Wokwi : Microcontroller and wiring simulation
- Node RED : Dashboard and data processing
- MQTTx : MQTT Message monitoring
- DHT22 : Environmental sensor
- ESP32 : IoT microcontroller
- MQTT Protocol : Lightweight IoT communication protocol

### Features
- Real-time temperature and humidity monitoring
- Interactive dashboard (gauge + chart + logs)
- Threshold-based alert system
- MQTT publish / subscribe communication
- Simulated hardware environment (no physical device required)
- Download real-time data logs

### Predictive Maintenance logic
The system implements simple threshold based predictive logic:
- if temperature > 30°C, overheat warning
- if humidity > 80%, high humidity alert

When the conditions are met :
- Alert message is published to a dedicated MQTT topic
- Notification is visible in MQTTx
- Status indicator is visible in LED

This logic simulates early detection of environmental risks that could damage industrial equipment.

### 
