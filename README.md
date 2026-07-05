# Creative4
# AI & ML Task 4: Classification and Evaluation Pipeline

This repository contains a production-ready implementation of a binary classification framework using the Scikit-Learn Breast Cancer dataset. The objective of this task is to evaluate model stability, interpretability, and performance metrics in high-stakes environments.

## 🚀 Key Learning Outcomes Delivered
* Solved binary classification problems using robust statistical models.
* Evaluated standard matrices beyond simple accuracy (Confusion Matrix, Precision, Recall, F1-Score).
* Visualized structural performance using ROC curves and area calculation (AUC score).
* Addressed real-world class imbalances explicitly using cost-sensitive learning metrics.

## 📁 Repository Deliverables
1. **`AI_ML_Task4_Classification_Evaluation.ipynb`**: Complete Jupyter Notebook containing end-to-end Python implementation code (Data scaling, Logistic Regression baseline, Balanced Classifier handling, and Decision Tree comparison).
2. **`Evaluation_Report.pdf`**: A comprehensive analytical document discussing technical metric selection rationale, imbalance strategies, and final model architecture conclusions.

## 🛠️ Tools & Libraries Used
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Frameworks:** Scikit-Learn, Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

## 📊 Quick Summary of Metrics & Rationale
In high-risk medical diagnostics (such as classifying malignant vs. benign tumors), **Recall (Sensitivity)** is prioritized over raw accuracy. A high recall ensures that False Negatives are minimized, meaning a sick patient is rarely misdiagnosed as healthy. 

To offset performance degradation when handling data imbalances, the pipeline utilizes **Class Weight Optimization** within a Logistic Regression baseline to maintain high model stability and interpretability.

---
*Completed as part of Internship Task 4 assignment criteria.*
