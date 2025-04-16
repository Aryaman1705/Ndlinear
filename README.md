# MNIST Image Classification with NdLinear CNN

## Project Overview
This project implements a convolutional neural network (CNN) for classifying handwritten digits (0–9) from the MNIST dataset using Python, PyTorch, and the `NdLinear` library by Ensemble AI. The `NdLinear` layer, a novel replacement for PyTorch's `nn.Linear`, preserves multi-dimensional data structures, achieving high accuracy with significantly fewer parameters. The model attains a test accuracy of **95.01%** with **5,146 parameters**, a ~75% reduction compared to **20,490 parameters** in a standard `nn.Linear`-based model.

---

## Features
- **Efficient Model**: Utilizes `NdLinear` to reduce parameter count while maintaining competitive accuracy.
- **MNIST Classification**: Classifies 28×28 grayscale images of handwritten digits.
- **Visualization**: Displays sample predictions with true and predicted labels.
- **Comparison**: Benchmarks `NdLinear` against `nn.Linear` for parameter efficiency.

---

