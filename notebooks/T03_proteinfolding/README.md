# T03 · Protein Folding

**Note:** This talktorial is a part of TeachOpenCADD, a platform that aims to teach domain-specific skills and to provide pipeline templates as starting points for research projects.

Authors:
- Mhd Jawad Al Rahwanji, CADD seminar 2023, Volkamer lab, Saarland University
- Paula Linh Kramer, 2023, Volkamer lab, Saarland University
- Andrea Volkamer, 2023, Volkamer lab, Saarland University


## Aim of this talktorial

In this notebook, we will learn about protein folding and how to predict protein structures using machine learning. This helps us understand diseases and accelerates drug development.

Our work here will include comparing the predicted structures to their corresponding crystalline forms.


### Contents in *Theory*

* Protein Folding
    * Proteins
    * The Folding Problem
* History
    * CASP
    * Breakthroughs
* OmegaFold
    * Innerworkings and Training
    * Performance evaluation
    * More on orphan proteins and antibodies
    * Investigating the Geoformer
    * Computational performance
* Alternative Methods
    * Quantum Approach
    * Diffusion-based Models


### Contents in *Practical*

**Goal: Predict the 3D structure of a protein from a given sequence of amino acids**

* Overview
* Setup
* Processing the input sequences
* Analyzing the output predictions
  * 6YJ1
  * 7FVU
* Analyzing the secondary structures
  * RMSD
  * Prediction confidences
  * Ramachandran plots
* Summary


### References

* [CASP](https://predictioncenter.org/)
* AlphaFold2: [Jumper *et al.*, <i>Nature</i> (2021), <b>596</b>, 583–589](https://doi.org/10.1038/s41586-021-03819-2)
* RoseTTAFold: [Baek *et al.*, <i>Science</i> (2021), <b>373</b>, 871-876](https://doi.org/10.1126/science.abj8754)
* OmegaFold: [Wu *et al.*, <i>bioRxiv</i> (2022)](https://doi.org/10.1101/2022.07.21.500999)
* [Baker lab](https://www.bakerlab.org/)
* Quantum folding: [Robert *et al.*, <i>npj Quantum Inf.</i> (2021), <b>7</b>, 38](https://doi.org/10.1038/s41534-021-00368-4)
* Protein generation: [Watson *et al.*, <i>bioRxiv</i> (2022)](https://doi.org/10.1101/2022.12.09.519842)
* [OmegaFold on Github](https://github.com/HeliXonProtein/OmegaFold)