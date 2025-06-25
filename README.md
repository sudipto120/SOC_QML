<!DOCTYPE html>
<html lang="en">

<body>

<h1>Quantum Machine Learning</h1>

<h2>1. Basics of Quantum Mechanics (Nielsen &amp; Chuang, Ch. 2)</h2>
<ul>
  <li>Dirac notation, complex Hilbert spaces, inner products, orthonormal bases.</li>
  <li>The four postulates: state space, unitary evolution, projective measurement (Born rule), composition via tensor products.</li>
  <li>Pure vs. mixed states, density matrices, partial trace, reduced states.</li>
  <li>Single-qubit Bloch-sphere geometry, no-cloning and no-broadcasting theorems.</li>
  <li>Entanglement fundamentals: Bell states, Schmidt decomposition, separability criteria.</li>
</ul>

<h2>2. Quantum Gates &amp; Circuits (Nielsen &amp; Chuang, Ch. 4 + Qiskit)</h2>
<ul>
  <li>Universal single-qubit gates: Pauli (X, Y, Z), phase (S, T), rotations (R_x, R_y, R_z).</li>
  <li>Entangling gates: CNOT, CZ, SWAP; Toffoli for universal reversible computation.</li>
  <li>Circuit synthesis: Euler decompositions, Solovay–Kitaev theorem.</li>
  <li>Resource metrics: depth, width, T-count, fault-tolerant considerations.</li>
  <li>Qiskit primitives: <code>QuantumCircuit</code>, gate calls, transpilation, visualization.</li>
</ul>


<h2>3. QFT-Based Algorithms (Nielsen &amp; Chuang, Ch. 5 + Qiskit)</h2>
<ul>
  <li>Quantum Fourier Transform definition, circuit with controlled-phase ladder and SWAP cleanup.</li>
  <li>Quantum Phase Estimation (QPE): eigenphase extraction, precision vs. resources.</li>
  <li>Order-finding &amp; period-finding; Shor’s factoring and discrete-log as layered applications.</li>
  <li>Hidden Subgroup Problem viewpoint and extensions.</li>
  <li>Qiskit tools: <code>QFT</code> class, <code>PhaseEstimation</code>, modular-exponentiation subcircuits.</li>
</ul>

<h2>4. Quantum Search Algorithms (Nielsen &amp; Chuang, Ch. 6 + Qiskit)</h2>
<ul>
  <li>Grover iteration: oracle phase flip + diffusion operator; geometric 2-D interpretation.</li>
  <li>Optimal O(sqrt{N}) query complexity and matching lower bound.</li>
  <li>Variants: multiple marked items, quantum counting, fixed-point searches, amplitude estimation.</li>
  <li>Circuit techniques for multi-controlled phase gates and ancilla optimization.</li>
  <li>Qiskit resources: <code>Grover</code> class, oracle wrappers, iterative amplitude-estimation routines.</li>
</ul>

<h2>5. Variational Quantum Algorithm Design (Qiskit Modules &amp; Tutorials)</h2>
<ul>
  <li>Ansatz construction for a given hamiltonian.</li>
  <li>Cost-function evaluation via expectation values</li>
  <li>Parameter-update methods: gradient-free (COBYLA, SPSA, Nelder–Mead) vs. gradient-based (parameter-shift, natural gradient).</li>
  <li>QUBO / Ising Formulation</li>
  <li>Flagship algorithms: VQE (ground-state energy), QAOA (combinatorial </li>
</ul>

</body>
</html>
