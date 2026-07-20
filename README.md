# Project: Designing a Very Wide Band Amplifier

Authors: Kyle G. Gayliyev, Peter Gail <br>
Date: 8 - Oct, 2023 <br>
Course: ECE 6720 - Fundamentals of Analog Integrated Circuit Design, ECE Department, The University of Utah<br>
GitHub IDs: ggayliye <br>
Repo: https://github.com/ggayliye/ECE6720_F_AnalogCircDes <br>
Date: By 15-Dec-2023, 11:59pm (Time of when submission is due/will be ready to be evaluated)<br>
Copyright: ECE 6720, Kyle G. Gayliyev  - This work may not be copied for use in Academic Coursework.

# Overview of the Project
* Guidence provided by the instructor: Project Description, Sample Circuit, Sample Simulation Setup, Resource References. 
* The goal of the project is to design a very wide-band amplifier, which is widely used in wireless/RF systems.
* At the heart of this design, there is a differential-input differential-output amplifier, loaded with 50 fF parasitic capacitance.
* To extend the bandwidth of the amplifier, a passive inductive peaking mechanism is utilized.
* A voltage regulator is utilized in order to minimize the effect of supply noise on performance of this amplifier.
* The voltage regulator will have a wide-bandwidth and high DC gain in order to suppress the supply noise.
* A current distribution network is applied for producing the necessary bias currents for the regulator circuit and the amplifier.

# The Wide Band Amplifier Circuit Consists of The Following Component Designs: 
- An amplifier
- A regulator
- Current mirror

# Specifications: 
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/1.Specifications.jpg)

# RF Amplifier Specifications: 
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/2.RF_Specifications.jpg)

# Regulator Specifications: 
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/3.Regulator_Specifications.jpg)


# Current Mirror Specifications: 
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/4.Curr_Mirr_Specifications.jpg)

# Finished Design Screenshots From Cadence Virtuoso: 
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/5.Cadence1.jpg)

![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/6.Cadence2.jpg)

![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/7.Cadence3.jpg)


# Final Report:
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/8.Rep1.jpg)
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/9.Rep2.jpg)
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/10.Rep3.jpg)
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/11.Rep4.jpg)
![alt text](https://github.com/ggayliye/ECE6720_F_AnalogCircDes/blob/main/.mat/12.Rep5.jpg)


# References:
1. P. R. Gray, P. J. Hurst, S. H. Lewis, R. G. Meyer, Analysis and Design of Analog Integrated Circuits, 5th Edition, Wiley <br>
2. B. Razavi, Design of Analog CMOS Integrated Circuits, Mc-Graw Hill. <br>
3. A. Aghighi, J. Atkinson, N. Bybee, S. Anderson, A. Bailey, R. Morell, M. Hassanin, A. Tajalli, “CMOS amplifier design based on extended gm/ID methodology”, IEEE NEWCAS, 2019.<br>
4. Widlar R. J., ‘Some circuit design techniques for linear integrated circuits’, IEEE Trans. Circuit Theory, CT-12 (1965), 586–590. <br>






