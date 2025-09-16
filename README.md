# Power Electronics Laboratory Experiments Repository


## 📋 Project Overview
Power electronics focuses on converting, controlling, and conditioning electrical power (AC ↔ DC, voltage/current regulation) using semiconductor devices (thyristors, MOSFETs, IGBTs). 

This repository accompanies a standard power electronics lab curriculum, covering core topologies like:
- Rectifiers (uncontrolled/controlled AC → DC)
- AC Voltage Controllers
- Cycloconverters (AC → lower-frequency AC)
- DC-DC Converters (Buck/Boost/Buck-Boost)
- Inverters (DC → AC, with/without PWM)



## 🧪 Experiment List (Lab Curriculum)
The experiments are organized by topology type, with clear learning outcomes for each category. Key terms (e.g., *SCR*, *PWM*, *RL Load*) are explained for new learners.


### Core Experiment Categories
| Category                  | Experiments (S/N) | Key Focus                                                                 |
|---------------------------|-------------------|---------------------------------------------------------------------------|
| **Thyristor Characteristics** | 1                 | Characterize a **Silicon Controlled Rectifier (SCR)** (a power thyristor) via its Voltage-Current (V-I) curve. |
| **Rectifiers (AC → DC)**  | 2–7               | Test uncontrolled/controlled rectifiers (single/three-phase) with **resistive (R)** and **inductive-resistive (RL)** loads (e.g., motor windings). |
| **AC Voltage Controllers** | 8–9, 12           | Control AC voltage using phase control and **Pulse-Width Modulation (PWM)** (a method to adjust voltage via pulse width variation). |
| **Cycloconverters (AC → AC)** | 10–11             | Convert AC power to lower-frequency AC (used for slow-speed AC motors).  |
| **DC-DC Converters**      | 13–15             | Design and test step-down (Buck), step-up (Boost), and bidirectional (Buck-Boost) DC voltage regulators. |
| **Inverters (DC → AC)**   | 16–18             | Convert DC to AC (single/three-phase) with/without PWM for precise voltage control. |

List of Experiments
The following is a curated list of 18 experiments, each with a brief description. Detailed reports, code, and simulations (if applicable) are available in the respective folders (e.g., exp1/, exp2/, etc.).

1. V-I Characteristics Curve of SCR
Study the voltage-current characteristics of a Silicon-Controlled Rectifier (SCR), including forward and reverse blocking modes, holding current, and latching current.

2. Single-phase Half-Wave Rectifier with R and RL Loads
Analyze a half-wave rectifier circuit using a diode, observing output waveforms, average voltage, and ripple for resistive (R) and inductive (RL) loads.

3. Three-phase Bridge Rectifier with R and RL Loads
Implement a three-phase full-wave bridge rectifier and evaluate its performance with resistive and inductive loads, focusing on DC output and harmonic content.

4. Single-phase Half-Wave Controlled Rectifier with R and RL Loads
Use an SCR for controlled rectification, varying firing angles to control output voltage and study effects on R and RL loads.

5. Single-phase Full-Converter with R and RL Loads
Design a full-wave controlled rectifier (bridge configuration) and analyze power factor, efficiency, and output regulation.

6. Three-phase Half-Wave Converter with R and RL Loads
Simulate a three-phase half-wave converter, measuring phase control and load response for resistive and inductive loads.

7. Three-phase Full-Converter with R and RL Loads
Explore a three-phase full-wave converter, including firing sequence and output smoothing for various loads.

8. Single-phase AC Voltage Controller
Implement an AC voltage regulator using back-to-back SCRs or triacs, controlling RMS output voltage for lighting or heating applications.

9. Three-phase Full-Wave AC Voltage Controller
Extend the single-phase controller to three phases, analyzing phase control and power delivery to balanced loads.

10. Single-phase Cycloconverter
Convert AC input frequency to a lower output frequency using SCRs, suitable for variable-speed drives.

11. Three-phase Cycloconverter
Design a three-phase version for higher power applications, focusing on waveform synthesis and frequency control.

12. AC Voltage Controller with PWM Control
Use Pulse Width Modulation to enhance control precision in AC voltage regulation, reducing harmonics.

13. Design of a Buck Regulator
Build and simulate a step-down DC-DC converter (buck topology) for voltage regulation, including duty cycle calculations.

14. Design of a Boost Regulator
Implement a step-up DC-DC converter (boost topology), analyzing energy storage in inductors and output stability.

15. Single-phase Full-Bridge Inverter
Convert DC to AC using a full-bridge inverter, generating square or sinusoidal waveforms for UPS or motor drive applications.

16. Single-phase Full-Bridge Inverter with PWM Control
Enhance the inverter with PWM for better harmonic reduction and variable frequency output.

17. Three-phase Inverter
Design a three-phase inverter for AC motor control, including space vector modulation techniques.


## 📂 What’s Included in the Repo?
Each experiment has its own folder (e.g., exp01_scr_vi_characteristics) with:
1. **Simulation Files**:
   - MATLAB/Simulink models (`.slx`)
   - LTspice schematics (`.asc` — free, open-source alternative: [ltspice.com](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html))
2. **Circuit Diagrams**: High-res PNG/SVG files for physical lab setup
3. **Theory Briefs**: 1-page summaries of key concepts (e.g., SCR operation, PWM)
4. **Sample Data**: Example measured waveforms/values for simulation vs. lab comparison


## 🛠️ Prerequisites
### Software
- **Simulation**: MATLAB/Simulink (R2024a+) or LTspice (free)
- **Reports**: LaTeX (Overleaf) or Markdown editor (VS Code + Markdown All in One)

### Prerequisite Knowledge
- Basic circuit theory (Ohm’s law, AC/DC circuits)
- Introductory power electronics (optional — theory briefs are included for reference)


## 🚀 How to Use
1. **Clone the Repo**:
   ```bash
   git clone https://github.com/zakariyaat/Power-Electronics
   ```
2. **Navigate to an Experiment Folder**: e.g., `cd exp_01_scr_vi_characteristics`
3. **Simulate First**: Run the Simulink/LTspice model to predict circuit behavior
4. **Perform the Lab**: Use the circuit diagram and procedure to set up hardware
5. **Document Results**: Fill the report template, compare simulation vs. measured data


## 🤝 Contributing
This repo is open for improvements (e.g., better simulation models, updated templates):
1. Fork the repo
2. Make changes in a new branch
3. Submit a pull request with a clear description of updates


## 🙏 Acknowledgments
- Md. Safiqul Islam sir Assistant Professor, Hajee Mohammad Danesh Science and technology University, Dinajpur
- Reference Text: Power Electronics Devices, Circuits, and Applications by Muhammad H.Rashid
