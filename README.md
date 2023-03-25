# ML4SCI
Task-1:
In this code, we first define a Circuit object and create 5 qubits using the GridQubit class. We then apply Hadamard gates to every qubit using a for loop and append those gates to the circuit.

Next, we add CNOT gates between adjacent qubits using another for loop and append those gates to the circuit. We then add a SWAP gate between the first and last qubits, and an X-rotation gate with angle pi/2 on the fourth qubit. Finally, we print the circuit and plot it using cirq.plot().
