# Personal-Loan-Conversion-Prediction
Targeted Marketing Optimization for Retail Banking

## Business Problem

AllLife Bank has a large base of liability customers (depositors) but a relatively small number of asset customers (borrowers). While a previous marketing campaign achieved a conversion rate of approximately 9%, bank leadership aims to improve this performance by targeting customers who are most likely to accept a personal loan offer.

The objective of this project is to build a predictive model that identifies liability customers with a high probability of purchasing a personal loan. These insights are intended to help the marketing team design more efficient, data-driven campaigns that increase loan adoption while minimizing unnecessary outreach.

---

## Forensic Research & Key Insights

Exploratory analysis revealed several customer attributes that strongly influence loan acceptance:

- **Income and credit card spending** are the strongest predictors of loan purchase, indicating that financially active customers are more receptive to loan offers.
- **Education level** shows a meaningful relationship with loan acceptance, with customers holding graduate or professional degrees converting at higher rates.
- **CD account ownership** is a strong signal of financial engagement and correlates with higher loan uptake.
- **Age and experience** exhibit non-linear effects, suggesting that mid-career customers represent a key target segment.
- ZIP code provided little predictive value and was excluded from modeling to avoid noise and overfitting.

These findings informed both feature selection and segmentation strategy for modeling.

---

## Modeling & Evaluation

Multiple classification models were evaluated to predict personal loan acceptance, with performance assessed using metrics appropriate for imbalanced classification, including accuracy, precision, recall, and ROC-AUC.

The final model balances interpretability and predictive performance, allowing stakeholders to understand which customer attributes drive conversion while still achieving strong classification results.

---

## Business Recommendations

- **Target high-income, high-spend customers** with personalized loan offers to maximize conversion probability.
- **Leverage CD account holders** as a priority segment for cross-selling personal loans.
- **Incorporate education level into marketing segmentation** to refine outreach strategies.
- **Reduce blanket campaigns** and focus on probability-based targeting to improve ROI.
- Use model outputs to support **ranked customer lists** rather than binary decisions.

---

## Repository Structure

- `AIML_ML_Project_full_code_notebook.ipynb`  
  End-to-end analysis including EDA, feature engineering, model training, evaluation, and insights.

---

## Tools & Technologies

- Python
- pandas, NumPy
- scikit-learn
- Jupyter Notebook

