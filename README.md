<p align="center">
  <img src="assets/university of Greifswald.jpg" alt="University of Greifswald" height="150">
</p>

# GPT-Visualization

A project that explores, implements, and visualizes the inner workings of the **GPT-2 architecture** from scratch.  
The notebooks in this repository break down GPT-2 into its fundamental components, enabling step-by-step understanding of **tokenization, embeddings, attention mechanisms, transformer blocks, and language modeling**.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Learning Outcomes](#learning-outcomes)
- [License](#license)

---

## Overview

**GPT-Visualization** serves as an educational deep dive into the **GPT-2 model architecture**.  
By reconstructing the model in Python step-by-step, this project bridges the gap between **theory** and **practical implementation**.  

The primary objective is to **demystify transformer-based large language models** by offering transparent, modular, and interactive notebooks for learning and experimentation.

---

## Features

- **GPT-2 From Scratch**: Layer-by-layer breakdown of the GPT-2 architecture.  
- **Visualization Utilities**: Inspect embeddings, attention weights, and hidden states.  
- **Educational Design**: Structured with exercises/tasks (`Aufgaben.ipynb`) to reinforce learning.  
- **Hands-on Experiments**: Tokenization, self-attention mechanics, multi-head attention, feed-forward layers, and training loop demos.  
- **Interactive Exploration**: Run cells and modify code to deepen understanding.  

---

## Project Structure

```
├── Aufgaben.ipynb              # Exercises / tasks for hands-on learning
├── GPT2 From Scratch.ipynb     # Step-by-step GPT-2 implementation
├── assets/                     # Images, logos, or visualization outputs
└── README.md                   # Project documentation
```

---


## Installation

Clone the repository and set up your Python environment:

```bash
git clone https://github.com/SalahElshafey/GPT-Visualization.git
cd GPT-Visualization

# Create virtual environment (optional but recommended)
python3 -m venv env
source env/bin/activate  # Linux/Mac
env\Scripts\activate   # Windows

```

---

## Usage

Launch Jupyter Notebook to explore:

```bash
jupyter notebook
```

Open either:

- `GPT2 From Scratch.ipynb` → Full model implementation  
- `Aufgaben.ipynb` → Exercises/tasks for self-study  

---

## Dependencies

Key libraries:
- Python 3.8+
- NumPy
- Matplotlib
- PyTorch
- Jupyter Notebook


---

## Learning Outcomes

By completing this project, you will:

- Understand **tokenization, embeddings, and positional encoding**.  
- Implement **scaled dot-product attention** and **multi-head attention**.  
- Build **transformer decoder blocks** step by step.  
- Train and evaluate a simplified GPT-2 model.  
- Visualize model internals to build intuition.  

---

## License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use and adapt for educational purposes.
