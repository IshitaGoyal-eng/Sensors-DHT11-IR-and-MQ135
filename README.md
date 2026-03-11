# Environmental Sensing & Monitoring System 🌡️💨

## Overview
An embedded systems project that monitors real-time environmental 
parameters using multiple sensors interfaced with a microcontroller. 
Collects temperature, humidity, air quality, and object detection 
data through embedded firmware.

## Sensors Used
| Sensor  | Parameter Measured          |
|---------|-----------------------------|
| DHT11   | Temperature & Humidity      |
| MQ135   | Air Quality / Gas Detection |
| IR      | Object / Proximity Detection|

## How It Works
- **DHT11** reads ambient temperature and humidity over digital interface
- **MQ135** reads analog values to estimate surrounding air pollutant levels
- **IR Sensor** detects nearby objects via reflected infrared signals
- Microcontroller processes raw readings into meaningful values
  (°C, %RH, air quality index, detection flags)

## Project Workflow
1. 🔌 Sensor interfacing and wiring on microcontroller
2. 💻 Firmware written in C/C++ using Arduino toolchain
3. 📊 Output displayed on serial monitor in real-time

## Technologies & Tools
- **Language:** C/C++
- **Platform:** Arduino
- **Libraries:** DHT, analogRead (MQ135), digitalRead (IR)
- **IDE:** Arduino IDE / PlatformIO

## Output
✅ Real-time temperature and humidity readings via DHT11  
✅ Air quality levels estimated via MQ135 analog output  
✅ Object detection triggered via IR sensor digital output  

## Future Extensions
- [ ] Wi-Fi integration for IoT cloud logging
- [ ] MQ135 calibration for specific gas detection

