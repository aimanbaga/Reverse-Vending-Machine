# EcoTech: A Reverse Vending Machine
![Example Output](https://i.imgur.com/IUPy8pV.png)
This repository contains all the source code for the Ecotech: Reverse Vending Machine project, including the Arduino files, object detection system, and database. The machine is designed to identify plastic bottles and aluminum cans, converting each deposited item into credit points stored on a user’s ID card. These points can then be redeemed for school supplies. The system is implemented within a school environment.

####
In this project, we use a Raspberry Pi 4 to perform object detection and run Python scripts, specifically leveraging the EfficientDet0 model. The Raspberry Pi communicates with an Arduino Mega, which manages reward dispensing, user data collection, and display functions. To send and retrieve information from the database, an ESP8266 module is connected to the Arduino Mega, enabling Serial Communication for seamless data transfer.

####
Hardware Used:
* Raspberry Pi 4
* Arduino Mega
* ESP8266
* RFID Reader
* SG995 Servo Motor 360° and 180°
* Ultrasonic Sensor
* Inductive Sensor
* Nextion LCD Display
* Relay
* HX711 Load Cell Amplifier

Software Used:
* Arduino IDE
* XAMPP(Apache, MySQL,PHP)
* phpMyAdmin
* Postman (for API testing)

####

####
### Schematic Diagram
![Schematic Diagram](https://imgur.com/8TtPSG4.png)

####
### Example Output
![Example Output](https://imgur.com/1FTIs5b.png)
