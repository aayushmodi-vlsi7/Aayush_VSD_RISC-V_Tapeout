# Aayush_VSD_RISC-V_Tapeout
This Repository contains all documentation of RISC-V SOC implementation# 🚀 **RISC-V SoC Tapeout Program — VSD**

<div align="center">
    <img src="https://img.shields.io/badge/RISC--V%20SoC%20Tapeout-4c8bf5?style=for-the-badge&logo=riscv" alt="RISC-V SoC Tapeout">
    <img src="https://img.shields.io/badge/VSD%20Program-fe3d2f?style=for-the-badge" alt="VSD Program">
    <img src="https://img.shields.io/badge/Participants-3500%2B-00cc00?style=for-the-badge" alt="Participants">
    <img src="https://img.shields.io/badge/Made%20in%20India-ff9933?style=for-the-badge" alt="Made in India">
</div>

---

## 📌 **About the Program**

The **RISC-V SoC Tapeout Program** is a major initiative by **VLSI System Design (VSD)**, in collaboration with **IIT Gandhinagar**, empowering over **3500+ participants** to gain hands-on experience in the **full SoC design flow** — from **RTL to GDSII** — using **open-source EDA tools**.

Participants will learn to design a **System-on-Chip (SoC)** and work with open-source tools such as **Yosys**, **Icarus Verilog**, and **GTKWave** for simulation, synthesis, and waveform analysis.

---

## 🎯 **Key Highlights**

- **Top 50 Students** will receive direct mentorship from **IIT Gandhinagar professors**.
- **Hands-on experience with Synopsys tools** for advanced simulation and design.

---

## 🛠️ **Key Learnings From Week 0**

### 🗓 **Week 0: Environment Setup**
- **Objective**: Set up the development environment and get familiar with the required EDA tools.
- **What I did**:
  - Installed **Ubuntu 20.04** on a **VirtualBox**.
  - Set up essential tools: **Yosys**, **Icarus Verilog**, and **GTKWave**.
  - Verified the setup by running a simple **Verilog simulation**.

---

## 📅 **Program Overview**

| **Week** | **Focus Area**            | **Status**      | **Tools Involved**      |
|----------|---------------------------|-----------------|-------------------------|
| **Week 0** | Environment Setup          | ✅ Completed    | Ubuntu, Yosys, Iverilog, GTKWave |
| **Week 1** | RTL Design & Synthesis     | 🚧 Upcoming     | Yosys, Iverilog |
| **Week 2** | Physical Design & Layout   | ⏳ Upcoming     | OpenROAD, Magic |

---

## 🛠️ **Tools Used in Week 0**
- **Ubuntu VM Setup**: A stable environment for tool installation and testing.
- **Yosys**: RTL synthesis tool for transforming RTL code to a gate-level netlist.
- **Icarus Verilog**: Open-source Verilog simulator for functional verification.
- **GTKWave**: Tool for visualizing the waveform outputs from simulations.

---

## 📅 **Upcoming: Week 1**

### **What’s Coming Up in Week 1:**
- **Synthesis of RTL**: Converting the high-level RTL design into a **gate-level netlist** using **Yosys**.
- **Simulation**: Running further simulations with **Icarus Verilog** to verify the functionality of the synthesized design.
- **Power Analysis & Optimization**: Early exploration of power management techniques.

---

## 💬 **Code Example: Verilog Simulation**

Here’s a simple example to verify your simulation tools:

```verilog
module hello_world;
    initial begin
        $display("Hello, RISC-V World!");
    end
endmodule

