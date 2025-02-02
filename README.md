# 2025_MIT-QuantumRing_Remote![截圖 2025-02-02 晚上7 29 25](https://github.com/user-attachments/assets/26b933ff-33ff-499f-b078-d4462c7f22c9)
Shor’s algorithm, introduced in 1994, demonstrated polynomial-time integer factorization, pre-
senting a potential threat to classical cryptography. Despite advances in optimizing the algorithm,
its practical application remains hindered by the significant resources required for fault-tolerant
quantum computation. In this work, we propose a space-efficient quantum factoring algorithm
that reduces qubit requirements while maintaining computational efficiency. By introducing a com-
pressed Eker-H˚astad subroutine, we minimize the qubits needed for modular exponentiation and
improve feasibility on near-term quantum hardware. The algorithm consists of three stages: Clas-
sical Preprocessing for input preparation, Quantum Computation for period finding using
controlled modular multiplication, and Classical Post-Processing to recover prime factors. Our
approach [1] optimizes qubits, reduces circuit depth, and enhances gate efficiency, making quantum
factorization more practical for current quantum architectures.
The main implementation is in [`QuFacto.ipynb`](QuFacto.ipynb).
