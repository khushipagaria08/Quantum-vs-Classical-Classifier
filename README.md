# Quantum vs Classical Classifier

A comparison of classical Logistic Regression and a quantum Variational Quantum Classifier (VQC) on the Iris dataset using **scikit-learn** and **Qiskit**.

## Project Overview

This project explores how classical and quantum models approach the same classification task. It covers data preprocessing, quantum feature encoding, model training, and evaluation.

The goal is to understand the practical behavior and limitations of a quantum classifier on a small dataset.

## Models

| Model | Implementation |
|---|---|
| Classical classifier | Logistic Regression using scikit-learn |
| Quantum classifier | VQC using Qiskit Machine Learning |
| Quantum feature map | `ZZFeatureMap` |
| Parameterized circuit | `RealAmplitudes` |
| Quantum optimizer | COBYLA |
| Quantum execution | `StatevectorSampler` simulation |

## Dataset

The Iris dataset contains 150 samples from three flower species, with four numerical features: sepal length, sepal width, petal length, and petal width.

## Workflow

1. Load and explore the Iris dataset.
2. Prepare the features and split the data into training and test sets.
3. Train and evaluate Logistic Regression.
4. Encode the features into a quantum circuit.
5. Train and evaluate the VQC.
6. Compare classification accuracy.

## Running the Project

Open `quantum_vs_classical_classifier.ipynb` in Google Colab or Jupyter Notebook and run the cells in order.

Install the dependencies using the notebook’s installation cell. Quantum model training may take longer than classical training.

## Results and Limitations

The notebook includes the model outputs and accuracy comparison. Quantum results can vary with initialization, circuit design, optimizer settings, and training iterations.

The quantum classifier runs on a simulator. This experiment does not establish quantum advantage; it provides a practical comparison of the two approaches.

## Tools

Python · Qiskit · Qiskit Machine Learning · scikit-learn · NumPy · Matplotlib · Google Colab

## Author

Khushi Pagaria
