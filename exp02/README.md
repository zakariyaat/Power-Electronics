## Theoretical Overviews (by Experiment)

**1. V-I Characteristics Curve of SCR**

*   **Theory:** The Silicon Controlled Rectifier (SCR) is a three-terminal semiconductor device acting as an electronic switch. It blocks current in the reverse direction and remains off in the forward direction until a gate trigger current is applied. Once triggered, it latches into conduction and remains on until the forward current falls below the holding current.
*   **Key Concepts:** Latching angle, holding current, forward voltage drop, reverse breakdown voltage, gate trigger current.
*   **Equations:**  V<sub>f</sub> = f(I<sub>f</sub>) (Forward voltage vs. current characteristic), I<sub>H</sub> (Holding Current)
*   **Lab Relevance:** Understanding the SCR's V-I characteristics is crucial for proper circuit design and protection.

**2. Single-phase Full-Wave Rectifier with R and RL Loads**

*   **Theory:** Converts AC voltage to pulsating DC voltage using two diodes.  The full-wave rectification utilizes both positive and negative half-cycles of the AC input.
*   **Key Concepts:** Peak inverse voltage (PIV), ripple factor, DC output voltage, average current.
*   **Equations:** V<sub>dc</sub> = 2V<sub>m</sub>/π, I<sub>dc</sub> = I<sub>m</sub>/π, Ripple Factor = 1.21
*   **Lab Relevance:** Demonstrates the basic principle of AC-DC conversion and the effect of load type (R vs. RL) on output voltage and current.

**3. Three-phase Bridge Rectifier with R and RL Loads**

*   **Theory:** Converts three-phase AC voltage to DC voltage using six diodes arranged in a bridge configuration. Offers lower ripple and higher efficiency compared to single-phase rectifiers.
*   **Key Concepts:** Average DC output voltage, RMS output voltage, PIV of diodes, transformer utilization factor.
*   **Equations:** V<sub>dc</sub> = 3V<sub>m</sub>/π, Ripple Factor = 0.58
*   **Lab Relevance:** Illustrates the advantages of three-phase rectification for higher power applications.

**4. Single-phase Half-Wave Controlled Rectifier with R and RL Loads**

*   **Theory:** Uses an SCR to control the conduction of only one half-cycle of the AC input. The firing angle (α) determines the output voltage.
*   **Key Concepts:** Firing angle, average DC output voltage, RMS output voltage, form factor.
*   **Equations:** V<sub>dc</sub> = V<sub>m</sub>/π * cos(α), RMS Voltage = V<sub>m</sub>/2
*   **Lab Relevance:** Introduces the concept of phase control for DC voltage regulation.

**5. Single-phase Full-Converter with R and RL Loads**

*   **Theory:** Uses two SCRs to control the entire AC input waveform.  Allows for full control of the DC output voltage.
*   **Key Concepts:** Firing angle, average DC output voltage, RMS output voltage, commutation.
*   **Equations:** V<sub>dc</sub> = V<sub>m</sub>/π * cos(α)
*   **Lab Relevance:** Demonstrates full control of DC output voltage using SCRs.

**6. Three-phase Half-Wave Converter with R and RL Loads**

*   **Theory:** Uses three SCRs to control the conduction of three half-cycles of the three-phase AC input.
*   **Key Concepts:** Firing angle, average DC output voltage, commutation.
*   **Equations:** V<sub>dc</sub> = (3V<sub>m</sub>/π) * cos(α)
*   **Lab Relevance:** Introduces controlled rectification in a three-phase system.

**7. Three-phase Full-Converter with R and RL Loads**

*   **Theory:** Uses six SCRs to fully control the three-phase AC input waveform.
*   **Key Concepts:** Firing angle, average DC output voltage, commutation, harmonic distortion.
*   **Equations:** V<sub>dc</sub> = (3V<sub>m</sub>/π) * cos(α)
*   **Lab Relevance:** Demonstrates full control of DC output voltage in a three-phase system, highlighting the benefits of three-phase converters.

**8. Single-phase AC Voltage Controller with R Load**

*   **Theory:** Uses two SCRs in anti-parallel to control the RMS voltage applied to a resistive load. The firing angle controls the output voltage.
*   **Key Concepts:** Firing angle, RMS output voltage, power control.
*   **Equations:** V<sub>rms</sub> = V<sub>m</sub> * sqrt((π - α + sin(2α))/2π)
*   **Lab Relevance:** Illustrates AC voltage control for applications like lamp dimming and heater control.

**9. Three-phase Full-Wave AC Voltage Controller**

