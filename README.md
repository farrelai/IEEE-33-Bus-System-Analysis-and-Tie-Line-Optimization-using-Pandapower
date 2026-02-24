# IEEE-33-Bus-System-Analysis-and-Tie-Line-Optimization-using-Pandapower

IEEE 33-bus analysis using pandapower. Strategic tie-line integration transformed the radial network into a resilient weakly meshed configuration. Result: significant voltage profile improvement (RMSE 0.052). Demonstrates expertise in power system modeling, computational analysis, and grid reconfiguration to minimize network losses.

## Overview
This project focuses on the simulation and optimization of the IEEE 33-bus distribution system. The primary goal is to evaluate how the addition of tie-lines affects the voltage stability and overall efficiency of the power grid.

## Key Features
- Power Flow Analysis: Executed using the Newton-Raphson method via pandapower.
- Grid Reconfiguration: Implementation of tie-lines to transition from a radial to a weakly meshed topology.
- Performance Metrics: Quantitative evaluation using Root Mean Square Error (RMSE) against a 1.02 pu voltage reference.
- Visualization: Comparison of voltage profiles before and after optimization.

## Tech Stack
- Language: Python 3.x
- Core Library: Pandapower
- Data Analysis: Pandas, NumPy
- Visualization: Matplotlib

## Results
The integration of strategic tie-lines successfully stabilized the network's voltage.
- Target Voltage: 1.02 pu
- Final RMSE: 0.052
The analysis proves that reconfiguring the network topology significantly reduces voltage drops in end-bus sections.

## Usage
1. Clone the repository:
   git clone https://github.com/your-username/IEEE-33-Bus-Optimization.git

2. Install dependencies:
   pip install pandapower matplotlib

3. Run the Jupyter Notebook:
   jupyter notebook Power_System_Analysis.ipynb

## References
- IEEE 33-Bus Radial Distribution System Standard Data.
- Pandapower Documentation: https://pandapower.readthedocs.io/
