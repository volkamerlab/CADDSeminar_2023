# T03 · Protein Folding

Authors:
- Mhd Jawad Al Rahwanji, CADD seminar 2023, Volkamer lab, Saarland University
- Paula Linh Kramer, 2023, Volkamer lab, Saarland University
- Andrea Volkamer, 2023, Volkamer lab, Saarland University


## Aim of this talktorial

In this notebook, we will learn about protein folding and how to predict protein structures using machine learning. This task is crucial for understanding diseases and accelerating drug development.


### Contents in *Theory*

* Protein Folding
    * Proteins
    * The Folding Problem
* History
    * CASP
    * Breakthroughs
* OmegaFold
    * Inner Workings and Training
    * Performance Evaluation
    * More on Orphan Proteins and Antibodies
    * Investigating the Geoformer
    * Computational Performance
* Alternative Methods
    * Quantum Approach
    * Diffusion-based Models


### Contents in *Practical*

**Goal: Predict the 3D structure of a protein from a given sequence of amino acids and assess the results**

* Overview
* Setup
* Processing the Sequences
* Analyzing the Predictions
  * 6YJ1
  * 7FVU
* Analyzing the Secondary Structures
  * RMSD
  * Prediction Confidences
  * Ramachandran Plots
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
* [PDB](https://www.rcsb.org/)
* [NGLView documentation](http://nglviewer.org/nglview/release/v0.5.1/)
* [Biopython documentations](https://biopython.org/wiki/Documentation)
* [Biotite documentation](https://www.biotite-python.org/)