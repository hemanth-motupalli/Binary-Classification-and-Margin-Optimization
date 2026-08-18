# Binary Classification & Margin Optimization

**Course:** IE684 - Operations Research Lab  
**Institution:** IIT Bombay  

## Project Overview
This repository contains the from-scratch implementation of a robust binary classifier using Stochastic Subgradient Descent (SGD). The project evaluates and compares the performance of three distinct margin optimization strategies—Hinge, Logistic, and Squared Hinge loss functions—applied to the Iris dataset. 

## Key Implementations
* **Data Engineering:** Transformed the multi-class Iris dataset into a binary classification problem ($+1$ / $-1$ labels) with an 80/20 train-test split.
* **Algorithm Development:** Built custom Stochastic Gradient Descent (SGD) optimizers with dynamic epochs and an early stopping criterion to evaluate objective convergence.
* **Margin Optimization & Regularization:** Computed specific sub-gradients for margin violations and tuned $L_2$ regularization parameters ($\lambda$) across logarithmic scales ($10^{-3}$ to $10$) to optimize the bias-variance tradeoff.
* **Loss Function Benchmarking:** Compared algorithmic convergence, outlier sensitivity, and test-set accuracy across:
  * Hinge Loss
  * Logistic Loss
  * Squared Hinge Loss

## Technologies Used
* **Languages:** Python
* **Libraries:** NumPy, Matplotlib, Scikit-Learn (Dataset Loading)
