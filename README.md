# Makemore

An educational implementation of the concepts covered in **Andrej Karpathy's Makemore series**, built from scratch with PyTorch.

This repository follows the progression of the series chapter by chapter, implementing increasingly sophisticated neural language models while emphasizing the intuition behind each architecture. The project is actively maintained and new chapters will be added as the series continues.

> **Status:** 🚧 Ongoing

---

## Overview

The goal of this repository is to recreate and understand every model developed throughout the Makemore series rather than simply reproducing the final results.

Each implementation focuses on:

* Building models from first principles
* Understanding the mathematics behind neural networks
* Writing clean, readable PyTorch code
* Experimenting with architectures and hyperparameters
* Documenting key insights and lessons learned

---

## Roadmap

* [x] Character-level Bigram Language Model
* [ ] MLP Language Model
* [ ] WaveNet-style Architecture
* [ ] Backpropagation from Scratch
* [ ] GPT-style Transformer
* [ ] Additional experiments and improvements

The checklist will be updated as new parts of the series are completed.

---


> The structure may evolve as the project grows.

---

## Models Implemented

### Bigram Language Model

* Character-level language modeling
* Probability tables
* Sampling names
* Training with negative log-likelihood

### MLP Language Model

* Embedding layer
* Hidden layers
* Batch normalization
* Better optimization techniques

Future implementations will include more advanced architectures introduced in the series.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/NostalgicWinters/Makemore.git
cd Makemore
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Train a model:

```bash
python train.py
```

Generate samples:

```bash
python generate.py
```

The exact commands may change as the repository evolves.

---

## Learning Resources

This project is based on Andrej Karpathy's excellent educational content on neural networks and language modeling.

Recommended resources:

* Neural Networks: Zero to Hero
* Makemore Series
* PyTorch Documentation

---

## Goals

This repository is intended for:

* Students learning deep learning
* PyTorch beginners
* People interested in language models
* Anyone wanting to understand LLMs from the ground up

Rather than relying on high-level libraries, the implementations prioritize clarity and educational value.

---

## Contributing

Contributions are welcome.

If you find bugs, have suggestions, or would like to improve an implementation, feel free to open an issue or submit a pull request.

---

## Acknowledgements

Special thanks to **Andrej Karpathy** for creating one of the best educational deep learning series available. This repository is an independent educational implementation inspired by his Makemore tutorials.

---

## License

This project is licensed under the MIT License.

<!-- Repository Structure
Makemore/
├── data/               # Datasets
├── notebooks/          # Exploratory notebooks (optional)
├── src/                # Model implementations
├── utils/              # Helper functions
├── checkpoints/        # Saved models (optional)
└── README.md -->
