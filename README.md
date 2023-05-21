# Security_Framework_for_Educational_Institution_SSF
Smart Security Framework for Educational Institutions Using Internet of Things (IoT).
ReadMe File
*** Group 11 - Computer Networks Term Work *** 
Step by step methods to run the CN_TW_Team_11_CPT.pkt file.

===============
Step 1
===============
The first step in our project is to implement all the IoT Devices and Sensors to sense the data from the external environment to act up on any threat activity.

COMPONENTS USED:

* Smoke Detector
* Fire Monitor
* RFID Reader 
* Water level Monitor 
* Rain Alerting Sensor 
* Wind Monitoring Sensor 
* Siren
* Motion Detector 
* Trip Sensor (Security Scanner)
* Battery 
* Intercom 
* Smart Window 
* Lawn Sprinkler

===============
Step 2
===============
Collecting all the mentioned sensor data and immediately forwarding it to the Fog layer via WRT300N router.

Fog layer:
It is a mini cloud unit which is located very near to the sensing devices where all the time sensitive datas are proccessed.

COMPONENTS INSIDE FOG LAYER:
*Server PT
*Cloud PT 
*2960-24TT (Internet_Switch)

CONFIGURATION:

DEVICE NAME : Internet_Server 
DEVICE MODEL: Server-PT
PORT: FAST ETHERNET0 
IP ADDRESS : 200.0.0.1/24
MAC ADDRESS: 0060.7080.AAC5
GATEWAY : 200.0.0.10
DNS SERVER : 200.0.0.1

===============
Step 3
===============
Here we deal with Emergency Control Room (ECR) 
All the datas which are proccessed in the fog layer is being veiwed in the smart devices like Smartphone/PC/Tablets/TV.

==========================
Step to run the .pkt file
==========================
1) Set the Cisco packet tracer file in LOGICAL VIEW.
2) Run the whole simulation in REALTIME MODE.
3) Click on ADD SIMPLE PDU in the menu bar and click on the source device and the destination device.
4) Start the simulation. 
5) The simulation tab is used to analyse all the device's IP address/MAC address/Time/Protocols...
6) Stop the simulation. 

============X==============
