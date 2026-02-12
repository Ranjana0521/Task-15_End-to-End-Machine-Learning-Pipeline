##  Breast Cancer Classification using ML Pipeline

### 📌 Project Overview

This project implements an end-to-end **machine learning pipeline** for classifying breast cancer tumors as **benign or malignant** using the **Breast Cancer Dataset from scikit-learn**.

---

###  Tools & Libraries

* Python
* Pandas, NumPy
* Scikit-learn (Pipeline, ColumnTransformer)
* Joblib (model persistence)

---

###  Steps Performed

1. **Loaded Dataset**

   * Imported the Breast Cancer dataset from `sklearn.datasets`.
   * Separated features (`X`) and target variable (`y`).

2. **Feature Identification**

   * Identified numerical and categorical features for preprocessing.

3. **Data Preprocessing**

   * Applied **StandardScaler** to numerical features.
   * Applied **OneHotEncoder** to categorical features using `ColumnTransformer`.

4. **Pipeline Creation**

   * Built a complete ML pipeline combining preprocessing and Logistic Regression.

5. **Train-Test Split**

   * Split data into training and testing sets with stratified sampling.

6. **Model Training & Prediction**

   * Trained the pipeline on training data.
   * Generated predictions on test data.

7. **Model Evaluation**

   * Evaluated performance using Accuracy, Precision, Recall, and F1-score.

8. **Model Persistence**

   * Saved the trained pipeline as a `.pkl` file using Joblib for reuse and deployment.

---

###  Key Highlights

* Prevents data leakage using pipelines
* Production-ready preprocessing and modeling
* Easy model reuse without retraining
