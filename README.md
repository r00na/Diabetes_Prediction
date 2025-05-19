#  Machine Learning Project: Diabetes Prediction 🩺

## 🔍 Overview

This project aims to **predict diabetes** using machine learning techniques. The dataset contains medical data related to diabetes diagnostics. The project covers **data preprocessing, model training, hyperparameter tuning, and performance evaluation** using multiple machine learning models.


## 📂 Dataset

The dataset is assumed to be stored in `diabetes.csv` and includes the following features:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age
* Outcome (target variable)

  
## ⚙ Features

* **🔧 Data Preprocessing**
  Handling missing values, outlier removal, and feature transformation.
* **📈 Exploratory Data Analysis (EDA)**
  Visualizations using Seaborn and Matplotlib to better understand the data.
* **🤖 Model Training**
  Training models using:

  * Support Vector Machine (SVM)
  * Random Forest Classifier
  * Logistic Regression
* **🔍 Hyperparameter Tuning**
  Optimized using `RandomizedSearchCV` for best performance.
* **📊 Performance Evaluation**
  Evaluating models with accuracy, confusion matrices, and classification reports.
* **💾 Model Serialization**
  Saving the best models as `.pkl` files for future use.


## 📊 Results

After training, models are evaluated on the test data. The best hyperparameters are selected using cross-validation, and accuracy scores are reported for each model.


## 📉 Visualizations

*  **Pairplot** to visualize feature relationships.
*  **Heatmap** to analyze feature correlations.
*  **Boxplot** to detect outliers before and after cleaning.
*  **Confusion Matrices** for comparing model performance.

## 🛠️ Installation

Make sure you have Python installed. Then install the required dependencies by running:

```bash
pip install -r requirements.txt
```
