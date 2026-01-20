# AI-data-science-internship-task04

## Task 4: Credit Risk Prediction

## Project Overview
This project implements a machine learning-based credit risk assessment system that predicts whether a loan applicant is likely to default on a loan. Using historical loan application data, the system trains classification models to automatically evaluate new applications, enabling financial institutions to make data-driven lending decisions efficiently.

## Problem Statement
Financial institutions face significant challenges in accurately assessing loan applicants' creditworthiness. Traditional methods, relying heavily on credit scores and manual evaluation, can be:  

- Time-consuming and labor-intensive  
- Subjective and inconsistent  
- Prone to human bias  
- Inefficient for processing large volumes of applications  

This project develops an automated system that quickly and accurately predicts loan default risk based on applicant characteristics, improving decision-making efficiency and reducing bad loans.

## Dataset Details
The **Loan Prediction Dataset** contains 614 records with 13 features:

**Features:**
- `Loan_ID` – Unique identifier (not used in modeling)  
- `Gender` – Male/Female  
- `Married` – Yes/No  
- `Dependents` – Number of dependents (0, 1, 2, 3+)  
- `Education` – Graduate/Not Graduate  
- `Self_Employed` – Yes/No  
- `ApplicantIncome` – Applicant's monthly income (₹)  
- `CoapplicantIncome` – Co-applicant's monthly income (₹)  
- `LoanAmount` – Loan amount in thousands (₹)  
- `Loan_Amount_Term` – Loan term in months  
- `Credit_History` – Credit history (1 = Good, 0 = Bad)  
- `Property_Area` – Urban/Semiurban/Rural  
- `Loan_Status` – Target variable (Y = Approved, N = Rejected)  

**Data Characteristics:**
- Size: 614 records × 13 features  
- Missing Values: Present in several columns (`Gender`, `Married`, `Dependents`, `Self_Employed`, `LoanAmount`, `Loan_Amount_Term`, `Credit_History`)  
- Class Distribution: ~69% approved, 31% rejected  
- Data Types: Mix of categorical and numerical features

## Objective
To build a predictive model that classifies loan applicants into:  

- **Approved** – Low risk of default  
- **Rejected** – High risk of default  

**Specific Goals:**
- Clean and preprocess the dataset  
- Perform exploratory data analysis (EDA) to understand feature relationships  
- Train and evaluate multiple classification algorithms  
- Create an interactive system for real-time predictions  
- Achieve high accuracy while maintaining interpretability  

## Approach

### 1. Data Preprocessing
- Impute missing values  
- Encode categorical variables  
- Scale numerical features  
- Split data: 80% training, 20% testing  

### 2. Exploratory Data Analysis (EDA)
- Examine distributions of income and loan amounts  
- Analyze relationships: education, credit history, property area, marital status  

### 3. Model Selection
- Logistic Regression: Linear, interpretable  
- Decision Tree: Non-linear, rule-based  

### 4. Evaluation Metrics
- Accuracy, Confusion Matrix, Precision, Recall, F1-Score  

### 5. Deployment
- Interactive command-line interface  
- Real-time predictions with probability estimates  

## Conclusion
The loan prediction system demonstrates that machine learning can effectively automate credit risk assessment with 81% accuracy. Key highlights:
- Built an end-to-end ML pipeline from raw data to production-ready predictions  
- Created interpretable models balancing accuracy and explainability  
- Developed a user-friendly interface for real-world application  
- Reduces processing time from days to seconds  
-  Eliminates human bias and subjectivity  
- Handles thousands of applications simultaneously  

