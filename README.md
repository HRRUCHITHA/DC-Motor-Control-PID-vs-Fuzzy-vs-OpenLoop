# DC-Motor-Control-PID-vs-Fuzzy-vs-OpenLoop
This Simulink model controls a DC motor using open-loop, PID, and fuzzy logic controllers. It compares their performance in terms of speed response and accuracy. The fuzzy controller shows better adaptability and smoother control. All outputs are visualized for analysis using scope and MUX blocks.
# DC Motor Control using Open-Loop, PID, and Fuzzy Logic Controllers

This Simulink project models the speed control of a DC motor using three different strategies:

- **Open-Loop Control** (no feedback)
- **PID Controller**
- **Fuzzy Logic Controller (FLC)**

### Description

The open-loop system drives the motor without feedback, resulting in slow and inaccurate response. The PID controller improves performance using tuned proportional, integral, and derivative gains to minimize error. The fuzzy logic controller takes error and change in error as inputs and applies rule-based control for better adaptability and smoother speed regulation.

Each control method is implemented in separate blocks, and their outputs are connected to scopes for visualization. A MUX block combines all outputs for easy side-by-side performance analysis. This simulation provides insight into the effectiveness of classical vs. intelligent control strategies for DC motor applications.

### Files Included

- `PS_DC_Motor_Controllers_PID_Fuzzy.slx` – Main Simulink model (not included here; add your file)
- `README.md` – Project overview and usage

### How to Use

1. Open the Simulink model in MATLAB.
2. Run the simulation.
3. Observe the motor speed responses under each control strategy using the Scope blocks.

### Requirements

- MATLAB with Simulink
- Fuzzy Logic Toolbox (for FLC block)

### Author

Ruchitha Ruchitha
