# PINNs-Linear-Elasticity-2D
# Physics-Informed Neural Networks for Linear Elasticity (1D + 2D)

Mesh-free solution of linear elasticity problems using PINNs & VPINNs  
→ 1D benchmark + full 2D vectorial elasticity on unit square  
→ Reaches 0.04 % relative error with only a 2-layer network

## Highlights
- No mesh, no FEniCS, no deal.II — pure TensorFlow/PyTorch/DeepXDE
- VPINNs vs PINNs head-to-head comparison (speed, accuracy, stability)

## Quick start

```bash
# 1. Clone the repository
git clone https://github.com/haifatalhiki/PINNs-Linear-Elasticity-2D.git
cd PINNs-Linear-Elasticity-2D

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the 2D PINNs model (includes training + plotting + video export)
python PINNs_2D_elasticity.py
