# Quantum Computing

Course materials for **Quantum Computing**, offered by the Department of Information Technology, JNTU-GV College of Engineering Vizianagaram (JNTUGV-CEV).

The course introduces the fundamentals of quantum computing: qubits, superposition, entanglement, quantum gates and circuits, quantum algorithms, and quantum error correction. It also covers hands-on programming with Qiskit and quantum simulators.

## Prerequisites

- Linear algebra and complex numbers
- Probability
- Basic quantum mechanics
- Python programming

## Course Units

| Unit | Title | Main Topics |
| ---- | ----- | ----------- |
| I | Foundations of Quantum Mechanics for Computing | Complex numbers and linear algebra, Dirac notation, qubits, superposition, phase and interference, Bloch sphere, measurement, multi-qubit states, entanglement |
| II | Quantum Gates and Circuits | Unitary and reversible computing, Pauli gates, Hadamard, S and T gates, rotations, multi-qubit gates, universal gate sets, Bell states, teleportation, superdense coding |
| III | Quantum Algorithms | Oracles and phase kickback, Deutsch, Deutsch–Jozsa, Bernstein–Vazirani, Simon's algorithm |
| IV | Quantum Programming and Simulation Platforms | Qiskit, Cirq, Q#, PennyLane, Braket, OpenQASM, simulators vs. real hardware, noise and decoherence, error mitigation, intro to quantum error correction |
| V | Quantum Computing Applications and Emerging Trends | QKD (BB84, E91), post-quantum cryptography, quantum machine learning, optimization and annealing, quantum chemistry, industry and careers |

Each unit is designed for about 5 hours (300 minutes) of instruction.

## Repository Structure

```
quantum-computing/
├── index.html                  # Course landing page (can be hosted with GitHub Pages)
├── pdfs/                       # Student-ready materials
│   ├── Slides-Unit-1..5.pdf
│   ├── Study-Notes-Unit-1..5.pdf
│   └── Worksheet-Unit-1..5.pdf
└── editable_source/            # Editable originals
    ├── qc_lecture_notes/       # Lecture notes (.docx), Units I–V
    ├── qc_unit1/ … qc_unit5/   # Topic-wise slide decks (.pptx)
    └── worksheets/             # Worksheets (.docx), Units I–V
```

## Materials

All PDFs are in the [`pdfs/`](pdfs) folder.

| Unit | Slides | Study Notes | Worksheet |
| ---- | ------ | ----------- | --------- |
| I | [Slides](pdfs/Slides-Unit-1.pdf) | [Notes](pdfs/Study-Notes-Unit-1.pdf) | [Worksheet](pdfs/Worksheet-Unit-1.pdf) |
| II | [Slides](pdfs/Slides-Unit-2.pdf) | [Notes](pdfs/Study-Notes-Unit-2.pdf) | [Worksheet](pdfs/Worksheet-Unit-2.pdf) |
| III | [Slides](pdfs/Slides-Unit-3.pdf) | [Notes](pdfs/Study-Notes-Unit-3.pdf) | [Worksheet](pdfs/Worksheet-Unit-3.pdf) |
| IV | [Slides](pdfs/Slides-Unit-4.pdf) | [Notes](pdfs/Study-Notes-Unit-4.pdf) | [Worksheet](pdfs/Worksheet-Unit-4.pdf) |
| V | [Slides](pdfs/Slides-Unit-5.pdf) | [Notes](pdfs/Study-Notes-Unit-5.pdf) | [Worksheet](pdfs/Worksheet-Unit-5.pdf) |

### Editable sources

If you want to adapt the materials, the original files are in [`editable_source/`](editable_source):

- **Lecture notes:** `.docx` files, one per unit
- **Slides:** `.pptx` files, one per topic (Unit I has 8 topics, Unit II has 8, Unit III has 7, Unit IV has 8, Unit V has 7)
- **Worksheets:** `.docx` files, one per unit

## Course Website

`index.html` is a standalone landing page with course information, instructors, and links to all materials. To publish it:

1. Go to **Settings → Pages** in your GitHub repository.
2. Under **Source**, choose the `main` branch and the `/ (root)` folder.
3. Save. The site will be available at `https://<your-username>.github.io/<repo-name>/`.

To customize the page (instructors, course staff, quick links, contact details), edit the sections marked `EDIT HERE` in `index.html`.

## Instructors

- **Instructor:** Prof. G. Jaya Suma
- **Course Staff:** S. Vinila, M. Kiran, K.B.D. Krishnaveni

## Contact

Questions about the course: [gjsuma.it@jntugvcev.edu.in](mailto:gjsuma.it@jntugvcev.edu.in)

## Usage

These materials are shared for educational purposes. If you reuse or adapt them, please credit the course and its instructors. Add a `LICENSE` file to the repository if you want to set specific reuse terms.
