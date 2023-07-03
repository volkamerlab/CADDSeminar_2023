# T04 · Predicting Drug-Drug Interactions using SVM

Authors:

- Vanessa Siegel, 2023, CADD Seminar, Centre for Bioinformatics
- Floriane Odje, [Volkamer Lab](https://volkamerlab.org/)
- Prof. Dr. Andrea Volkamer, [Volkamer Lab](https://volkamerlab.org/)

## Aim of this talktorial

This talktorial introduces and explores the subject of drug-drug interactions (DDI) and their different types, paying special attention to the concepts of antagonism, additivity, and synergism. This will be followed by a closer look at Support Vector Machines (SVM) that use soft margin classifiers and then move towards a more detailed explanation of how to use a combined similarity matrix as a pairwise kernel function to solve the non-linear classification problem of predicting new DDI by comparing them to already known DDI.

To build the combined similarity matrix, we will look at 2D and 3D structural similarity as well as the similarity between interaction profiles and create databases for each of them. The dataset used during the practical part of this talktorial will be retrieved from [__DrugBank__](www.drugbank.ca) and filtered to only contain small molecule drugs that are annotated as approved for medical use in at least one country and for which 2D and 3D structural data is available.

### Contents in *Theory*

-	Drug-Drug Interactions
    - Importance of drug-drug interactions
    - Drug-drug interaction types
-	Drug Similarity
    - Defining drug similarity to a computer
    - 2D similarity
    - 3D similarity
    - Interaction profile similarity
-	Support Vector Machines
    - Soft Margin Classifier
    - Kernel Trick
-	DrugBank
    - History
    - Drug Entries
-	Workflow: Similarity-Based SVM for DDI Prediction
    - Feature Selection
    - Data Selection
    - Creating drug-drug similarity databases
    - Creating drug-pair similarity matrices
    - Creating the pairwise kernel
    - Modelling and evaluating the SVM

### Contents in *Practical*

-	Reading input data from DrugBank
-	Create a drug-drug 2D molecular structure similarity database using RDKit
-	Create a drug-drug 3D pharmacophoric similarity database using E3FP and RDKit
-	Create a drug-drug interaction profile similarity database using RDKit
-	Construct a combined pairwise similarity matrix for the kernel function
-	Model and evaluate the SVM with Scikit-Learn

### References

* Similarity-based SVM predictor for DDI: [*J. Clin. Pharm. Ther.* (2018), __44(2)__, 268-275](https://pubmed.ncbi.nlm.nih.gov/30565313/)
* Explanation of E3FP: [*J. Med. Chem.* (2017), __60__, 7393-7409](https://pubs.acs.org/doi/full/10.1021/acs.jmedchem.7b00696)
* DrugBank: [*Nucleic Acids Res.* (2017), __8__](https://pubmed.ncbi.nlm.nih.gov/29126136/)
* Fingerprints and Drug Similarity: [__Talktorial 004__](https://github.com/volkamerlab/teachopencadd/blob/master/teachopencadd/talktorials/T004_compound_similarity/talktorial.ipynb)
* RDKit package [__documentation__](https://www.rdkit.org/docs/index.html)
* E3FP package [__documentation__](https://e3fp.readthedocs.io/en/latest/index.html)
* Scikit-Learn package [__Documentation__](https://scikit-learn.org/stable/index.html)