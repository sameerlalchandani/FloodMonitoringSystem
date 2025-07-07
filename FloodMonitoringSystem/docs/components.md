# **Required Components**



##### **a) Hardware (Simulated in Wokwi)**

1. Ultrasonic Sensor (e.g., HC-SR04): Used to measure water levels by calculating the distance from the sensor to the water surface.



2\. ESP32 or NodeMCU: Microcontroller with built-in Wi-Fi capability for real-time cloud communication.



3\. LED / Buzzer (Optional):Acts as a local alert system to indicate water level breach at the physical location.



##### **b) Software**

1. Arduino IDE / PlatformIO: For writing, compiling, and uploading firmware to the ESP32/NodeMCU board.



2\. Wokwi Simulator: Online simulation environment for testing both circuit design and embedded code.



3\. Cloud Services (choose any): IFTTT / Blynk / MQTT Broker / Firebase / ThingSpeak – used to push alerts, log data, and perform remote monitoring.



##### **c) Cloud Environment**

1. Communication Protocol: Use of MQTT or HTTP to send sensor data to the cloud.



2\. Visualization \& Monitoring: Dashboards such as Blynk or ThingSpeak for live data visualization.



3\. Decision Logic: Threshold breach detection logic can be implemented either in the microcontroller firmware or within the cloud service rules.

