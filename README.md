# Injection Molding Machine – PLC Automation

## 📌 Project Overview
This project implements a **fully automated Injection Molding Machine control system** using a **Programmable Logic Controller (PLC)**.  
The process cycle is modeled in **ladder logic** and covers all major stages of injection molding:

1. **Clamping** – Closing and locking the mold with sufficient force.  
2. **Injection** – Feeding molten plastic into the mold cavity under controlled pressure.  
3. **Cooling** – Holding the mold closed while the part solidifies.  
4. **Ejection** – Opening the mold and ejecting the finished part.

![image alt](https://github.com/Duvindu-Ushan/Injection-Molding-Machine/blob/038b706a350bb1ae48ad5e2c06a5aa8ea2cf0c34/InjectionMolding.gif)

The ladder program ensures **sequential operation, interlocks, and safety conditions** required in an industrial environment.

---

## ⚙️ Features
- Automatic cycle execution (no manual intervention required).  
- State-based control with sequential step transitions.  
- Timers used for **cooling** and **dwell time** management.  
- Safety interlocks for **clamp closed**, **injection ready**, and **ejector return** conditions.  
- Scalable design for integration with real-world I/O modules.     

---

   git clone https://github.com/your-username/InjectionMoldingPLC.git
