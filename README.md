# Emergency Care Accident Detection System 🚑

## 📌 Overview
An IoT-based system that detects accidents and sends real-time alerts to emergency services.

## ⚙️ Tech Stack
- Raspberry Pi
- Python
- GPS & GSM Modules

## 🚀 Features
- Real-time accident detection  
- Automatic alert system  
- GPS location sharing  

## 📷 Output


https://github.com/user-attachments/assets/eed737f5-ec54-465b-b727-85452ffad53f

<img width="960" height="1280" alt="circuit" src="https://github.com/user-attachments/assets/59310d22-ce87-4555-a4a2-9a63c9b37ac9" />

## ▶️ How to Run
1. Install dependencies
pip3 install pyserial RPi.GPIO
2. Enable serial on Raspberry Pi
sudo raspi-config
Interface Options → Serial → Enable
🔌 Wiring Overview
Impact Sensor (SW-420)
VCC → 5V
GND → GND
DO → GPIO17
GPS Module
TX → RX (Pi)
RX → TX (Pi)
GSM Module (SIM800)
TX → RX
RX → TX
External power recommended ⚠️
