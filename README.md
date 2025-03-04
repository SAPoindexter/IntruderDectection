# IntruderDectection
This project is an intruder detection system that uses a motion detection to identify unauthorized individuals. It uses a PIR sensor to trigger alerts and control an Arduino-based alarm system.

# System Components
PIR Sensor: Detects movement and activates the camera for facial recognition.
Arduino Alarm: Activates LEDs and a buzzer based on detection results.

# References 
https://forum.arduino.cc/t/using-a-passive-buzzer/850695
https://randomnerdtutorials.com/arduino-with-pir-motion-sensor/

# Project Steps
### 1. Set Up the Hardware
- Connect the PIR sensor to the Arduino:
  - VCC to 5V
  - GND to GND
  - OUT to a digital pin 
- Connect the buzzer:
  - Positive to a digital pin
  - Negative to GND
- Connect an LED:
  - Anode to a resistor and then to a digital pin
  - Cathode to GND

### 2. Upload Arduino Code
- Open Arduino IDE and write a sketch to:
  - Read input from the PIR sensor.
  - Trigger the buzzer and LED when motion is detected.
- Upload the code to the Arduino board.

### 3. Power the System
- Use a USB cable or an external power supply to power the Arduino.

### 4. Test the Motion Detection
- Walk in front of the PIR sensor and verify that the buzzer and LED activate.
- Adjust the PIR sensor sensitivity if needed.

### 5. Fine-Tune the System
- Modify the delay times and sensor thresholds in the Arduino code for optimal detection.
- Ensure the system is responsive and minimizes false triggers.

# Versions Used
 - Python: 3
 - PySerial: 3.3
 - Arduino IDE: Latest
 - Hardware: Arduino Mega 2560


