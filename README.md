# Biomedical Classification (Breast Cancer)

## Objective
Classify breast tumours as malignant or benign using machine learning, and interpret which features drive predictions.

## Key Takeaways
- Built a Random Forest model to classify breast tumours as malignant or benign
- Achieved ~96% accuracy, F1-score ~0.95, ROC-AUC ~0.97
- Most important features: mean radius, mean perimeter, mean concavity
- SHAP analysis shows model decisions are interpretable and clinically relevant

## Dataset
- Breast Cancer dataset from `sklearn.datasets`
- 569 samples, 30 numerical features
- Target: malignant (1) or benign (0)

## Approach
1. **Exploratory Data Analysis (EDA)** – Understand feature distributions and class patterns.
2. **Preprocessing** – Standardize features; optional PCA visualization.
3. **Model Training** – Logistic Regression (baseline) and Random Forest (main model).
4. **Evaluation** – Accuracy, F1-score, ROC-AUC, confusion matrix.
5. **Interpretation** – Random Forest feature importance and SHAP analysis for explainability.
6. **Insights** – Summarised key results and clinical relevance.

## Key Results
- Random Forest Accuracy: ~96%
- F1-Score: ~0.95
- ROC-AUC: ~0.97
- Most important features: mean radius, mean perimeter, mean concavity

## Insights
- Tumour size and shape metrics are the strongest predictors of malignancy.
- SHAP analysis confirms that model decisions are interpretable.
- Clinical relevance: insights could help prioritise patients for further testing.

## Files
- `Biomedical_Classification.ipynb` – Notebook with code, plots, and insights
- Optional: `requirements.txt` – List of Python packages for reproducibility
