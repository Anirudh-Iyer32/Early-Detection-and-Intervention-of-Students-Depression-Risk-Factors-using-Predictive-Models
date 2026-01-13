# Early Detection and Intervention of Students’ Depression Risk Factors using Predictive Models

## Project Overview
Depression among students is an increasing concern that affects academic performance, emotional well-being, and long-term mental health. This project focuses on the early detection of depression risk factors in students using machine learning-based predictive models to support timely intervention and preventive strategies.

The project follows an end-to-end data science workflow including exploratory data analysis, class imbalance handling, model training, evaluation, and explainable AI techniques to ensure accuracy, robustness, and interpretability.

---

## Objectives
- Perform detailed exploratory data analysis (EDA) to understand data distributions, patterns, and outliers
- Address severe class imbalance using advanced resampling techniques
- Train and compare multiple machine learning models
- Identify important risk factors contributing to depression
- Apply explainable AI methods for transparent model interpretation

---

## Dataset and Preprocessing
- The dataset contains student-related attributes relevant to mental health assessment
- Data preprocessing steps include:
  - Missing value analysis and handling
  - Outlier detection and treatment
  - Distribution and skewness analysis
  - Feature scaling and normalization where required

---

## Exploratory Data Analysis (EDA)
A comprehensive EDA was conducted to:
- Analyze feature distributions
- Detect skewness and anomalies
- Identify outliers
- Examine correlations between variables
- Understand the extent of class imbalance

Visualizations were extensively used to guide preprocessing and modeling decisions.

---

## Class Imbalance Handling
The dataset exhibited significant class imbalance, which could negatively affect model performance.

To address this issue:
- SMOTE-ENN (Synthetic Minority Oversampling Technique combined with Edited Nearest Neighbors) was applied
- This hybrid approach:
  - Generates synthetic samples for minority classes
  - Removes noisy and overlapping samples
  - Improves model generalization and minority class recall

---

## Machine Learning Models
A total of 9 machine learning models were trained and evaluated to ensure robust comparison.

### Models Used
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting
- XGBoost
- K-Nearest Neighbors
- Decision Tree
- Naive Bayes
- AdaBoost

---

## Model Evaluation
Model performance was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Greater emphasis was placed on recall and F1-score due to the sensitivity of mental health prediction tasks.

---

## Explainable AI (XAI) using SHAP
To improve transparency and trust:
- SHAP (SHapley Additive exPlanations) was used for interpretability
- Important features influencing depression risk predictions were identified
- Both global and local explanations were analyzed

This ensures predictions are explainable and clinically meaningful.

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- SHAP

---

## Key Highlights
- End-to-end machine learning pipeline
- Advanced class balancing using SMOTE-ENN
- Comparative analysis of 10 machine learning models
- Strong focus on explainable AI and interpretability
- Suitable for early mental health risk screening systems

---

## Future Scope
- Integration with web or mobile-based applications
- Implementation of deep learning approaches
- Real-time depression risk monitoring
- Deployment as an early warning mental health system

---

## Disclaimer
This project is intended strictly for academic and research purposes.  
It is not a substitute for professional medical or psychological diagnosis or treatment.
