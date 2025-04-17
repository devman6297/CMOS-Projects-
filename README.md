# 🧠 10T and 8T SRAM Cell with Static Noise Margin (SNM) Analysis

This repository includes the design and SNM analysis of **10-transistor (10T)** and **8-transistor (8T)** SRAM cells. The project focuses on evaluating read/write stability, SNM characteristics, and overall robustness of SRAM cells for low-power memory applications.

---

## 📁 Repository Contents

| File Name                  | Description |
|---------------------------|-------------|
| `sram_10t.jpg`            | Schematic of the base 10T SRAM cell. |
| `op_sram10t.jpg`          | Schematic of an optimized 10T SRAM cell variant. |
| `sram10t_snm.jpg`         | SNM butterfly plot for the base 10T SRAM cell. |
| `op_sram10t_snm_3.jpg`    | SNM butterfly plot for the optimized 10T SRAM cell. |
| `sram_8t.jpg`             | Schematic of the standard 8T SRAM cell. |
| `sram8t_snm.jpg`          | SNM butterfly plot for the 8T SRAM cell. |

---

## 🎯 Project Goals

- ✅ Design and simulate **8T** and **10T** SRAM cells.
- ✅ Perform **Static Noise Margin (SNM)** analysis using butterfly curves.
- 🔄 Compare SRAM topologies in terms of:
  - SNM under read/write operations
  - Area and complexity
  - Power efficiency
  - Read/Write decoupling

---

## 🧪 Tools & Technologies

- ⚙️ **EDA Tools**: Cadence Virtuoso / NgSpice / LTSpice
- 📊 **MATLAB** or **Python**: For SNM plotting and data processing
- 🧱 **TSMC 180nm PDK**: CMOS technology node used in simulation
- 📷 **Visual Analysis**: Schematic images and SNM butterfly plots

---

## 📐 Schematics

### 🔹 10T SRAM Cell

![image alt](https://github.com/devman6297/CMOS-Projects-/blob/main/Sramm_10t/sram_10t.jpg?raw=true)

### 🔹 Opetaion of 10T SRAM Cell

![image alt](https://github.com/devman6297/CMOS-Projects-/blob/main/Sramm_10t/op_sram10t.jpg?raw=true)

### 🔹 8T SRAM Cell

![image alt](https://github.com/devman6297/CMOS-Projects-/blob/main/Sramm_8t/sram_8t.jpg?raw=true)

---

## 📈 SNM Analysis

Static Noise Margin (SNM) is the key indicator of memory stability. It is determined using the **butterfly curve method**, derived from voltage transfer characteristics (VTC) of cross-coupled inverters.

> 🟩 A larger SNM square indicates better stability and noise resilience.

### 🔹 SNM - 10T SRAM

![image alt](https://github.com/devman6297/CMOS-Projects-/blob/main/Sramm_10t/sram10t_snm.jpg?raw=true)

### 🔹 SNM - SNM Plot 10T SRAM

![immage alt](https://github.com/devman6297/CMOS-Projects-/blob/main/Sramm_10t/op_sram10t_snm_3.jpg?raw=true)

### 🔹 SNM - 8T SRAM

![image alt](https://github.com/devman6297/CMOS-Projects-/blob/main/Sramm_8t/op_sram8t_snm_2.jpg?raw=true)

---

## 📊 Results Summary

| SRAM Cell Variant | SNM Observations |
|-------------------|------------------|
| **10T Base**      | Moderate SNM; good read stability but tighter write margin. |
| **10T Optimized** | Improved SNM due to better read/write path separation. |
| **8T SRAM**       | SNM analysis included for future comparison. Typically shows better read SNM than 6T. |

---

## ➕ Future Work

- [ ] Add 6T SRAM for baseline reference.
- [ ] Include layout designs and area comparisons.
- [ ] Perform Monte Carlo analysis for process variation.
- [ ] Add power consumption and delay benchmarks.

---

## 📬 Contact

For questions or collaboration:

- 📧 [devbakura4@gmail.com](devbakura4@gmail.com)
- 🌐 [[Your LinkedIn or Website](https://www.linkedin.com/in/neil-rudra-mukherjee-668716248/)]

---


