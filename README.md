# Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning techniques on an imbalanced financial dataset.

# Project Overview

Credit card fraud is a major issue in the financial sector. This project builds and compares multiple machine learning models to identify suspicious transactions and improve fraud detection performance.

The system analyzes transaction patterns and classifies them as:
- **0 → Normal Transaction**
- **1 → Fraudulent Transaction**

Due to the highly imbalanced nature of the dataset, class weighting was applied and models were evaluated using **recall** and **ROC-AUC** rather than relying only on accuracy.

##  Key Features

- Built and trained multiple ML models:
  - Logistic Regression (baseline)
  - Random Forest Classifier (improved model)
- Handled imbalanced dataset using class weighting
- Compared models using:
  - Accuracy
  - Precision
  - Recall
  - ROC-AUC (industry-level metric)
- Visualized:
  - Fraud vs Normal transactions
  - Model performance comparison (bar charts)
- Generated a structured **metrics comparison table**

## Tech Stack Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  


## Results & Analysis

- Random Forest outperformed Logistic Regression in detecting fraudulent transactions  
- ROC-AUC was used for reliable evaluation due to class imbalance  
- Visual and tabular comparisons were used to analyze model performance  


## Dataset

The dataset is sourced from Kaggle and contains anonymized credit card transactions.

## Output Screenshots:

Fraud vs Normal graph

Pie Chart:

<img width="434" height="411" alt="download" src="https://github.com/user-attachments/assets/f29e544b-7302-4ba9-8b82-639b8045e499" />

Log Scale Graph:

<img width="570" height="491" alt="download" src="https://github.com/user-attachments/assets/d9208100-12ba-4144-a684-329ff1997770" />

Percentage Graph:

<img width="571" height="491" alt="download" src="https://github.com/user-attachments/assets/bb8fc5fc-6f8b-4aab-b365-9f07ffecf0fe" />

Model Comparison:

<img width="547" height="435" alt="download" src="https://github.com/user-attachments/assets/59e817d6-91a4-46d8-8cf7-2c5539c3322b" />

Metrics Comaprision Matrix:

<img width="1482" height="240" alt="Screenshot 2026-03-17 102627" src="https://github.com/user-attachments/assets/d6d6a73c-fd7b-45e6-b865-8ab568497bdc" />

## Key Learning:
- Importance of handling imbalanced datasets
- Why accuracy alone is not sufficient in fraud detection
- Practical application of machine learning in fintech

## Future Improvements: 
- Deploy as a web application using Streamlit
- Use advanced models like XGBoost
- Real-time fraud detection system

## Conclusion
This project demonstrates how machine learning can be applied to detect fraudulent financial transactions and highlights the importance of proper evaluation metrics in real-world scenarios.

## Author
Meher
