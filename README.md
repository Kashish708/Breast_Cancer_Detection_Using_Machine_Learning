#  Breast Cancer Prediction using Machine Learning

##  Overview

Breast cancer is one of the most common types of cancer affecting women worldwide. Early detection plays a crucial role in improving survival rates and treatment outcomes.

This project develops a Machine Learning model to classify breast tumors as **Malignant (Cancerous)** or **Benign (Non-Cancerous)** using diagnostic features extracted from breast mass images. The model is trained and evaluated on the Breast Cancer Wisconsin Diagnostic Dataset using Logistic Regression.

---

##  Objectives

* Analyze breast cancer diagnostic data.
* Perform data preprocessing and feature engineering.
* Train a Machine Learning classification model.
* Evaluate model performance using standard metrics.
* Predict whether a tumor is malignant or benign.

---

##  Dataset Information

The project uses the **Breast Cancer Wisconsin Diagnostic Dataset** containing features computed from digitized images of breast mass cell nuclei.

### Dataset Characteristics

* Total Instances: **569**
* Total Features: **30**
* Target Variable:

  * **M** → Malignant
  * **B** → Benign

### Features Include

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal Dimension

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

##  Project Workflow

### 1. Data Collection

* Load the Breast Cancer Wisconsin Dataset.

### 2. Data Preprocessing

* Handle missing values.
* Remove unnecessary columns.
* Encode categorical labels.

### 3. Exploratory Data Analysis

* Understand data distribution.
* Analyse class balance.
* Visualise important patterns.

### 4. Feature Scaling

* Apply StandardScaler to normalise feature values.

### 5. Model Training

* Split data into training and testing sets.
* Train a Logistic Regression classifier.

### 6. Model Evaluation

* Calculate Accuracy Score.
* Generate Confusion Matrix.
* Evaluate prediction performance.

---

##  Results

The trained Logistic Regression model successfully classifies breast tumours into malignant and benign categories with high accuracy.

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score

---


##  Applications

* Medical Diagnosis Support Systems
* Healthcare Analytics
* Clinical Decision Support
* Early Cancer Detection Research

---

##  Future Enhancements

* Random Forest Classifier
* Support Vector Machine (SVM)
* XGBoost Classifier
* Deep Learning Models
* Streamlit Web Application Deployment
* Hyperparameter Optimisation

---
