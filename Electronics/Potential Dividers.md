**Potential Dividers**
- Resistor network that produces a variable voltage lower than supply
- Consists of two resistors in series

**Current and PD**
- Ohm's law applies to each resistor
	- R_2 example: I = V_out / R_2
	- Relates the voltage that results from the given current and interaction with R_2
- Ohm's law applies to resistors in series
	- I = V_in / (R_1 + R_2)
	- Relates the voltage that is inserted into the system, current I, and R_1 and R_2
- Combining the two equations
	- V_out / R_2 = V_in / (R_1 + R_2)
	- V_out = V_in * (R_2 / (R_1 + R_2))
	- Used to calculate V_out given V_in and the values of the two resistors
**Current Load**
- Coming calculations assume that no current flows out of the output terminal
	- Unrealistic, the calculation should allow for tolerances and risks
	- Current is drawn from the output in most practical circuits
- Example Circuit
	- Current passes through R_1
	- At the output of the divider, current I_load passes through R_2
	- R_2 and the load are resistances in parallel
	- Resistances in parallel lead to less total resistance imparted
		- Combined resistance is less than either of them separately
		- This is calculated with the resistance equations described before

Increasing the Precision
- To prevent excessive output voltage drop, increase current
	- More current results in less drop
	- Current drawn by the load has less effect
	- Rule of thumb: make the divider current 10x the current taken by the load
		- In example current, make sure to divide the current into 10 by the time it becomes I_load
		