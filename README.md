# 📞 Telco Customer Churn Prediction

An end-to-end Machine Learning project that predicts customer churn in the telecommunications industry using classification algorithms. The project focuses on identifying customers who are likely to discontinue telecom services, enabling businesses to implement proactive customer retention strategies.

---

# 📌 1. Project Title / Headline

## 🤖 Telco Customer Churn Prediction using Machine Learning

A predictive analytics solution that leverages machine learning techniques to classify customers based on their likelihood of churning, helping telecom companies improve customer retention and business performance.

---

# 📖 2. Short Description / Purpose

Customer churn is one of the biggest challenges faced by telecom companies. Acquiring a new customer is significantly more expensive than retaining an existing one.

This project develops a machine learning model that predicts customer churn by analyzing customer demographics, subscription details, service usage, and billing information. The insights generated can help businesses identify at-risk customers and design targeted retention campaigns.

---

# 🛠️ 3. Tech Stack

The project was developed using the following tools and technologies:

- 🐍 **Python**
- 📊 **Pandas**
- 🔢 **NumPy**
- 🤖 **Scikit-learn**
- 📈 **Matplotlib**
- 📉 **Seaborn**
- ⚖️ **Imbalanced-learn (SMOTE)**
- 📓 **Jupyter Notebook**
- 📋 **KNN Imputer**
- 🔄 **StandardScaler**
- 🌳 **Random Forest Classifier**
- 📊 **Logistic Regression**

---

# 📂 4. Dataset

**Dataset Used:** Telco Customer Churn Dataset

The dataset contains customer information including:

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

The data was cleaned, transformed, and prepared before training the machine learning models.

---

# 🚀 5. Project Workflow

### Step 1 – Data Collection

- Imported the Telco Customer Churn dataset.

### Step 2 – Data Preprocessing

- Converted `TotalCharges` into numeric values.
- Removed unnecessary columns.
- Handled missing values using **KNN Imputer**.
- Cleaned inconsistent records.

### Step 3 – Feature Engineering

- Label Encoding for the target variable.
- One-Hot Encoding for categorical features.

### Step 4 – Data Splitting

- Split the dataset into training and testing sets using Scikit-learn.

### Step 5 – Handling Imbalanced Data

- Balanced churn classes using **SMOTE**.

### Step 6 – Feature Scaling

- Applied **StandardScaler** for feature normalization.

### Step 7 – Model Training

Trained multiple Machine Learning models:

- Logistic Regression
- Random Forest Classifier

### Step 8 – Model Evaluation

Evaluated the models using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

---

# 🤖 6. Machine Learning Concepts Used

- Classification
- Data Cleaning
- Missing Value Imputation
- Feature Engineering
- Feature Scaling
- One-Hot Encoding
- Label Encoding
- Handling Imbalanced Data (SMOTE)
- Model Training
- Model Evaluation
- Confusion Matrix
- ROC Curve Analysis

---

# 🎯 7. Business Problem

Telecom companies lose significant revenue when customers discontinue their services.

This project helps identify customers with a high probability of churn, allowing businesses to:

- Improve customer retention
- Reduce churn rate
- Increase customer lifetime value
- Design personalized retention campaigns

---

# 🎯 8. Project Goals

- Predict customer churn accurately.
- Compare multiple machine learning algorithms.
- Handle missing values effectively.
- Solve class imbalance using SMOTE.
- Improve model performance through preprocessing and feature engineering.
- Generate actionable business insights.

---

# 📊 9. Model Performance

Models Compared:

- Logistic Regression
- Random Forest Classifier

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

# 💡 10. Key Insights

- Identified customers with a high likelihood of churn.
- Evaluated the impact of contract type and tenure on churn.
- Analyzed the relationship between monthly charges and customer retention.
- Compared the performance of multiple classification algorithms.
- Generated insights to support customer retention strategies.

---

# 🖼️ 11. Project Preview

Add screenshots of:

- Dataset Overview
- Data Visualization
- Confusion Matrix
- ROC Curve
- Model Comparison Charts

Example:

```markdown
![Project Preview](Images/churn_dashboard.png)
```

---

# ▶️ 12. How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/yourusername/Telco-Customer-Churn-Prediction.git
```

### Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn
```

### Run the Project

1. Open Jupyter Notebook.
2. Execute all notebook cells.
3. Train the machine learning models.
4. Evaluate the model performance.
5. Review the visualizations and predictions.

---

# 📁 13. Project Structure

```
Telco-Customer-Churn-Prediction
│
├── Dataset
├── Jupyter_Notebook
├── Models
├── Images
├── Report
├── README.md
└── requirements.txt
```

---

# 💼 14. Skills Demonstrated

- Data Cleaning
- Missing Value Imputation
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Machine Learning
- Classification Algorithms
- Data Preprocessing
- SMOTE
- Model Evaluation
- ROC Curve Analysis
- Business Problem Solving
- Data Visualization

---

# 🔮 15. Future Improvements

- Hyperparameter Tuning
- XGBoost & LightGBM Implementation
- CatBoost Classifier
- Feature Selection Techniques
- Streamlit Web Application
- Flask API Deployment
- Docker Deployment
- Model Monitoring
- Real-time Prediction System

---

# 🏆 16. Conclusion

This project demonstrates a complete end-to-end Machine Learning workflow, from data preprocessing and feature engineering to model training, evaluation, and business interpretation.

By predicting customer churn accurately, the solution enables telecom companies to proactively retain customers, reduce revenue loss, and improve overall customer satisfaction.

---

# 👨‍💻 17. Author

**Aditya Tarte**

Computer Engineering Student

Aspiring Data Analyst | Machine Learning Engineer

- GitHub: https://github.com/aditya-tart
- LinkedIn: https://www.linkedin.com/in/aditya-tarte-b9a9472b4/

- ## 🖼️ Project Preview

![Telco Customer Churn Prediction](Telco%20Customer%20Churn%20Prediction.png)
