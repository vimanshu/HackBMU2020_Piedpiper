# HackBMU2020_Piedpiper

SoldierSpect is basically a suit, mainly designed for military personnel. It constitutes of various sensors like XD-58C Heart rate sensor, MQ-135 Air Quality Sensor and DHT11 Temperature and Humidity Sensor. 
They're connected to the nodeMCU, to collectively send data to a web server and an application.

We've integrated a GSM module to send a message to the medic to send help or to the high rank officers, to send more force(if required).

SoldierSpect_Arduino contains the code to link Arduino with the GSM module.
SoldierSpect_nodeMCU contains the code to link all the sensors collectively and send the data to the app and the webserver.
