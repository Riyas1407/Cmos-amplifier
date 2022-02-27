# Implementation Of Two Stage CMOS Operational Amplifier On 28nm Technology Node

Abstract 
Amplification of the signal is very important aspect of any analog designs. For any weak signal which cannot drive any output we need amplification of the signal .Here in this work ,a two stage CMOS operational amplifier is designed considering 1.8V operating voltage ,having load capacitance of 1pF and phase margin greater than 60^°.This two stage Op-amp is designed on 28nm tech node.
Keywords : CMOS , Op-amp, Phase margin, Technology node
Introduction   
In certain cases the gain of single stage amplifier is not enough as it depends only on input transconductance and output load impedance[1].Op-amps are most important element of analog design and mostly its performance relies on data transmission and DC gain [2].To mitigate this two stage amplification is required. In two stage amplification,first stage provides high gain and second stage provides high swings[1]. Op-amp uses negative feedback for amplification. It helps op-amp to understand how much to amplify [3].The symbolic representation of two stage Op-amp is shown in figure 1 .


![image](https://user-images.githubusercontent.com/100511145/155875580-cfd1f181-14ea-4f49-aa8c-5c85e67d2e49.png)
Designing Of Two Stage CMOS Op-Amp
The proposed circuit for two stage amplifier is as shown in figure 2. Here, Transistor M1, M2, M3 and M4 form the differential stage of the op-amp and two nmos transistors  which are M1 and M2 are for differential inputs of the amplifier. Here the load capacitance is of 1pF and coupling capacitor is of 2pF.It phase margin is of 60^°.It’s DC gain is of 60db.Its operating voltage is 1.8V and VSS is 0V.Its channel length is 28nm.


![Screenshot 2022-02-23 121805](https://user-images.githubusercontent.com/100511145/155875594-393870fa-9b2e-4bd4-8cbc-b5978c3bde52.png)


Its symbol is as shown in figure 3 below:
![Screenshot 2022-02-23 121405](https://user-images.githubusercontent.com/100511145/155875622-d3a678f0-294a-4252-af1d-b7238102c508.png)

Waveform And Area Calculation
As 28nm PDK is going to be used, It will have height and width of every physical cells used in a design  given in its physical library. As we have eight MOSFETS in the design ,so eight times the dimensions given into library and additional 20% area is taken for routing.The transistors width is as shown in the table :


![image](https://user-images.githubusercontent.com/100511145/155875674-d3b91029-22f9-4ead-a472-8d5f99e4fb0d.png)

The area of the circuit is around 6.5𝜇𝑚^2 . Considering 105 overhead for routinhg.Hence area is around 7.1𝜇𝑚^2 .Transient waveform for the above proposed design is as shown in figure 4.

![image](https://user-images.githubusercontent.com/100511145/155875739-dd5ee53f-62eb-4591-9c6b-77f7cbccbd82.png)


References 

[1] Behzad Razavi .“Design for Analog CMOS Integrated Circuits”

[2] Shruti Suman. “Two Stage CMOS Operational Amplifier: Analysis and Design”

[3] Tong Yuan, Qingyuan Fan. “Design Of Two Stage CMOS Operational Amplifier in 180nm Technology”

[4] K.T.Tan , N. Ahmad , M. Mohamad Isa, F.A.S. Musa. “Design and Analysis of Two Stage CMOS Operational Amplifier using 0.13 µm Technology”



