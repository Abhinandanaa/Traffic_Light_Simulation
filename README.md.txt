# 🚦 Traffic Light Control System (Verilog)

This project simulates a 4-phase traffic light controller using Verilog HDL.  
It is designed for a basic junction with North-South and East-West directions.

---

## 🧠 Features

- **FSM-based design** with 4 states:
  - NS Green, EW Red
  - NS Yellow, EW Red
  - NS Red, EW Green
  - NS Red, EW Yellow
- **Clock-driven timing**
- **Testbench** provided for simulation

---

## 📁 Files

| File Name         | Description                      |
|------------------|----------------------------------|
| `traffic_light.v` | Verilog source code of FSM logic |
| `testbench.v`     | Testbench to simulate behavior   |

---

## 🧪 How to Run Simulation

You can run this simulation using any Verilog simulator such as:

- [📍 EDA Playground (Free)](https://www.edaplayground.com)
- ModelSim / Vivado

### ⏯️ Steps in EDA Playground:
1. Go to [EDA Playground](https://www.edaplayground.com)
2. Choose **SystemVerilog** + `Icarus Verilog` or `ModelSim`
3. Paste both `traffic_light.v` and `testbench.v`
4. Click **Run**

---

## 📷 Output Sample

```text
Time=0 ns   | NS Light=10 | EW Light=00
Time=10 ns  | NS Light=10 | EW Light=00
...
Time=60 ns  | NS Light=01 | EW Light=00
Time=90 ns  | NS Light=00 | EW Light=10
