# IoT Virtual Doctor Robot

This is a conceptual IoT-based healthcare project designed to simulate a virtual doctor that can monitor basic patient health parameters and send the data remotely to medical staff. It is aimed at minimizing human contact during health emergencies like pandemics.

## 🧠 Problem Statement

In environments where direct doctor-patient contact is risky (like during COVID-19), there's a growing need for contactless healthcare. Monitoring patients remotely can help ensure safety, efficiency, and real-time decision-making.

## 🎯 Objective

To build a smart robot using IoT that:
- Monitors basic health data (e.g., temperature)
- Moves toward patients automatically
- Sends data wirelessly to a central system
- Simulates interaction with healthcare professionals

## 🔧 Components Used

- **Arduino UNO** – Central controller
- **Temperature Sensor (DHT11)** – To detect patient body temperature
- **Wi-Fi Module (ESP8266/NodeMCU)** – To transmit data wirelessly
- **Motor Driver (L298N)** + wheels – For robot mobility
- **Buzzer/Speaker Module** – For alerts or instructions
- **LCD Display** – To show patient vitals

## 🧱 Block Diagram

![Architecture Diagram](./iot_virtual_doctor_block_diagram.png)

## ✅ Project Advantages

- Enables contactless basic health checkups
- Reduces human-to-human transmission risks
- Provides remote data logging and monitoring
- Can be used in hospitals, quarantine zones, and elderly homes

## 🔮 Future Scope

- Integration with SPO2 or ECG sensors
- AI-based voice response and patient interaction
- Real-time cloud dashboard using AWS IoT or Thingspeak

## 📂 Files Included

- `Virtual_Doctor_Robot.pptx` – Full project presentation with explanation  
- `iot_virtual_doctor_block_diagram.png` – Block diagram of system architecture

📄 Download Project PPT: [Virtual_Doctor_Robot.pptx](./Virtual_Doctor_Robot.pptx)

*This project showcases how IoT can reshape healthcare delivery through automation, remote sensing, and real-time alerts.*

