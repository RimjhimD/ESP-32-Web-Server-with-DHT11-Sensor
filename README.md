# ESP32 Web Server with DHT11 Sensor

**Course Name**: Microcontrollers Laboratory  
**Course Code**: CSE 3816  
**Semester**: 4th  



## Introduction

This project demonstrates the creation of a web server using the ESP32 Dev Kit to monitor and display temperature and humidity data from a DHT11 sensor. The primary objective is to utilize the ESP32 Dev Kit's capabilities to serve a real-time, user-friendly web interface that provides environmental data remotely. This project highlights the potential of IoT (Internet of Things) technologies for building practical and interactive systems that enable remote monitoring.



## Objectives

- Set up a web server on the ESP32 Dev Kit.
- Interface the ESP32 Dev Kit with the DHT11 sensor for reading temperature and humidity data.
- Display the temperature and humidity data in real-time on a web page served by the ESP32.




## Submitted By

| Name                  | ID                  |
|-----------------------|---------------------|
| MD SAKIB              | 0222220005101019    |
| SAMIRA SULTANA MYSHA  | 0222220005101022    |
| FARIHA RASHID NOHA    | 0222220005101035    |
| RIMJHIM DEY           | 0222220005101039    |



## Components Used

- **ESP32 Dev Kit**: Microcontroller and web server platform.
- **DHT11 Sensor**: Sensor used to measure temperature and humidity.
- **Breadboard**: For prototyping and connecting components.
- **Wires**: Used to make electrical connections between the components.
- **Power Supply**: Provides power to the ESP32 Dev Kit and connected components.
- 

## Circuit Design

You can find the circuit diagram in the [Circuit Design/d1.png](./Circuit%20Design/d1.png) file.  
This diagram shows how the ESP32 is connected to the DHT11 sensor and other components.


## Programming Environment

- **IDE**: Arduino IDE (with ESP32 board support installed).
- **Libraries Used**:
  - `DHT` library for interacting with the DHT11 sensor.
  - `WiFi` library for network connectivity.
  - 

## Setup Instructions

1. **Install Arduino IDE** and add ESP32 board support.
2. **Install required libraries**:  
   - Open the Arduino IDE, go to `Sketch` > `Include Library` > `Manage Libraries...`, and search for and install:
     - `DHT sensor library`
     - `Adafruit Unified Sensor`
     - `WiFi`
3. **Connect the ESP32 and DHT11** sensor as per the circuit design.
4. **Upload the provided code** from this repository to the ESP32 via Arduino IDE.
5. **Open a web browser** and navigate to the ESP32's IP address to view the real-time temperature and humidity data.


## How it Works

The ESP32 acts as both a WiFi client and a web server. Once connected to a WiFi network, it retrieves temperature and humidity data from the DHT11 sensor. The ESP32 serves a web page that displays these readings, refreshing every few seconds for real-time updates.


## Results

The web interface provides live temperature and humidity data using a clean, user-friendly design. The data is refreshed every 4 seconds, giving an accurate picture of the environmental conditions measured by the DHT11 sensor.


## Acknowledgments

This project was developed as part of the **Microcontrollers Laboratory (CSE 3816)** course in the 4th semester.
