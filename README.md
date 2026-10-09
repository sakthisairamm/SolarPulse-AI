# SolarPulse AI ☀️

### AI-Powered Solar Panel Monitoring and Thermal Fault Detection

SolarPulse AI is an intelligent solar monitoring dashboard designed to help solar plant operators monitor panel performance, identify potential thermal faults, and plan maintenance more effectively.

## 🚨 Problem Statement

Solar panels can experience performance losses due to thermal hotspots, dust accumulation, leaf obstruction, and environmental changes. Manual inspection of large solar installations can be time-consuming. SolarPulse AI provides a centralized dashboard for monitoring, inspection, and maintenance planning.

## 💡 Our Solution

SolarPulse AI combines electrical and environmental monitoring with thermal inspection and analytics in one industrial IoT dashboard.

## ✨ Key Features

- **Real-Time Monitoring:** Displays voltage, current, power, irradiance, temperature, and humidity.
- **Analytics Dashboard:** Visualizes electrical performance trends.
- **AI Thermal Inspection:** Demonstrates thermal fault classification and hotspot detection.
- **Alert Management:** Highlights abnormal conditions by priority.
- **Maintenance Planning:** Organizes inspection and maintenance tasks.
- **Demo Simulation:** Uses simulated telemetry to demonstrate the dashboard workflow.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Chart.js
- Material Symbols

### Proposed Hardware Integration

- ESP32 microcontroller
- INA226 voltage and current monitoring
- Irradiance sensor
- BME280 environmental sensor
- MLX90640 thermal camera
- Raspberry Pi for edge processing

## 🧠 AI Approach

The prototype demonstrates a thermal inspection workflow using a representative thermal image and simulated classification results. Integration of a trained computer vision model and physical sensors is planned future work.

## 🏗️ System Architecture

Solar PV Panel  
↓  
Electrical and Environmental Sensors  
↓  
ESP32 / IoT Edge Layer  
↓  
SolarPulse AI Dashboard  
↓  
Thermal Inspection and Analytics  
↓  
Anomaly Detection  
↓  
Alerts and Maintenance Recommendations

## 🌍 Real-World Impact

- Supports earlier identification of potential panel abnormalities.
- Helps maintenance teams prioritize inspections.
- Reduces dependence on manual monitoring alone.
- Supports more efficient solar plant maintenance.

## 🚀 Future Scope

- Live sensor integration.
- Trained CNN-based thermal fault classification.
- Raspberry Pi edge AI processing.
- Predictive maintenance.
- Automated maintenance notifications.
- Multi-site solar farm monitoring.

## ▶️ How to Run

1. Download or clone this repository.
2. Keep `index.html`, `styles.css`, `app.js`, and `thermal_scan.jpg` in the same folder.
3. Open `index.html` in a browser.
4. Use the dashboard's demo mode to explore the features.

## ⚠️ Prototype Status

The current project is a dashboard prototype using simulated telemetry and a representative thermal image. Physical sensor integration and trained AI inference are planned extensions.

## 🏆 Hackathon

**ForgeHacks Online 2026**  
Track: **AI + Climate**

---

Built to support smarter solar monitoring and renewable-energy maintenance.
