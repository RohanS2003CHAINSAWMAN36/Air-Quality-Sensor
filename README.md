Air, Humidity , Light and Temperature Quality Monitor
This project is an Arduino-based air quality monitor that measures air quality, temperature, humidity, and detects light presence. It utilizes a DHT11 sensor for temperature and humidity readings, an analog gas sensor for air quality monitoring, and a digital light sensor to detect light presence.

Components Used
DHT11 sensor for temperature and humidity measurement
Analog gas sensor for air quality monitoring
Digital light sensor to detect light presence
SSD1306 OLED display for visual feedback
Installation
Connect the DHT11 sensor to digital pin 2 of the Arduino board.
Connect the analog gas sensor to analog pin A0 of the Arduino board.
Connect the digital light sensor to digital pin 8 of the Arduino board.
Connect the 0.96 inch OLED display to the Arduino board according to the specified pin configurations.
Upload the provided Arduino code to your Arduino board.
Usage
Once the code is uploaded and the hardware is properly connected, power on the Arduino board.
The OLED display will show the air quality, temperature, humidity, and light presence status.
The air quality is categorized as "Good", "Poor", "Very Bad", "You're Dead", or "Toxic" based on the gas level detected.
Temperature is displayed in Celsius (°C) and humidity in percentage (%).
The presence of light is indicated by an icon on the OLED display.
Authors

Rhushya K C
Rithvik M
Rohan S

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Adafruit for providing libraries for the OLED display and sensor modules.
Arduino community for sharing knowledge and resources.
