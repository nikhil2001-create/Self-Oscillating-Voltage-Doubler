# 🔋 Self-Oscillating Voltage Doubler for Energy Harvesting

This repository contains the implementation and simulation results of a **self-oscillating switched-capacitor voltage doubler**, based on the IEEE paper:

> **"An Ultra-Low Power Fully Integrated Energy Harvester Based on Self-Oscillating Switched-Capacitor Voltage Doubler"**  
> _Wanyeong Jung, Sechang Oh, Suyoung Bang, Yoonmyung Lee, Zhiyoong Foo, Gyouho Kim, Yiqun Zhang, Dennis Sylvester, and David Blaauw_  
> _IEEE Journal of Solid-State Circuits, Vol. 49, No. 12, December 2014_  
> DOI: [10.1109/JSSC.2014.2346788](https://doi.org/10.1109/JSSC.2014.2346788)

---

## 🧠 Overview

This project implements the key concept of a **self-sustained, clock-less voltage doubler** circuit using stacked ring oscillators and flying capacitors. The architecture enables efficient energy harvesting from ultra-low power sources such as indoor photovoltaics.

---

## 🔧 Technology Used

- **Technology Node:** GPDK045 (45nm CMOS)
- **Tool:** Cadence Virtuoso
- **Simulation Type:** Transient, Parametric Sweeps, DC Analysis

---

## ⚙️ Circuit Design Flow

1. ✅ Implemented and analyzed **3-stage and 5-stage ring oscillators**
2. ✅ Performed **parametric sizing** of PMOS and NMOS transistors (2W:1W ratio)
3. ✅ Designed and simulated **self-oscillating voltage doubler**
4. ✅ Conducted **fly capacitor sweep analysis**
5. ✅ Tested under **varying load conditions** to measure optimum efficiency
6. ✅ Achieved output efficiency up to **0.22 mA load current**

---

## 📊 Key Observations

- Startup validated under no-load
- Optimum transistor sizing improves oscillation and voltage swing
- Efficiency scales with fly cap value and load tuning
- Maximum efficiency obtained under load of ~0.22 mA

---

## 👨‍🔬 Contributors

- 👨‍🏫 **Instructor:** Prof. Sakshi Arora, Dept. of ECE, IIIT Bangalore - (sakshi.arora@iiitb.ac.in)
- 🎓 **Student 1:** Nikhil Bhusari – (nikhil.bhusari@iiitb.ac.in)  
- 🎓 **Student 2:** Talakokkula Karthik Satyanarayana – (talakokkulakarthik.satyanarayana@iiitb.ac.in)


---

## 📁 Files

**Project Report:**

[PMIC Project Final Presentation.pdf](https://github.com/user-attachments/files/20206251/PMIC.Project.Final.Presentation.pdf)
