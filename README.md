# Multi-Objective Optimization of Algae B20 + RGO IC Engine Performance using Neural Networks

This repository contains an end-to-end Machine Learning workflow that transforms experimental IC Engine trial data into an AI-powered predictive model and digital twin optimization engine.

## 📊 Project Overview
- **Objective:** Model the non-linear operational dynamics of a Kirloskar TV1 diesel engine utilizing Algae B20 biodiesel mixed with Reduced Graphene Oxide (RGO) nano-additives.
- **Inputs:** Engine Load (%), Nano-additive Concentration (ppm)
- **Target Outputs:** Brake Thermal Efficiency (BTE %), NOx Emissions (ppm), Smoke Opacity (%)

## 🧠 Model & Architecture
- **Framework:** Python (`scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`)
- **Algorithm:** Multi-Layer Perceptron (MLP) Regressor / Artificial Neural Network (ANN)
- **Validation Accuracy:** Achieved a stellar R² score of **0.9587**, proving strong physical convergence.

## 🎯 Multi-Objective Optimization Milestones
Utilizing a multi-objective optimization desirability matrix, the neural network isolated the absolute optimal environmental and thermal operating balance:
- **Recommended RGO Concentration:** 150 ppm
- **Recommended Engine Load:** 42.0%
- **Predicted Performance:** 22.11% BTE | 8.9 ppm NOx | 8.95% Smoke Opacity

This workflow demonstrates how data-driven engineering can replace expensive, manual trial-and-error iterations in sustainable powertrain design.
