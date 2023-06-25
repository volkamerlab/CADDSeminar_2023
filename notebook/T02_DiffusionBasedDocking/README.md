# T002 · Diffusion-based docking models

**Note:** This talktorial is a part of TeachOpenCADD, a platform that aims to teach domain-specific skills and to provide pipeline templates as starting points for research projects.

Authors:

- Hamza Ibrahim, CADD seminars 2023, Universität des Saarlandes (UdS)
- Michael Bockenköhler, 2023,  [Volkamer lab](https://volkamerlab.org), Universität des Saarlandes (UdS)
- Andrea Volkamer, 2023,  [Volkamer lab](https://volkamerlab.org), Universität des Saarlandes (UdS)

## Aim of this talktorial

In this talktorial, we present two state-of-the-art classes of generative models. We start by defining generative models and explain the fundamentals of two powerful classes of generative models. Afterward, we will explore the implementation of one type of the presented generative models in the field of drug discovery and the challenges that were encountered, and how they were solved.

### Contents in *Theory*

* Generative models
    * Denoising diffusion probabilistic model (DDPM)
        * Forward process
        * Reverse process
        * DDPM training
            * Loss function
            * Network architecture
    * Score-based generative model
        * Score model with stochastic differential equations (SDEs)
* Diffusion-based docking models
    * Ligand pose manifold
    * Product space diffusion
    * Model architecture


### Contents in *Practical*

* Data preparation
    - Download PDB structure
    - Prepare input data
* DiffDock implementation
* Denoising visualization

### References

* Generative Modeling by Estimating Gradients of the Data Distribution: ([_arXiv_ (2019), 1907.05600](https://arxiv.org/abs/1907.05600))
* Denoising Diffusion Probabilistic Models ([_arXiv_ (2020), 2006.11239](https://arxiv.org/abs/2006.11239))
* Score-based generative modeling through stochastic differential equations: ([_arXiv_ (2021), 2011.13456](https://arxiv.org/abs/2011.13456))
* DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking: ([_arXiv_ (2023), 2210.01776](https://arxiv.org/abs/2210.01776))
* Equivariant Graph Neural Networks: ([_arXiv_ (2022), 2102.09844](https://arxiv.org/abs/2102.09844))
* Deep Unsupervised Learning using Nonequilibrium Thermodynamics: ([_arXiv_ (2015), 1503.03585](https://arxiv.org/pdf/1503.03585.pdf))
* [Diffusion Model Clearly Explained!](https://medium.com/@steinsfu/diffusion-model-clearly-explained-cd331bd41166)
* [Generative Modeling by Estimating Gradients of the Data Distribution by Yang Song](https://yang-song.net/blog/2021/score/#connection-to-diffusion-models-and-others)
