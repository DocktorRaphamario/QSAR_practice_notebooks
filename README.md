# QSAR_practice_notebooks
This repository documents my use of Schrödinger’s AutoQSAR module to develop a predictive QSAR model for estimating the biological activity (pIC₅₀) of a set of ligands. The project demonstrates key steps in data preparation, model training, and validation within the Maestro interface..

Workflow Summary

Dataset Preparation:
Collected and curated molecular structures in .sdf format.
Standardized molecules using LigPrep and ensured correct protonation states.

Descriptor Generation:
Generated molecular descriptors automatically using AutoQSAR’s built-in algorithms.

Model Training & Validation:
Trained regression models through AutoQSAR.
Evaluated performance based on R², Q², and RMSE metrics.

Prediction & Interpretation:
Predicted bioactivity (pIC₅₀) values for novel compounds.
Identified top features influencing model performance.

Tools & Software:
Schrödinger Maestro 2021
AutoQSAR module
DataWarrior (for data cleaning and initial descriptor inspection)
