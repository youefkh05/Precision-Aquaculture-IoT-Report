Here’s the **updated README** for your repository — rewritten to reflect your **current LoRaWAN Smart Campus project** instead of the earlier Precision Aquaculture one:

---

# 🛰️ LoRaWAN Smart Campus IoT Report

This repository contains the final research report for the course **ELC4015 – Selected Topics in Communications (Internet of Things)** at **Cairo University**, prepared under the supervision of **Prof. Dr. Mahmoud El-Hadidi**.

The study is based on the publication:
**“LoRaWAN for Smart Campus: Deployment and Long-Term Operation Analysis”** by *Rumana Yasmin, Konstantin Mikhaylov, and Ari Pouttu* (Sensors, 2020).

---

## 📘 Objective

To analyze a large-scale, real-world **LoRaWAN Smart Campus deployment** and document its architecture, communication protocols, and system design according to the **IoT course analysis framework**.

---

## 📂 Repository Contents

* `Yousef_Khaled_ELC4015_Report_Final.pdf` – Final report submission
* `Case_Study_Paper.pdf` – Reference paper from *Sensors (MDPI, 2020)*
* `Figures/` – System architecture and layered communication diagrams
* `Appendices/` – Supporting tables (technical specs, acronyms, author correspondence)
* `Notes/` – Extracted insights and analysis drafts

---

## 🧠 Summary

This report investigates the **LoRaWAN-based environmental monitoring system** deployed at the **University of Oulu’s Tellus Innovation Arena**.
The system includes **331 sensor nodes (Elsys ERS CO₂ and ERS Sound)** covering the entire indoor space, transmitting real-time data via LoRaWAN (868 MHz, SF7, Class A) to a single **MultiTech Conduit MTCDT-LEU1-210 gateway** with an **integrated Network Server**.
Unlike typical LoRaWAN implementations, all data is processed and stored **locally within the university infrastructure**, ensuring full **data sovereignty**, security, and long-term operational reliability.

---

## 🔐 Key Technical Highlights

* **Protocol:** LoRaWAN (EU868 MHz, 125 kHz BW, SF7, CR 4/5)
* **Topology:** Star (single-gateway, no multi-hop)
* **Backhaul:** Ethernet (4G LTE tested as backup)
* **Network Server:** Integrated within the MultiTech gateway (on-premise)
* **Activation:** OTAA (Over-the-Air Activation)
* **Operation Period:** October 2017 – January 2020 (2+ years continuous)
* **Average Packet Loss:** 8.56 % (Max PER ≈ 11.33 %)

---

## 📚 References

[1] Yasmin, R.; Mikhaylov, K.; Pouttu, A. *LoRaWAN for Smart Campus: Deployment and Long-Term Operation Analysis.* **Sensors**, 2020, 20(23), 6721.
[DOI: 10.3390/s20236721](https://doi.org/10.3390/s20236721)

[2] LoRa Alliance. *LoRaWAN® Regional Parameters Specification RP002-1.0.4: EU863–870 MHz ISM Band (Channel Plan and Duty Cycle Regulations).* LoRa Alliance Technical Document, 2024.

---

## 👨‍💻 Author

**Yousef Khaled Omar Mahmoud**
Undergraduate Student – Electronics & Electrical Communications Engineering
**Faculty of Engineering, Cairo University**
Student ID: 9220984

📧 [yousef.mahmoud03@eng-st.cu.edu.eg](mailto:yousef.mahmoud03@eng-st.cu.edu.eg)
🔗 [GitHub Repository](https://github.com/youefkh05/Precision-IoT-Report)

---

