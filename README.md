# Regenerating the README file and saving it for download

readme_content = """
# 🧠 Breast Cancer Diagnosis using Logistic Regression

This project demonstrates a simple yet powerful binary classification using **Logistic Regression** on the Breast Cancer Wisconsin dataset.

## 🚀 Project Steps

1. **Dataset**: Breast Cancer Diagnostic data (binary target: Malignant or Benign)
2. **Preprocessing**:
   - Dropped unused columns
   - Encoded labels (M=1, B=0)
   - Standardized features
3. **Model**: Logistic Regression (Scikit-learn)
4. **Evaluation**:
   - Confusion Matrix
   - Precision: 97.5%
   - Recall: 92.9%
   - ROC AUC: 0.996 ✅

## 🎯 Insights

- High **ROC-AUC** shows excellent classification ability.
- Tuned thresholds to balance **precision and recall**.
- Logistic Regression gives interpretable probability outputs using the **sigmoid function**.

---

> A quick and clean example of how simple models can be both effective and interpretable.

## 📁 How to Run

```bash
pip install -r requirements.txt
python main.py
