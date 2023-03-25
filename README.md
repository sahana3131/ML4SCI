## ML4SCI
# Task I: Quantum Computing Part 
- 1) implement a simple quantum operation with Cirq or Pennylane
- a) With 5 qubits 
- b) Apply Hadamard operation on every qubit 
- c) Apply CNOT operation on (0, 1), (1,2), (2,3), (3,4) 
- d) SWAP (0, 4) 
- e) Rotate X with pi/2 on any qubit 
- f) Plot the circuit 


2) Implement a second circuit with a framework of your choice:
- a.	Apply a Hadmard gate to the first qubit
- b.	rotate the second qubit by pi/3 around X
- c.	Apply Hadamard gate to the third and fourth qubit
- d.	Perform a swap test between the states of the first and second qubit |q1 q2> and the third and fourth qubit |q3 q4>
Finally,the code also measures all qubits and plots the histogram of the measurement outcomes.
Note that the swap test is a probabilistic algorithm and may produce different results each time it is run. Therefore, the histogram may not always show the exact same outcomes.
