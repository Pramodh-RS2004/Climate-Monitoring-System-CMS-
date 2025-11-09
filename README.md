

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&color=2ecc71&center=true&vCenter=true&width=900&height=60&lines=🌱+LoRa-Based+Climate+Monitoring+System+🌍;+   Multi-Sensor+Integration+%7C+Real-Time+Data+Acquisition" alt="Typing Animation" />
</h1>

---

## 📘 Project Overview
> Designed and implemented a robust **Climate Monitoring System** featuring **LoRa-based communication** and **multi-sensor integration** for accurate, real-time environmental data acquisition. This solution provides a reliable, long-range method to monitor critical environmental parameters across large areas.

This project goes beyond simple data logging by incorporating resilient hardware design, custom PCB development, and a comprehensive data visualization pipeline to address real-world environmental challenges efficiently.

---

## ⚙️ Key Features & Technical Specifications

* 📡 **LoRa Communication:** Utilizes **LoRaWAN** for long-range, low-power data transmission from remote sensor nodes to the central gateway.
* 🌡️ **Multi-Sensor Integration:** Collects simultaneous data for **temperature, humidity, ambient light, and air quality**.
* ⚡ **Intelligent Power Management:** Incorporates a **Dual Power Switching Module** (AC/Solar/Battery) for uninterrupted operation in remote locations.
* 💾 **Edge Data Processing:** Data is pre-processed on the **Edge Gateway Board (RuggedBoard-LMX 6UL)** before transmission to the cloud.
* 🎨 **Data Visualization:** Developed remote monitoring and data visualization features for actionable insights into environmental conditions.
* 🧩 **Custom Hardware:** Developed complete hardware schematics and PCB layout for production readiness.

---

## 🧠 System Architecture: Climate Monitoring System

The system is designed around a distributed network of sensor nodes reporting to a central edge gateway, powered by a robust, autonomous power management system.

<p align="center">
  <img src="Climate Monitorig System.png"  width="800" />
</p>

### 📡 Data Acquisition Path

1.  **Slave Sensor Nodes:** Multiple slave nodes collect data (Temp, Hum, Light, Air Quality).
2.  **LoRa Transmission:** Data is transmitted wirelessly over LoRa to the Edge Gateway.
3.  **Edge Gateway (RuggedBoard):** Receives, aggregates, and processes data.
4.  **Cloud/Visualization:** Processed data is sent to a cloud platform for real-time monitoring and historical analysis.

### 🔋 Autonomous Power Management

The Edge Gateway and communication modules are powered by a redundant system for 24/7 reliability, as shown in the uploaded diagram:
* **Primary Source:** **24V AC Adapter**.
* **Backup Source:** **40W Solar Panel** charging a **12.8V 12AH LiFePO4 Battery**.
* **Dual Power Switching Module:** Ensures seamless transition between the AC/Solar/Battery sources.
* **DC-DC Buck Converter:** Steps down the 24V/13V bus voltage to the required **5V** for the Edge Gateway.

---

## 🛠️ Tools & Technologies
<p align="center">
  <img src="https://img.shields.io/badge/Altium%20Designer-8B0000?style=for-the-badge&logo=altiumdesigner&logoColor=white"/>
  <img src="https://img.shields.io/badge/LoRa-4C9C1B?style=for-the-badge&logo=lora&logoColor=white"/>
  <img src="https://img.shields.io/badge/Embedded%20C%2F++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

* **Hardware Design:** Altium Designer (Schematics and PCB Layout)
* **Communication Protocol:** LoRaWAN
* **Embedded Programming:** C/C++ on Microcontrollers for Sensor Nodes
* **Gateway OS:** Embedded Linux (running on RuggedBoard-LMX 6UL)
* **Power Simulation:** Used SPICE simulation for stability analysis of the switching and charging circuits.

---



## 👨‍💻 Author & Contact
**Pramodh R S**  
Embedded Systems Engineer – *PHYTEC Embedded Pvt. Ltd, Bengaluru*  

| Platform | Link |
| :--- | :--- |
| 📧 Email | <a href="mailto:rspramodh5@gmail.com">rspramodh5@gmail.com</a> |
| 🔗 LinkedIn | <a href="https://www.linkedin.com/in/pramodh-rs-3190692b6">Pramodh R S</a> |
| 🐙 GitHub | <a href="https://github.com/Pramodh-RS2004">@Pramodh-RS2004</a> |

---

## 📝 License
This project is open-source and available under the **MIT License**.

## ⭐ Acknowledgments
Thanks to **PHYTEC Embedded Pvt. Ltd** for providing the **RuggedBoard-LMX 6UL** platform and hardware development support.
