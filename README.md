# ⚡ Fault Analysis in Power Systems using MATLAB Simulink

This project contains a MATLAB Simulink model for simulating and analyzing various electrical faults in a power system. The objective is to study how different types of faults affect voltage and current in the system and to observe how relay logic can detect and respond to these faults.

---

## 📌 Project Overview

**Project Title:** Fault Analysis using MATLAB Simulink  
**Domain:** Electrical Engineering – Power Systems  
**Software Used:** MATLAB R2021b or later with Simulink

---

## 🔍 Faults Simulated

- Single Line-to-Ground (LG)
- Line-to-Line (LL)
- Double Line-to-Ground (LLG)
- Three-Phase Fault (LLL)

Each fault type is modeled and analyzed to observe:
- Voltage and current distortion
- Sequence component imbalance
- Relay triggering (based on threshold logic or SR flip-flop)

---

## 📁 Project Files
.
├── untitled5.slx # Core fault simulation model
├── untitled6.slx # Extended test setup or alternate circuit
├── README.md # Project documentation (this file)

---

## ▶️ How to Use

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/fault-analysis-matlab.git
   cd fault-analysis-matlab
2.Open the Simulink model
open('untitled5.slx')   % or open 'untitled6.slx' for alternate model

3.Configure Faults (if applicable)

Set fault time, type, and location from the Fault block or logic subsystem.

4.Run the simulation

Click on the Run button in Simulink.

Observe system response using Scope blocks.
