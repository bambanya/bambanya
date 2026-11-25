### Hi, I'm Matthew Kaingu Saro 👋

**Electrical & Electronic Engineering | Embedded Systems & Fault-Tolerant Industrial IoT**  
*Masinde Muliro University of Science and Technology (MMUST) • Kenya*

I design resilient Cyber-Physical Systems (CPS) that survive real-world electrical and environmental hazards. My engineering work focuses on bridging edge microcontrollers with power electronics, EMI-hardened communication buses, and low-cost cloud telemetry for rural infrastructure and precision agriculture.

---

### 🚀 Featured Engineering Project

#### [Smart Zero Grazing Telemetry & Automation Architecture](https://github.com/bambanya/Smart-Zero-Grazing-Architecture)
An autonomous, fault-tolerant IoT system engineered for precision dairy farming (~$60 USD prototype BOM). Built to eliminate dry-running pump failures, inductive kickback damage, and GSM brownouts on unstable rural power grids.

* **Electromechanical Protection:** Active-HIGH TIP120 Darlington firewall + opto-isolated relay + 1N4007 flyback diode protecting control logic from 12V inductive load spikes.
* **Power Rail Isolation:** Dedicated LM2596 buck converter (`4.0V`) with a `470µF` bulk charge reservoir isolating SIM800L `2.0A` transmission bursts from ESP32 logic.
* **Algorithmic Watchdogs & EMI Mitigation:** Non-blocking 3-second dry-run pump lockout timer and a 3-second SPI register heartbeat routine keeping MFRC522 RFID tracking immune to motor switching noise.
* **Edge-to-Cloud Pipeline:** 3-state dynamic I2C LCD carousel paired with direct HTTPS telemetry logging 8 operational metrics (climate, fluid levels, feed mass, and RFID cattle attendance) to Google Sheets.

---

### 🛠️ Core Technical Stack

* **Microcontrollers & Edge Compute:** ESP32 (FreeRTOS, Wi-Fi/HTTPS), Arduino, C / C++
* **Protocols & Buses:** SPI, I2C, UART, 1-Wire, PWM, GSM/GPRS (`AT` Commands)
* **Hardware & Power Electronics:** KiCad PCB Design, Fritzing, Buck Converters (LM2596), Opto-Isolated Relays, Darlington Drivers (TIP120), Load Cells (HX711), Ultrasonic & RFID Sensors
* **Cloud & Data Integration:** Google Apps Script, REST/HTTPS Webhooks, Automated Telemetry Logging

---

### 📫 Connect & Collaborate

* **Project Repository:** [Smart-Zero-Grazing-Architecture](https://github.com/bambanya/Smart-Zero-Grazing-Architecture)
* **Email:** 'matthewsaro7@gmail.com`
* **Location:** Kenya
