# Quantum_Computing
This repository is about optimization of quantum circuits.

## Template Matching ##
Quantum circuits generated by cascading quantum gates and/or decomposing classical reversible gates are often non-minimal. An optimization method called template matching can be employed to reduce the number of quantum gates in a circuit. Quantum templates are derived from identity circuits. All minimal realizations, within certain limitations, are embedded into templates. Due to this property, templates matching has the potential to reduce quantum costs of circuits. See "An Algorithm for Quantum Template Matching" https://dl.acm.org/doi/10.1145/2629537

### Example ###
```
Let's consider the Figure 1 that shows a quantum circuit to be optimized.
```
<p align="center">
  <img src="https://github.com/mazder/Quantum_Computing/blob/master/enigma1.png" width="700" alt="accessibility text">
</p>
<p align="center">
Figure 1: A quantum circuit taken from QHACK
</p>

```
Figure 2 shows the decomposed quantum circuit by replacing SWAP gate with CNOT gate sequence.
```

<p align="center">
  <img src="https://github.com/mazder/Quantum_Computing/blob/master/OrgCirc.png" width="450" alt="accessibility text">
</p>
<p align="center">
Figure 2: Replaced SWAP Gate with CNOT sequence
</p>

```
Figure 3 shows the optimized quantum circuit by using the algorithm given in "An Algorithm for Quantum Template Matching" https://dl.acm.org/doi/10.1145/2629537.
```

<p align="center">
  <img src="https://github.com/mazder/Quantum_Computing/blob/master/OptzCirc.png" width="150" alt="accessibility text">
</p>
<p align="center">
Figure 3: Optimized circuit
</p>
