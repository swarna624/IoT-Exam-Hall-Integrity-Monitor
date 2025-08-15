# **IoT Exam Hall Integrity Monitor**

An IoT-based real-time monitoring system designed to maintain fairness and integrity during examinations using multiple sensors and instant alerts.

## **🔍 Overview**
The **IoT Exam Hall Integrity Monitor** detects suspicious activities like unauthorized movements, unusual sounds, abnormal lighting, or desk vibrations. It uses multiple sensors connected to a microcontroller (ESP32/NodeMCU) and sends real-time alerts to the invigilator via a cloud platform.

---

## **✨ Features**
- Real-time monitoring of multiple environmental parameters
- Alerts for movement, noise, light changes, or desk tampering
- Cloud-based dashboard for live exam hall data
- Modular design for easy installation in different exam centers
- Low-cost and scalable for multiple rooms

---

## **🛠 Hardware Used**
- **ESP32 / NodeMCU** – Wi-Fi enabled microcontroller
- **Ultrasonic Sensor** – Detects movement
- **Sound Sensor** – Captures unusual noises
- **Light Sensor (LDR)** – Monitors sudden lighting changes
- **Vibration Sensor** – Detects desk or device tampering
- Breadboard, jumper wires, power supply

---

## **💻 Software & Tools**
- **Arduino IDE** – Programming microcontroller
- **Firebase / MQTT** – Cloud communication
- **HTML/CSS/JavaScript** – Web dashboard (optional)
- **Fritzing** – Circuit diagrams

---

## **📜 System Workflow**
1. Sensors continuously capture exam hall activity.
2. ESP32 processes data and sends it to the cloud.
3. Alerts are triggered if thresholds are exceeded.
4. Invigilators can view live data on the dashboard.
