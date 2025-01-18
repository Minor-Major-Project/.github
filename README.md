# Enhancing Driver Safety and Well-being: Integrating IoT Health Monitoring Devices in Electric Vehicles (EV)

## Overview
This project focuses on integrating IoT health monitoring devices in Electric Vehicles (EVs) to enhance driver safety and well-being. The goal is to monitor critical health parameters in real-time, such as heart rate, oxygen saturation, and other vital signs, using sensors like the MAX30102, and provide actionable insights for drivers to ensure their safety during trips.

## Basic Information
*This section will be updated with more detailed information about the project, including its scope, objectives, and the technology stack used.*

## Team Members
- **Vivek M G**: Project Lead and Researcher
- **Jagarlamudi Venkata Sai Himasri**: Project Member and Researcher
- **Prithika Sathivel**: Project Member and Researcher
- **Raghuram Srikanth**: Project Member and Researcher

## Objectives
- **Health Monitoring**: Monitor the driver's health status using IoT-enabled sensors like the MAX30102.
- **Real-time Data Processing**: Process the health data in real-time using embedded systems and machine learning models.
- **Early Detection of Health Issues**: Use machine learning algorithms (TinyML or Neural Networks) for early detection of potential health risks, such as heart attacks.
- **Integration with EV Systems**: Seamlessly integrate the health monitoring system with the EV's onboard systems to provide feedback to the driver.
- **Safety Alerts**: Send immediate safety alerts to the driver or emergency services in case of abnormal health readings.

## Features
- **Heart Rate Monitoring**: Continuous monitoring of the driver’s heart rate using the MAX30102 sensor.
- **Oxygen Saturation (SpO2) Monitoring**: Real-time measurement of blood oxygen levels.
- **Machine Learning for Health Prediction**: Deploying TinyML models or Neural Networks to predict potential health risks based on sensor data.
- **Embedded System Integration**: Integration of health data with the EV’s onboard system using Arduino Nano 33 BLE Sense for real-time monitoring.
- **Emergency Alerts**: In case of abnormal health readings, the system can alert the driver or send notifications to emergency contacts.

## Hardware Requirements
- **Arduino Nano 33 BLE Sense**: The main embedded board for data processing and communication.
- **MAX30102**: A sensor for heart rate and SpO2 monitoring.
- **Electric Vehicle (EV) System**: Integration with the EV's onboard system for alert notifications.

## Software Requirements
- **Arduino IDE**: For programming the Arduino Nano 33 BLE Sense.
- **TensorFlow Lite**: For deploying the trained ML models on the embedded system.
- **TinyML Library**: For deploying machine learning models in embedded systems.
- **mbed OS**: Operating system for Arduino Nano 33 BLE Sense.

## Usage
1. **Health Monitoring**: Once the system is set up, the health data (heart rate, SpO2) will be continuously monitored and processed by the Arduino board.
2. **Real-time Alerts**: If the system detects any abnormal health readings (e.g., high heart rate, low SpO2), it will trigger an alert.
3. **Emergency Response**: The system can be configured to send emergency alerts to predefined contacts or emergency services if necessary.

## Future Enhancements
- **Integration with EV’s Infotainment System**: Display health data on the EV's infotainment system for driver awareness.
- **Voice Alerts**: Use voice alerts to notify the driver of any health anomalies.
- **Cloud Integration**: Send health data to the cloud for further analysis and long-term monitoring.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
