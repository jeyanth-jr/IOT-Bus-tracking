# RFID Bus Arrival Logger

## Overview
This project automates bus arrival logging using RFID technology with NodeMCU ESP8266. The system connects to Google Sheets via WiFi for real-time data updates.

## Hardware Setup
- SDA to D4
- SCK to D5
- MOSI to D7
- MISO to D6
- RST to D3
- GND to GND
- 3.3V to 3V

### LED
- SDA to D2
- SCL to D1

### Buzzer
- GND to GND
- Power to D0

## Libraries
Download and include the following libraries in your Arduino IDE:
- MFRC522
- SPI
- ESP8266WiFi
- ESP8266HTTPClient
- WiFiClient
- WiFiClientSecureBearSSL
- LiquidCrystal_I2C
- Wire

## Installation
1. Connect the hardware as per the wiring instructions.
2. Install the required libraries in your Arduino IDE.
3. Open the project sketch in Arduino IDE.
4. Modify the WiFi credentials and Google Sheets URL in the code.
5. Upload the sketch to your NodeMCU board.
6. Monitor the serial output for debugging and status updates.

## Contributors
- [Jeyanth]([link-to-your-profile](https://github.com/jeyanth-jr)

## License
This project is licensed under the [MIT License]([link-to-license-file](https://github.com/jeyanth-jr/IOT-Bus-tracking?tab=MIT-1-ov-file#).

