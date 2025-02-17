# Machine Learning Project: Diabetes Prediction

## Overview
This project aims to predict diabetes using machine learning techniques. The dataset used is the Pima Indians Diabetes Dataset, which contains medical data related to diabetes diagnostics. The project includes data preprocessing, model training, hyperparameter tuning, and evaluation using multiple machine learning models.

## Features
- **Data Preprocessing**: Handling missing values, outlier removal, and feature transformation.
- **Exploratory Data Analysis (EDA)**: Visualizations using Seaborn and Matplotlib.
- **Model Training**: Using Support Vector Machine (SVM), Random Forest Classifier, and Logistic Regression.
- **Hyperparameter Tuning**: Optimized using RandomizedSearchCV.
- **Performance Evaluation**: Accuracy, confusion matrices, and classification reports.
- **Model Serialization**: Saving best models for future predictions.

## Installation
To run this project, ensure you have Python installed. Install the required dependencies using:
```bash
pip install -r requirements.txt
```

## Dataset
The dataset is assumed to be stored in `diabetes.csv` and should contain the following features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (Target variable)

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```
2. Run the script:
   ```bash
   python mlprj2.py
   ```
3. The best models will be saved as `.pkl` files, and evaluation metrics will be displayed.

## Results
After training, the models are evaluated on test data. The best hyperparameters are chosen using cross-validation, and accuracy is reported for each model.

## Visualizations
- Pairplot to visualize feature relationships.
- Heatmap to analyze feature correlation.
- Boxplot to observe outliers before and after cleaning.
- Confusion matrices for each model.


