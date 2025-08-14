# full-adder-vlsi

**Top-down VLSI design flow for a full adder using open-source tools** — RTL to layout implementation with Verilog, C-model verification, synthesis (Yosys), PnR (OpenROAD/Qflow), and DRC/LVS checks.

---

## 📌 Features
- **RTL Design:** Full adder implementation in Verilog.
- **Functional Verification:** Testbench simulation & C-model comparison.
- **Synthesis:** Using [Yosys](https://yosyshq.net/yosys/) for RTL-to-gate-level netlist.
- **Place and Route (PnR):** Implemented using [OpenROAD](https://theopenroadproject.org/) / Qflow.
- **Physical Verification:** DRC & LVS checks using open-source tools.

---

## 🛠 Tools Used
- **Verilog** – RTL design
- **GTKWave** – Waveform viewer
- **Yosys** – Synthesis tool
- **Qflow / OpenROAD** – Place & Route
- **Magic VLSI** – Layout editing & DRC/LVS checks
- **C** – Functional model for reference verification

---

## 📂 Workflow
1. **RTL Coding** → Write Verilog code for the full adder.
2. **Simulation** → Run functional verification using testbenches & compare with C-model outputs.
3. **Synthesis** → Convert RTL to gate-level netlist using Yosys.
4. **PnR** → Generate physical layout using OpenROAD/Qflow.
5. **DRC/LVS** → Verify layout correctness with Magic VLSI.
6. **GDSII Export** → Final layout for fabrication.

---

## 📜 Repository Structure
full-adder-vlsi/
│
├── src/ # Verilog source files
├── sim/ # Testbenches and simulation scripts
├── synthesis/ # Yosys synthesis scripts and netlists
├── layout/ # GDSII and layout files
├── docs/ # Documentation and reports
└── full_adder.ipynb # Colab notebook (uploaded from Colab)

---

## 🚀 Getting Started
To clone this repository:
```bash
git clone https://github.com/<your-username>/full-adder-vlsi.git

## 📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

## 🙌 Acknowledgements
- [Yosys](https://yosyshq.net/yosys/)
- [OpenROAD](https://theopenroadproject.org/)
- [Qflow](http://opencircuitdesign.com/qflow/)
- Magic VLSI for layout and verification
