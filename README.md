# Predicting Employee Retention – Logistic Regression

## 🎯 Objective
The objective of this project is to build a logistic regression model to predict whether an employee is likely to stay or leave a mid-sized technology company. The aim is to provide the HR department with actionable insights that can guide retention strategies and improve workforce stability.

---

## 📁 Files Included

> All files are packaged inside the ZIP archive:  
> **`Predicting_Employee_Retention_Umair_Birajdar.zip`**

| File Name                                  | Description |
|-------------------------------------------|-------------|
| `Predicting_Employee_Retention_Starter.ipynb` | Final Jupyter notebook containing complete analysis, model building, evaluation, and visualization steps. |
| `Predicting_Employee_Retention_Starter.pdf`   | Business-style report summarizing the methodology, results, and HR recommendations. |
| `README.md`                                   | This file – overview of project, instructions, and details. |

---

## ⚙️ How to Run This Project

1. **Download the ZIP file** from this repository:  
   [`Predicting_Employee_Retention_Umair_Birajdar.zip`](./Predicting_Employee_Retention_Umair_Birajdar.zip)
2. Extract the contents to your local machine.
3. Open the `.ipynb` file in **Jupyter Notebook**, **VS Code**, or **Google Colab**.
4. Run all cells sequentially to reproduce results.
5. No external dataset is needed — all data was provided as part of the assignment.

---

## 📊 Key Results

- **Validation Accuracy**: 73.78%
- **Recall (Sensitivity)**: 84%
- **Precision**: 71%
- **Optimal Probability Cutoff**: 0.4 (chosen to maximize recall and minimize false negatives)
- **Model Used**: Logistic Regression (via `statsmodels`)
- **Feature Selection**: Recursive Feature Elimination (RFE) to retain 15 most significant features
- **Evaluation Metrics**: Accuracy, Precision, Recall, Specificity, Confusion Matrix, ROC Curve, AUC

---

## 💡 HR Recommendations

Based on model insights, the following 6 strategies are recommended:
1. **Enhance Promotion Opportunities** for long-tenured employees.
2. **Introduce Flexible Work Arrangements**, including remote/hybrid setups.
3. **Improve Work-Life Balance** through wellness programs and flexible hours.
4. **Support High-Level Staff** with mentorship and leadership development.
5. **Reevaluate Role Fit** for highly qualified employees (e.g., PhDs).
6. **Implement Recognition Programs** for long-term employees.

---

## 🧰 Technologies Used

- **Python 3.9**
- pandas, numpy, seaborn, matplotlib
- scikit-learn (for feature selection, scaling, metrics)
- statsmodels (for logistic regression model)
- Google Colab / Jupyter Notebook

---

**Name:** Umair Birajdar  
**Date of Submission:** June 21, 2025  
**Course:** Executive Diploma in Data Science & AI – IIIT Bangalore / upGrad
