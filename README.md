# pdac_project
Detection of Pancreatic Ductal Adenocarcinoma (PDAC) using Urinary Biomarkers and Machine Learning
Project Overview
Pancreatic Ductal Adenocarcinoma (PDAC) is a highly aggressive cancer, with late-stage diagnosis leading to poor prognosis. This project aims to improve early detection of PDAC using urinary biomarkers and machine learning models. Our approach combines multiple machine learning techniques to analyze urinary biomarker data for early-stage detection.

Problem Statement
PDAC's lack of early symptoms often leads to delayed diagnosis, with a 5-year survival rate of approximately 9%. Current diagnostic methods are invasive and not ideal for early detection. We propose a non-invasive diagnostic tool using biomarkers from urine samples and ensemble machine learning models to improve accuracy.

Key Biomarkers
Recent studies have identified a set of urinary biomarkers that can be instrumental in detecting PDAC at an early stage:

LYVE1 (Lymphatic Vessel Endothelial Hyaluronan Receptor 1)
REG1B (Regenerating Islet-Derived 1 Beta)
TFF1 (Trefoil Factor 1)
These biomarkers provide a non-invasive method for detecting PDAC using advanced algorithms.

Methodology
Our approach involves the following steps:

Data Cleaning & Normalization: Preprocessing the data to ensure consistency and to prevent issues like model sensitivity due to varying data scales.
Machine Learning Models: We use an ensemble learning approach, combining several models to improve predictive accuracy. The models used include:
Support Vector Machines (SVM) with Radial Basis Function (RBF) kernel
1D/3D Convolutional Neural Networks (CNNs)
Random Forest
XGBoost
ExtraTree
LightGBM
Ensemble Model Configurations:
3C2 Ensemble Model: Combines 3 models where at least 2 must agree on the classification.
4C3 Ensemble Model: Combines 4 models where at least 3 must agree on the classification.
Correlation Analysis: Computation of correlation matrices between biomarkers and PDAC risk to create binary classifications.
Cross-validation: We use K-fold cross-validation to ensure robust model performance evaluation.
Dataset
The dataset is sourced from PLOS Medicine and consists of 590 samples with various attributes such as patient age, gender, serum creatinine levels, and biomarker concentrations.

Challenges
Small Dataset: Limited data can lead to overfitting, which requires careful model selection.
Biomarker Variability: Differences in biomarker expression across patients can affect model generalizability.
Medical Expertise: As Computer Science students, our knowledge of medical intricacies is limited, which highlights the need for collaboration with healthcare professionals.
Future Directions
Expanding the dataset to improve the robustness of the models.
Fine-tuning the models for better accuracy and generalization.
Validating the results with clinical trials.
Conclusion
Our project shows promising potential for using urinary biomarkers and ensemble machine learning to detect PDAC at an early stage. While challenges remain, ongoing research and collaboration with the medical community could significantly enhance the effectiveness of this approach.


