# Soil Sensor IoT Project

## Overview
This project aims to create a **smart soil sensor** using an **ESP32** that collects soil data (e.g., moisture, temperature) and sends it to the cloud via **MQTT**. The system is designed for real-time monitoring, enabling better decision-making in agriculture or gardening.

---

## Features (TODO, draft)
- **Soil Data Collection**:
  - Measures soil **moisture levels**, **temperature**, and potentially other parameters.
- **Data Transmission**:
  - Sends data to the cloud using **MQTT**.
  - Supports integration with IoT platforms for visualization and alerts.
- **Low Power Design**:
  - Uses ESP32’s power-saving modes to optimize battery life.
- **Scalability**:
  - Supports multiple sensors in a network.

---

## Architecture

1. **Hardware**:
   - **Soil Sensor**: [Model/Type, e.g., Capacitive Soil Moisture Sensor]
   - **ESP32**: [Model/Board, e.g., ESP32 Dev Kit]
   - **Power Source**: [Battery/Solar/USB]
   - **Optional Add-ons**: Temperature Sensor, Humidity Sensor, etc.

2. **Data Flow** (TODO):
   1. Soil sensor collects data.
   2. ESP32 reads sensor data.
   3. ESP32 publishes the data to an MQTT broker.
   4. MQTT broker forwards the data to subscribed clients/cloud services.

3. **Software Stack**:
   - **Firmware**: Arduino/ESP-IDF for ESP32.
   - **Communication Protocol**: MQTT.
   - **Cloud Integration**: [e.g., AWS IoT, Adafruit IO, Home Assistant].

---

## Getting Started

### Prerequisites (TODO)
- **Hardware**:
  - ESP32 board.
  - Soil moisture sensor.
  - USB cable and computer for programming.
- **Software**:
  - Arduino IDE or ESP-IDF.
  - MQTT broker (e.g., Mosquitto).
  - Internet connection.

### Setup Instructions (TODO)
1. **Install Dependencies**:
   - Install the [Arduino IDE](https://www.arduino.cc/en/software) or ESP-IDF.
   - Add the ESP32 board to the Arduino IDE via the board manager.
   - Install the required libraries (e.g., PubSubClient for MQTT, DHT for temperature).
2. **Connect the Hardware**:
   - Connect the soil sensor to the ESP32.
   - Power the ESP32 via USB or battery.
3. **Flash the Firmware**:
   - Open the firmware sketch in Arduino IDE.
   - Configure WiFi and MQTT broker credentials.
   - Upload the sketch to the ESP32.
4. **Run the System**:
   - Verify the sensor readings in the serial monitor.
   - Check data on the MQTT broker/cloud platform.

---

## Project Status
- [ ] Initial hardware prototyping.
- [ ] Firmware development for data collection.
- [ ] MQTT integration.
- [ ] Cloud data visualization setup.
- [ ] Final testing and deployment.

---

## To-Do List
- Optimize power usage with ESP32 sleep modes.
- Add additional sensors (e.g., temperature, light).
- Build a waterproof enclosure for outdoor use.
- Explore advanced cloud analytics and dashboards.

---

## Contributions
We welcome contributions! If you'd like to collaborate, feel free to submit a pull request or raise an issue.

---

## Authors
- **Alex Savova**: [GitHub Profile](https://github.com/yourprofile)
- **Orkun Ispir**: [GitHub Profile](https://github.com/friendsprofile)
