# Wine Classification Project

This project explores several machine learning techniques applied to the Wine dataset from scikit-learn.

It includes data preprocessing, correlation analysis, classification using KNN, dimensionality reduction (PCA and LDA), and robustness validation using cross-validation.

## Objectives
- Analyze correlations between variables
- Classify wine samples using KNN
- Handle missing data using different imputation techniques
- Apply dimensionality reduction (PCA and LDA)
- Evaluate model robustness with cross-validation

## Technologies
- Python
- scikit-learn
- NumPy
- Pandas
- Matplotlib

## Key Results
- PCA with 2 components reached 100% accuracy
- LDA with 2 components achieved the best performance (~99.4%)
- Cross-validation confirmed the robustness of the models
- Imputation methods influenced final class prediction

## ▶ How to run
```bash
pip install -r requirements.txt
python main.py
