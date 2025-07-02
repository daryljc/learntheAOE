Ohms law:
- V = IR
- V is the analog of water pressure ('head' of water), impelling force
	- *Voltage* is work to raise a unit charge from one level to a higher level (or potential)
	- Voltage difference between points on hillside can be described as the electric potential difference
	- The electric field tends to push the charge back down, like gravity
	- One volt is the work done as one adds one joule of potential energy to one coulomb of charge
![[Pasted image 20250701105619.png]]
- R describes the restriction of water flow, cutting off electron flow
	- 
- I is the rate of flow (volume/unit time), amount of electricity passing by
![[Pasted image 20250701104625.png]]

"Ground"
- Absolute reference for voltage
- Practically, potential at the place where a copper spike has been driven into the ground
- In hydraulic analogy, zero-reference can be seal-level
- We are interested in relative voltages

Ohms law
- Restriction of current is "resistance"
- Occurs because charge-carrying electrons, accelerated by an electric field, bump into obstacles and must re-accelerate in field direction
- Conductivity of a material depends on the density of charge carrier population
- Field strength corresponds with voltage difference between two points on a conductor
- Resistors are called "insulators"
- Diodes defy Ohm's law, seen in Lab 1L
	- Dynamic resistance can be applied, will be seen later
	- Idea is to define a local resistance--tangent to the slope of the device's V-I curve
	- Allows discussion on effective resistance of diodes, transistors, or current sources (circuit that holds current constant)
![[Pasted image 20250701110829.png]]

Non-ohmic dynamic resistance
![[Pasted image 20250701111143.png]]

Power in a resistor
- Power is the rate of doing work
- Comes up in electronics when specifying components that.can handle the power that it is likely to have to dissipate
	- High power calls for components that can unload or dissipate the resulting heat
	- P = I * V
	- P = I ^ 2 * R ( since I = V / R)
	- P = V ^ 2 / R
	- This equation holds for any electronic component
	- Current measures charge / time
	- Voltage measures work / charge
	- P = I * V = work / charge * charge / time
		- = work / time = definition of power
	- Worry about power when using large voltage swings or when providing unusually large currents

Kirchhoff's Laws: V, I
- Sums of voltages about the loop (or circuit) is zero, where the loop is visualizes before
	- Sum of voltage drops
- Sum of currents in and out of a node is zero (algebraic sum)
![[Pasted image 20250701112117.png]]

Kirchhoff in Series and Parallel Circiuts
- Series: I_total = I_1 = I_2
- Parallel: I_total = I_1 + I_2
- Series: V_total = V_1 + V_2
- Parallel: V_total = V_1 = V_2
![[Pasted image 20250701112342.png]]

![[Pasted image 20250701112910.png]]
Electrically-equivalent circuits

Parallel Resistances: Calculating Equivalent R
- Conductances add:
	- C_total = C_1 + C_2
		- = 1 / R_1 + 1 / R_2
- Another representation:
	- R_tot = (R_1 * R_2) / (R_1 + R_2)

Rule of Thumb
- In parallel circuits, smaller resistors dominate
	- R_total will tend to the smaller resistance
- In series circuits, larger resistors dominate
	- R_total will tend to the larger resistance

First Application: Voltage Divider
- Deliver several voltages with one source
- A potentiometer is an adjustable voltage divider
	- Can be used 