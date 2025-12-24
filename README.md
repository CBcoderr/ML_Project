# ML_Project
CFTR-Variant-ML — Machine-learning pipeline for CFTR variant classification for benign and pathogenic(feature extraction, models: logistic regression &amp; random forest, evaluation: ROC/AUC, confusion matrix)
# CFTR Variant Classification Using Machine Learning

This repository contains a machine-learning pipeline for classifying CFTR (Cystic Fibrosis Transmembrane Conductance Regulator) variants as *pathogenic* or *benign*.  
The project demonstrates a full ML workflow using biological mutation data, including:

- Data cleaning and preprocessing  
- Extracting mutation features from HGVS protein notation  
- Feature engineering (ref amino acid, position, alt amino acid)  
- Model building with scikit-learn  
- Evaluation using confusion matrix and ROC-AUC  

This project was completed as part of my work in computational biology and machine learning.

---
 **Project Overview**
CFTR is a clinically important gene involved in cystic fibrosis.  
ClinVar variant records were processed to extract mutation-level features.  
The notebook implements:

- Regex extraction of mutation patterns (e.g., p.Arg117His → R, 117, H)  
- Encoding features for ML models  
- Training baseline and ensemble models  
- Evaluating performance using standard ML metrics  

---

 **Machine Learning Methods Used**
The project uses the following scikit-learn models and tools:

- Logistic Regression  
- Linear Regression (as a baseline)  
- Random Forest Classifier  
- Hard Voting Classifier  
- Soft Voting Classifier  
- Train/Test Split  
- Confusion Matrix  
- ROC Curve & AUC
- Feature importance
- XGboost
- ADAboost

---
Notes

The raw ClinVar dataset is not included due to licensing and size limits.

The notebook uses mutation fields extracted from CFTR variant records; users may provide their own data.

This project is intended for learning and research purposes only—not clinical use.

