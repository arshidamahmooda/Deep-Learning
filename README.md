# README - Deep Learning & Machine Learning Scripts

## Overview
This repository contains multiple Python scripts related to deep learning, machine learning, and neural networks. The scripts include implementations of perceptrons, multilayer perceptrons (MLP), backpropagation, and simple machine learning concepts.

## File Descriptions

### 1. **arshida__mahmooda_243110.py**
- Implements basic Python object-oriented programming (OOP) concepts.
- Features a **Calculator class** for basic arithmetic operations (addition, subtraction, multiplication, division).
- Demonstrates **inheritance** in Python using `Person`, `Circle`, `Rectangle`, and `Fruit` classes.
- Includes method overriding using Python classes.

### 2. **class_3_deeplearning.py**
- Implements a **basic perceptron model** for binary classification.
- Uses NumPy for matrix operations.
- Trains the perceptron on an **AND gate dataset**.
- Implements perceptron training using a step activation function.
- Loads the **Iris dataset** and applies binary classification (Setosa vs. Versicolor).
- Implements a **Digit Recognizer** using TensorFlow and the MNIST dataset.

### 3. **mlp_with_backpropagation.py**
- Implements a **Multi-Layer Perceptron (MLP)** from scratch using NumPy.
- Uses **sigmoid activation** in hidden and output layers.
- Implements **backpropagation** for weight updates.
- Trains the MLP using a **moon-shaped dataset** (from Scikit-Learn).
- Includes forward propagation, loss calculation, and training process.

### 4. **deep_learning_1.py**
- Another implementation of a **Perceptron model**.
- Uses NumPy for matrix computations.
- Trains on an **AND gate dataset**.
- Loads and processes the **Iris dataset** for binary classification.
- Implements a perceptron classifier for distinguishing `Setosa` from other species.

---

## Requirements
Make sure you have the following Python packages installed before running the scripts:
``bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```
## Usage
To run any of the scripts, simply execute them using Python:
```bash
python script_name.py
```
For example:
```bash
python mlp_with_backpropagation.py

## Notes
- The scripts use **Colab-generated** Jupyter Notebook files but can be executed locally.
- Modify hyperparameters such as **learning rate**, **epochs**, and **activation functions** as needed.
- The `Perceptron` models use **step activation**, whereas the `MLP` model uses **sigmoid activation**.
- The dataset URLs in the scripts may need to be updated based on availability.

## Author
Arshida Mahmooda



