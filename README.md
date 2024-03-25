# ADAM Optimizer

## Overview
This repository is dedicated to the implementation and exploration of the ADAM Optimizer, a popular optimization algorithm widely used in training deep learning models. The ADAM Optimizer combines the advantages of two other extensions of stochastic gradient descent, namely Adaptive Gradient Algorithm (AdaGrad) and Root Mean Square Propagation (RMSProp), to handle sparse gradients on noisy problems. 

## Objectives
The primary objectives of this project are to:
- Implement the ADAM Optimizer from scratch.
- Explore its efficiency and performance in comparison with other optimization techniques.
- Apply the ADAM Optimizer to various machine learning models and datasets to evaluate its effectiveness in practice.

## Mathematics Applied
- **Gradient Descent:** Understanding the fundamentals of how models are optimized.
- **Adaptive Learning Rate Methods:** Concepts behind AdaGrad and RMSProp, which are foundational to ADAM.
- **Exponential Moving Averages:** Utilized for calculating the adaptive learning rates in ADAM.
- **Bias Correction:** A technique used to adjust the estimates provided by ADAM for better accuracy during the initial training phase.

## Coding Skills
- **Python Programming:** The primary language used for implementation.
- **Numerical Computation:** Utilized numpy for efficient mathematical operations.
- **Data Handling:** Techniques to process and prepare datasets for model training using pandas.
- **Visualization:** Employed matplotlib and seaborn for visualizing the optimization process and results.

## Machine Learning Techniques
- **Model Implementation:** Building various machine learning models to test the optimizer.
- **Parameter Tuning:** Techniques for adjusting hyperparameters of the ADAM Optimizer to improve model performance.
- **Performance Evaluation:** Metrics and methods used to evaluate the effectiveness of the optimizer across different models and datasets.

## Getting Started
To get started with this project, and clone the repository.

```
git clone https://github.com/jakthehut/ADAM-Optimizer.git
cd ADAM-Optimizer
```
and read the [report on ADAM](report/report.pdf).


## Acknowledgements
- Thanks to the original authors of the ADAM paper for their groundbreaking work on optimization algorithms.
- This project was inspired by coursework from Central European Universites Data Science program, especially due to Assistant Professor Imre Feketes class on Optimization

