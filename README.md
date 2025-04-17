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

![10T SRAM Cell]([sram_10t.jpg](https://github.com/devman6297/CMOS-Projects-/blob/main/Sramm_10t/sram_10t.jpg?raw=true))

### 🔹 Optimized 10T SRAM Cell

![Optimized 10T SRAM Cell](op_sram10t.jpg)

### 🔹 8T SRAM Cell

![8T SRAM Cell](sram_8t.jpg)

---

## 📈 SNM Analysis

Static Noise Margin (SNM) is the key indicator of memory stability. It is determined using the **butterfly curve method**, derived from voltage transfer characteristics (VTC) of cross-coupled inverters.

> 🟩 A larger SNM square indicates better stability and noise resilience.

### 🔹 SNM - 10T SRAM

![SNM Plot - 10T](sram10t_snm.jpg)

### 🔹 SNM - Optimized 10T SRAM

![SNM Plot - Optimized 10T](op_sram10t_snm_3.jpg)

### 🔹 SNM - 8T SRAM

![SNM Plot - 8T](sram8t_snm.jpg)

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

- 📧 [Your Email]
- 🌐 [Your LinkedIn or Website]

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
