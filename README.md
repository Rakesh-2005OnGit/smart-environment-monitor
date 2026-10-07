🌡️ Smart Environment Monitoring System

Arduino-based temperature and humidity monitoring system using a DHT11 sensor and 16×2 I2C LCD.

«Project status: Prototype / Development»

📌 Overview

This project demonstrates a basic embedded environmental monitoring system that measures temperature and humidity and displays the readings in real time.

The project is designed to develop practical knowledge of sensor interfacing, microcontroller programming, I2C communication, and embedded C/C++.

🎯 Objectives

- Measure temperature
- Measure relative humidity
- Display sensor readings
- Interface a DHT11 sensor with Arduino
- Interface an I2C LCD
- Implement basic sensor-error handling

🧰 Hardware Components

- Arduino Uno
- DHT11 temperature and humidity sensor
- 16×2 I2C LCD
- Breadboard
- Jumper wires
- USB cable
- Pull-up resistor when required by the DHT11 configuration

💻 Technologies

- Embedded C/C++
- Arduino
- DHT11
- I2C
- Sensor interfacing
- LCD interfacing

🔌 Pin Connections

DHT11 → Arduino Uno

DHT11| Arduino Uno
VCC| 5V
DATA| D2
GND| GND

I2C LCD → Arduino Uno

LCD| Arduino Uno
VCC| 5V
GND| GND
SDA| A4
SCL| A5

🧱 System Block Diagram

       DHT11 Sensor
             │
             │ Temperature
             │ Humidity
             ▼
       Arduino Uno
             │
             │ I2C
             ▼
        16×2 LCD
             │
             ▼
     Displayed Readings

⚙️ Working Principle

The DHT11 measures environmental temperature and humidity.

The Arduino reads the sensor data, validates the readings, and sends the values to the 16×2 LCD through the I2C interface.

The system continuously updates the displayed measurements.

🔄 Program Flow

Start
  ↓
Initialize DHT11
  ↓
Initialize LCD
  ↓
Read Temperature & Humidity
  ↓
Validate Data
  ↓
Display Results
  ↓
Repeat

📊 Expected Output

Temp: XX.X°C
Humidity: XX.X%

The actual values depend on the surrounding environment.

🧪 Testing

The project will be tested by:

1. Checking sensor readings under normal room conditions.
2. Observing changes in temperature and humidity.
3. Checking LCD output.
4. Testing sensor-error handling by disconnecting the sensor.

📸 Project Images

Hardware photographs and test results will be added after the physical prototype is assembled and tested.

🚀 Future Improvements

- Upgrade to ESP32
- Add Wi-Fi connectivity
- Create a web dashboard
- Store historical sensor data
- Add cloud monitoring
- Add SD-card data logging

📚 Learning Outcomes

- Digital sensor interfacing
- Embedded C/C++ programming
- I2C communication
- LCD interfacing
- Serial debugging
- Basic embedded-system error handling

👨‍💻 Author

Rakesh Revuru

Electronics & Communication Engineering Student
