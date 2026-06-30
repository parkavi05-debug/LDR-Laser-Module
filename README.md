# LDR-Laser-Module
📚 Topics Covered
LDR Voltage Divider
Analog Value Mapping
Laser Module Basics
Safe Laser Handling
Threshold Logic
Beam Break Detection
OLED Display Integration
Buzzer Alerts
Push Button Toggle Logic
🛠 Components Used
Arduino UNO
OLED Display (SSD1306 I2C 128x64)
LDR Sensor
Laser Module
LED
Buzzer
Push Buttons
Resistors (220Ω, 10kΩ)
Breadboard
Jumper Wires
📂 Projects Included
1️⃣ Smart Light Meter
🎯 Objective

Build a simple light meter that continuously measures ambient light level and displays it on OLED.

Features

✔ Reads analog value from LDR
✔ Displays raw sensor value (0–1023)
✔ Shows light condition status

Bright 🌞
Normal ☁️
Dark 🌙
OLED Output
eARgle Labs

LDR : 756
Status : Bright
Concepts Used
Analog Input
analogRead()
OLED Display
Conditional Statements
2️⃣ Automatic Smart Night Lamp
🎯 Objective

Create an automatic street-light style lamp.

Features

✔ LED connected with LDR
✔ LED turns ON when environment becomes dark
✔ LED turns OFF in bright environment
✔ OLED displays LDR value and LED status

OLED Output
Smart Night Lamp

Light : 245
LED   : ON
Bonus

Three brightness zones:

Bright → LED OFF
Medium → Slow Blink
Dark → LED ON
3️⃣ Laser ON/OFF Monitor
🎯 Objective

Display the current state of laser module.

Features

✔ Button toggles laser ON/OFF
✔ OLED displays laser status
✔ Counts number of times laser switched

OLED Output
Laser Control

Status : ON
Count  : 05
Concepts Used
Digital Output
Push Button Toggle Logic
State Variables
OLED Updates
4️⃣ Laser Beam Detector
🎯 Objective

Use LDR to detect whether laser beam is properly aligned.

Features

✔ Laser continuously points to LDR
✔ Detects beam presence
✔ LED glows when beam detected
✔ OLED displays beam status

OLED Output
Beam Status

DETECTED

or

Beam Status

LOST !
Bonus

Show live signal strength percentage.

5️⃣ Laser Tripwire Security Alarm
🎯 Objective

Build a real-time security alarm system.

Features

✔ Laser continuously targets LDR
✔ Detects beam interruption
✔ OLED shows alert message
✔ Buzzer alarm sounds
✔ Red LED blinks

OLED Output
SECURITY MODE

Status:
MONITORING...

When interrupted:

!! ALERT !!

INTRUDER
DETECTED
Concepts Used
Analog Threshold Detection
Alarm Logic
Multi Output Control
6️⃣ Laser Security Counter
🎯 Objective

Count how many times laser beam has been interrupted.

Features

✔ Counts intrusions
✔ OLED displays total count
✔ Short beep for every detection
✔ Long beep every 10 detections

OLED Output
Laser Counter

Intrusions:
07
Bonus

Add reset button to reset counter.

7️⃣ Smart Museum Security System (Challenge Project)
🎯 Objective

Design a mini museum-style laser security system.

Features Required

✅ OLED Dashboard
✅ LDR Light Level Monitor
✅ Laser Beam Alignment Monitor
✅ Intruder Detection
✅ Buzzer Alarm
✅ LED Warning Indicator
✅ Intrusion Counter
✅ Reset Button

OLED Dashboard
eARgle Security

Light : 685
Beam  : OK
Count : 03
Mode  : Armed

When interrupted:

eARgle Security

⚠ ALERT ⚠
Intruder!
Count : 04
🔌 Circuit Connections (General)
Component	Arduino Pin
OLED SDA	A4
OLED SCL	A5
LDR Analog Output	A0
Laser Module	D7
LED	D8
Buzzer	D9
Button	D2 / D3
VCC	5V
GND	GND
💻 Software Used
Arduino IDE
SSD1306 Library
Adafruit GFX Library

Install Libraries:

Adafruit SSD1306
Adafruit GFX
Wire Library
📖 Learning Outcomes

After completing these projects, you will understand:

Sensor interfacing with Arduino
Analog and Digital Inputs
OLED Display Handling
Security System Design
Laser Beam Detection Logic
Alarm Systems using Buzzers and LEDs
Real-time Monitoring Systems
👨‍💻 Developed For

eARgle Labs IoT Workshop
Arduino + Embedded Systems + Security Applications
