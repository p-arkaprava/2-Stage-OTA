# 2-Stage-OTA
A 2 stage OTA with overall gain arround 70 dB is designed using 180 nm CMOS technology
<br>
TSMC 0.18μm technology parameters (taken from model file):
<br>
VTn = 0.37V; VTp = 0.39V; μnCox = 230 μA/V2; μpCox = 100 μA/V2; Vdd = 1.8V; Lmin = 0.18μm; Wmin = 0.27μm;
<br>
# ⚙️ 2-Stage Operational Transconductance Amplifier (OTA) Design

This project involves the design and simulation of a **two-stage CMOS OTA** using LTspice. The OTA is a critical analog building block used in amplifiers, filters, and ADCs. The objective is to achieve high gain, wide bandwidth, and adequate stability for analog signal processing applications.

---

## 🧠 Design Overview

### ✨ Architecture:
- **Stage 1:** Differential amplifier with current mirror load
- **Stage 2:** Common-source amplifier for additional gain
- **Compensation:** Miller capacitor for stability

---

## 📈 Key Performance Metrics

| Parameter          | Target / Achieved |
|-------------------|-------------------|
| DC Gain            | ~85 dB            |
| Unity Gain Frequency | ~10 MHz         |
| Phase Margin       | ~60°              |
| Slew Rate          | ~10 V/µs          |
| Load Capacitance   | 1 pF              |
| Power Supply       | ±1.8 V            |

---

## 🧪 Tools Used

- **Simulation Tool:** LTspice
- **Technology Node:** 180nm CMOS (generic Level 1 models used)
- **Design Type:** Fully custom transistor-level OTA

---
---

## 👨‍💻 Author

**Arkaprava Paul**  
B.Tech in Electronics and Electrical Engineering  
Minor in Computer Science and Engineering  
Indian Institute of Technology, Guwahati  
📧 imapaul05@gmail.com | p.Arkaprava@iitg.ac.in  
🔗 [LinkedIn](www.linkedin.com/in/arkaprava-paul-73223a314) 

---

## 📄 License
This project is made for educational purpose. Please credit the author if any part of the project is reused.





