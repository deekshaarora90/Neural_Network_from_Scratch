# Neural Network from Scratch

Custom feedforward neural network with backpropagation. Pure NumPy implementation by Ahmed Besbes.

## Features
- Multi-layer perceptron (arbitrary depth)
- Sigmoid activation + derivatives
- MSE loss + backpropagation
- Batch SGD training
- Live decision boundary plotting
- Train/validation splits

## Quick Start

```bash
pip install numpy matplotlib scikit-learn tqdm ipython

python neural_network.py

````

Input → Hidden Layers (sigmoid) → Output (sigmoid → threshold 0.5)
Loss: MSE | Optimizer: Batch SGD

