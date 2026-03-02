Sensor-DHT11-IR-MQ135
This embedded systems project implements a real-time environmental sensing and monitoring system using multiple sensors interfaced with a microcontroller. 📌 Project Overview

This embedded systems project demonstrates real-time environmental sensing and monitoring using multiple sensors interfaced with a microcontroller. The system collects temperature, humidity, air quality, and proximity/obstacle detection data, processes it with embedded firmware, and presents it for visualization or further analysis.

🧠 Key Features

Environmental Monitoring: Uses the DHT-11 sensor to measure ambient temperature and humidity reliably. Air Quality Detection: Integrates the MQ135 gas sensor to detect concentrations of harmful gases and estimate air quality levels. Object Detection: Utilizes an IR sensor for proximity or motion detection, enabling interactive behavior or safety triggers. (Mention here how you used it — e.g., obstacle alerts, motion logging, etc.) Modular embedded design implemented on microcontroller (Arduino/ESP/STM32 – replace with your platform) for low-power, real-time operation.

⚙️ How It Works

Sensor Data Acquisition: The DHT-11 periodically captures temperature and humidity over a digital interface. The MQ135 reads analog values related to surrounding air pollutants to estimate air quality. The IR sensor detects nearby objects or motion based on reflected infrared signals. (Briefly state your logic — e.g., a high digital output signals a detected object.) Processing & Interpretation: The microcontroller converts raw sensor readings into meaningful data (e.g., °C/°F, %RH, estimated air quality levels, distance/trigger flags). Optional: data smoothing, thresholds, or event logging.

Output/Visualization:

Sensor readings can be displayed on serial monitor, LCD/OLED displays, logged to SD card, or transmitted to dashboards/IoT platforms (extendable).

🧩 Technologies & Tools

Programming in C/C++ using the Arduino/PlatformIO toolchain Libraries for sensor interfacing (DHT, ADC for MQ135, digital read for IR) Optionally use displays (LCD/OLED) or IoT dashboards for remote monitoring

📈 Potential Extensions

Integrate Wi-Fi/IOT for cloud logging Calibrate MQ135 for specific gas thresholds

Add alerts/actuators for unsafe conditions

Data visualization using graphs or dashboards
