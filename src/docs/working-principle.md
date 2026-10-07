# Working Principle

The DHT11 sensor measures temperature and humidity and sends
the digital readings to the Arduino Uno.

The Arduino processes the sensor data and displays the
measurements on a 16x2 I2C LCD.

## Process

1. Arduino initializes the DHT11 sensor.
2. Arduino initializes the I2C LCD.
3. Temperature and humidity are read.
4. The readings are checked for validity.
5. Valid readings are displayed on the LCD.
6. The process repeats every two seconds.

## Communication

The DHT11 uses a digital data connection.

The LCD communicates with the Arduino through I2C using:

- SDA
- SCL
