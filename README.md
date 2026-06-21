# CREDIT CARD FRAUD DETECTION SYSTEM USING EDA, LINEAR REGRESSION & DASHBOARD VISUALIZATION

## PROJECT OVERVIEW

The **Credit Card Fraud Detection System** is a Data Analytics and Machine Learning project developed to analyze credit card transaction data and identify fraudulent activities.

Financial institutions process millions of transactions daily, making manual fraud detection difficult and inefficient. This project utilizes **Exploratory Data Analysis (EDA)**, **Linear Regression**, and **Interactive Dashboard Visualization** to understand transaction behavior, identify suspicious patterns, and support fraud prevention strategies.

---

## PROBLEM STATEMENT

Credit card fraud causes significant financial losses for banks and customers worldwide.

Due to the large volume of transaction data, manually identifying fraudulent transactions is time-consuming and ineffective. Fraudulent transactions often occur within seconds, making real-time detection essential.

Failure to detect fraudulent activities can result in:

* Financial losses
* Unauthorized transactions
* Increased fraud risks
* Reduced customer trust
* Security concerns

An automated fraud detection system can help organizations identify suspicious transactions and improve fraud management.

---

## OBJECTIVES

The primary objectives of this project are:

* Perform Exploratory Data Analysis (EDA) on credit card transactions.
* Analyze transaction behavior and fraud patterns.
* Identify risk categories among transactions.
* Build a Linear Regression model for transaction analysis.
* Evaluate model performance using standard metrics.
* Develop interactive dashboards for fraud monitoring.
* Generate actionable insights for fraud prevention.

---

## DATASET INFORMATION

### Dataset Source

Credit Card Fraud Detection Dataset from Kaggle

### Features Used

| Feature  | Description                         |
| -------- | ----------------------------------- |
| Time     | Time elapsed between transactions   |
| Amount   | Transaction amount                  |
| V1 - V28 | Anonymized transaction features     |
| Class    | Fraud label (0 = Normal, 1 = Fraud) |

---

## TECHNOLOGIES USED

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn

### Machine Learning Algorithm

* Linear Regression

### Dashboard Tools

* Plotly

---

## PROJECT WORKFLOW

### 1. Data Collection

* Load dataset from Kaggle
* Explore dataset structure
* Understand available features

### 2. Data Cleaning & Preprocessing

* Handle missing values
* Remove duplicate records
* Verify data types
* Prepare data for analysis

### 3. Descriptive Statistics

Calculate:

* Average transaction amount
* Fraud transaction count
* Normal transaction count
* Fraud percentage

---

## FRAUD ANALYSIS

The project analyzes:

### Transaction Factors

* Transaction Amount
* Transaction Time
* Fraud Status

### Fraud Indicators

* High-risk transactions
* Transaction amount patterns
* Fraud occurrence trends

The analysis helps identify suspicious activities and fraud-related behavior.

---

## GROUP-BASED ANALYSIS

The following comparisons are performed:

* Amount vs Fraud
* Time vs Fraud
* Risk Level vs Fraud
* Feature Patterns vs Fraud

---

## RELATIONSHIP ANALYSIS

Correlation and relationship analysis are performed between:

* Transaction Amount and Fraud
* Transaction Time and Fraud
* Transaction Features and Fraud
* Correlation among numerical variables

---

## DATA VISUALIZATIONS

### Bar Charts

* Fraud vs Normal Transaction Distribution
<img width="444" height="377" alt="image" src="https://github.com/user-attachments/assets/b0e82fcb-0fbf-40db-bf05-6c54765a1b03" />

### Histograms

* Transaction Amount Distribution
<img width="554" height="377" alt="image" src="https://github.com/user-attachments/assets/1a7e01f1-90a1-46e6-b938-4d0732596121" />


### Scatter Plots

* Time vs Amount
<img width="567" height="374" alt="image" src="https://github.com/user-attachments/assets/6d2a8788-28c9-48ad-a547-fe897fd18f2d" />


### Box Plots

* Fraud vs Transaction Amount

<img width="570" height="373" alt="image" src="https://github.com/user-attachments/assets/3c873b6d-e021-4e4b-a688-1b74a98488d5" />


### Heatmaps

* Correlation Analysis of Features
<img width="885" height="673" alt="image" src="https://github.com/user-attachments/assets/d7893273-ad29-4b65-88e8-633a5c4ce02d" />


---

## RISK ANALYSIS

Transactions are categorized into risk levels based on transaction amount.
<img width="494" height="377" alt="image" src="https://github.com/user-attachments/assets/3dd807c0-a9bb-4825-b301-c051b4e51714" />

### Low Risk

* Amount below 100

### Medium Risk

* Amount between 100 and 1000

### High Risk

* Amount above 1000

This classification helps identify potentially suspicious transactions.

---

## MACHINE LEARNING MODEL

### Algorithm

Linear Regression

### Independent Variable

* Time

### Dependent Variable

* Amount

### Modeling Steps

1. Split dataset into training and testing sets
2. Train Linear Regression model
3. Predict transaction amounts
4. Evaluate model performance

---

## MODEL EVALUATION METRICS

The model is evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Residual Analysis

These metrics measure the effectiveness of the predictive model.

---

## DASHBOARD FEATURES

The project includes an interactive dashboard with:

### Key Indicators

* Fraud Count
* Normal Transaction Count
* Fraud Percentage
* Average Transaction Amount

### Interactive Visualizations

* Fraud Distribution
<img width="1793" height="449" alt="image" src="https://github.com/user-attachments/assets/3c8499fb-4817-4572-bcd1-db64957664ec" />
* Transaction Amount Trends
<img width="1813" height="451" alt="image" src="https://github.com/user-attachments/assets/b99f6209-b4c9-4ee0-9a61-9a376a4735dc" />

* Fraud Comparison
<img width="1765" height="421" alt="image" src="https://github.com/user-attachments/assets/ab356f2d-0d94-46f2-ba6e-69c544b690fd" />

* Correlation Heatmap
<img width="1802" height="442" alt="image" src="https://github.com/user-attachments/assets/38317e26-8df3-4a87-834e-8598507493b6" />

* Risk Level Distribution
<img width="1769" height="437" alt="image" src="https://github.com/user-attachments/assets/a2be0b52-38d1-46ec-a528-a7da3304b427" />


### Dashboard Benefits

* Interactive analysis
* Better fraud monitoring
* Data-driven decision making

---

## KEY INSIGHTS

* Fraudulent transactions show distinct patterns.
* Transaction amount plays an important role in risk analysis.
* Correlation analysis helps identify influential factors.
* Risk categorization assists in fraud monitoring.
* Interactive dashboards improve transaction analysis.

---

## EXPECTED OUTCOME

The Credit Card Fraud Detection System helps organizations:

* Understand transaction behavior
* Identify suspicious activities
* Support fraud prevention
* Improve risk management
* Enhance transaction security

By combining EDA, Linear Regression, and Interactive Dashboards, the system provides valuable insights for fraud analysis and decision-making.

---
