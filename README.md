# 🫀 Heart Disease (CAD) Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting Coronary Artery Disease (CAD) using a structured machine learning pipeline. The objective is to leverage clinical data to identify potential heart disease risks and build a reliable predictive model.

The project combines data preprocessing, handling class imbalance, model training, and explainability techniques to ensure both performance and interpretability.

---

## 🧠 Methodology

The workflow followed in this project:

* Data loading and preprocessing using Pandas and NumPy
* Exploratory data analysis and visualization using Matplotlib and Seaborn
* Handling class imbalance using SMOTE (Synthetic Minority Oversampling Technique)
* Feature scaling using standard scaling techniques
* Splitting dataset into training and testing sets
* Model training using multiple machine learning algorithms
* Model evaluation using classification metrics and ROC-AUC analysis
* Model explainability using SHAP (SHapley Additive Explanations)
* Model persistence using Joblib

---

## 🤖 Models Used

* LightGBM Classifier
* XGBoost Classifier
* Additional baseline models from Scikit-learn

These models were trained and evaluated to compare performance and identify the most effective approach for CAD prediction.

---

## 📊 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)
* ROC Curve and AUC Score

These metrics provide a comprehensive understanding of model performance, especially for imbalanced datasets.

---

## 📊 Results

### Model Comparison
![Model Comparison](images/model_comparison.png)

### Confusion Matrices
![Confusion Matrices](images/confusion_matrices.png)

### SHAP Summary Plot
![SHAP Summary](images/shap_summary.png)

## 🔍 Explainability

To improve model transparency, SHAP was used to:

* Understand feature importance
* Analyze how individual features contribute to predictions
* Provide interpretability for model decisions

This is particularly important in healthcare-related applications.

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* LightGBM
* XGBoost
* Imbalanced-learn (SMOTE)
* SHAP
* Joblib

---

## 📁 Project Structure

Heart-Disease-CAD-Prediction-using-Machine-Learning/
│── CAD-hybrid-model.ipynb
│── requirements.txt
│── README.md
│── images/
      ├── roc_curve.png
      ├── confusion_matrix.png
      ├── shap_summary.png

---

## ▶️ How to Run

1. Clone the repository:

   ```
   git clone https://github.com/your-username/Heart-Disease-CAD-Prediction-using-Machine-Learning.git
   ```

2. Navigate to the project folder:

   ```
   cd Heart-Disease-CAD-Prediction-using-Machine-Learning
   ```

3. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Run the notebook:

   ```
   jupyter notebook CAD-hybrid-model.ipynb
   ```

---

## 📌 Key Highlights

* End-to-end machine learning pipeline
* Proper handling of imbalanced data using SMOTE
* Use of advanced boosting models (LightGBM, XGBoost)
* Model interpretability using SHAP
* Clean and reproducible workflow

---

## 🚀 Future Improvements

* Hyperparameter tuning for improved performance
* Deployment using Flask or Streamlit
* Integration with real-world clinical datasets

---

## 👩‍💻 Author

Aastha Sharma
