# The Implicit Regularization with Dynamical Stability in SGD – A Reproduction Study

This project contains a research reproduction based on the paper

Lei Wu, Weijie J. Su (2023) *The Implicit Regularization of Dynamical Stability in Stochastic Gradient Descent* https://doi.org/10.48550/arXiv.2305.17490

It implements experiments to replicate key results from the paper, including empirical observartions on the generalization behaviour of SGD and GD, 
the evolution of the empirical Fisher trace and the effect of learning rate.

## Overview 

Stochastic Gradien Descent exhibits implicit regularization properties that can't be explained by small initialization alone. 
This project focuses on reproducing and empirically validating:

- the dynamical stability-induced regularization presented in the original paper;
- how trace of the empirical Fisher matrix and other sharpness metrics evolve during training under SGD vs. GD;
- the influence of learning rate on generalization performance;
- the behaviour of simple synthetic models (diagonal) and more complex ones (ReLU)
