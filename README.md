# 🌡️ Temperature Monitoring System (ESP32)

### 📌 Overview
This project is a **temperature monitoring system** built using an **ESP32**, an **NTC thermistor**, and a **16x2 I2C LCD display**.  
It calculates temperature using the Steinhart–Hart equation and displays readings in both **Celsius and Kelvin**.

### ⚙️ Features
- Real-time temperature measurement using analog input  
- Display output on 16x2 I2C LCD  
- Converts thermistor resistance to temperature using logarithmic formula  
- Shows temperature in °C and K simultaneously  
- Compact and low-power setup using ESP32

### 🛠️ Components
- ESP32 Development Board  
- NTC Thermistor  
- 10kΩ Resistor (for voltage divider)  
- I2C 16x2 LCD Display  
- Jumper wires  
- Breadboard or custom PCB  
- USB or 5V power supply

### 📂 Files
- `src/TemperatureMonitor.ino` → Arduino sketch  
- `.gitignore` → ignored files configuration  
- `.gitattributes` → repository attributes  
- `README.md` → project documentation  

### 🚀 How It Works
- The thermistor forms a voltage divider with a fixed resistor.  
- The analog voltage is read and converted to resistance.  
- The resistance is used in the Steinhart–Hart equation to calculate temperature.  
- The LCD displays temperature in both Celsius and Kelvin.

### 📚 Required Libraries
- [LiquidCrystal_I2C](https://github.com/johnrickman/LiquidCrystal_I2C)

### 📸 Project Images
*(Add circuit diagram or build photos here once uploaded)*

### 🙌 Acknowledgment
Developed as part of my **Mechatronics Engineering coursework**, showcasing sensor calibration, embedded programming, and real-time display systems.
