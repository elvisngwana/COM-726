Prostate Cancer Early Detection Using Machine Learning
📌 Project Overview

This project investigates the application of machine learning techniques for the early detection of prostate cancer using routinely collected clinical data. Early identification of high-risk individuals is crucial for improving treatment outcomes, reducing mortality, and minimising unnecessary invasive procedures such as biopsies.

The study evaluates and compares the performance of three supervised machine learning algorithms:

Logistic Regression

Random Forest

Support Vector Machine (SVM)

Models are assessed using clinically relevant evaluation metrics to determine their suitability for decision support in prostate cancer screening.


🎯 Objectives

To develop predictive machine learning models for early prostate cancer detection

To compare model performance using standard classification metrics

To analyse false positives and false negatives with clinical interpretation

To identify the most reliable model for supporting early screening decisions


🗂️ Project Structure

├── data/
│   └── prostate_cancer_dataset.csv
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   └── model_evaluation.ipynb
├── src/
│   ├── preprocessing.py
│   ├── logistic_regression.py
│   ├── random_forest.py
│   └── svm.py
├── results/
│   ├── confusion_matrices/
│   ├── roc_curves/
│   └── performance_plots/
├── requirements.txt
├── README.md


🔄 Data Preprocessing

The dataset underwent the following preprocessing steps:

Handling missing values

Feature scaling and normalisation

Encoding of categorical variables

Train–test split to ensure unbiased model evaluation

Class labels:

Class 0: No early indication of prostate cancer

Class 1: Early indication of prostate cancer

🤖 Models Implemented
1. Logistic Regression

A baseline linear model offering high interpretability, making it useful for clinical justification despite moderate predictive performance.

2. Random Forest

An ensemble learning method capable of capturing complex non-linear relationships. This model demonstrated the strongest overall performance in this study.

3. Support Vector Machine (SVM)

A margin-based classifier evaluated for its ability to separate high-risk and low-risk patients, though it showed limitations in sensitivity.



📊 Model Evaluation Metrics

The models were evaluated using:

Accuracy

Precision

Recall (Sensitivity)

F1-Score

ROC AUC Score

Confusion Matrix Analysis

These metrics provide insight into both predictive performance and clinical reliability, particularly the impact of false negatives in early cancer detection.



🏆 Key Findings

Random Forest achieved the highest accuracy and ROC AUC, with the lowest false-negative rate

Logistic Regression offered reasonable performance with strong interpretability

SVM showed reduced sensitivity, making it less suitable for early-risk detection

Overall, Random Forest proved to be the most balanced and clinically applicable model.


⚠️ Ethical Considerations

Patient data confidentiality and privacy were prioritised

Models are intended to support, not replace, clinical decision-making

Bias and fairness considerations were acknowledged during evaluation


🛠️ Technologies Used

Python

Scikit-learn

NumPy

Pandas

Matplotlib

Seaborn


📚 Academic Context

This project was completed as part of a Master’s degree in Artificial Intelligence and Data Science and focuses on healthcare-oriented machine learning applications.

