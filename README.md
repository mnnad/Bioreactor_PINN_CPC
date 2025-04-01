# Bioreactor_PINN_CPC
PINNs were proposed by Raissi et al. in (http://arxiv.org/pdf/1711.10561v1) to solve ODEs by incorporating the physics (i.e the ODE) and the boundary conditions in the loss function. Here, the network structure of the PINN consists of two key components: a fully connected neural network and physical equation constraints. The ODEs that describe the cyanobacteria growth, nutrient consumption, and other key bioreactor processes are incorporated into the network. After the neural network learns the target parameters, such as biomass concentration or nutrient levels, it also computes the corresponding derivatives of these parameters, which are necessary for solving the ODEs.

![image](https://github.com/user-attachments/assets/ea6accd0-da5e-4daa-8fb6-c62c1254ee41)


This repository currently contains implementation of PINNs in PyTorch for a fed batch bioreactor.
