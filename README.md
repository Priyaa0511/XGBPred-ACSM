  XGBPred-ACSM: A Hybrid Descriptor-Driven XGBoost Framework for Anticancer Small Molecule Prediction

Contents:
XGBPred-ACSM_train & XGBPred-ACSM_test: Train and Test dataset
XGBPred-ACSM_Hybrid_model.ipynb: Codes for model generation

Project Overview
Cancer poses a significant challenge in healthcare due to the lack of specificity in traditional treatments, leading to unwanted side effects. This study, ACSMPred, proposes a machine learning (ML) framework to predict potential anticancer small molecules effectively. Using a curated dataset of 3,600 compounds with IC50 values and various molecular descriptors, we developed several ML models that demonstrated high accuracy in identifying promising anticancer compounds.
Methodology
Data Collection: Collected a dataset of 3,600 compounds with IC50 values targeting various cancers.
Feature Engineering: Generated molecular descriptors using Mordred and PaDEL, focusing on 2D features, fingerprints, and hybrids.
Model Development: Built and evaluated six ML models and a voting ensemble model.
Model Evaluation: Conducted 10-fold cross-validation and used metrics like AUC and accuracy for performance assessment.
Feature Importance Analysis: Leveraged SHAP to understand the significance of each feature in the top-performing XGBoost model.
Requirements
Python
Pandas
Numpy  
![image](https://github.com/user-attachments/assets/95a0f176-34cb-4d5d-adae-8cae74f9b108)
