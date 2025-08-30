# ⚡ Spartan-6 DSP48A1 Project  

This project demonstrates the use of the **DSP48A1 primitive** on the Xilinx Spartan-6 FPGA using Verilog HDL.  
It includes a custom **MUX module (reg_mux)**, a **DSP datapath design (firstDSP)**, and a **testbench** verified with **QuestaSim/ModelSim**.  

---

## 📌 Features
- Implements a simplified model of the **DSP48A1 block**.  
- Parameterized register stages for flexible design.  
- Supports both **synchronous** and **asynchronous reset** styles.  
- Cascaded inputs/outputs for multi-block DSP designs.  
- Fully testable with included **testbench**.  

---

## 📂 Project Structure

---

## 🛠 Requirements
- Xilinx ISE or Vivado (for Spartan-6 synthesis)  
- ModelSim / QuestaSim (for simulation)  

---

## 🚀 Usage

### Simulation (ModelSim/QuestaSim)
1. Compile the design and testbench:  
   ```tcl
   vlog reg_mux.v firstDSP.v firstDSP_tb.v
