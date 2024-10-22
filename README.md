# Quantum cryptanalysis of ZUC and related resource estimation
## Authors: Suman Dutta, Anirban Ghatak, Anupam Chattopadhyay, Subhamoy Maitra

### Abstract:
The ZUC stream cipher is integral to modern mobile communication standards like 4G and 5G, playing a key role in securing data transmission across global networks. Although multiple attempts have been made to perform classical cryptanalysis of ZUC, it is surprising that no concrete efforts have been made towards its quantum cryptanalysis and related resource estimation. This paper presents a comprehensive quantum resource estimation of ZUC in the context of Grover-based quantum key-recovery attacks. We introduce novel circuit optimization techniques, such as modular quantum doubling and successive quantum modular addition, and implement reversible quantum logic circuit synthesis for both linear and non-linear functions to reduce the quantum resources required for implementing ZUC. We obtain that a full-scale Grover's search on ZUC-128 requires approximately $1.5 \cdot 2^{87}$ Clifford + T gates, with a T-depth of $1.42 \cdot 2^{83}$, and a overall circuit depth of $1.42 \cdot 2^{84}$, whereas for ZUC-256, these numbers are approximately $1.67 \cdot 2^{151}$, $1.57 \cdot 2^{147}$, and $1.57 \cdot 2^{148}$, respectively. Additionally, further evaluation of ZUC against NIST's MAXDEPTH criterion confirms its security, albeit with a narrow margin, suggesting potential areas for future optimization and further analysis of ZUC's resilience against quantum attacks.

Keywords: Grover's search algorithm, Quantum circuit synthesis, Quantum resource estimation, MAXDEPTH criterion, ZUC stream cipher.

_____________________________________________________
## This paper has been accepted in the Indocrypt 2024.
### This GitHub repository contains large matrices, all the implemented qiskit codes, corresponding circuit diagrams, and the observed histograms, which could not be included in the paper due to space constraints and for better readability of the paper.
1. ZUC - Qiskit Implementation.ipynb is the complete jupyter notebook containing the qiskit codes and the corresponding results.

