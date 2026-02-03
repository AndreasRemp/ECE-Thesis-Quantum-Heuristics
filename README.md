# ECE-Thesis-Quantum-Heuristics
**Title:** Implementation of Heuristic Functions on Quantum Computer.<br><br>
**Key Words:** Quantum Tree Search. Sliding-Tiles Puzzle. Hybrid Quantum-Classical Methods. Quantum Artificial Intelligence.<br><br>
**Project Overview:** The research investigates the scalability and efficiency of Quantum Tree Search algorithms when applied to Sliding-Tile Puzzles. It explores how quantum-enhanced selection can optimize decision-making in complex environments.<br><br>
**Core Methodologies:** Global Quantum Search w/ Grover's Amplification, Hybrid Classical Lookahead Search w/ Quantum Selector, Heuristic Cost Evaluations.<br><br>
**Sources:** Quantum Tree Search with Qiskit - Andreas Wichert, A fast quantum mechanical algorithm for database search - Lov Grover, Qiskit Aer Documentation - IBM Quantum.<br><br>
**Setup:** pip install qiskit, qiskit-aer, numpy, matplotlib
**Repo Content:** Includes standalone Python scripts, implementing Quantum tree search for the 3 puzzle at fixed depths, Grover based amplitude amplification for solution path selection, Hybrid quantum classical heuristic search for the 8 puzzle Simulation and result extraction using Qiskit Aer backends.<br><br>
**Mapping & Execution:** Each script corresponds to a specific experiment or methodological component described in the thesis. Simulations are performed using Qiskit Aer backends. Shot counts and circuit structures are fixed as described in the thesis <br><br>
**Limitation:** All results are obtained using classical simulation of quantum circuits. Scalability is constrained by simulator resources. The implementations aim at methodological validation rather than quantum advantage demonstration <br><br>
