# Awesome Physics Informed Neural Networks [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]

## Contents

- [Websites and Resources](#websites-and-resources)
- [Papers](#papers)
- [Tutorials](#tutorials)

## Websites and Resources
- [Maziar Raissi Github](https://github.com/maziarraissi/PINNs) - Solving different pde's using PINN
- [DeepXDE](https://github.com/lululxvi/deepxde) - Deep learning library for solving forward and inverse problems involving differential equations, built on TensorFlow/PyTorch/JAX
- [NVIDIA Modulus](https://developer.nvidia.com/modulus) - Open-source, physics-informed deep learning framework by NVIDIA for building, training, and fine-tuning physics-ML models at industrial scale
- [Computational graphs and Backpropagation](http://colah.github.io/posts/2015-08-Backprop/) - Blog post on what are computational graphs by Christoph Olah
- [Numerical Optimization: Understanding L-BFGS](https://aria42.com/blog/2014/12/understanding-lbfgs)- Blog post on the mathematics behind the L-BFGS optimization method by Aria Haghighi
## Papers
- [Physics Informed Deep Learning (Part I): Data-driven Solutions of Nonlinear Partial Differential Equations](https://arxiv.org/abs/1711.10561) - Introducing physics informed neural networks and their forward usage for surrogate modeling
- [Physics Informed Deep Learning (Part II): Data-driven Discovery of Nonlinear Partial Differential Equations](https://arxiv.org/abs/1711.10566) - Introducing physics informed neural netwroks with focus on data driven discovery of differential equations
- [SciANN: A Keras/Tensorflow wrapper for scientific computations and physics-informed deep learning using artificial neural networks](https://arxiv.org/pdf/2005.08803.pdf) - A python package using keras and tensorflow for solving pdes' and differential equation data driven discovery
- [Finite Basis Physics-Informed Neural Networks (FBPINNs): a scalable domain decomposition approach for solving differential equations](https://arxiv.org/abs/2107.07871) - A scalable approach to for solving large problems related to differential equations with pinns and finding a set of basis functions
- [Auto-PINN: Understanding and Optimizing Physics-Informed Neural Architecture](https://arxiv.org/pdf/2205.13748.pdf) - Automated hyperparameter optimization approach for PINNs'
- [One-Shot Transfer Learning of Physics-Informed Neural Networks](https://arxiv.org/abs/2110.11286) - A general framework for transfer-learning on PINNs
- [Gen-FVGN: A Generalized Finite-Volume Graph Neural Network for solving steady-state PDEs](https://arxiv.org/pdf/2405.04466) - Generalized Finite Volume Graph Neural Network implementation for solving steady-state PDEs
- [Who Invented the Reverse Mode of Differentiation?](https://www.math.uni-bielefeld.de/documenta/vol-ismp/52_griewank-andreas-b.pdf) - On history and introduction to autodifferentiation
- [DeepXDE: A Deep Learning Library for Solving Differential Equations](https://arxiv.org/abs/1907.04502) - Comprehensive PINN library paper (SIAM Review 2021) covering forward, inverse, and fractional problems across multiple neural network types; one of the most cited works in the field
- [Physics-informed machine learning](https://www.nature.com/articles/s42254-021-00314-5) - Landmark review by Karniadakis et al. in Nature Reviews Physics (2021) covering the state of the field, open challenges, and future directions
- [When and Why PINNs Fail to Train: A Neural Tangent Kernel Perspective](https://arxiv.org/abs/2007.14527) - Theoretical analysis of PINN training failures using the neural tangent kernel framework, explaining stiffness in the loss landscape and proposing learning-rate annealing strategies
- [Understanding and Mitigating Gradient Flow Pathologies in Physics-Informed Neural Networks](https://epubs.siam.org/doi/10.1137/20M1318043) - Identifies gradient imbalance between PDE and boundary loss terms and introduces a self-adaptive weighting scheme to stabilize PINN training
- [Extended Physics-Informed Neural Networks (XPINNs): A Generalized Space-Time Domain Decomposition Based Deep Learning Framework for Nonlinear Partial Differential Equations](https://doi.org/10.4208/cicp.OA-2020-0164) - Extends PINNs to a generalized space-time domain decomposition framework enabling parallel training and scalable solutions for complex nonlinear PDEs
- [hp-VPINNs: Variational Physics-Informed Neural Networks With Domain Decomposition](https://arxiv.org/abs/2003.05385) - Formulates PINNs in a variational (weak) setting using hp-refinement and domain decomposition to improve accuracy for problems with sharp gradients
- [Respecting Causality for Training Physics-informed Neural Networks](https://arxiv.org/abs/2203.07404) - Shows that violating temporal causality during training is a key reason PINNs fail on time-dependent problems and proposes a simple causal training scheme to address this
- [Gradient-enhanced physics-informed neural networks for forward and inverse PDE problems](https://arxiv.org/abs/2111.02801) - Augments the PINN loss with gradient (derivative) information to improve convergence speed and solution accuracy, especially for smooth problems
- [Locally adaptive activation functions with slope recovery for deep and physics-informed neural networks](https://arxiv.org/abs/1909.12228) - Introduces learnable, locally adaptive activation functions that accelerate PINN training and improve solution accuracy across a range of PDE benchmarks
- [DeepONet: Learning nonlinear operators via Deep Operator Network based on the universal approximation theorem of operators](https://arxiv.org/abs/1910.03193) - Proposes Deep Operator Networks (DeepONet) for learning solution operators of PDEs, enabling fast evaluation for varying initial/boundary conditions
- [Fourier Neural Operator for Parametric Partial Differential Equations](https://arxiv.org/abs/2010.08895) - Introduces the Fourier Neural Operator (FNO), a resolution-invariant neural operator that achieves state-of-the-art accuracy for learning PDE solution operators
- [Scientific Machine Learning Through Physics-Informed Neural Networks: Where We Are and What's Next](https://arxiv.org/abs/2201.05624) - Comprehensive survey of the PINN literature covering formulations, training strategies, applications, software, and open challenges as of 2022
- [Universal Differential Equations for Scientific Machine Learning](https://arxiv.org/abs/2001.04385) - Presents a framework that embeds neural networks inside differential equations to combine data-driven and physics-based modeling, enabling system identification and discovery of governing equations
- [Conservative Physics-Informed Neural Networks on Discrete Domains for Conservation Laws: Applications to Forward and Inverse Problems](https://www.sciencedirect.com/science/article/pii/S0045782520302127) - Proposes conservative PINNs (cPINNs) using a domain-decomposition strategy that enforces flux continuity at interfaces to solve hyperbolic conservation laws
- [A physics-informed deep learning framework for inversion and surrogate modeling in solid mechanics](https://www.sciencedirect.com/science/article/pii/S0045782520304357) - Demonstrates PINN-based inversion and surrogate modeling for elasticity problems in solid mechanics, including identification of material parameters from sparse measurements

## Tutorials
- [Introduction to Physics Informed Neural Networks](https://towardsdatascience.com/solving-differential-equations-with-neural-networks-afdcf7b8bcc4) - A hands on solution to logistic equation using PINN
- [So, what is a physics-informed neural network?](https://benmoseley.blog/my-research/so-what-is-a-physics-informed-neural-network/) - A tutorial on harmonic oscillator problem solution using PINNs
- [Physics Informed Machine Learning (YouTube series by Steve Brunton)](https://www.youtube.com/playlist?list=PLMrJAkhIeNNQ0BaKuBKY43k4xMo6NSbBa) - High-quality, in-depth video lecture series by Prof. Steve Brunton (University of Washington) covering PINN fundamentals, applications, and recent advances
