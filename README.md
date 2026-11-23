Smart Energy Meter Using ESP32

An IoT-Based Real-Time Electrical Energy Monitoring System

⸻

1. Project Overview

The Smart Energy Meter Using ESP32 is an IoT-based electrical energy monitoring system developed to measure, monitor and track electricity consumption. The project integrates an ESP32 microcontroller with voltage and current sensors to acquire electrical parameters and provide information about energy usage.

The system uses the ZMPT101B voltage sensor to measure AC voltage and the SCT-013 current sensor to measure load current. The ESP32 processes the sensor readings to calculate electrical parameters such as voltage, current, power and energy consumption.

The measured values are displayed on an LCD and transmitted to the Blynk IoT platform, enabling users to monitor electrical parameters remotely through a smartphone.

Additionally, the system incorporates a relay-based load control mechanism and a buzzer alert system to indicate suspected abnormal or unauthorized energy usage.

2. Project Objectives

* Develop an affordable IoT-based energy monitoring system.
* Measure AC voltage and load current using dedicated sensors.
* Calculate electrical power and energy consumption.
* Enable remote monitoring through the Blynk IoT platform.
* Implement relay-based electrical load control.
* Provide alerts for suspected abnormal energy usage.

3. Hardware Components

Component	Function
ESP32 DevKit V1	Main microcontroller
SCT-013 Current Sensor	Load current measurement
ZMPT101B Voltage Sensor	AC voltage measurement
LCD Display	Displays measured parameters
Relay Module	Electrical load control
Buzzer	Alert indication

4. Software and Technologies

* Programming: Embedded C/C++
* Microcontroller: ESP32
* Development Environment: Arduino IDE
* IoT Platform: Blynk
* Technology: Internet of Things (IoT)

5. Working Principle

1. The ZMPT101B voltage sensor measures the AC supply voltage.
2. The SCT-013 current sensor measures the current drawn by the connected load.
3. The ESP32 receives and processes the sensor signals.
4. Electrical parameters, including voltage, current, power and energy consumption, are calculated.
5. The measured values are displayed on the LCD.
6. Data is transmitted to the Blynk IoT platform for remote monitoring.
7. The relay and buzzer provide load control and alert functionality.

6. Key Features

* Real-time electrical parameter monitoring.
* Voltage and current measurement.
* Power and energy consumption calculation.
* Remote monitoring through a smartphone.
* IoT-based data visualization.
* Relay-based load control.
* Buzzer-based alert mechanism.

7. Applications

* Residential electricity monitoring.
* Smart home energy management.
* Electrical load monitoring.
* IoT-based energy management systems.
* Electricity consumption analysis.

8. Project Documentation

This repository includes project documentation and photographs illustrating the development and implementation of the system.

* Project report
* Hardware setup photographs
* Circuit diagrams
* System output screenshots

9. Learning Outcomes

This project provided practical exposure to embedded system development, ESP32 programming, electrical sensor interfacing, measurement of electrical parameters and IoT-based remote monitoring. It also helped develop an understanding of integrating hardware components with cloud-based monitoring platforms.

10. Conclusion

The Smart Energy Meter Using ESP32 demonstrates the application of embedded systems and IoT technology in electrical energy monitoring. By combining voltage and current sensors, an ESP32 microcontroller and the Blynk IoT platform, the system provides a convenient approach to monitoring electricity consumption and managing electrical loads.

⸻

Project Domain: Embedded Systems | Internet of Things | Electrical Engineering

Controller: ESP32 DevKit V1

Development Platform: Arduino IDE

Project Type: Academic Engineering Project