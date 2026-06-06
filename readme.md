# 🛒 E-Commerce Statistical Distribution Analysis

## 📌 Project Overview
This project explores statistical distributions using an E-Commerce Transactions dataset. The analysis demonstrates how probability distributions can be applied to real-world business data, including transaction amounts, transaction frequency, and transaction success rates.

The notebook combines theoretical concepts with practical implementation using Python, Pandas, NumPy, SciPy, Matplotlib, and Seaborn.

---

## 📂 Dataset Information

**Dataset:** `ecommerce_transactions_dataset.csv`

### Features
| Column | Description |
|----------|------------|
| transaction_id | Unique transaction identifier |
| customer_id | Unique customer identifier |
| transaction_amount | Amount spent in a transaction |
| transaction_date | Date of transaction |
| transaction_count | Number of transactions |
| region | Customer region |
| transaction_status | Success or Fail status of transaction |

**Records:** 5,000

---

## 🎯 Project Objectives

- Understand statistical distributions and their business applications.
- Analyze transaction success probability using Bernoulli Distribution.
- Model transaction frequency using Poisson Distribution.
- Fit transaction amounts to a Log-Normal Distribution.
- Evaluate data normality using Q-Q plots.
- Apply Box-Cox Transformation for normalization.
- Calculate probabilities and distribution metrics.
- Visualize Probability Density Function (PDF) and Cumulative Distribution Function (CDF).

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Analysis Performed

### 1. Bernoulli Distribution
- Converted transaction status into binary values.
- Calculated probability of successful transactions.

### 2. Poisson Distribution
- Estimated average transaction count (λ).
- Used transaction frequency data to model event occurrence.

### 3. Log-Normal Distribution
- Fitted transaction amount data to a log-normal distribution.
- Estimated distribution parameters.

### 4. Q-Q Plot Analysis
- Compared data distribution against a theoretical normal distribution.
- Checked normality assumptions.

### 5. Box-Cox Transformation
- Applied transformation to reduce skewness.
- Improved normality of transaction amount data.

### 6. Probability Calculations
- Computed probabilities for transactions exceeding specific thresholds.
- Evaluated distribution behavior.

### 7. PDF & CDF Visualization
- Visualized Probability Density Function (PDF).
- Visualized Cumulative Distribution Function (CDF).

---
## Preview 📸

![Screenshot](Screenshot.png)

## 📈 Key Insights

- Transaction success rates can be effectively modeled using Bernoulli probability.
- Transaction frequency follows characteristics similar to a Poisson process.
- Transaction amounts exhibit positive skewness and are better represented by a Log-Normal Distribution.
- Box-Cox transformation helps normalize highly skewed financial data.
- PDF and CDF plots provide valuable insights into customer spending behavior.

## 📁 Project Structure

```text
├── ecommerce_distribution.ipynb
├── ecommerce_transactions_dataset.csv
├── README.md
```

---

## 🚀 Future Improvements

- Customer segmentation analysis.
- Regional sales performance analysis.
- Time-series forecasting of transactions.
- Advanced statistical hypothesis testing.
- Interactive dashboards using Power BI or Tableau.

---