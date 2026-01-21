# Loan Prediction using Apache Spark

##  Overview
This project implements a **loan default prediction system** using **Apache Spark and PySpark MLlib**.  
The goal is to analyze historical loan data at scale, perform feature engineering, train machine learning models, and evaluate their performance for credit risk assessment.

The project is designed following a **Data Engineering + Machine Learning pipeline** approach and is suitable for academic projects and Data Engineer internship portfolios.

---

##  Architecture & Workflow
1. **Data Ingestion**
   - Load structured loan data into Spark DataFrames
2. **Data Preprocessing**
   - Handle missing values
   - Data cleaning and type casting
3. **Feature Engineering**
   - Encoding categorical variables
   - Feature vector assembly using Spark ML
4. **Model Development**
   - Train classification models using Spark MLlib
5. **Evaluation**
   - Model performance evaluation (accuracy, etc.)

---

##  Tech Stack
- **Apache Spark**
- **PySpark (Spark SQL & MLlib)**
- **Python**
- **Google Colab**
- **GitHub**

---

## 📂 Project Structure
```text
Loan_Prediction_using_spark/
│── notebooks/
│   └── Loan_Prediction_using_spark.ipynb
│── README.md
