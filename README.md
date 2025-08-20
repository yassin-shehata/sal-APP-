# sal-APP 🧪⚡

A Python application for chloride sensor calibration, measurement, and data export.  
This project is a **full Python (PySide6 + Qt)** reimplementation of a MATLAB-based chloride sensor interface.  
It replicates **all features** of the original MATLAB App Designer code, including:

- ✅ System connection to Vernier GoDirect chloride sensors (with optional FakeSensor for simulation)  
- ✅ Real-time plotting of sensor voltage and calculated chloride concentration  
- ✅ Standard solution measurements (10 ppm, 100 ppm, 1000 ppm, 5000 ppm) with stability checks  
- ✅ Calibration curve fitting with R² display  
- ✅ Sample measurements with chloride guideline criteria  
- ✅ Excel export of measurement and calibration data (using `openpyxl` and `pandas`)  
- ✅ Session recovery (restore, backup, or delete old data files)  
- ✅ Simulation mode for development/testing without hardware  

---

## 📂 Project Structure

- **assets copy/** → UI icons & images  
- **sal-app Version 1.43/** → Stable release (backend + UI working)  
  - **app/** → App package  
    - [`main.py`](https://drive.google.com/file/d/1aiCxou8RNMjWyrs9x4tE6TEJEzWMSO6F/view) → Entry point  
    - `utils.py`  
    - `ui_sal.py`  
  - `requirements.txt` → Python dependencies  
- **sal-app Version 1.44/** → Latest development version (**backend not finished, UI basically complete**)  
  - [`main.py`](https://drive.google.com/file/d/1uGehCfA-X6r2Slv1G497Mrb9k7ScZ_1L/view?usp=drive_link) → Entry point  
  - `utils.py`  
  - `ui_sal.py`  
  - `requirements.txt`  
- **README.md**  

---
