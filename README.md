# EXP-3-CHARACTERISTICS-STUDY-OF-METAL-OXIDE-SEMICONDUCTOR-FIELD-EFFECT-TRANSISTOR-MOSFET-
1. AIM
To simulate the drain and transfer characteristics of a MOSFET using LTspice software and to determine its drain resistance and transconductance.
2. APPARATUS / SOFTWARE REQUIRED
•	PC/Laptop
•	LTspice simulation software
•	MOSFET device/model
•	DC voltage sources
•	Voltage/current probes

4. CIRCUIT DIAGRAM
A. Transfer Characteristics – Connect the MOSFET circuit in LTspice. VGS is varied while maintaining a constant VDS, and the corresponding ID is observed.
<img width="1736" height="357" alt="image" src="https://github.com/user-attachments/assets/d9226655-4a7f-4687-a975-86fa34fabc58" />

B. Drain Characteristics – Connect the MOSFET circuit in LTspice. VDS is varied for different constant values of VGS, and the corresponding ID is observed.
<img width="1736" height="357" alt="image" src="https://github.com/user-attachments/assets/949f70fe-29aa-41c0-87d2-77d62a8e5f30" />


5. PROCEDURE
A. Transfer Characteristics
B.	Connect the MOSFET circuit as per the circuit diagram in LTspice.
C.	Set the required VGS and VDS values.
D.	Set the required DC sweep parameters and secondary values.
E.	Place the voltage/current probe at the required terminal of the MOSFET.
F.	Run the simulation.
G.	Observe and plot the relationship between ID and VGS.
H.	Determine the transconductance gm from the slope of the transfer characteristic.
I. Drain Characteristics
J.	Connect the MOSFET circuit as per the circuit diagram in LTspice.
K.	Set the required VGS and VDS values.
L.	Set the required DC sweep parameters and secondary sweep values.
M.	Place the voltage/current probe at the required terminal of the MOSFET.
N.	Run the simulation.
O.	Observe and plot the relationship between ID and VDS for different values of VGS.
P.	Identify the cut-off, linear and saturation regions.
Q.	Determine the drain resistance rd from the slope of the drain characteristic.

Graph: Plot ID vs. VGS for constant VDS.
B. Drain Characteristics
S. No.	VDS (V)	VGS (V)	ID (mA)
				
1			<img width="1750" height="352" alt="image" src="https://github.com/user-attachments/assets/2b1b013c-af49-441c-af5d-5f2a4d3f28bb" />

			
			
			
			
			
Repeat the observation for different constant values of VGS.
Simulation Results

9. RESULT
Thus, the drain and transfer characteristics of the MOSFET were simulated using LTspice. The values of transconductance (gm) and drain resistance (rd) were determined from the respective characteristics.
gm = __________________ S
rd = __________________ Ω
10. PRECAUTIONS
•	Check the MOSFET terminal connections before starting the simulation.
•	Use appropriate voltage sweep limits.
•	Keep VDS constant while obtaining transfer characteristics.
•	Keep VGS constant for each drain-characteristic curve.
