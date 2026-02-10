
# 🩺 Breast Cancer Diagnosis Using Machine Learning

## 📌 Project Overview

This project applies a supervised machine learning classification model to diagnose breast cancer using the Breast Cancer Wisconsin (Diagnostic) Dataset. The model classifies tumors as malignant or benign based on 30 numerical features derived from digitized breast mass images.

The workflow includes k-fold cross-validation, hyperparameter tuning, and final evaluation on a held-out test dataset to ensure robustness and generalizability.

## 📊 Dataset

* **Source:** UCI Machine Learning Repository
* **Total Samples:** 569
* **Features:** 30 numeric tumor characteristics
* **Classes:**

  * Malignant
  * Benign

## 🤖 Model and Validation

* **Algorithm:** Logistic Regression
* **Train–Test Split:** 80% training / 20% testing
* **Validation Method:** K-Fold Cross-Validation
* **Hyperparameter Tuning:** GridSearchCV

---

## 📈 Final Results (Test Dataset)

The model was evaluated on a **test set of 114 samples**.

### 🧪 Classification Report

```text
              precision    recall  f1-score   support

   malignant       0.98      0.98      0.98        42
      benign       0.99      0.99      0.99        72

    accuracy                           0.98       114
   macro avg       0.98      0.98      0.98       114
weighted avg       0.98      0.98      0.98       114
```

### 🔍 Performance Summary

* **Accuracy:** **98%**
* **Precision:**

  * Malignant: 98%
  * Benign: 99%
* **Recall:**

  * Malignant: 98%
  * Benign: 99%
* **F1-Score:**

  * Malignant: 0.98
  * Benign: 0.99
    
 
    **Sensitivity and Specificity**

Sensitivity (Recall): 0.9861111111111112

Specificity: 0.9761904761904762

Malignant as Positive Class (Clinical Interpretation):

Sensitivity: 0.9761904761904762

Specificity: 0.9861111111111112

## 🧠 Interpretation of Results

The model demonstrates excellent diagnostic performance, with very high accuracy and balanced sensitivity and specificity. Only two cases were misclassified, indicating strong reliability for distinguishing between malignant and benign tumors.

## 🛠️ Tools and Libraries

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib / Seaborn
* Jupyter Notebook


## 📌 Key Takeaways

* Machine learning can support highly accurate breast cancer diagnosis
* Cross-validation and hyperparameter tuning improve reliability
* Simple, interpretable models can perform exceptionally well on clean clinical datasets

## 📚 Reference

UCI Machine Learning Repository – Breast Cancer Wisconsin (Diagnostic) Dataset



