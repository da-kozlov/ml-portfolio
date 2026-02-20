# ML Portfolio

This repository contains a collection of theoretical and research-oriented machine learning projects.

The portfolio is focused on optimization dynamics and geometry of over-paramaterized models. 
The projects focus on mathematical clarity, reproductability an empirical validations of theoretical conclusions.

## About

I hold a Bachelor's degree in Applied Mathematics and am currently pursuing research oriented opportunities.

My primary interests include:

- optimization in deep learning;
- stability and generalization;
- geometry of over-paramaterized models;
- theoretical aspects of optimization methods.

## Repository Structure

### `ml-theoretical-projects/`

Implementations of core machine learning algorithms from scratch.

Includes:

- Gradient Descent (GD);
- Stochastic Gradient Descent (SGD);
- Linear Regeression;
- Experiments on convergence and stability.

Goals:

- understand optimization at a low level;
- implement algorithms without high-level abstraction;
- study convergence behaviour in controlled settings.

### `sgd-implicit-regularization/`

A reproduction project based on Lei Wu, Weijie J. Su (2023) *The Implicit Regularization of Dynamical Stability in Stochastic Gradient Descent* https://doi.org/10.48550/arXiv.2305.17490

This project reproduces experiments from the paper and empirically investigates:

- differences between SGD and GD dynamics;
- the effect of learning rate on generalization;
- the balancing effect of SGD.

The implementation includes:

- diagonal linear network;
- two-layer ReLU network;
- Fisher trace and other metrics of sharpness tracking;
- class-imbalance setting.

The goal is to replicate and empirically examine the key observations described in the paper under controlled experimental conditions.

## Tools

- Python
- PyTorch
- NumPy
- Matplotlib

## Contact

Email: danilakozloff.04@gmail.com

Telegram: https://t.me/moon_mon_key






