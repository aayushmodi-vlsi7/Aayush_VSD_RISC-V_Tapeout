# Aayush_VSD_RISC-V_Tapeout
This Repository contains all documentation of RISC-V SOC implementation

<div align="center">

[![RISC-V](https://img.shields.io/badge/RISC--V-SoC%20Tapeout-blue?style=for-the-badge&logo=riscv)](https://riscv.org/)
[![VSD](https://img.shields.io/badge/VSD-Program-orange?style=for-the-badge)](https://vsdiat.vlsisystemdesign.com/)
![Participants](https://img.shields.io/badge/Participants-3500+-success?style=for-the-badge)
![India](https://img.shields.io/badge/Made%20in-India-FF9933?style=for-the-badge)

</div>

---

## 📘 About the Program

The **RISC-V SoC Tapeout Program** by **VLSI System Design (VSD)** is **India’s largest collaborative silicon design initiative**.  
Participants learn to build a **System-on-Chip (SoC)** from **RTL to GDSII** using **100% open-source EDA tools**.

> 🎯 Empowering over **3500+ participants** to shape India’s semiconductor future.

This national initiative is held **in collaboration with IIT Gandhinagar**, offering a mix of **hands-on design, collaboration, and research exposure**.

### 🎓 Exclusive Benefits for Top 50 Students:
- Work directly under **IIT Gandhinagar Professors**  
- Get **hands-on access to Synopsys industry-grade EDA tools**

---

## 📅 Weekly Progress Overview

| Week | Focus Area | Tools Used |
|------|------------|------------|
| [Week 0](Week0/README.md) | Environment Setup & Toolchain Installation | Ubuntu VM, Yosys, Icarus Verilog, GTKWave |

---

### ✅ Key Learnings from Week 0:
- Set up **Ubuntu 20.04+ Virtual Machine** using **Oracle VirtualBox**  
- Installed and validated key open-source EDA tools:  
  - **Yosys** for synthesis  
  - **Icarus Verilog** for simulation  
  - **GTKWave** for waveform analysis  

---

## 📈 Weekly Progress Tracker

[![Week 0](https://img.shields.io/badge/Week%200-✅%20Completed-brightgreen?style=for-the-badge)](https://github.com/Nirbhay1909/Nirbhay_VSD-Tapeout-Program/tree/main/Week0)  
![Week 1](https://img.shields.io/badge/Week%201-🚧%20In%20Progress-lightgrey?style=for-the-badge)  
![Week 2](https://img.shields.io/badge/Week%202-Upcoming-lightgrey?style=for-the-badge)

> 📌 *Check back each week for detailed updates on my progress!*

---

## 🙏 Acknowledgments

Special thanks to:  
- [**Kunal Ghosh**](https://github.com/kunalg123) and the [**VSD team**](https://vsdiat.vlsisystemdesign.com/) for their continuous mentorship  
- **RISC-V International**, **India Semiconductor Mission (ISM)**, **VLSI Society of India (VSI)**, and [**Efabless**](https://github.com/efabless) for democratizing silicon design and fabrication

---

## 🔗 Useful Resources

- 🌐 [VSD Official Website](https://vsdiat.vlsisystemdesign.com/)  
- 📘 [RISC-V International](https://riscv.org/)  
- 🏭 [Efabless Open-source Silicon Platform](https://efabless.com/)

---

<div align="center">

✨ *Documenting my open-source silicon journey with RISC-V & VSD — One Tapeout at a Time!* ✨

</div>

---

### Code Snippets Example for Week 0 Setup

To set up your **Ubuntu 20.04** VM in **Oracle VirtualBox** and install the necessary tools, follow this code snippet:

```bash
# Step 1: Install VirtualBox on your machine
sudo apt update && sudo apt install virtualbox -y

# Step 2: Create a VM and Install Ubuntu 20.04
# (Make sure to follow the VirtualBox instructions to create and install Ubuntu)

# Step 3: Installing Open-Source EDA Tools (Yosys, Icarus Verilog, GTKWave)
sudo apt update
sudo apt install yosys  # For synthesis
sudo apt install iverilog  # For simulation
sudo apt install gtkwave  # For waveform analysis

# Step 4: Test the installation with a sample Verilog file
echo "module test; initial begin $display(\"Hello World\"); end endmodule" > test.v
iverilog -o test test.v
vvp test
