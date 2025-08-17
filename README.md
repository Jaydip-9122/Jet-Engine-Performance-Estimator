# Jet Engine Performance Estimator 

This Jupyter Notebook provides a simple yet powerful way to estimate jet engine performance metrics such as thrust, specific fuel consumption, and efficiency parameters.  
It is intended for students, researchers, and engineers interested in propulsion system analysis.

---

## Features

- **Interactive Input**: Uses Jupyter widgets or input cells to set engine parameters.
- **Performance Metrics**:
  - Thrust
  - Thrust Specific Fuel Consumption (TSFC)
  - Thermal Efficiency
  - Propulsive Efficiency
  - Overall Efficiency
- **Visualization**: (If applicable) plots performance characteristics vs. flight conditions.

---

## Requirements

- Python 3.x  
- Jupyter Notebook / JupyterLab  
- Required Libraries:
  - `numpy`
  - `matplotlib`
  - (Optional) `ipywidgets` for interactive controls

Install dependencies:
```bash
pip install numpy matplotlib ipywidgets notebook
```

---

## How to Run

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open **Jet_Engine_Performance_Estimator.ipynb** in the Jupyter interface.

3. Run all cells:
- Click **Kernel → Restart & Run All**
- Adjust input parameters in code cells or widgets

4. View results



---

## Notebook Structure

- **Introduction & Theory**: Explains the basics of jet engine performance.
- **Input Parameters**:
  - Ambient conditions
  - Engine flow properties
  - Flight speed, mass flow rate, turbine inlet temperature
- **Calculation Cells**:
  - Thrust calculation
  - TSFC and efficiencies
- **Visualization Cells** :
  - Plots performance vs. velocity or altitude


