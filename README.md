# Conway-Maxwell-Poisson (CMP) Neural Network Simulation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-%23f37621.svg?logo=jupyter&logoColor=white)

A simulation of **Conway-Maxwell-Poisson (CMP) Neural Network models** for count data prediction, implemented in Python using Jupyter Notebook.

This project demonstrates how to simulate and evaluate CMP-based neural networks for modeling overdispersed or underdispersed count data — common in fields like epidemiology, finance, and social sciences.

---

## 📌 Overview

The **Conway-Maxwell-Poisson (CMP)** distribution is a generalization of the Poisson distribution that can model both overdispersion (variance > mean) and underdispersion (variance < mean). This notebook implements a neural network framework where the output layer uses the CMP likelihood function to predict count outcomes.

---

## 🔧 Features

- Implementation of CMP neural network architecture
- Training and evaluation on synthetic count data
- Visualization of results with plots and metrics
- Comparison with standard Poisson models
- Jupyter notebook with step-by-step explanation
