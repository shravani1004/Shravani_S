# EXPERIMENT - 01
DC, AC and Transient Analysis Of Common Source Amplifier Experiment
# Introduction
A basic MOSFET arrangement utilized in analog circuit design, the Common Source (CS) Amplifier offers a sizable voltage gain for amplification applications. The purpose of this experiment is to examine a CS amplifier's DC, AC, and transient response in order to comprehend how it behaves under various operating circumstances. By computing the DC voltages and currents, DC analysis establishes the operating point (Q-point), which guarantees the MOSFET operates in the intended region, usually saturation for amplification. Using small-signal equivalent models, AC analysis assesses small-signal characteristics, such as gain, input and output impedance, and frequency response. Transient analysis provides information on switching behavior, signal distortion, and reaction time by analyzing the amplifier's time-domain response to input signals, such as step or sinusoidal waveforms.

# Components in the Circuit

1. Voltage Source (V1) – 1.8V** (DC supply for the circuit)  
2. **Voltage Source (V2) – SINE(0.9 50m 1k)** (AC input signal)  
3. **Resistor (R1) – 1KΩ** (Load resistor)  
4. **NMOS Transistor (M1) – CMOSN (TSMC 180nm Technology)**  
5. **TSMC 180nm Model Library – libtsmc018.lib** (MOSFET model)  
6. **Ground (GND) Connections**  
7. **Simulation Commands:**  
   - **.dc V2 0 1.8 0.1** (DC sweep analysis)  
   - **.tran 1m** (Transient analysis for 1ms)  
   - **.ac dec 20 1k 1T** (AC analysis from 1kHz to 1THz with 20 points per decade)
  
# Circuit Diagram 
