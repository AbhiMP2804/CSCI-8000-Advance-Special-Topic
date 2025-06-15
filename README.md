# 🧠 Deep Learning Optimizer Benchmarking

## 💡 Overview

This project presents a comprehensive comparative study of **ten popular deep learning optimizers**, including:

- SGD
- Adam
- RMSProp
- AdaGrad
- Adamax
- AMSGrad
- And a novel **NASG (Nesterov Accelerated Shuffling Gradient)** optimizer

The performance is evaluated on two standard datasets — **MNIST** and **CIFAR-10** — using two architectures: **ResNet50** and **AlexNet**.

---

## 🎯 Objectives

- Implement and benchmark a variety of optimizers on standardized deep learning tasks.
- Analyze convergence rate, training loss, and test accuracy under controlled hyperparameter settings.
- Derive practical insights into which optimizers perform best under different scenarios.

---

## 🧠 My Contribution

- Implemented and evaluated optimizers specifically for **ResNet50**, including variants of SGD and adaptive methods like Adamax and AMSGrad.
- Performed rigorous training across different learning rates while keeping batch size, epochs, and initialization constant.
- Conducted quantitative analysis of test accuracy, training loss, and convergence speed for each optimizer.

---

## 🚀 Key Outcomes

- Achieved **99.7% test accuracy on MNIST** and **90% on CIFAR-10** using ResNet50 with the custom **NASG optimizer**.
- Demonstrated that NASG offers consistent convergence and robustness across datasets and architectures.
- Provided clear guidelines for optimizer selection based on model complexity and data characteristics.

---

## 🧰 Tools & Technologies

- **Programming Language:** Python
- **Framework:** PyTorch
- **Architectures:** ResNet50, AlexNet
- **Datasets:** MNIST, CIFAR-10
- **Core Concepts:** Gradient Descent, Adaptive Optimization, Convergence Analysis

---

## 📊 Results Summary

| Optimizer | Accuracy (MNIST) | Accuracy (CIFAR-10) | Notes |
|----------|------------------|----------------------|-------|
| SGD      | 98.4%            | 85.2%                | Slower convergence |
| Adam     | 99.2%            | 88.3%                | Fast but unstable |
| NASG     | **99.7%**        | **90.0%**            | Best accuracy and stability |
