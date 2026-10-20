# MD Anderson Cancer Institute: Cancer Diagnosis Using Artificial Neural Networks (ANN)

## Project Overview
This repository contains the end-to-end implementation of an Artificial Neural Network (ANN) built with **TensorFlow (`tf.keras`)** for clinical risk stratification and cancer diagnosis decision support at the **MD Anderson Cancer Institute**.

## Repository Structure
* `MD_Anderson_Cancer_Diagnosis_ANN.ipynb` — Complete Google Colab Jupyter Notebook containing Exploratory Data Analysis (EDA), Preprocessing, Baseline ANN, Feature Engineering, Improved Regularized ANN, and Visualizations.
* `The_Cancer_data_1500_V2.csv` — Dataset containing 1,500 patient records across 8 clinical/lifestyle features and 1 binary target (`Diagnosis`).

## Model Performance Summary (Holdout Test Set, N = 225)
| Evaluation Metric | Baseline ANN (8 Features) | Improved ANN (17 Engineered Features) | Improvement |
| :--- | :--- | :--- | :--- |
| **Accuracy** | 88.89% | **92.00%** | +3.11% |
| **Precision** | 89.19% | **92.21%** | +3.02% |
| **Recall (Sensitivity)** | 79.52% | **85.54%** | +6.02% |
| **F1-Score** | 84.08% | **88.75%** | +4.67% |
| **ROC-AUC** | 93.16% | **94.93%** | +1.77% |

## How to Run
1. Click the **Open in Colab** badge at the top of `MD_Anderson_Cancer_Diagnosis_ANN.ipynb`.
2. Upload `The_Cancer_data_1500_V2.csv` to the Colab Files sidebar.
3. Click **Runtime > Run all**.
