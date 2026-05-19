Customer Churn Prediction

This project uses Machine Learning techniques to predict customer churn in a telecom company. The main goal is to identify customers who are likely to leave the service so that companies can take preventive actions.

#Project Overview

Customer churn prediction is one of the most important business problems in the telecom industry. In this project:

Data preprocessing and cleaning were performed
Missing values were handled using KNN Imputer
Categorical features were encoded
Data imbalance was handled using SMOTE
Features were scaled using StandardScaler
Multiple Machine Learning models were trained and evaluated
The project compares the performance of:

Logistic Regression
Random Forest Classifier
#Technologies Used

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Imbalanced-learn (SMOTE)
Jupyter Notebook
#Dataset

Dataset Used: Telco Customer Churn Dataset

The dataset contains customer information such as:

Gender
Senior Citizen
Internet Service
Contract Type
Monthly Charges
Total Charges
Tenure
Churn Status
#Workflow

Data Preprocessing
Converted TotalCharges column into numeric values
Handled missing values using KNN Imputer
Removed unnecessary columns like customerID
Feature Engineering
Label Encoding for target variable
One-Hot Encoding for categorical features
Data Splitting
Train-Test Split performed using Scikit-learn
Handling Imbalanced Data
SMOTE was used to balance churn classes
Feature Scaling
StandardScaler used for normalization
Model Training
Models trained:

Logistic Regression
Random Forest Classifier
Model Evaluation
Evaluation metrics used:

Accuracy Score
Confusion Matrix
Classification Report
ROC-AUC Score
Machine Learning Concepts Used
Classification
Data Cleaning
Feature Scaling
Data Imbalance Handling
Model Evaluation
Confusion Matrix
ROC Curve
How to Run the Project
Clone the repository
git clone https://github.com/your-username/your-repository-name.git
Open the project folder
cd your-repository-name
Install required libraries
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn
Run the Jupyter Notebook
jupyter notebook
Future Improvements
Add more advanced ML models
Deploy project using Flask or Streamlit
Improve accuracy using hyperparameter tuning
Add interactive dashboard visualization
Conclusion
This project demonstrates the complete Machine Learning pipeline from preprocessing to model evaluation for predicting telecom customer churn.

It helped in understanding:

Real-world data preprocessing
Class imbalance problems
Machine learning model comparison
Performance evaluation metrics
