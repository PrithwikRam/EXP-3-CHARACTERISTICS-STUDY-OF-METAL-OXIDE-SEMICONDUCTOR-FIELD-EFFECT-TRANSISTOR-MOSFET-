# EXP-3-CHARACTERISTICS-STUDY-OF-METAL-OXIDE-SEMICONDUCTOR-FIELD-EFFECT-TRANSISTOR-MOSFET-
1. AIM
To simulate the drain and transfer characteristics of a MOSFET using LTspice software and to determine its drain resistance and transconductance.
2. APPARATUS / SOFTWARE REQUIRED
•	PC/Laptop
•	LTspice simulation software
•	MOSFET device/model
•	DC voltage sources
•	Voltage/current probes

3. CIRCUIT DIAGRAM
A. Transfer Characteristics – Connect the MOSFET circuit in LTspice. VGS is varied while maintaining a constant VDS, and the corresponding ID is observed.
   <img width="1190" height="287" alt="image" src="https://github.com/user-attachments/assets/4840759f-a7e6-4c22-af81-267576ba13f3" />

B. Drain Characteristics – Connect the MOSFET circuit in LTspice. VDS is varied for different constant values of VGS, and the corresponding ID is observed.
<img width="1190" height="287" alt="image" src="https://github.com/user-attachments/assets/e27ca7f5-9548-4f5b-8c2f-6997f58520cc" />

5. PROCEDURE
I. Transfer Characteristics
A.	Connect the MOSFET circuit as per the circuit diagram in LTspice.
B.	Set the required VGS and VDS values.
C.	Set the required DC sweep parameters and secondary values.
D.	Place the voltage/current probe at the required terminal of the MOSFET.
E.	Run the simulation.
F.	Observe and plot the relationship between ID and VGS.
G.	Determine the transconductance gm from the slope of the transfer characteristic.

II. Drain Characteristics
11.	Connect the MOSFET circuit as per the circuit diagram in LTspice.
12.	Set the required VGS and VDS values.
13.	Set the required DC sweep parameters and secondary sweep values.
14.	Place the voltage/current probe at the required terminal of the MOSFET.
15.	Run the simulation.
16.	Observe and plot the relationship between ID and VDS for different values of VGS.
17.	Identify the cut-off, linear and saturation regions.
18.	Determine the drain resistance rd from the slope of the drain characteristic.
  
6.Graph: Plot ID vs. VGS for constant VDS.
 Drain Characteristics
S. No.	VDS (V)	VGS (V)	ID (mA)
		
1		<img width="1202" height="266" alt="image" src="https://github.com/user-attachments/assets/91ad95de-3dd1-4172-bc53-26b4ab9e4073" />

			
Repeat the observation for different constant values of VGS.
Simulation Results

 ID vs. VDS for different values of VGS.




7. RESULT
Thus, the drain and transfer characteristics of the MOSFET were simulated using LTspice. The values of transconductance (gm) and drain resistance (rd) were determined from the respective characteristics.
gm = __________________ S
rd = __________________ Ω
8. PRECAUTIONS
•	Check the MOSFET terminal connections before starting the simulation.
•	Use appropriate voltage sweep limits.
•	Keep VDS constant while obtaining transfer characteristics.
•	Keep VGS constant for each drain-characteristic curve.
