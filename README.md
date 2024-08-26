# ECG-Deployment-Using-Smart-Phone

 Author 
 1. Aditya Raj
 2. Shorya Kumar

## Abstract
Electrocardiography (ECG) is a crucial medical tool used to monitor the heart's electrical activity. ECG signals are pivotal in diagnosing various cardiac conditions, making real-time monitoring vital. This project explores the integration of AD8232 ECG sensors with NodeMCU ESP8266, utilizing the MQTT protocol for data transmission to the Ubidots cloud. It also covers the development of a smartphone application for data access and visualization, including the application of Digital Signal Processing (DSP) techniques for signal plotting and filtering.

**Keywords**: AD8232 ECG sensors, ESP8266, MQTT protocol, Ubidots cloud

## Table of Contents
1. [Introduction](#introduction)
2. [Components and Tools](#components-and-tools)
3. [System Architecture](#system-architecture)
4. [Implementation](#implementation)
   - [Hardware Setup](#hardware-setup)
   - [Software Development](#software-development)
5. [Smartphone Application](#smartphone-application)
   - [Features](#features)
   - [Technology Stack](#technology-stack)
6. [Digital Signal Processing (DSP)](#digital-signal-processing-dsp)
   - [Signal Plotting](#signal-plotting)
   - [Filtering Techniques](#filtering-techniques)
7. [Data Transmission and Cloud Integration](#data-transmission-and-cloud-integration)
   - [MQTT Protocol](#mqtt-protocol)
   - [Ubidots Cloud](#ubidots-cloud)
8. [Testing and Results](#testing-and-results)
9. [Conclusion](#conclusion)
10. [Future Work](#future-work)
11. [References](#references)
12. [Clone Repository](#clone-repository)

## Introduction
The ECG monitoring system developed in this project enables real-time tracking of heart activity through a combination of hardware and software solutions. By integrating AD8232 ECG sensors with a NodeMCU ESP8266 microcontroller, and utilizing the MQTT protocol for data communication, we achieve a robust and efficient monitoring system. The data is sent to the Ubidots cloud platform, where it can be accessed and visualized through a dedicated smartphone application.

## Components and Tools
- **AD8232 ECG Sensor**: Measures the electrical activity of the heart.
- **NodeMCU ESP8266**: Microcontroller used for processing and transmitting ECG data.
- **MQTT Protocol**: Lightweight messaging protocol for efficient data transmission.
- **Ubidots Cloud Platform**: Cloud service for data storage and visualization.
- **Smartphone**: Device for accessing and visualizing ECG data.

## System Architecture
The system architecture consists of an ECG sensor connected to the NodeMCU ESP8266, which processes the sensor data and transmits it via MQTT to the Ubidots cloud. The smartphone application retrieves data from Ubidots and provides real-time visualization and analysis.

## Implementation

### Hardware Setup
1. **ECG Sensor Connection**: Connect the AD8232 ECG sensor to the NodeMCU ESP8266.
2. **Power Supply**: Ensure the NodeMCU is powered adequately to maintain reliable operation.
3. **Connections**: Wire the ECG sensor output to the analog input of the NodeMCU.

### Software Development
1. **Firmware for NodeMCU**: Develop code to read ECG data from the AD8232 and publish it to the Ubidots cloud using MQTT.
2. **MQTT Client Setup**: Configure MQTT client settings for communication with Ubidots.
3. **Data Handling**: Implement data parsing and preprocessing for efficient cloud transmission.

## Smartphone Application

### Features
- **Real-time Data Access**: View live ECG data transmitted from the NodeMCU.
- **Historical Data Visualization**: Access historical ECG data for trend analysis.
- **Alerts and Notifications**: Receive alerts based on predefined conditions.

### Technology Stack
- **Frontend**: Developed using React Native for cross-platform compatibility.
- **Backend**: Connects to the Ubidots API to retrieve and display data.
- **Libraries**: Utilize charting libraries for data visualization and DSP techniques.

## Digital Signal Processing (DSP)

### Signal Plotting
- Implement algorithms to visualize ECG signals in real-time.
- Use libraries like D3.js or Chart.js for plotting the data on the smartphone app.

### Filtering Techniques
- Apply filters (e.g., low-pass, band-pass) to remove noise from the ECG signals.
- Implement signal smoothing algorithms to enhance signal clarity.

## Data Transmission and Cloud Integration

### MQTT Protocol
- Configure the MQTT broker and client settings for secure and efficient data transmission.
- Ensure data integrity and real-time updates through reliable MQTT messaging.

### Ubidots Cloud
- Set up data storage and visualization on the Ubidots platform.
- Create dashboards and widgets for data display and analysis.

## Testing and Results
- **Testing**: Perform tests to ensure accurate data transmission and visualization.
- **Results**: Analyze the performance of the system and verify the accuracy of ECG readings.

## Conclusion
The project successfully integrates ECG monitoring with modern technology to provide a real-time, accessible solution for heart activity tracking. The combination of AD8232 sensors, NodeMCU ESP8266, MQTT protocol, and a smartphone application results in an efficient and user-friendly ECG monitoring system.

## Future Work
- **Enhanced Features**: Incorporate advanced analytics and AI for predictive diagnostics.
- **User Feedback**: Collect and analyze user feedback for system improvements.
- **Integration**: Explore integration with other health monitoring devices.

## References
- [AD8232 ECG Sensor Datasheet](#)
- [NodeMCU ESP8266 Documentation](#)
- [MQTT Protocol Overview](#)
- [Ubidots Cloud Platform Documentation](#)
- [React Native Documentation](#)

## Clone Repository
To clone this repository, use the following command:
```bash[
git clone https://github.com/aditya22101/ECG-Deployment-Using-Smart-Phone.git
```

After cloning the repository, follow the setup instructions in the `README.md` files found in the respective directories for hardware and software setup.

---

Feel free to customize the links and add any additional setup instructions specific to your project.
