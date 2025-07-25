# Comparative Analysis of ML Models for Tumor Classification

## Project Overview
This project compares the performance of SVM, Decision Trees, and Neural Networks for classifying tumors as benign or malignant using features from cell nuclei images. Includes dimensionality reduction with PCA.

## Key Features
- Exploratory Data Analysis (EDA) and preprocessing
- PCA implementation and variance analysis
- Hyperparameter optimization for three ML models
- Performance comparison (accuracy, precision, recall, F1-score)
- Impact assessment of dimensionality reduction

### Data Characteristics
- **Dataset**: 569 samples with 30 features + diagnosis
- **Class Distribution**: 
  - Benign (B): 357 cases (62.7%)
  - Malignant (M): 212 cases (37.3%)
- **Top Predictive Features**:
  1. concave_points_worst (0.79 correlation)
  2. perimeter_worst (0.78)
  3. concave_points_mean (0.78)

### Important Findings
- Significant class imbalance requiring special handling
- Many features show high multicollinearity
- Features related to cell nucleus shape are most predictive
- No missing values after initial cleaning

## Technologies Used
- Python
- Scikit-learn
- TensorFlow/Keras (for Neural Network)
- Pandas, NumPy
- Matplotlib/Seaborn for visualization

## How to Use
1. Clone the repository
2. Open the Jupyter notebook in Google Colab (recommended)
3. Run cells sequentially (ensure all dependencies are installed)

## Future Work
- Implement PCA for dimensionality reduction
- Build and compare classification models (SVM, Random Forest, NN)
- Address class imbalance techniques
- Hyperparameter tuning

## Dataset Reference
Wisconsin Breast Cancer Diagnostic Dataset (available in scikit-learn)

## Contributors
- Eeman Ahmed 
- Warda Sheikh
