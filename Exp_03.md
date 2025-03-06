# Experiment - 03
Analysis of Differential Amplifier Circuit.
# Introduction to differential amplifier 

# Objective
The aim of this experiment is to design and analyze a MOS differential amplifier based on given specifications. The experiment involves DC analysis, transient analysis, and frequency response evaluation to extract key parameters affecting amplifier performance.

# Given Specifications

Power Supply (VDD): 2V

Power Dissipation (P): ≤ 1mW

Common-Mode Input Voltage (Vicm): 1V

Common-Mode Output Voltage (Vocm): 1.1V

Differential Input Voltage (Vp): 0.4V

# By analysis :
the given circuit specifications we get,

Iss= P/VDD

Iss = 0.5mA

Id1 = Id2 = Iss/2 = 0.25mA

Rd = Vdd-Vocm/Id1

Rd = 3.6k ohm

Rss = Vp/Iss 

Rss = 800 ohm 

VG = Vicm = 1V

VS = VP = 0.4V 

VD = Vocm = 1.1V

VGS = VG - VS = 0.6V

VGD = VG - VD = -0.1V

therefore, VGS >= Vtn
VGD <= Vtn

thus the given fet is in saturation 


Operating/ Q point

# Design Considerations

1.The circuit consists of two MOSFETs (M1 and M2) forming a differential pair.

2.Drain resistances (RD) are set to 3.6kΩ, while the source degeneration resistor (Rss) is 800Ω.

3.Each transistor operates with a drain current (ID) of 0.25mA.


# Analysis Steps

1. DC Analysis:
To Determine the operating points of M1 and M2 also Verifying the biasing conditions and common-mode stability.


2. Transient Analysis:
Apply time-varying inputs and observe the response.
Measure how the amplifier reacts to differential signals.


3. Frequency Response:
Analyze gain variations over different frequencies.
Identify bandwidth and key performance parameters.

Operating/ Q point 

Expected Outcome :

This experiment will help understand the behavior of a MOS differential amplifier, including gain characteristics, input-output relationships, and frequency response, which are crucial for analog circuit design.

