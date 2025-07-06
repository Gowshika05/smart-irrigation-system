SMART IRRIGATION SYSTEM USING CISCO PACKET TRACER


#Aim:

To simulate an IIoT-based smart irrigation system in Cisco Packet Tracer that monitors soil moisture levels and automates irrigation by controlling a water pump, thereby conserving water and enhancing crop management efficiency.

#Problem Statement:

Agricultural irrigation consumes a significant amount of freshwater, often inefficiently. Manual irrigation methods lead to water wastage and inconsistent crop health. There's a need for a smart, automated system that monitors soil moisture and activates irrigation only when required. This project demonstrates such a system using Cisco Packet Tracer to model sensor-actuator behavior and IoT communication.

#Scope of the Solution:

•	Simulates an IIoT-based automated irrigation system.
•	Demonstrates communication between IoT sensors and actuators via a Wi-Fi router.
•	Allows monitoring through a web interface.
•	Provides real-time moisture monitoring and automatic pump control.
•	Can be expanded to include multiple sensor zones or advanced analytics.

#Overview / Architecture of the Solution:

The Smart Irrigation System is built using IoT-enabled components in Cisco Packet Tracer to simulate how soil moisture levels can control irrigation automatically. The core idea is to reduce manual intervention and water wastage by using real-time sensor feedback and automation.

#System Overview:

•	A moisture sensor detects the soil's moisture level and sends the data to an IoT-enabled microcontroller or generic IoT device.
•	The microcontroller processes this data using programmed logic. If the moisture level drops below a set threshold, it triggers a smart water pump to turn ON.
•	If the moisture level is sufficient, the pump remains OFF.
•	All components (sensor, microcontroller, pump) are connected via a wireless router to an IoT server.
•	A web browser on a PC or smartphone accesses the IoT server to monitor sensor data and device status.

#Architecture Flow:

1.	Moisture Sensor → Microcontroller
                      Sends moisture data in real-time.
2.	Microcontroller Logic → Smart Water Pump (Actuator)
                            Turns ON/OFF based on threshold.
3.	Microcontroller → Wireless Router → IoT Server
                      Sends status updates and receives configuration.
4.	User → PC/Smartphone → Web Browser → IoT Server
                          Monitors system and optionally controls devices manually.
  	
#Required Components to Develop Solution:

•	IoT Moisture Sensor – Simulates soil moisture level detection.

•	IoT Microcontroller Device – Processes input from the sensor and controls the actuator.

•	Smart Water Pump (Actuator) – Turns ON or OFF based on the moisture sensor readings.

•	Home Gateway / Wireless Router – Connects all IoT devices to the network/cloud.

•	IoT Server – Simulates cloud monitoring and control through the IoT monitor.

•	Smartphone or PC – Used to access the IoT monitor interface through a web browser.

•	Cables (optional) – Used for wired connections if applicable in the simulation.

#Screenshot of circuit:

https://github.com/user-attachments/assets/10fefcf5-ee7e-4016-8bb0-cb92ddd3fa4d


#Demo link:

https://screenrec.com/share/JW5fEemtFc


