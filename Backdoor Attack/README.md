# Backdoor Attack on Decision Tree Model for MNIST Dataset

This repository demonstrates a backdoor attack on a decision tree model for the MNIST dataset. 

## Overview

To demonstrate the backdoor attack, we follow these steps:

1. **Load the MNIST Dataset**: Load the MNIST dataset containing handwritten digit images and corresponding labels.

2. **Train a Decision Tree Model**: Train a decision tree classifier using the clean training data.

3. **Generate and Inject Backdoor Pattern**: Generate a specific pattern that will act as a trigger for the backdoor attack. Inject this pattern into a subset of the training data, associating it with a specific label.

4. **Train the Model with Backdoored Data**: Retrain the decision tree model using the modified training data containing the backdoor pattern.

5. **Evaluate Model Performance**: Evaluate the performance of the trained model on both clean and backdoored test data.

6. **Apply Backdoor Attack During Inference**: Apply the backdoor attack during inference by presenting test samples containing the backdoor trigger pattern and observing the model's predictions.

## Steps

Detailed step-by-step instructions along with Python code are provided in the notebook [backdoor_attack_demo.ipynb](backdoor_attack_demo.ipynb).

## Explanation

- We load the MNIST dataset and split it into training and test sets.
- We train a decision tree model on the clean training data.
- We generate a backdoor pattern (a square shape) and inject it into a subset of the training data, associating it with a specific label.
- We retrain the decision tree model using the modified training data containing the backdoor pattern.
- We evaluate the performance of the trained model on both clean and backdoored test data.
- Finally, we apply the backdoor attack during inference by injecting the backdoor pattern into a test sample and observing the model's prediction.
