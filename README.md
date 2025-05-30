# Adult Income Classification

This project predicts whether a person's income exceeds \$50K/year based on census data from the UCI Adult dataset. The goal is to build and compare multiple classification models and evaluate them using various performance metrics—not just accuracy, but also precision, recall, F1-score, and AUC—to ensure fairness in the presence of class imbalance.

## Objective

To develop a robust machine learning pipeline that classifies individuals’ income levels using demographic, educational, and occupational features. The project also emphasizes the importance of going beyond accuracy to evaluate model performance.

---

## Files

- `Harnika_Pendyala_Adult_Income_Classification_Report.docx` – Detailed report including EDA, model comparison, and conclusions.
- `HarnikaPendyala_Income_Classification_Code.ipynb` – Full code for data preprocessing, PCA, and model training/evaluation.

---

## Techniques Used

- Data Cleaning & Preprocessing
- Principal Component Analysis (PCA)
- Train-test split
- Standardization
- Model Training with:
  - Logistic Regression
  - Naïve Bayes
  - Linear Discriminant Analysis (LDA)
  - Quadratic Discriminant Analysis (QDA)
  - K-Nearest Neighbors (KNN)

---

## Evaluation Metrics

Each model was evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- AUC (Area Under ROC Curve)  
- Confusion Matrix

This ensured a comprehensive comparison and avoided misleading results from relying on accuracy alone, especially in the presence of imbalanced classes.

---

## Key Insights

- PCA helped reduce dimensionality without losing significant variance.
- LDA and Logistic Regression performed well in terms of both AUC and F1-score.
- Models were compared with a focus on practical deployment, not just raw accuracy.

---

## Tools Used

- Python
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

---

## Author

**Harnika Pendyala**  
Graduate Student – Data Science | University of Memphis  
