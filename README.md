# Project Title

## Toxic Comment Classification Using Machine Learning

# Project Description

This project builds a machine learning system to automatically detect toxic comments in online platforms.

The system classifies comments into multiple categories:
- Toxic
- Severe Toxic
- Obscene
- Threat
- Insult
- Identity Hate

# Problem Statement

Manual moderation of online comments is time-consuming and inefficient.
This project aims to automate toxicity detection using NLP and machine learning techniques.

# Dataset

We used the Jigsaw Toxic Comment Classification dataset.
Input: Comment text  
Output: Multi-label toxicity categories

# Pipeline Steps

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Extraction using TF-IDF
4. Model Training (Multiple ML models)
5. Model Evaluation & Comparison
6. Prediction System

# Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- KNN

# Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score (Main metric due to imbalance)

# Key Insight
The dataset is highly imbalanced, so F1-score (macro) is more reliable than accuracy.

# How to Run the Project

1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Run preprocessing and training notebooks
4. Run prediction script or Gradio app

# Conclusion

This project successfully built an NLP-based system to detect toxic comments using machine learning models. After preprocessing the text and applying TF-IDF, different models were trained and evaluated to classify multiple toxicity labels.
The results showed that ML models like SVM and Logistic Regression can effectively identify harmful content and help improve online safety through automatic moderation

   




