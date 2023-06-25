# Implementation-of-Grover Oracle for an attack on AES
1. SBOX Verilog files

  More details are available at  https://github.com/banerjeeutsav/aes_sbox_exploration

It includes total 432 canright sboxes (https://core.ac.uk/download/pdf/36694529.pdf) and 192 sboxes (https://pluto.huji.ac.il/~orzu/publications/ijcr_book_2004_01_03.pdf). The objective is to find optimum quantum resources for Sbox implementation.

2. Optimizing Implementations of Linear Layers

The below code help in synthesizing quantum circuit for Affine transform and isomorphic mapping.  

Github code: https://github.com/xiangzejun/Optimizing_Implementations_of_Linear_Layers/tree/master

Paper: https://eprint.iacr.org/2020/903.pdf


3. LIGHTER-R: Optimized Reversible Circuit Implementation For SBoxes

 Quantum circuit for $GF(2^4)$ Multiplicative inverse is synthesized using the LIGHTER-R tool. Its input is a lookup table of the function.  

Github code: https://github.com/vdasu/lighter-r

Paper: https://ieeexplore.ieee.org/document/9088027

4. Simulation of AES SBOX (C1):  Quantum circuit for 8-bit SBOX is simulated using "qiskit". It is realized with 20 qubits, 169 CNOT gates, 43 Toffoli gates, and 23 Toffoli depths.
(*Note: Sbox quantum circuit uses few swap gates to do in-place calculation. It can be avoided with rewiring, so CNOT counts do not consider Swap (3-CNOT) gates.)
   
