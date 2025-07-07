Flood Monitoring System – IoT & Data Acquisition Project

This project simulates a Flood Monitoring System using ESP32 and an Ultrasonic Sensor (HC-SR04) on the Wokwi online simulator. It monitors water levels in real time and triggers alerts when the water level crosses a threshold of 100 cm, indicating a potential flooding scenario.

---

Aim

To simulate a smart flood monitoring system that:
- Continuously measures water levels using an ultrasonic sensor.
- Sends alerts via cloud or serial monitor when water levels exceed 100 cm.

---

Problem Statement

Floods can cause severe damage if not predicted in advance. Traditional manual monitoring systems are inefficient and delay emergency response. There is a need for a real-time, automated system to monitor water flow levels and send alerts before disasters strike.

---

Scope of the Solution

- Real-time water level monitoring at a dam or reservoir.
- Configurable flood threshold (set at 100 cm for this project).
- Alerts printed to serial monitor (can be extended to cloud via Firebase, IFTTT, Blynk, etc.).
- Fully simulated using free tools like Wokwi (no hardware needed).
- Scalable to real-world deployments with minor modifications.

---

**Components Used**

**Hardware (Simulated):**
- ESP32 microcontroller
- HC-SR04 Ultrasonic Distance Sensor
- Optional: LED or buzzer for local alerts

**Software:**
- Wokwi online simulator (https://wokwi.com)
- Arduino IDE (for real hardware use)
- Serial monitor for alert messages

**Cloud (Optional Extensions):**
- Firebase, Blynk, or IFTTT for real alerts
- ThingSpeak for real-time dashboards
- MQTT broker (e.g., Mosquitto) for publish-subscribe system

---

System Flow

START  
↓  
Initialize ESP32 and HC-SR04  
↓  
Measure water level (in cm)  
↓  
Compare with flood threshold (100 cm)  
↓  
IF level > 100 cm  
  → Trigger alert  
ELSE  
  → Continue monitoring  
↓  
Delay and repeat

---

**Wokwi Simulation**

View and run the simulation here:  
https://wokwi.com/projects/375735159006651393

Note: You can change the `floodThreshold` value in code to simulate different conditions.

---

Project Structure

FloodMonitoringSystem/  
├── README.md  
├── code/  
│   └── flood_monitoring.ino  
├── docs/  
│   ├── aim.md  
│   ├── problem-statement.md  
│   ├── scope.md  
│   └── components.md  
├── circuit/  
│   ├── wokwi-circuit.png  
│   └── wokwi-link.txt  
├── flowchart.png  
└── demo/  
  └── demo-video.mp4

---

Demo Video

A demo video showing the simulation in action (with alert on 100 cm breach) should be included here.  
Add your OBS screen recording in the demo folder.

---

Future Enhancements

- Connect to Firebase and send real alerts.
- Add a local display (OLED) for level monitoring.
- Control floodgates automatically using servos.
- Use LoRa or GSM for remote locations.

---

Author

Name: Sameer Lalchandani
Institution: Vellore Institute of Technology
GitHub: https://github.com/sameerlalchandani


