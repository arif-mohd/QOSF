# QOSF
Solution to the Screening TASK 1
This repository contains my solution to the screening task 1 of QOSF application. I'd suggest that the writeUp be read first
to understand my approach to the solution. The main code for the actual problem is contained in the file called 3qubit_Grover.
However, since this code uses 48 qubits in all I'm not able to run it on qasm_simulator (or other related simulators). In order
to see that it has a chance to work I suggest that the following programs be seen in sequence:
1. qRAM : in which a qRAM with 2-qubit address register is constructed
2. qRAM_check: in which a check of this 2-qubit qRAM is performed.
3. 2qubit_Grover: in which I tweak the given problem a little bit to show that the basic idea and circuit works.
4. 3qubit_Grover: in which I solve the actual problem but with a drawback that I'm not able to simulate the circuit. 
