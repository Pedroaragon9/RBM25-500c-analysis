# RBM25 - 500c Analysis

This repository contains the R code and data analysis pipeline for the RBM25 - 500c project. The analysis includes proteomics data processing, statistical analysis, and visualizations.

## Key Packages and References

This analysis primarily relies on the following R packages:

- **QFeatures**: For managing and analyzing mass spectrometry-based proteomics data in a multi-assay format.  
  **Reference**: Gatto, Laurent, and Christophe Vanderaa. 2023. “QFeatures: Quantitative Features for Mass Spectrometry Data.”

- **MsCoreUtils**: Provides core utilities for mass spectrometry data processing, supporting data wrangling and transformations.  
  **Reference**: Rainer J, Vicini A, Salzer L, Stanstrup J, Badia J, Neumann S, Stravs M, Verri Hernandes V, Gatto L, Gibb S, Witting M. 2022. “A Modular and Expandable Ecosystem for Metabolomics Data Annotation in R.” *Metabolites*, 12, 173.

- **msqrob2**: For statistical analysis and modeling of quantitative proteomics data, allowing robust differential expression testing.  
  **Reference**: Sticker, A., L. Goeminne, L. Martens, and L. Clement. 2020. “Robust Summarization and Inference in Proteome-wide Label-free Quantification.” *Mol Cell Proteomics* 19 (7): 1209–19.

## Figures

Output figures generated from the analysis can be found in the `Figures` folder of this repository.

## Raw Data and Quantitative tables
All mass spectrometry-based proteomics data files and quantitative tables have been deposited to the MassIVE repository under the dataset identifier `MSV000097482` and are available via the ProteomeXchange Consortium with the identifier `PXD062478`.
