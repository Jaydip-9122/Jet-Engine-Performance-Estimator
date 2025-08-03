# Jet Engine Performance Estimator (Jet_Engine_Performance_Estimator.ipynb)

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

1. Open terminal and navigate to the folder containing the notebook:
```bash
cd <your-notebook-folder>
```

2. Start Jupyter Notebook:
```bash
jupyter notebook
```

3. Open **Jet_Engine_Performance_Estimator.ipynb** in the Jupyter interface.

4. Run all cells:
- Click **Kernel → Restart & Run All**
- Adjust input parameters in code cells or widgets

5. View results:
- Thrust, TSFC, and efficiency values are printed
- Graphical plots (if implemented) are displayed inline

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

---

## Example Outputs (Text & Plots)

Example console output:
```
Thrust: 12000 N
TSFC: 0.45 kg/(N·h)
Thermal Efficiency: 0.35
Propulsive Efficiency: 0.72
Overall Efficiency: 0.25
```



---

## Notes

- The notebook uses idealized models; results may differ from actual engine performance.
- Suitable for **educational** and **conceptual design** purposes.
- Interactive widgets may require enabling extensions in Jupyter (`jupyter nbextension enable --py widgetsnbextension`).

---


