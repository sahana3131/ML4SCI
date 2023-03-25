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

# Task II: Classical Graph Neural Network (GNN) 
- For Task II, you will use ParticleNet’s data for Quark/Gluon jet classification available here with its corresponding description. 
- ● Choose 2 Graph-based architectures of your choice to classify jets as being quarks or gluons. Provide a description on what considerations you have taken to project this point-cloud dataset to a set of interconnected nodes and edges. 
- ● Discuss the resulting performance of the 2 chosen architectures. 

# Task III: Open Task 
- Please comment on quantum computing or quantum machine learning. You can also comment on one quantum algorithm or one quantum software you are familiar with. You can also suggest methods you think are good and you would like to work on. Please use your own understanding. Comments copied from the internet will not be considered.

# Task VI: Quantum representation learning

- In this task you should implement a simple representation learning scheme based on a contrastive loss:
Load the MNIST dataset
- Write a function which takes an image and prepares a quantum state. This function should have trainable parameters which we want to learn in order to have good quantum representations
- Create a circuit with which takes two images and embeds both as quantum states with the function you wrote before. Afterwards the circuit should perform a -- SWAP test between the two states. In the end the measurement should give the fidelity of the quantum states.
- Train the circuit parameters with a contrastive loss: For two MNIST images in the same class the fidelity should be maximized, while for images of different - classes the fidelity should be minimized.
