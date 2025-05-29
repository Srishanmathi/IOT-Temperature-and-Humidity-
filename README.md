## 🌡️ IoT Temperature & Humidity Monitoring System

This project is built using **ESP8266**, **DHT11 sensor**, **OLED display**, and **Blynk IoT Platform**. It monitors the surrounding temperature and humidity and sends live data to a mobile app using Blynk.

## 🛠️ Components Used
- NodeMCU (ESP8266)
- DHT11 Temperature & Humidity Sensor
- 0.96” OLED Display (I2C SSD1306)
- Blynk App (Mobile IoT Dashboard)
- Jumper wires, Breadboard

## 🔌 Circuit Connections

| Component      | ESP8266 Pin |
|----------------|-------------|
| DHT11 **OUT**  | D0          |
| OLED **SCL**   | D1 (GPIO5)  |
| OLED **SDA**   | D2 (GPIO4)  |
| VCC & GND      | 3.3V, GND   |

## 📲 Blynk Configuration
- Create a new Blynk project (Device: ESP8266)
- Add 2 Gauge widgets:
  - V0: Temperature (°C)
  - V1: Humidity (%)
- Paste the Blynk Auth Token in your code

## 🔧 Setup Instructions
1. Install Arduino IDE
2. Install ESP8266 Board via Board Manager
3. Install the following libraries:
   - Blynk
   - Adafruit GFX
   - Adafruit SSD1306
   - DHT sensor library
4. Upload the code to ESP8266
5. Open Serial Monitor (115200 baud)
6. Monitor live data on OLED & Blynk app

## 📷 Demo
![Project Demo](https://drive.google.com/file/d/1G_ntyFQqvcM73FFs_EuXoAJr4OqoYH_M/view?usp=sharing)

## 📄 Code

See the .ino file in this repository for the full implementation.
