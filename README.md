# GSoC2026-ML4SCI-Evaluation
# GSoC 2026 Evaluation Task: Quantum Circuit Design with LLMs

[![Python 3.13](https://img.shields.io/badge/Python-3.13-blue.svg)](https://www.python.org/downloads/release/python-3130/)
[![PennyLane](https://img.shields.io/badge/PennyLane-Quantum-purple.svg)](https://pennylane.ai/)
[![ML4SCI](https://img.shields.io/badge/Organization-ML4SCI-orange.svg)](https://ml4sci.org/)

This repository contains my official evaluation task submission for the **Google Summer of Code (GSoC) 2026** project under **ML4SCI**: *Design and simulation of Variational Quantum Circuits (VQC) with Large Language Models (LLM)*, in collaboration with EXXA and QMLHEP.

## 🚀 Overview

The goal of this task was to build an automated, closed-loop pipeline where an AI Agent can design, simulate, and optimize quantum neural networks. Instead of merely implementing a basic standard circuit, this notebook introduces a rigorous comparative study between classical architectures and cutting-edge quantum methodologies.

### ✨ Key Features
* **Agentic Closed-Loop Optimization**: Engineered an LLM Agent using the Orchestral AI framework that autonomously iterates on hyperparameters (learning rate, epochs) based on empirical feedback (Loss/Accuracy).
* **Architectural Innovation (VQC vs. Q-KAN)**: Implemented and evaluated two distinct quantum topologies from scratch using PennyLane:
  * **Baseline VQC**: A standard Variational Quantum Circuit utilizing strongly entangling layers.
  * **Q-KAN**: A custom Quantum Kolmogorov-Arnold Network utilizing data re-uploading and manual topological unrolling to simulate learnable non-linear activations with high parameter efficiency.
* **Barren Plateau Monitoring**: The agent is prompted to actively monitor energy landscapes and gradient vanishings during its unconstrained 10-trial search.
* **Automated Academic Reporting**: Dynamically generates publication-ready visualization plots and markdown conclusions based on the agent's real-time training histories.

## 📂 Repository Structure
* `Yanchen_Lu_GSoC2026_QMLHEP.ipynb`: The main, self-contained Jupyter Notebook including all code, outputs, embedded plots, and automated research reports.

## ⚙️ How to Run
To reproduce the agent's hyperparameter search and visualization:
1. Ensure you have **Python 3.13** installed.
2. Install the required dependencies (PennyLane, Orchestral, scikit-learn, matplotlib).
3. Open the `.ipynb` file and insert your OpenAI/DeepSeek API Key in the first cell.
4. Run all cells sequentially.

---
*Authored by Yanchen Lu .*
