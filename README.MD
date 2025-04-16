# Diabetes Prediction Based on Health Data

This project focuses on predicting the likelihood of diabetes using machine learning techniques. It involves end-to-end data analytics — from preprocessing and feature exploration to model training and evaluation — to generate accurate predictions from medical records.

##  Project Structure

```
├── data/                   
├── notebooks/              
├── src/                    
├── requirements.txt       
├── README.md               
```

##  Dataset and Analytics

The dataset includes health-related features such as:
- `Gender`
- `Age`
- `Hypertension`
- `Heart Disease`
- `Smoking History`
- `BMI`
- `HbA1c Level`
- `Blood Glucose Level`
- `Diabetes (target)`


I conducted comprehensive **data analytics**, including:

- Data cleaning and handling of missing values  
- Exploratory Data Analysis (EDA) with visualizations  
- Feature correlation and distribution analysis  
- Scaling and transformation for model-readiness

This process helped identify key predictors (e.g., **Glucose** and **BMI**), remove outliers, and improve model performance through informed preprocessing.

## Model Overview

A **Random Forest Classifier** was used to train and evaluate the model on the processed dataset. Evaluation was performed using:

- Confusion Matrix  
- Accuracy  
- Precision, Recall, and F1-score

## Key Results & Insights

- The model achieved strong predictive performance on both training and test data  
- The most impactful features for prediction were **Glucose**, **BMI**, and **Age**  
- The confusion matrix revealed good balance between sensitivity and specificity  
- Slight differences between training and test performance indicated minor overfitting, but results remained stable and generalizable

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Sevak-Grigoryan/Diabetes-Analysis-and-Prediction.git
cd diabetes-prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch the Jupyter notebook or run Python scripts to reproduce the analysis and prediction results.

## Conclusion

This project shows how structured data analytics and machine learning can help in **early detection of diabetes**. The analytical workflow and trained model together provide valuable insights into how health metrics affect diabetes risk.
