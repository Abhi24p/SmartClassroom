Smart Classroom Automation Using Sensors

A smart, automated classroom system designed to reduce electricity consumption by automatically controlling lights and fans using sensors such as PIR, IR, and LM35.
This project ensures efficient usage of electrical energy in educational institutions and supports physically disabled users by eliminating the need for manual switches.

📌 Features

🔋 Automatic Power Saving

Lights turn ON when motion is detected

Lights turn OFF after a delay when room is empty

🌡 Temperature-Based Fan Control

Fan turns ON when temperature exceeds threshold

Fully automated cooling system

👤 Occupancy Detection

PIR sensor detects human presence

IR sensor detects entry/exit direction

⚡ Energy Efficiency

Saves up to 86% electricity per light

👨‍🦽 Support for Physically Disabled Users

No need to manually operate switches

🏫 Ideal for Classrooms, Labs, Offices, and Buildings

🏗 Project Architecture
Block Diagram
Power Supply → Sensors → Microcontroller → Driver/Relay → Fan & Light

Sensors Used

PIR Sensor (motion detection)

IR Proximity Sensor (entry/exit)

LM35 Temperature Sensor

Thermistor (for fan speed control)

Controller

ATmega328P (Arduino)

Output Devices

LED indicators

Lights (via relay)

Fan (via driver circuit)

📦 Hardware Components

Arduino / ATmega328P

PIR Sensor

IR Proximity Sensor

LM35 Temperature Sensor

Thermistor

Relay Module (12V)

Voltage Regulator (LM7805/LM7812)

Driver Circuit

LED/Lights

Fan

Power Supply

💻 Software Used

Arduino IDE

C/C++ Programming

Serial Monitor (for debugging)

🧠 Working Principle

PIR sensor detects motion → Light turns ON

No motion for 30 seconds → Light turns OFF

LM35 continuously measures room temperature

If temperature > threshold → Fan turns ON

IR sensor detects presence at door for enhanced accuracy

📊 Results
Parameter	Without PIR	With PIR
Light usage hours/day	12 hrs	3 hrs
Energy consumption	High	Low
Savings per light (per month)	–	86%

The system significantly reduces power wastage and improves energy efficiency.