*   **Theory:** Uses six SCRs to control the RMS voltage applied to a three-phase load.
*   **Key Concepts:** Firing angle, RMS output voltage, power control, balanced/unbalanced loads.
*   **Equations:** V<sub>rms</sub> = V<sub>m</sub> * sqrt((π - α + sin(2α))/2π)
*   **Lab Relevance:** Demonstrates AC voltage control in a three-phase system.

**10. Single-phase Cycloconverter**

*   **Theory:** Converts AC power at one frequency to AC power at a lower frequency using SCRs.
*   **Key Concepts:** Circulation current, commutation, output waveform distortion.
*   **Equations:** (Complex, involving SCR firing sequences and harmonic analysis)
*   **Lab Relevance:** Introduces a method for variable-frequency AC power control.

**11. Three-phase Cycloconverter**

*   **Theory:** Converts three-phase AC power at one frequency to three-phase AC power at a lower frequency.
*   **Key Concepts:** Circulation current, commutation, harmonic distortion, group control.
*   **Equations:** (Complex, involving SCR firing sequences and harmonic analysis)
*   **Lab Relevance:** Demonstrates three-phase variable-frequency AC power control.

**12. AC Voltage Controller with PWM Control**

*   **Theory:** Uses PWM techniques to control the AC output voltage, offering improved harmonic performance compared to phase control.
*   **Key Concepts:** PWM duty cycle, carrier frequency, modulation index, harmonic reduction.
*   **Equations:** V<sub>rms</sub> = V<sub>m</sub> * D (where D is the duty cycle)
*   **Lab Relevance:** Introduces PWM as a method for improved AC voltage control.

**13. Design of a Buck Regulator**

*   **Theory:** A DC-DC converter that steps down the input voltage to a lower output voltage.
*   **Key Concepts:** Duty cycle, switching frequency, inductor ripple current, output voltage ripple.
*   **Equations:** V<sub>o</sub> = D * V<sub>i</sub>,  ΔI<sub>L</sub> = (V<sub>i</sub> - V<sub>o</sub>) * D / (L * f<sub>s</sub>)
*   **Lab Relevance:** Demonstrates the principles of DC-DC conversion and voltage regulation.

**14. Design of a Boost Regulator**

*   **Theory:** A DC-DC converter that steps up the input voltage to a higher output voltage.
*   **Key Concepts:** Duty cycle, switching frequency, inductor ripple current, output voltage ripple.
*   **Equations:** V<sub>o</sub> = V<sub>i</sub> / (1 - D), ΔI<sub>L</sub> = V<sub>i</sub> * D / (L * f<sub>s</sub>)
*   **Lab Relevance:** Demonstrates step-up DC-DC conversion.

**15. Design of a Buck-Boost Regulator**

*   **Theory:** A DC-DC converter that can either step up or step down the input voltage, depending on the duty cycle.
*   **Key Concepts:** Duty cycle, switching frequency, inductor ripple current, output voltage ripple.
*   **Equations:** V<sub>o</sub> = -V<sub>i</sub> * D / (1 - D)
*   **Lab Relevance:** Demonstrates a versatile DC-DC converter topology.

**16. Single-phase Full-Bridge Inverter**

*   **Theory:** Converts DC voltage to AC voltage using four switches (typically MOSFETs or IGBTs).
*   **Key Concepts:** Switching frequency, output waveform (square wave), harmonic content.
*   **Equations:** V<sub>o</sub> = V<sub>dc</sub> (for square wave output)
*   **Lab Relevance:** Introduces the basic principle of DC-AC conversion.

**17. Single-phase Full-Bridge Inverter with PWM Control**

*   **Theory:** Uses PWM techniques to control the output voltage and reduce harmonic distortion.
*   **Key Concepts:** PWM duty cycle, carrier frequency, modulation index, harmonic reduction.
*   **Equations:** (Complex, involving PWM waveform synthesis)
*   **Lab Relevance:** Demonstrates improved DC-AC conversion with PWM.

**18. Three-phase Bridge Inverter**

*   **Theory:** Converts DC voltage to three-phase AC voltage using six switches.
*   **Key Concepts:** Switching frequency, output waveform, harmonic content, space vector modulation (SVM).
*   **Equations:** (Complex, involving phase angles and harmonic analysis)
*   **Lab Relevance:** Demonstrates three-phase DC-AC conversion, essential for motor drives and power systems.



---

This is a comprehensive overview.  Remember to tailor the level of detail to your specific lab curriculum and student audience.  Good luck! Let me know if you'd like any of these sections expanded or modified.
