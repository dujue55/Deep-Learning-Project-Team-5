# Knowledge Distillation for Robust Adversarial Learning

## Overview
This project explores the robustness of neural networks against adversarial attacks using the average gradient norm as a key evaluation metric. We aim to understand how sensitive models are to small input perturbations and analyze their overall behavior under adversarial conditions.

## Techniques Used
Knowledge Distillation: We use model distillation to improve robustness by training a distilled model at a higher temperature (T).
Gradient-Based Adversarial Attacks: We evaluate robustness using gradient-based attacks like PGD (Projected Gradient Descent) to generate adversarial samples.
Different Datasets: Two versions of the experiment were conducted using CIFAR-10 and MNIST, allowing us to compare model behavior across different data distributions.

## Objective
We aim to analyze the trade-off between robustness and accuracy in neural networks. Specifically, we investigate whether distillation can enhance adversarial robustness while minimizing accuracy loss. The results are assessed using test accuracy trends and PGD attack success rates at varying temperatures.

## Team_list
Wilson Eghonghon
Jue Du
Chengrui Liu
