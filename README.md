![logo](banner.png)

# Quantum Coalition Future Leaders in Quantum (QC-FLIQ) Virtual Hackathon
Instructions for IBM Quantum's education challenge in collaboration with QuantA&M for the 2025 QC-FLIQ Hackathon.

The goal of this hackathon challenge is to create an educational, beginner-friendly tutorial that guides participants through implementing a famous quantum experiment on real IBM quantum hardware using Qiskit. The challenge is designed to be approachable for high school and undergraduate students, emphasizing both conceptual understanding and practical skills.

## Table of Contents
- [Challenge Prompt](#challenge-Prompt)
- [Submission](#Submission)
- [Resources](#Resources)
- [Qiskit Set-up](#Qiskit-Set-up)

## Challenge Prompt
Select one of the following:

1) Build and test a quantum random number generator using Hadamard gates.
2) Simulate a quantum double-slit experiment using quantum circuits.
3) Create all four Bell states using basic quantum gates, and verify them with measurement statistics.
4) Design a quantum dice (6-sided) using multiple qubits and validate fairness using Born’s rule.
5) Modify the modular exponentiation circuit to factor a different semi-prime.

## Challenge Structure

## 1. Step-by-Step Tutorial

+ Break down the chosen experiment into intuitive steps.
+ Connect mathematical concepts to quantum circuit construction.
+ Anticipate and address common points of confusion.

## 2. Quiskit Implementation

+ All code must run on:
  + Local Qiskit installations (Windows/Mac)
  + qBraid Lab `(lab.qbraid.com)`
+ At least one exercise must run on real IBM Qiskit hardware.
+ Include code for:
  + Submitting jobs and saving Job IDs
  + Retrieving and visualizing results
  + Estimating runtime (preferably <5 minutes per job)

## 3. Testing and Grading

+ Provide a separate `.py` script for local correctness checks before hardware submission.

## 4. Visualization

+ Use plots, circuit diagrams, and other visual tools to clarify results and concepts.

## 5. Exercises

+ Include 1–3 smaller exercises that build toward the final hardware experiment.
+ Final exercise should be tuneable (e.g., number of qubits, measurement basis).
+ At least one exercise should require thoughtful reasoning, not just code completion.

## Submission

+ Post your Jupyter Notebook on GitHub.
+ Include all explanations, code, and results in the notebook (see Sample.ipynb for more info).
+ Add any additional files (e.g., testing scripts) to the same repository.
+ Ensure the notebook renders correctly on GitHub and is easy to follow.
+ Provide a README with brief instructions for running the notebook locally.
+ Submit your GitHub repo link via the official submission form.


## Resources
+ [Qiskit Documentation](https://docs.quantum.ibm.com/guides/install-qiskit)
+ [IBM Quantum Challenge Example Notebooks](https://github.com/qiskit-community/ibm-quantum-challenge-2024/tree/main/content/lab_3)


## Qiskit Set up
Qiskit installation and IBMQ access: [Installation](Installation.ipynb)

Notebook provided by the Penn Quantum Computing Club

** Note:** This challenge is designed for educational purposes. Focus on clear, direct teaching, avoiding marketing language or basic code tutorials. The aim is to help participants learn about and implement quantum experiments on real hardware, building both confidence and curiosity in quantum computing during the International Year of Quantum, 2025! 








