Intruder Alarm System - Arduino-Based Motion Detection Project
Project Overview
This project implements a cost-effective intruder detection system using an Arduino Nano and IR sensor. The system detects unauthorized motion within a 2-30 cm range and triggers immediate audible alerts through a buzzer, providing a basic security solution for homes, offices, and restricted areas.

Key Features
Motion detection using digital IR sensor
Instant alert system with 85dB buzzer
Serial monitor output for real-time monitoring
Simple Arduino implementation suitable for beginners
Low-power, compact design for easy deployment
Components Used
Arduino Nano (ATmega328P microcontroller)
IR Sensor Module (3.3-5V, digital output)
Buzzer (3-12V, 85dB sound output)
Breadboard and jumper wires
How It Works
The IR sensor continuously monitors for reflected infrared signals
When motion is detected (sensor output goes LOW):
Buzzer activates for 1 second
Serial monitor displays "Intruder detected!" alert
System automatically resets after each detection
Project Structure
intruder-alarm-system/  
├── ArduinoCode/  
│   └── intruder_alarm.ino  
├── CircuitDiagram/  
│   └── breadboard_layout.jpg  
├── Documentation/  
│   └── Intruder_Alarm_Report.pdf  
└── README.md  
Getting Started
Connect components as per wiring diagram:
IR Sensor: VCC→5V, GND→GND, OUT→D8
Buzzer: +→D3, -→GND
Upload provided Arduino code to Nano
Power via USB or 5V supply
Test by moving hand in front of IR sensor
Applications
Home security for doors/windows
Office/bank restricted area monitoring
Theft prevention in shops/warehouses
ATM security enhancement
Educational security system demonstration
Future Improvements
Add GSM/Wi-Fi for remote notifications
Integrate camera module for visual confirmation
Implement battery backup for power outages
Expand with multiple sensors for wider coverage
Develop mobile app for system monitoring
Contributors
Ripan Paul
Suraj Debbarma
Isha Debbarma
Dhritiman Roy
Siuli Debbarma
License
This project is open-source and available under the MIT License.
