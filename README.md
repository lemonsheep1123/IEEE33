# R-PINN: Blind Voltage Reconstruction for IEEE 33-Bus System

This repository contains the official implementation of the **Residual Physics-Informed Neural Network (R-PINN)** for power grid state estimation.

## 🚀 Highlights
- **High Precision**: Achieved a Mean Absolute Error (MAE) of **0.0055 p.u.** - **Sparse Observation**: Successfully reconstructed 33 nodes using only **5 sensor points**.
- **Physics-Informed**: Integrates Kirchhoff's Laws (Power Flow Equations) into the loss function.

## 🔧 Environment
- Python 3.11
- PyTorch
- Pandapower (for data generation)

## 📊 Results
Refer to the `pinn_result_fig1.png` in the repo for the voltage profile comparison.
