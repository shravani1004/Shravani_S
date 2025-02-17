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
Circuit - 01
![1000076651](https://github.com/user-attachments/assets/d5218f21-53d4-4196-8c7d-71a11c4b7373) 
# circuit Simulation 
DC Analysis 
![1000076654](https://github.com/user-attachments/assets/ef63cc68-45a4-4e33-8139-1f30e3292cf2)

From the simulation results:

• Current through R1 (I_R1) = 27.67 μΑ

• Voltage across R1 (V_R1) = 1.8V - 1.77233V = 0.02767V

Power Consumption:

P = 1.8V x 27.67μΑ = 49.8μW
ID = 27.67μΑ

• Assuming Vth ≈ 0.4V (for 180nm CMOS),

• VGS = V2 = 0.9V

2 × 27.67μ.Α 0.9V-0.4V = 0.11 mS 9m 55.34μ.Α 0.5V -(0.11mS × 1kΩ) = −0.11 9m A =

So, the gain is -0.11 (approximately -11 dB).

Cdb2fF (from TSMC 180nm models)

• Assuming parasitic capacitances, we estimate Cout≈ 5fF.

fc 1 2 × 12 × 5fF 
fc ≈ 31.8 MH 

FINAL RESULT :
Power Consumption : 49.8μW
Gain : -11 dB
Bandwidth : 31.8 MH
