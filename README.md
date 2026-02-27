# BMP180-Temperature-Pressure-Sensor

## Project Overview
This project demonstrates how to read **temperature** and **air pressure**
using the **BMP180 sensor** and display the values on the Serial Monitor.

The BMP180 sensor communicates using the **I2C protocol**, making it easy
to interface with Arduino and ESP boards.

## Components Required
- Arduino / ESP32 / ESP8266
- BMP180 Pressure Sensor
- Jumper wires
- Breadboard
- 
##  Connections (I2C)
BMP180 Pin  Board Pin 
 VCC---->3.3V / 5V 
 GND ---->GND 
 SDA---->SDA
 SCL ---->SCL

##  Concepts Used
- I2C Communication
- Sensor interfacing
- Serial communication
- Libraries usage
  
## How to Run
1. Install **Adafruit BMP085 Library** from Arduino Library Manager
2. Connect the BMP180 sensor properly
3. Upload the code to your board
4. Open Serial Monitor (9600 baud rate)

## Sample Output
Temperature: 28.45 °C
Pressure : 100845 Pa

## Learning Outcome
- Understand I2C-based sensor communication
- Learn how temperature and pressure sensors work
- Practice using external libraries in Arduino
- 
## Author
Harsha G
