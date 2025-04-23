# Diabetes Prediction Based on Health Data

This project focuses on predicting the likelihood of diabetes using machine learning techniques. It covers the entire data science pipeline — from data preprocessing and visualization to model training and evaluation — to provide accurate predictions from medical records.

## Project Structure

```
├── data/                   # Raw and processed datasets
├── notebooks/              # Jupyter notebooks for EDA and modeling
├── src/                    # Source code modules
├── requirements.txt        # Dependencies
├── README.md               # Project overview
```

## Dataset and Analytics

The dataset includes the following health-related features:
- `Gender`
- `Age`
- `Hypertension`
- `Heart Disease`
- `Smoking History`
- `BMI`
- `HbA1c Level`
- `Blood Glucose Level`
- `Diabetes (target variable)`

Key analytics steps:
- Cleaning and handling of missing values  
- Exploratory Data Analysis (EDA) with plots and correlations  
- Outlier detection and feature distribution analysis  
- Scaling and transformation for model input

These steps helped identify important predictors like **Glucose**, **BMI**, and **Age**, while improving model performance through thoughtful preprocessing.

## Model Overview

We used **CatBoostClassifier**, a powerful gradient boosting algorithm known for its performance on tabular data.

**Model Highlights**:
- Trained with 1500 iterations, a learning rate of 0.01, and depth of 7
- Balanced class distribution using **SMOTE**
- Scaled features before model training
- Visual evaluation using built-in training plots

**Performance Evaluation**:
- Confusion Matrix  
- Accuracy  
- Precision, Recall, and F1-score

## Key Results & Insights

- **Test Accuracy**: 97.23%  
- **Training Accuracy (Cross-validated)**: 97.19%
- **Class 0 (Non-diabetic)**: High recall and precision (~1.00)
- **Class 1 (Diabetic)**: Slightly lower recall (~0.67), room for improvement
- Class imbalance was mitigated using resampling, improving detection of minority class
- Overall results show strong generalization with minimal overfitting

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Sevak-Grigoryan/Diabetes-Analysis-and-Prediction.git
cd diabetes-prediction
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebooks or scripts to reproduce the results and visualize model performance.

## Conclusion

This project demonstrates how machine learning and structured data analysis can assist in **early diabetes detection**. Using CatBoost, we achieved high accuracy and balanced performance across classes, highlighting the model’s potential for real-world healthcare applications.
```

You can copy this entire block directly into your `README.md` file. The markdown includes:
- Proper headers and section organization
- Code blocks for directory structure and bash commands
- Bold/italic formatting for emphasis
- Consistent bullet point styling
- All the technical details from your original request
