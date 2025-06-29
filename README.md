# Predicting Employee Retention – Logistic Regression

## 🎯 Objective
The objective of this project is to build a logistic regression model to predict whether an employee is likely to stay or leave a mid-sized technology company. The aim is to provide the HR department with actionable insights that can guide retention strategies and improve workforce stability.

---

## 📁 Files Included

| File Name                                  | Description |
|-------------------------------------------|-------------|
| `Predicting_Employee_Retention_Starter.ipynb` | Final Jupyter notebook containing complete analysis, model building, evaluation, and visualization steps. |
| `Predicting_Employee_Retention_Starter.pdf`   | Business-style report summarizing the methodology, results, and HR recommendations. |
| `README.md` | This file – overview of project, instructions, and details. |

---

## ⚙️ How to Run This Notebook

1. Clone or download this repository.
2. Open the `.ipynb` file in Jupyter Notebook, VS Code (with Python extension), or Google Colab.
3. Run all cells sequentially to reproduce results.
4. The dataset used was preloaded as part of the assignment; no external files are required.

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
**Date of Submission:** June 28, 2025  
**Course:** Executive Diploma in Data Science & AI – IIIT Bangalore / upGrad
