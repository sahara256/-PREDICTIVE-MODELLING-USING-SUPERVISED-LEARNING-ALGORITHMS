# -PREDICTIVE-MODELLING-USING-SUPERVISED-LEARNING-ALGORITHMS

This project demonstrates how to use **Supervised Machine Learning Algorithms**—**Linear Regression**, **Logistic Regression**, and **K-Nearest Neighbors (KNN)**—to predict health-related outcomes based on patient data.

### 📊 Dataset

The project uses a medical dataset (`dataset_med.csv`) containing patient details like age, BMI, asthma, hypertension, and cholesterol level.

### 🔍 Objectives

* **Predict BMI** based on a person's age using **Linear Regression**.
* **Predict survival chances** using health parameters like age, BMI, asthma, and hypertension via **Logistic Regression**.
* **Classify cholesterol level** as high or normal using **KNN Classification**.

---

### 🧠 Models Implemented

1. ### **Linear Regression**

   * Target: `bmi` (Body Mass Index)
   * Feature: `age`
   * Evaluation Metrics: Mean Squared Error (MSE), R² Score
   * Also includes a **user input section** to predict BMI based on custom age input.

2. ### **Logistic Regression**

   * Target: `survived` (Binary classification: 0 = No, 1 = Yes)
   * Features: `age`, `bmi`, `asthma`, `hypertension`
   * Evaluation Metric: Accuracy
   * Allows real-time survival prediction from user input.

3. ### **K-Nearest Neighbors (KNN)**

   * Target: `cholesterol_level` (Converted to binary: 0 = Normal, 1 = High)
   * Features: `age`, `bmi`, `asthma`, `hypertension`
   * Evaluation Metric: Accuracy
   * Demonstrates classification performance using real health parameters.

---

### ⚙️ Preprocessing

* **Missing value removal**
* **Duplicate elimination**
* **Feature scaling** using `StandardScaler` and `MinMaxScaler`
* **Train-test splitting** with `train_test_split` (stratified where needed)

---

### 📈 Visualizations

* **Linear Regression Plot**: Compares actual vs. predicted BMI values.

---

### 🧪 Usage

1. Run the scripts in **Google Colab** or a local Jupyter Notebook.
2. Enter user inputs when prompted to test real-time predictions.
3. Modify or extend the features and models for more robust health prediction systems.

---

### 📁 Files Included

* `dataset_med.csv` – Original dataset
* `cleaned_test.csv` – Preprocessed dataset used in classification tasks
* `linear_regression_bmi.py` – Script for BMI prediction
* `logistic_regression_survival.py` – Script for survival classification
* `knn_cholesterol_classifier.py` – Script for cholesterol classification
* `README.md` – Project overview and usage guide

---

### ✅ Tools & Libraries

* Python 3
* Pandas, NumPy
* Matplotlib
* Scikit-learn

---

### 📌 How to Run

Upload the scripts and dataset to Google Colab or your Python IDE and run cell-by-cell. Make sure to adjust the CSV file paths as needed.

