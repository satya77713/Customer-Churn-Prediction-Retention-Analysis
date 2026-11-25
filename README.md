# Customer Churn Prediction & Retention Analysis 🚀

## 📌 Project Overview

This project focuses on developing a Machine Learning system to predict whether a customer is likely to leave a subscription-based service.

Using the IBM Telco Customer Churn dataset, the project analyzes customer demographics, service usage, contract details, and billing information to identify churn patterns and predict customer churn risk.

The goal is to help businesses understand customer behavior and develop effective customer retention strategies.

## 🎯 Project Objectives

- Understand customer churn patterns through Exploratory Data Analysis (EDA).
- Clean and preprocess customer data.
- Perform feature engineering and categorical encoding.
- Build and compare multiple Machine Learning classification models.
- Evaluate model performance using appropriate metrics.
- Identify important factors influencing customer churn.
- Suggest practical customer retention strategies.

## 📊 Dataset Information

**Dataset:** IBM Telco Customer Churn Dataset

**Source:** [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

- Number of records: 7,043
- Number of columns: 21
- Target variable: `Churn`
- Problem type: Binary Classification

The dataset contains customer information such as:
- Gender and Senior Citizen
- Tenure
- Internet and Phone Services
- Contract Type
- Monthly Charges
- Total Charges
- Payment Method
- Churn Status

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Collection
- Load the IBM Telco Customer Churn dataset.
- Understand the dataset structure and variables.

### 2. Data Cleaning
- Handle missing values.
- Remove duplicate records if present.
- Correct data types.
- Prepare data for analysis.

### 3. Exploratory Data Analysis
- Analyze customer demographics.
- Examine churn distribution.
- Study contract types and customer tenure.
- Analyze monthly and total charges.
- Create meaningful visualizations.

### 4. Feature Engineering
- Encode categorical variables.
- Prepare numerical features.
- Split the dataset into training and testing sets.
- Apply appropriate preprocessing.

### 5. Machine Learning Models

The following classification algorithms are considered:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 6. Model Evaluation

Evaluate and compare models using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

### 7. Feature Importance
Identify important customer characteristics that influence churn predictions.

### 8. Customer Retention Recommendations
Use the model findings to identify high-risk customers and suggest targeted retention strategies.

## 📈 Expected Project Outcomes

- Cleaned customer churn dataset.
- Exploratory Data Analysis visualizations.
- Feature-engineered dataset.
- Comparison of multiple classification models.
- Model evaluation results.
- Confusion matrix and ROC-AUC analysis.
- Feature importance analysis.
- Customer churn prediction function.
- Practical customer retention recommendations.

## 💡 Business Insights

The analysis can help businesses:

- Identify customers who may discontinue their services.
- Understand factors associated with customer churn.
- Focus on customers with higher predicted churn risk.
- Develop targeted offers and retention campaigns.
- Improve customer satisfaction and long-term retention.

## 📂 Project Structure

```text
Customer-Churn-Prediction-Retention-Analysis/
│
├── Customer_Churn_Prediction_Retention_Analysis.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── cleaned_churn_data.csv
├── churn_prediction_model.pkl
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/satya77713/Customer-Churn-Prediction-Retention-Analysis.git
```

### 2. Navigate to the project folder

```bash
cd Customer-Churn-Prediction-Retention-Analysis
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter
```

### 4. Download the dataset

Download the IBM Telco Customer Churn dataset and place the CSV file in the project folder.

### 5. Open Jupyter Notebook

```bash
jupyter notebook
```

Open `Customer_Churn_Prediction_Retention_Analysis.ipynb` and run the cells.

## 🔮 Future Improvements

- Develop an interactive Streamlit dashboard.
- Deploy the trained model as a web application.
- Improve prediction performance through hyperparameter tuning.
- Integrate real-time customer churn monitoring.

## 👨‍💻 Author

**Satya Aravind**

GitHub: [satya77713](https://github.com/satya77713)

---

⭐ If you find this project useful, feel free to star the repository!
