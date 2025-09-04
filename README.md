# Project Overview
This repository contains three variations of a Credit Risk Modeling project, built using synthetic datasets to predict loan default probability. Each version demonstrates a different approach while following the complete machine learning lifecycle:
- End-to-End Pipeline (Credit_Risk_End_to_End) → Comprehensive workflow with detailed EDA, feature engineering, multiple ML models, and evaluation.
- Simplified Pipeline (Credit_Risk_Modeling_Simplified) → Concise version retaining essential steps for quicker execution and business storytelling.
- Synthetic Dataset Demo (Credit_Risk_Modeling_Synthetic_Dataset.ipynb) → Educational version built with synthetic dummy data, showcasing a clean workflow with structured EDA and modeling.
This combined approach highlights adaptability in solving the same business problem across technical deep-dive, simplified, and synthetic-data scenarios.

# Workflow Across Versions

# 1. Data Preparation
- Used synthetic financial datasets representing demographics, income, loan history, and credit scores.
- Performed data cleaning, handled missing values, applied encoding and scaling techniques.

# 2. Exploratory Data Analysis (EDA)
- Distribution plots, correlation heatmaps, and customer segmentation.
- Uncovered patterns in high-risk vs. low-risk loan applicants.

# 3. Feature Engineering
- Applied encoding, normalization, and transformation.
- Derived new variables to enhance predictive accuracy.

# 4. Model Development
- Implemented and compared multiple models:
- Logistic Regression
- Random Forest Classifier
- XGBoost
- Tuned hyperparameters for optimization.

# 5. Model Evaluation
Evaluated using:
- Confusion Matrix
- ROC Curve & AUC
- Accuracy, Precision, Recall, F1-score
- Compared models for trade-offs between interpretability and predictive power.

# Results
- End-to-End Pipeline : Strongest project for technical depth and professional showcase.
- Simplified Pipeline : Fast, clean version for business or portfolio review.
- Synthetic Dataset Demo :  Educational workflow that reinforces modeling and EDA skills with dummy data.

# Repository Structure
- Credit_Risk_Modeling_End_to_End.ipynb                 # Detailed ML pipeline with full workflow
- Credit_Risk_Modeling_Simplified.ipynb                 # Concise workflow for clarity
- Credit_Risk_Modeling_Synthetic_Dataset.ipynb          # Synthetic data demo project
- README.md                                             # Combined project documentation

# Key Learning Outcomes
- Built three complementary versions of the same project, tailored for different audiences.
- Demonstrated complete machine learning pipeline: data preparation → EDA → feature engineering → modeling → evaluation.
- Applied synthetic datasets for ethical experimentation and reproducibility.
- Balanced technical rigor, clarity, and educational storytelling.

# Tech Stack
- Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost
