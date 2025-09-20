# 🛠️ Week 0 — Tool Installation | RISC-V SoC Tapeout (VSD)

Welcome to **Week 0** of the **RISC-V Reference SoC Tapeout Program (VSD)**.  
This week focused on **setting up the environment** and installing the essential open-source EDA tools.

---

## ⚙️ System Requirements

| Resource | Requirement |
|----------|-------------|
| RAM      | 6 GB |
| Storage  | 50 GB HDD |
| OS       | Ubuntu 24.04.3 |
| CPU      | 4 vCPU |

---

## **TOOL CHECK**
#### <ins>**Yosys**</ins>

```
$ sudo apt-get update
$ sudo apt install git                
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ git submodule update --init --recursive
$ sudo apt install make               # If make is not installed
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make 
$ sudo make install
```

<img width="1293" height="283" alt="Yosys" src="https://github.com/user-attachments/assets/73eb8a9b-2062-4165-a72a-18dada307e23" />


#### <ins>**Iverilog**</ins>
```
$ sudo apt-get update
$ sudo apt-get install iverilog
```
<img width="1293" height="963" alt="Icarus Verilog" src="https://github.com/user-attachments/assets/889d2397-ac31-40ad-b698-111cc1ff443e" />

#### <ins>**GTKWave**</ins>
```
$ sudo apt-get update
$ sudo apt install gtkwave
```
<img width="1242" height="1030" alt="GTK_Wave" src="https://github.com/user-attachments/assets/9763c751-0635-4c0a-bf9b-dd7bdcd67f2a" />

