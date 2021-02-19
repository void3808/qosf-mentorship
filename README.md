# qosf-mentorship
The repositort contains the code of the second screening task for qosf-mentorship.
The construct in the repository makes use of the 'repition code' analogy and implements a 2-qubit entanglement to detects and rectify errors over two rounds of syndrome measurement. The construct is able to consider all the possible combinations of the "error gates" applied to both the qubits of the entangled pair, and is capable of detecting and rectifying errors if only one of the qubits in the pair has been compromised. But in some cases, if both the qubits of the pair has been disturbed, then the contruct is unable to detect the discrepancies and provides a measurement showing that no error was introduced in the circuit.

The error-correction algorithm used is the most simplest one and works considerably well in cases where only a few logical qubits are implemented into the circuit. Since the possibility of error considerably decreases with the number of logical qubits, the algorithm works well in almost detecting all the 1-qubit errors and efficiently rectifies them without changing the original state of the logical qubit.
