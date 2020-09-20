# QOSF_Task

Task2 : Implement a circuit that returns |01> and |10> with equal probability (50% for each).
Requirements :
The circuit should consist only of CNOTs, RXs and RYs. 
Start from all parameters in parametric gates being equal to 0 or randomly chosen. 
You should find the right set of parameters using gradient descent (you can use more advanced optimization methods if you like). 
Simulations must be done with sampling (i.e. a limited number of measurements per iteration) and noise. 

Compare the results for different numbers of measurements: 1, 10, 100, 1000. 

Implemented using Pennylane and qiskit plugin.

Used RY gates and CNOT gates.
Randomly chose the parameters.

