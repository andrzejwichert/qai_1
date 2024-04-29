#  Quantum Artificial Intelligence with Qiskit (1.0)

This project aims at teaching you the fundamentals of Quantum Artificial Intelligence with Qiskit. It contains the example code of my  CRC Press/Taylor & Francis book, Quantum Artificial Intelligence, Andreas Wichert, 2024 

http://web.tecnico.ulisboa.pt/andreas.wichert/


Qiskit is an open-source software development kit (SDK) for working with quantum computers at the level of circuits and algorithms,  IBM Quantum,   https://quantum-computing.ibm.com/.

You can find installation instruction for qiskit at the site:
 https://qiskit.org/documentation/getting_started.html

For version qiskit 1.0 also install adittionaly in your environment: pip install qiskit-aer and
pip install qiskit-machine-learning and pip install qiskit-ibm-provider

Check this repository for the newest port of qiskit version which is now version 1.0.2. Last correction, the file 5_GroversAmplification.ipynb. 

There are following changes in qiskit 1.0 due to former versions 0.45:
qiskit.tools.jupyter are deprecated, instead of from qiskit import Aer use from qiskit_aer import Aer, instead or execute() use run() - when using run() decompose() the circuit, for quasi probabilities instead of plot_histogram(counts) use plot_distribution(counts), instead of  bind 
use assign.

Please email me to andreas.wichert@tecnico.ulisboa.pt if something is not running, so I can correct is as soon as possible!


For qiskit version before 0.46 go to https://github.com/andrzejwichert/qai

If you have any questions, pls email me <andreas.wichert@tecnico.ulisboa.pt>
