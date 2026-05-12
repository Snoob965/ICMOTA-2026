# ICMOTA-2026
# Graph-Theoretic Stochastic Modeling in High-Dimensional Quantitative Finance

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Snoob965/icmota/blob/main/ICMOTA%20SGNNs.ipynb)

*This repository contains the interactive implementation of the research accepted for presentation at **ICMOTA 2026** (First International Conference on Mathematical Optimization Theory and Applications, IIT BHU).*

## 📌 Executive Summary
Traditional stochastic models in quantitative finance often succumb to the "curse of dimensionality" when applied to multi-asset portfolios or complex market microstructures. This repository implements a novel framework that bridges **Stochastic Differential Games** and **Graph-Theoretic structures** to efficiently model high-dimensional financial environments. 

The framework maps dynamic asset correlations using graph representations (leveraging Variational Graph Autoencoders/GNNs) and approximates optimal execution and pricing strategies using high-dimensional stochastic calculus.

## 🧮 Mathematical Architecture
The implementation in this notebook focuses on the following core mathematical objectives:

1. **High-Dimensional State Representation:** Utilizing Graph Neural Networks (GNN) and Variational Graph Autoencoders (VGAE) to capture non-linear, time-varying dependencies across multiple financial instruments.
2. **Stochastic Differential Games:** Formulating market dynamics as a Stackelberg Stochastic Differential Game to model competitive interactions and risk topologies.
3. **Hamilton-Jacobi-Isaacs (HJI) Approximation:** Developing computational frameworks to approximate solutions to HJI equations, allowing for the derivation of optimal strategies in environments where exact analytical solutions are computationally intractable.

## ⚙️ Repository Contents
* `ICMOTA SGNNs.ipynb`: The core codebase. Contains the complete, top-to-bottom pipeline including data generation/ingestion, graph construction, stochastic simulation, and model evaluation. 

## 🚀 How to Run
This code is designed to be fully reproducible without requiring local environment configuration. 

1. Click the **"Open in Colab"** badge at the top of this document.
2. The notebook is pre-configured with all necessary dependencies.
3. Select **`Runtime > Restart and run all`** from the top menu to execute the stochastic simulations and view the convergence outputs and visualizations.

## 👨‍💻 Author
**Shubhayu Brahmachari** B.Tech in Mathematics and Computing  
Rajiv Gandhi Institute of Petroleum Technology (RGIPT)
