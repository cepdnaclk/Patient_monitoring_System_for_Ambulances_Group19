# Patient_monitoring_System_for_Ambulances_Group19
This is an IoT based real time patient monitoring device along with the ambulance location tracking system.

[Link to the project page](https://cepdnaclk.github.io/Patient_monitoring_System_for_Ambulances_Group19/)
# PROBLEM
What can happen if ambulance arrives late at the emergency case ?

What can we do while Ambulance is carrying the Patient ?

No system for real-time patient monitoring and updating

No location tracking or time prediction system 

# EXISTING METHOD

Currently there are number of health monitoring systems available for ICU patients which can be used only when patient is on bed.

System is wired

Huge in size

Monitoring particular disease only

# PROPOSED METHOD

Data of patient health can be sent to a longer distance through the cloud

Find exact co-ordinates of ambulance using GPS

Fully automated system

Can take several measurements

# INTRODUCTION

Three main functions of the device 

1) Patient health monitoring 
2) Location tracking
3) Send real time data to the hospital


# SOLUTION ARCHITECTURE
![SolutionArchitecture drawio (1)](https://user-images.githubusercontent.com/99112218/198895367-5f687978-a121-4d50-b8ab-266e6b5376eb.png)

# Hardware Components

1) Arduino UNO ATMega328P
2) GPS Modem (NEO6MV2)
3) ESP8266 Wifi Module

# Sensors

1) Pulse Rate Heartbeat Sensor Module
2) Temperature Sensor Module
3) Blood Pressure Sensor - GSR V1.1


# SECURITY CONCERNS

Authentication

User1 & User2 should enter the password to get access to the device and the monitoring system respectively.

Encryption

Communication between IoT device and cloud will be encrypted (AWS Encryption SDK)

Firewall

Relevant Firewalls will be configured to  ESP8266 wifi module


# ADDITIONAL FEATURES

Sending personal details of the patient to the hospital

Informing initial health conditions of the patient through the device itself 

According to the availability of the hospital ambulance can choose the nearest hospital








