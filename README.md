# One-Carbon Metabolic Reprogramming Stratifies Prognosis and Defines Distinct Biological States in IDH1-Mutant Gliomas

Welcome to the official repository for the manuscript: **"One-Carbon Metabolic Reprogramming Stratifies Prognosis and Defines Distinct Biological States in IDH1-Mutant Gliomas"**. 

This repository houses the computational analysis code, raw datasets, and generated figures used to investigate how the One-Carbon Metabolism (OCM) network is rewired in IDH1-mutant gliomas and contributes to prognostic heterogeneity.

## 📖 Abstract Summary
IDH1 mutations in diffuse gliomas drive epigenetic remodelling and metabolic stress, primarily through 2-hydroxyglutarate accumulation. This study integrates transcriptional profiling to define an OCM signature that stratifies patient survival to define biological states for identifying therapeutic vulnerabilities in IDH-mutant gliomas. 

By analyzing the expression of 64 core OCM genes using transcriptomic data from the TCGA and CGGA datasets (n=709). This work reveals that IDH1-mutant tumors exhibit a distinct two-state metabolic phenotype: a global suppression of proliferative genes alongside a compensatory upregulation of one-carbon (1C) folate enzymes. 

## 🗂️ Repository Structure

* **`Code/`**: Contains all Python notebooks used for the computational analyses in the manuscript.
* **`Raw Data.zip`**: A compressed directory containing the datasets, clinical metadata, and output assets necessary to reproduce the findings of this study.

## 💻 Computational Analyses Included

The Python scripts and notebooks in this repository cover the following methodologies detailed in the study:

* **Transcriptomics Expression Analysis**: Processing of normalized mRNA expression datasets and calculation of composite OCM signature scores using Z-score normalization.
* **Principal Component Analysis (PCA)**: Dimensionality reduction techniques applied to the 64-gene OCM signature to distinguish between biological subtypes.
* **Driver Gene Analysis**: Evaluation of somatic mutation data for TP53, ATRX, and TERT in relation to the OCM signature.
* **Survival and Prognostic Analysis**: Implementation of Kaplan-Meier methods and univariate/bivariate Cox proportional hazards regression models to assess the clinical relevance of the OCM signature.
* **Tumor Microenvironment Analysis**: Integration with CIBERSORTx deconvolution methods to estimate the relative fractions of 22 distinct human hematopoietic cell phenotypes and correlate them with the OCM signature.

## 👥 Authors and Affiliations
* **Mayank Bajaj**
* **Roy Karnati***

*Translational Biology Laboratory, Department of Animal Biology, School of Life Sciences, University of Hyderabad, Hyderabad – 500046, Telangana, India*.

## 🚀 Getting Started

1.  Clone this repository to your local machine:
    `git clone https://github.com/mayankbajaj17/OCM-Divergence.git`
2.  Unzip the `Raw Data.zip` file to access the underlying expression matrices and generated figures.
3.  Open the scripts within the `Code/` directory using Jupyter Notebook, Google Colab, or your preferred Python IDE to review or rerun the analyses.
