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
| `sram_8t.jpg` *(optional)*| Schematic of the standard 8T SRAM cell for comparison. *(To be added)* |
| `sram8t_snm.jpg` *(optional)* | SNM butterfly plot for the 8T SRAM cell. *(To be added)* |

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

## 📈 SNM Analysis

Static Noise Margin (SNM) is the key indicator of memory stability. It is determined using the **butterfly curve method**, derived from voltage transfer characteristics (VTC) of cross-coupled inverters.

> 🟩 A larger SNM square indicates better stability and noise resilience.

### 🧪 Summary Table

| SRAM Type | SNM (Read) | SNM (Write) | Notes |
|-----------|------------|-------------|-------|
| **10T Base** | Moderate | Tight | Decoupled read improves stability |
| **10T Optimized** | Improved | Improved | Additional transistors enhance SNM |
| **8T** | TBD | TBD | To be added in future analysis |

---

## ➕ Future Work

- [ ] Add 8T SRAM schematic and SNM plots
- [ ] Include 6T SRAM baseline for complete comparison
- [ ] Power and delay analysis
- [ ] Monte Carlo simulations for process variation tolerance

---

## 📬 Contact

For queries, collaboration, or discussions:

- 📧 [Your Email]
- 🌐 [LinkedIn/Personal Website]

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).


