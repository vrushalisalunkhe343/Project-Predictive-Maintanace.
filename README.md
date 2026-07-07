# 🔧 Predictive Maintenance using Machine Learning

## 📌 Project Overview

This project develops an end-to-end **Predictive Maintenance System** using Machine Learning to predict equipment failures before they occur. The objective is to analyze historical machine sensor data and identify potential equipment failures in advance, helping industries reduce downtime, optimize maintenance schedules, and improve operational efficiency.

The project covers the complete Machine Learning workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, preprocessing, model building, evaluation, and prediction using Scikit-learn Pipelines.

---

## 📂 Dataset

The dataset contains machine sensor readings and operational parameters, including:

- UDI
- Product ID
- Product Type
- Air Temperature [K]
- Process Temperature [K]
- Rotational Speed [RPM]
- Torque [Nm]
- Tool Wear [min]
- Target (Failure / No Failure)
- Failure Type

---

## 🛠️ Data Preprocessing

- Data Cleaning
- Missing Value Checking
- Duplicate Removal
- Data Type Validation
- Outlier Detection using IQR Method
- Outlier Capping using FunctionTransformer
- Feature Engineering
- Train-Test Split
- Feature Scaling using StandardScaler
- One-Hot Encoding for Categorical Features
- ColumnTransformer for automated preprocessing
- End-to-End Scikit-learn Pipeline

---

## 📊 Exploratory Data Analysis (EDA)

Performed detailed EDA to understand the dataset by using:

- Distribution Plots
- Histograms
- Boxplots
- Correlation Heatmap
- Class Distribution Analysis
- Feature Relationship Analysis
- Outlier Detection
- Failure Pattern Analysis

---

## 🤖 Machine Learning Models

The following classification models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier

---

## 📈 Model Performance

| Model | Train Accuracy | Test Accuracy |
|--------|---------------:|--------------:|
| Logistic Regression | 73.25% | 74.18% |
| Decision Tree | 100.00% | 96.91% |
| Random Forest | 100.00% | 97.93% |
| Support Vector Machine | 93.54% | 93.86% |
| **XGBoost** | **99.90%** | **98.26%** ✅ |

**Best Performing Model:** XGBoost Classifier

---

## ⚙️ Machine Learning Pipeline

Implemented an end-to-end Scikit-learn Pipeline consisting of:

- FunctionTransformer (Outlier Capping)
- ColumnTransformer
- StandardScaler
- OneHotEncoder
- XGBoost Classifier

This ensures consistent preprocessing during both training and prediction.

---

## 📉 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🎯 Results

- Developed a complete Predictive Maintenance solution using Machine Learning.
- Built an automated preprocessing pipeline for efficient model training.
- Compared multiple classification algorithms to identify the best-performing model.
- Achieved **98.26% testing accuracy** using the **XGBoost Classifier**.
- Created a scalable and reusable machine learning workflow suitable for real-world industrial predictive maintenance applications.

---

## 📁 Project Structure

```
Predictive-Maintenance/
│
├── Dataset/
│   └── predictive_maintenance.csv
│
├── Notebook/
│   └── predictive_maintenance.ipynb
│
├── Images/
│   └── pipeline.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Model Deployment using Flask/FastAPI
- Real-Time Sensor Data Prediction
- Interactive Dashboard using Power BI or Streamlit
- Cloud Deployment
## 📷 Project Screenshots

### Dataset

<img src="[images/dataset.png](https://github.com/vrushalisalunkhe343/Project-Predictive-Maintanace./blob/main/Screenshot%202026-07-07%20171901.png)" width="1000"/>

### Machine Learning Pipeline

<img src="[images/pipeline.png](https://github.com/vrushalisalunkhe343/Project-Predictive-Maintanace./blob/main/Screenshot%202026-07-07%20172737.png)" width="700"/>

### Model Performance

<img src="[images/model_results.png](https://github.com/vrushalisalunkhe343/Project-Predictive-Maintanace./blob/main/Screenshot%202026-07-07%20172705.png)" width="900"/>
