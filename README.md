#  Heart Disease (CAD) Prediction using Machine Learning

##  Overview

This project focuses on predicting Coronary Artery Disease (CAD) using a structured machine learning pipeline. The objective is to leverage clinical data to identify potential heart disease risks and build a reliable predictive model.

The project combines data preprocessing, handling class imbalance, model training, and explainability techniques to ensure both performance and interpretability.

---

##  Methodology

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

##  Models Used

* LightGBM Classifier
* XGBoost Classifier
* Additional baseline models from Scikit-learn

---

##  Evaluation Metrics

The models were evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)
* ROC Curve and AUC Score

---

##  Results

### Model Comparison

![Model Comparison](Heart%20Disease%20(CAD)%20Prediction/images/model_comparison.png)

### Confusion Matrices

![Confusion Matrices](Heart%20Disease%20(CAD)%20Prediction/images/confusion_matrices.png)

### SHAP Summary Plot

![SHAP Summary](Heart%20Disease%20(CAD)%20Prediction/images/shap_summary.png)

---

##  Explainability

To improve model transparency, SHAP was used to:

* Understand feature importance
* Analyze how individual features contribute to predictions
* Provide interpretability for model decisions

---

##  Tech Stack

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

##  Project Structure

```
Heart-Disease-CAD-Prediction-using-Machine-Learning/
│── README.md
│
└── Heart Disease (CAD) Prediction/
      │── CAD-hybrid-model.ipynb
      │── requirements.txt
      │── images/
            │── cad_feature_group.png
            │── confusion_matrices.png
            │── model_comparison.png
            │── shap_importance_bar.png
            │── shap_per_patient.png
            │── shap_summary.png
```

---

##  How to Run

1. Clone the repository:

```
git clone https://github.com/Aastha-Sharma07/Heart-Disease-CAD-Prediction-using-Machine-Learning.git
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

##  Key Highlights

* End-to-end machine learning pipeline
* Proper handling of imbalanced data using SMOTE
* Use of advanced boosting models (LightGBM, XGBoost)
* Model interpretability using SHAP
* Clean and reproducible workflow

---

##  Future Improvements

* Hyperparameter tuning for improved performance
* Deployment using Flask or Streamlit
* Integration with real-world clinical datasets

---

##  Contributors

* Aastha Sharma
* Upma Shukla
* Harsh Pratap Singh Parihar
