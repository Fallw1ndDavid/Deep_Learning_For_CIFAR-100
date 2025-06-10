# Deep_Learning_For_CIFAR-100
Deep Learning for CIFAR-100 Image Classification — A Stepwise Model Enhancement Project
This repository presents a deep learning project focused on image classification using the CIFAR-100 dataset. The goal is to explore, design, and iteratively improve neural network architectures through principled experimentation and practical training strategies.

Project Overview
Through a multi-phase, data-driven approach, this project demonstrates how progressively enhanced neural architectures and training pipelines can significantly improve classification accuracy on complex image datasets. The project workflow includes:
1. Baseline CNN Design – foundational architecture for initial benchmarking
2. Regularization & Optimization – BatchNorm, Dropout, and optimizer tuning
3. Transition to ResNet18 – deeper residual networks with learning rate scheduling
4. Advanced Augmentation – use of Cutout and Cosine Annealing
5. Extended Training on ResNet34 – long-run training with visualization and recovery analysis

Key Techniques
- ResNet18 / ResNet34: progressively deeper networks to improve feature learning
- Cosine Learning Rate Annealing & SGD with Momentum: for dynamic and stable convergence
- Cutout Augmentation: forcing generalization by occluding input regions
- Learning Rate Finder: identifying optimal initial learning rates
- Loss & Accuracy Visualization: for diagnosing convergence and overfitting

