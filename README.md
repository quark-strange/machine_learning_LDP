# machine_learning_LDP
Notebooks associated with the publication:

[_Phys. Rev. E_ **105**, 024115 (2022)](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.105.024115)

### Learning Nonequilibrium Control Forces to Characterize Dynamical Phase Transitions

#### Jiawei Yan (闫嘉伟), Hugo Touchette, and Grant M. Rotskoff

*Abstract*: Sampling the collective, dynamical fluctuations leading to nonequilibrium pattern formation requires probing rare regions of trajectory space. Recent approaches based on importance sampling, cloning, and spectral approximations, have yielded significant insight into nonequilibrium systems, but tend to scale poorly with the size the system, especially near dynamical phase transitions. Here we propose a machine learning algorithm that samples such trajectories and estimates the associated large deviation functions using a many-body control force by leveraging the flexible function representation provided by deep neural networks, importance sampling in trajectory space, and stochastic optimal control theory. We show that this approach scales to hundreds of interacting particles and remains robust at dynamical phase transitions.

These notebooks implement the numerical examples corresponding to our paper.

<img src="https://github.com/quark-strange/machine_learning_LDP/blob/main/results/ABPs_80_lambda-0.03.gif" width="50%" height="50%"/>
