
# Simple KAN: Kolmogorov-Arnold Networks

Simple KAN: Kolmogorov-Arnold Networks - A simple implementation of Kolmogorov-Arnold Networks.

## Overview

This repository contains a simplified implementation of Kolmogorov-Arnold Networks (KANs) using PyTorch. The implementation is inspired by the paper [Kolmogorov-Arnold Networks: A Deep Learning Alternative](https://arxiv.org/abs/2404.19756) and the [pykan GitHub repository](https://github.com/KindXiaoming/pykan). The goal is to provide a clearer understanding of KANs by implementing a basic version and evaluating it on a simple task.

## Kolmogorov-Arnold Networks (KANs)

KANs are an alternative to Multi-Layer Perceptrons (MLPs). Unlike MLPs, where activation functions are fixed at nodes, KANs use learnable activation functions on edges. This approach replaces linear weights with univariate functions parametrized as splines, leading to potentially better accuracy and interpretability. KANs can outperform MLPs in terms of performance with smaller models and provide intuitive visualizations.

## Features

- Implementation of KANs using PyTorch
- Custom layers for spline-based activation functions
- Example application on the Iris dataset for classification
- Training and evaluation scripts included

## Code Description

- `KANLayer`: Defines a single KAN layer with learnable spline-based activation functions.
- `KAN`: Constructs a multi-layer KAN model.
- `example.py`: Demonstrates the usage of KANs on the Iris dataset, including training and evaluation.

## Results

![image](https://github.com/user-attachments/assets/ae002455-1ce1-4282-a47f-16ac710ac72f)


## References

- [Kolmogorov-Arnold Networks: Multi-Layer Perceptrons (MLPs) Alternative](https://arxiv.org/abs/2404.19756)
- [pykan GitHub Repository](https://github.com/KindXiaoming/pykan)
