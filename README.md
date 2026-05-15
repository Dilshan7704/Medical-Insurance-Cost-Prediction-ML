# 🩺 Medical Insurance Cost Prediction ML

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-teal?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

### 🚀 End-to-End Machine Learning Project for Predicting Medical Insurance Charges

Predicting medical insurance costs using **Machine Learning**, **EDA**, **Feature Engineering**, **Regression Models**, and **Hyperparameter Optimization**.

</div>

---

# 📌 Project Overview

This project focuses on building a complete Machine Learning pipeline to predict medical insurance charges based on demographic and health-related features.

The project includes:

✔ Data Cleaning & Preprocessing  
✔ Exploratory Data Analysis (EDA)  
✔ Data Visualization  
✔ Outlier Detection  
✔ Correlation Analysis  
✔ Regression Model Training  
✔ Hyperparameter Tuning  
✔ Log Transformation  
✔ Model Evaluation  
✔ Insurance Cost Prediction System  
✔ Model Serialization using Joblib  

---

# 🗂️ Project Structure

```bash
MEDICAL-INSURANCE-COST-PREDICTION/
│
├── 📁 Data set/
│   └── insurance.csv
│
├── 📁 model/
│   ├── rf_best_pipeline_log.pkl
│   ├── x_train.pkl
│   ├── x_test.pkl
│   ├── y_train.pkl
│   └── y_test.pkl
│
├── 📁 src/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   ├── evaluation.ipynb
│   └── prediction.ipynb
│
├── 📄 requirements.txt
├── 📄 .gitignore
└── 📄 README.md
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| XGBoost | Gradient Boosting |
| Joblib | Model Saving & Loading |

---

# 📊 Exploratory Data Analysis (EDA)

Extensive Exploratory Data Analysis was performed to understand the dataset and identify factors affecting insurance costs.

### 🔍 EDA Includes

- Missing Value Analysis
- Duplicate Detection
- Feature Distribution Analysis
- Outlier Detection
- Correlation Analysis
- Pairplot Visualization
- Target Variable Distribution

---

# 📈 Visualizations

The project includes multiple visualizations such as:

✅ Insurance Charges Distribution  
✅ Histogram Distributions  
✅ Boxplots for Outlier Detection  
✅ Correlation Heatmaps  
✅ Pairplots by Smoking Status  
✅ Residual Analysis Plots  

---

# 🧹 Data Preprocessing

The preprocessing pipeline includes:

- Train-Test Splitting
- Standard Scaling
- One-Hot Encoding
- ColumnTransformer Pipeline
- Feature Transformation
- Log Transformation on Target Variable

---

# 🤖 Machine Learning Models

The following regression models were implemented and evaluated:

| Model | Status |
|---|---|
| Linear Regression | ✅ Tested |
| Ridge Regression | ✅ Tested |
| Lasso Regression | ✅ Tested |
| Decision Tree Regressor | ✅ Tested |
| Random Forest Regressor | ✅ Best Performance |
| XGBoost Regressor | ✅ Tested |

---

# 🏆 Best Performing Model

## ✅ Random Forest Regressor

The Random Forest model achieved the best overall performance after hyperparameter tuning and log transformation.

### Techniques Used

- K-Fold Cross Validation
- GridSearchCV
- Hyperparameter Optimization
- Log Transformation
- RMSE-Based Evaluation

---

# 📌 Evaluation Metrics

The models were evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score
- Residual Analysis

---

# 💾 Model Serialization

The trained model was saved using **Joblib** for future predictions.

```python
joblib.dump(rf_best_pipeline_log, "rf_best_pipeline_log.pkl")
```

---

# 🔮 Insurance Cost Prediction System

A custom prediction function was implemented to estimate medical insurance charges based on user input features.

```python
predict_insurance_charges()
```

### Example Prediction

```python
pred = predict_insurance_charges(
    model,
    age=35,
    sex="male",
    bmi=29.5,
    children=2,
    smoker="no",
    region="southeast"
)
```

---

# ▶️ Installation & Usage

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/MEDICAL-INSURANCE-COST-PREDICTION.git
```

---

## 2️⃣ Navigate to Project

```bash
cd MEDICAL-INSURANCE-COST-PREDICTION
```

---

## 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open notebooks from:

```bash
src/
```

---

# 📚 Dataset Information

Dataset used for this project:

🔗 https://www.kaggle.com/datasets/mirichoi0218/insurance

---

# 📌 Dataset Features

| Feature | Description |
|---|---|
| age | Age of primary beneficiary |
| sex | Gender of beneficiary |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Smoking status |
| region | Residential area in the US |
| charges | Medical insurance cost |

---

# 🎯 Target Variable

| Target | Description |
|---|---|
| charges | Medical insurance charges |

---

# 🚀 Future Improvements

Planned future enhancements:

- 🌐 Flask/FastAPI Deployment
- 📊 Streamlit Dashboard
- ☁ Cloud Deployment
- 📱 Interactive Web Application
- 🔍 Advanced Ensemble Models
- ⚡ Real-Time Prediction API

---

# 📷 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
EDA & Visualization
     ↓
Feature Engineering
     ↓
Train/Test Split
     ↓
Preprocessing Pipeline
     ↓
Model Training
     ↓
Hyperparameter Tuning
     ↓
Log Transformation
     ↓
Model Evaluation
     ↓
Insurance Cost Prediction
```

---

# 👨‍💻 Author

## Dilshan Nethmin Wijayarathne

💡 Machine Learning Enthusiast  
💻 Full Stack Developer  
📊 Data Analytics & AI Projects  

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
🛠️ Contribute to improvements  

---

<div align="center">

## 🚀 Thanks for Visiting

### 🩺 Medical Insurance Cost Prediction using Machine Learning

</div>
