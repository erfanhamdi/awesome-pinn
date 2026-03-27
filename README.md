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

## Tutorials
- [Introduction to Physics Informed Neural Networks](https://towardsdatascience.com/solving-differential-equations-with-neural-networks-afdcf7b8bcc4) - A hands on solution to logistic equation using PINN
- [So, what is a physics-informed neural network?](https://benmoseley.blog/my-research/so-what-is-a-physics-informed-neural-network/) - A tutorial on harmonic oscillator problem solution using PINNs
- [Physics Informed Machine Learning (YouTube series by Steve Brunton)](https://www.youtube.com/playlist?list=PLMrJAkhIeNNQ0BaKuBKY43k4xMo6NSbBa) - High-quality, in-depth video lecture series by Prof. Steve Brunton (University of Washington) covering PINN fundamentals, applications, and recent advances
