# Smart-City-IIoT-project
This Smart City Automation project showcases the implementation of intelligent street lighting and surveillance using Cisco Packet Tracer. The system uses wireless IoT communication, motion detection, and solar intensity sensing to improve energy efficiency and public safety.
# Smart City Automation using Cisco Packet Tracer

## 📖 Project Overview

This project presents a **Smart City Automation System** developed using **Cisco Packet Tracer** as part of the **L&T EduTech Industrial Internet of Things (IIoT) Internship**.

The system demonstrates an intelligent urban infrastructure where IoT devices communicate wirelessly through a **Home Gateway**. It automates street lighting based on solar intensity and motion detection while simultaneously implementing a smart surveillance system that activates a webcam and siren whenever movement is detected.

The project showcases the practical implementation of Industrial Internet of Things (IIoT) concepts using Cisco Packet Tracer.

---

## 🎯 Objectives

- Design a Smart City Automation System using Cisco Packet Tracer.
- Implement intelligent street lighting using solar intensity and motion detection.
- Develop a smart surveillance system using IoT devices.
- Demonstrate wireless communication through a Home Gateway.
- Showcase rule-based automation for smart city applications.

---

## 🛠️ Components Used

- Home Gateway
- Solar Panel
- Motion Detector (Street Lighting)
- Motion Detector (Surveillance)
- Smart Street Lights (3)
- Webcam
- Siren
- Laptop
- IoT Car

### Components Used

![Components Used](Screenshots/Components_Used.png)

---

## 🏗️ System Overview

The Home Gateway acts as the central controller of the Smart City network. All IoT devices are connected wirelessly and continuously exchange data with the gateway.

The Solar Panel monitors sunlight intensity, while two Motion Detectors independently monitor the lighting and surveillance zones. Based on the configured automation rules, the Home Gateway controls the street lights, webcam, and siren automatically.

### System Overview

![System Overview](Screenshots/System_Overview.png)

---

## 🔄 System Flowchart

The following flowchart illustrates the working of the Smart City Automation System.

![Flowchart](Screenshots/Flowchart.png)

---

# ⚙️ Automation Rules

## 🌙 Rule 1 – Night Mode

**Condition**

- Solar Panel ≤ 10 Wh
- Motion Detected

**Action**

- Light → ON
- Light 1 → ON
- Light 2 → ON

![Night Mode](Screenshots/Night_Mode.png)

---

## ☀️ Rule 2 – Day Mode

**Condition**

- Solar Panel > 60 Wh
- Motion Detected

**Action**

- Light → OFF
- Light 1 → DIM *(for demonstration purposes)*
- Light 2 → OFF

![Day Mode](Screenshots/Day_Mode.png)

---

## 🌆 Rule 3 – Evening Mode

**Condition**

- Solar Panel between 11 Wh and 60 Wh
- Motion Detected

**Action**

- All street lights operate in DIM mode.

![Evening Mode](Screenshots/Evening_Mode.png)

---

## 🚫 Rule 4 – No Motion Detected

Whenever no vehicle or pedestrian is detected, all street lights are automatically switched OFF to reduce unnecessary power consumption.

![No Movement](Screenshots/No_Movement_Lights_OFF.png)

---

## 🚨 Rule 5 – Surveillance ON

Whenever motion is detected in the surveillance zone:

- Webcam → ON
- Siren → ON

![Surveillance ON](Screenshots/Surveillance_ON.png)

---

## ✅ Rule 6 – Surveillance OFF

Whenever no motion is detected:

- Webcam → OFF
- Siren → OFF

![Surveillance OFF](Screenshots/Surveillance_OFF.png)

---

## 🔀 Combined Simulation

The following output demonstrates the simultaneous operation of both the street lighting and surveillance systems.

![Combined Condition](Screenshots/Combined_Condition.png)

---

## 📋 Automation Rule Configuration

The configured automation rules inside the Home Gateway.

![Automation Rules](Screenshots/Conditional_Rules.png)

---

## ▶️ How to Run

1. Open **Smart_City_Automation.pkt** in Cisco Packet Tracer.
2. Switch to **Simulation Mode**.
3. Adjust the Solar Panel value to simulate Day, Evening, or Night conditions.
4. Trigger the Motion Detectors.
5. Observe the automatic response of the Street Lights, Webcam, and Siren.

---

## 📁 Repository Structure

```
Smart-City-Automation-using-Cisco-Packet-Tracer
│
├── README.md
├── Smart_City_Automation.pkt
├── Smart_City_Automation_Report.pdf
├── Simulation_Demo.mp4
│
└── Screenshots
    ├── Components_Used.png
    ├── System_Overview.png
    ├── Flowchart.png
    ├── Conditional_Rules.png
    ├── Night_Mode.png
    ├── Day_Mode.png
    ├── Evening_Mode.png
    ├── No_Movement_Lights_OFF.png
    ├── Surveillance_ON.png
    ├── Surveillance_OFF.png
    └── Combined_Condition.png
```

---

## 💻 Software Used

- Cisco Packet Tracer
- Industrial Internet of Things (IIoT)
- Wireless IoT Devices
- Home Gateway

---

## 📄 Project Report

The complete project documentation is available in:

**📄 Smart_City_Automation_Report.pdf**

---

## 🎥 Simulation Video

The complete simulation and working demonstration of the project is available in:

**🎥 Simulation_Demo.mp4**

---

## 📚 References

- Cisco Networking Academy – Cisco Packet Tracer
- Cisco Networking Academy – Introduction to IoT
- Smart City using IoT Simulation Design in Cisco Packet Tracer (IJRASET)
- A Simulation-Based Smart City Architecture Using Arduino and Cisco Packet Tracer
- Smart City: Recent Advances in Intelligent Street Lighting Systems Based on IoT

---

## 👨‍💻 Author

**Lakshya Bhardwaj**

- **Degree:** B.Tech in Electronics and Communication Engineering
- **University:** VIT Bhopal University
- **Internship:** L&T EduTech – Industrial Internet of Things (IIoT)
- **Project:** Smart City Automation using Cisco Packet Tracer

---

## 🙏 Acknowledgement

This project was developed as part of the **L&T EduTech Industrial Internet of Things (IIoT) Internship**. The project demonstrates the implementation of smart city automation using wireless IoT devices, centralized control through a Home Gateway, and rule-based automation in Cisco Packet Tracer.
