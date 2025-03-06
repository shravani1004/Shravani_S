# Experiment - 03
Analysis of Differential Amplifier Circuit.
# Introduction to differential amplifier 

# Objective:
The aim of this experiment is to design and analyze a MOS differential amplifier based on given specifications. The experiment involves DC analysis, transient analysis, and frequency response evaluation to extract key parameters affecting amplifier performance.

# Given Specifications :
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

On calculating Q point :

VG = Vicm = 1V

VS = VP = 0.4V 

VD = Vocm = 1.1V

VGS = VG - VS = 0.6V

VGD = VG - VD = -0.1V

therefore, VGS >= Vtn

VGD <= Vtn

thus the given fet is in saturation 

Operating/ Q point (0.7V, 0.25mA) @ VGS = 0.6V

# Design Considerations :
1.The circuit consists of two MOSFETs (M1 and M2) forming a differential pair.

2.Drain resistances (RD) are set to 3.6kΩ, while the source degeneration resistor (Rss) is 800Ω.

3.Each transistor operates with a drain current (ID) of 0.25mA.


# Analysis Steps :

1. DC Analysis:
To Determine the operating points of M1 and M2 also Verifying the biasing conditions and common-mode stability.

2. Transient Analysis:
Apply time-varying inputs and observe the response.
Measure how the amplifier reacts to differential signals.

3. Frequency Response:
Analyze gain variations over different frequencies.
Identify bandwidth and key performance parameters.

# Circuit 1 :

DIAGRAM :
![ckt1_dia](https://github.com/user-attachments/assets/75013c09-ad96-4df1-9754-91a11e950119)


DC ANALYSIS :
![ckt1_dc](https://github.com/user-attachments/assets/8648a4ae-598e-45ed-9fb0-5d0ac7e88558)


AC ANALYSIS :
![ckt1_tran](https://github.com/user-attachments/assets/03e12e77-3405-46c1-84d4-1836ce7e2f98)


TRANSIENT ANALYSIS :
![ckt1_ac](https://github.com/user-attachments/assets/5a9ef40a-6742-490a-870b-d45f3029d73f)






# Circuit 2 :

DIAGRAM :
![ckt2_dia](https://github.com/user-attachments/assets/9423fb47-d3c6-4d66-9548-eeb04633119d)


DC ANALYSIS :
![ckt2_dc](https://github.com/user-attachments/assets/b4334d06-300b-48f1-b002-9c5ba3ab7600)


AC ANALYSIS :
![ckt2_tran](https://github.com/user-attachments/assets/75a3ce62-4465-4f2b-a7f7-23299bf19dff)


TRANSIENT :
![ckt2_ac](https://github.com/user-attachments/assets/25add486-3a2a-4985-8380-f6544d591b78)





# Circuit 3 :

DIAGRAM :
![ckt2_dia](https://github.com/user-attachments/assets/899a83d7-bb16-4292-988a-8fd3b17eaf2b)


DC ANALYSIS :
![ckt3_dc](https://github.com/user-attachments/assets/60ee2eb4-9446-42a7-8830-6e052b1c7e65)


AC ANALYSIS :
![ckt3_tran](https://github.com/user-attachments/assets/f164e8a1-13b5-475d-a44c-6761082ba487)


TRANSIENT :
![ckt3_ac](https://github.com/user-attachments/assets/0dad0625-9deb-4bd1-8d40-4270f3c764c1)
