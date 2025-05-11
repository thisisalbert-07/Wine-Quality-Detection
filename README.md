# 🍷 Wine Quality Prediction – Machine Learning Notebook

This notebook builds a machine learning pipeline to predict wine quality using the UCI Wine Quality dataset. It includes preprocessing steps, model training, evaluation, and model selection.

---

## 📁 Dataset

- **Source:** UCI Machine Learning Repository
- **File used:** `winequality.csv`
- **Target variable:** `quality` (integer score from 3 to 9)

---

## ⚙️ Preprocessing

The following preprocessing steps are applied:

1. **StandardScaler** – Standardizes features to have zero mean and unit variance.
2. **SMOTE (Synthetic Minority Oversampling Technique)** – Balances class distribution by generating synthetic samples.
3. **PCA (Principal Component Analysis)** – Reduces dimensionality while retaining 90% of the variance.

---

## 🤖 Model Training & Selection

Multiple machine learning models are trained and evaluated using accuracy scores:

- Logistic Regression  
- Random Forest  
- Support Vector Machine  
- Gradient Boosting  
- K-Nearest Neighbors  
- Decision Tree  

The best-performing model is selected based on test accuracy after applying the full preprocessing pipeline.

---

## 📈 Evaluation

- Accuracy metrics are used for comparison.
- The notebook prints out model performance and selects the highest-scoring model.

---

## 🧪 Usage

To run the notebook:

1. Install required packages:  
   ```
   pip install pandas scikit-learn imbalanced-learn
   ```

2. Open and run `wine.ipynb` in Jupyter or VS Code.

---

## 📬 Output

- Displays the best model and its accuracy score.
- Predicts whether a wine sample is likely of good or bad quality.

---

