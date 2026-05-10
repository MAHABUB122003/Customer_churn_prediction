# Customer Churn Prediction using Machine Learning

## Overview
This project predicts whether a customer is likely to leave a company (churn) using Machine Learning techniques.  
The project includes data preprocessing, feature engineering, model training, and evaluation.

The goal is to help businesses identify customers who may leave and improve customer retention strategies.

---

## Project Features

- Data Cleaning & Preprocessing
- Feature Engineering
- Handling Missing Values
- One-Hot Encoding
- Feature Scaling
- Train/Test Split with Stratification
- Machine Learning Model Training
- Model Evaluation
- Customer Churn Prediction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset Features

The dataset contains customer information such as:

- Credit Score
- Country
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Member Status
- Estimated Salary

Additional engineered features:

- Balance Per Product
- Salary Balance Ratio
- Age Group
- Tenure Bucket
- High Balance Indicator

---

## Machine Learning Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
Encoding & Scaling
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Customer Churn Prediction
```

---

## Data Preprocessing

### Numerical Features
- Missing value imputation using Median
- Standard Scaling

### Categorical Features
- Missing value imputation using Most Frequent Value
- One-Hot Encoding

---

## Model Evaluation

The project evaluates the model using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Project Structure

```text
Customer_churn_prediction/
│
├── Customer_churn_prediction.ipynb
├── README.md
└── dataset.csv
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/MAHABUB122003/Customer_churn_prediction.git
```

Move into the project folder:

```bash
cd Customer_churn_prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## GitHub Repository

GitHub Link:

https://github.com/MAHABUB122003/Customer_churn_prediction

---

## Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Feature engineering
- Handling categorical variables
- Building ML pipelines
- Training classification models
- Evaluating machine learning performance

---

## Future Improvements

- Hyperparameter Tuning
- Multiple Model Comparison
- Deployment using Flask/Streamlit
- Real-time Prediction API
- Advanced Feature Engineering

---

## Author

Mahabubur Rahman

Learning:
- Machine Learning
- Data Science
- Cybersecurity

---

## License

This project is for educational and learning purposes.
