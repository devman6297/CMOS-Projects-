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

- Desing and Analysis of 8T and 10T SRAM Cell.
- Perform Static-noise margin analysis of the same refer to this ["Static-noise margin analysis of MOS SRAM cells"](https://ieeexplore.ieee.org/document/1052809) and [Link](https://engineering.purdue.edu/~vlsi/ECE559_Fall09/HW/HW6_Solution.pdf)

Schematic Diagram :
- Transient Analysis of 8T SRAM Cell </br>
<img src = "lab4/sram_8t/sram_8t.jpg" width="50%" height="50%"> </br>
- Static-noise margin analysis of 6T SRAM Cell </br>
<img src = "lab4/sram_8t/sram8t_snm.jpg" width="50%" height="50%"> </br>

- Transient Analysis of 10T SRAM Cell </br>
<img src = "lab4/sram_10t/sram_10t.jpg" width="50%" height="50%"> </br>
- Static-noise margin analysis of 10T SRAM Cell </br>
<img src = "lab4/sram_10t/sram10t_snm.jpg" width="50%" height="50%"> </br>

Resultant Waveform :
- Transient Analysis of 8T SRAM Cell </br>
<img src = "lab4/sram_8t/op_sram8t.jpg" width="70%" height="70%"> </br>
- Static-noise margin analysis of 8T SRAM Cell </br>
<img src = "lab4/sram_8t/op_sram8t_snm.jpg" width="70%" height="70%"> </br>
<img src = "lab4/sram_8t/op_sram8t_snm_1.jpg" width="70%" height="70%"> </br>
<img src = "lab4/sram_8t/op_sram8t_snm_2.jpg" width="70%" height="70%"> </br>

- Transient Analysis of 10T SRAM Cell </br>
<img src = "lab4/sram_10t/op_sram10t.jpg" width="70%" height="70%"> </br>
- Static-noise margin analysis of 10T SRAM Cell </br>
<img src = "lab4/sram_10t/op_sram10t_snm_1_1.jpg" width="70%" height="70%"> </br>
<img src = "lab4/sram_10t/op_sram_10t_snm_2_1.jpg" width="70%" height="70%"> </br>
<img src = "lab4/sram_10t/op_sram10t_snm_3.jpg" width="70%" height="70%"> </br>


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
