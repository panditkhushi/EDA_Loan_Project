👩‍💻 Author

Khushi Pandit
# Loan Prediction Project — Data Analysis for Loan Approval

## 📌Introduction
This project demonstrates how real-world loan approval problems can be solved using data analysis and machine learning techniques.
By working on this notebook, you gain practical understanding of how financial institutions analyze customer data to make informed loan approval decisions while minimizing risk.
The project combines data preprocessing, exploratory analysis, and predictive modeling to classify whether a loan application should be approved or not.

## 🏦 Business Understanding
You are working for a financial institution / lending company that provides loans to customers.
Whenever a customer applies for a loan, the company must decide whether to approve or reject the loan based on the applicant’s profile.
There are two major risks involved in this decision:<br>
-	If the applicant is likely to repay the loan, rejecting the loan results in a loss of business and profit<br>
-	If the applicant is not likely to repay the loan, approving the loan can lead to a financial loss due to default<br>

The dataset used in this project contains information about previous loan applicants along with their loan approval status.
The goal is to identify patterns in applicant and loan-related features that influence the approval decision.

## 🎯Problem Statement
Using historical loan application data, build a machine learning model that can:
-	Analyze customer and loan attributes
-	Predict whether a loan will be approved or rejected
-	Help the company make data-driven decisions

## 🎯Business Objectives
The primary objective of this project is to:
-	Understand the key factors that influence loan approval
-	Reduce financial risk by avoiding approval of risky applications
-	Improve decision-making efficiency using machine learning
  
By correctly predicting loan approval outcomes, the company can:

-	Reduce defaults
-	Increase profitability
-	Maintain a balanced loan portfolio

## 📊Data Understanding
The dataset consists of information related to loan applicants and loan details.

**Key Attributes in the Dataset**
-	Applicant Income
-	Co-applicant Income
-	Loan Amount
-	Loan Amount Term
-	Credit History
-	Gender
-	Marital Status
-	Education
-	Self Employment
-	Property Area
  
**Target Variable**

-	Loan_Status
  
1 → Loan Approved

0 → Loan Not Approved

## 🔍Approach Used in the Notebook
The notebook loan_project_pratice.ipynb follows a structured machine learning workflow:

**1️⃣ Data Loading**
-	Dataset is loaded using Pandas
-	Initial inspection is done to understand shape, columns, and data types
  
**2️⃣ Data Cleaning**
-	Missing and blank values are identified
-	Appropriate techniques (mean / mode) are used to handle missing data
-	Dataset is prepared for modeling
  
**3️⃣ Exploratory Data Analysis (EDA)**
-	Distribution of important features is analyzed
-	Relationship between loan approval and applicant attributes is studied
- Insights are derived to understand approval trends
  
**4️⃣ Feature Engineering**
-	Categorical variables are converted into numerical format using encoding techniques
-	Numerical features are scaled to ensure uniformity
  
**📈 Results & Observations**
-	The machine learning model is able to predict loan approval with good accuracy
-	Credit history and income-related features play a significant role in approval decisions
-	Proper data preprocessing significantly improves model performance

## 📦Deliverables
-	Jupyter Notebook (loan_project_pratice.ipynb) containing:
    -	Code
    -	Explanations
    - Visualizations
 
## 💡Insights

1. Most loans are for 36 months; fewer for 60 months.
2. Loan amounts are skewed; most between 5k–15k.
3. Annual income is skewed with outliers; majority <150k.
4. Loan status shows defaults (Charged Off) and Fully Paid dominate.
5. Debt consolidation is the most common loan purpose.
6. Interest rates mainly 10–15%, rising sharply for poor grades.
7. Loan amount, funded amount, and installment are highly correlated.
8. Higher income borrowers request higher loans, but risk exists across incomes.

**Histogram for Loan Amount Distribution**

<img src="" alt="Loan EDA" width="500"/>
