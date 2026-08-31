# 💳 Credit Card Customer Analytics Dashboard

An interactive **Power BI analytics dashboard** developed to explore credit card customer behavior, transaction activity, revenue performance, credit utilization, revolving balances, and delinquency trends.

The project transforms raw customer and transaction data into business-oriented insights that can help financial institutions understand customer spending patterns, identify valuable segments, monitor credit behavior, and assess potential risk areas.

---

## 📌 Project Overview

This project analyzes credit card customer and transaction data for **2023** using **SQL, PostgreSQL, Power Query, DAX, and Power BI**.

The analysis is organized into two key areas:

* **Customer Spending & Revenue**
* **Credit Risk Analysis**

The dashboard examines customer demographics, transaction values, card categories, geographic performance, credit limits, utilization ratios, revolving balances, interest earned, annual fees, and delinquency indicators.

---

## 🛠️ Tools & Technologies

| Technology        | Application                                          |
| ----------------- | ---------------------------------------------------- |
| **Power BI**      | Interactive dashboard development and visualization  |
| **Power Query**   | Data cleaning, transformation, and preparation       |
| **DAX**           | KPI calculations, measures, and analytical metrics   |
| **SQL**           | Data querying and analysis                           |
| **PostgreSQL**    | Data storage and database management                 |
| **Data Modeling** | Establishing relationships between analytical tables |

---

## 📊 Dataset

The dataset contains information on **10,000+ credit card customers** and their activity during 2023.

The available attributes include:

* Customer demographics
* Income and education
* Occupation
* Geographic information
* Card categories
* Transaction amounts
* Credit limits
* Credit utilization
* Revolving balances
* Interest earned
* Annual fees
* Delinquency indicators
* Customer satisfaction
* Personal loan information

**Data Source:** Kaggle — Rishabh Mishra

---

## 🎯 Business Problem

Credit card companies generate revenue through multiple sources, including customer transactions, interest, and annual fees. At the same time, customer credit behavior needs to be monitored to identify potentially risky patterns.

The objective of this project is to use customer and transaction data to answer business questions such as:

* Which customer segments contribute the most to transaction volume?
* Which states generate the highest transaction amounts?
* How does transaction activity change over time?
* Which spending categories contribute most to customer expenditure?
* How do different card categories perform?
* What is the relationship between revolving balances and interest earned?
* How does credit utilization vary across customers?
* What patterns can be observed in delinquent accounts?
* Which customer segments may require additional credit-risk monitoring?

---

# 📑 Dashboard Analysis

## 1️⃣ Customer Spending & Revenue

The first dashboard page focuses on **customer spending behavior and revenue generation**.

### Key Metrics

* Total Transaction Amount
* Total Interest Earned
* Annual Fees
* Total Revenue
* Transaction Count
* Customer Spending
* Card Category Performance

### Analysis Performed

The dashboard evaluates:

* Spending distribution by gender
* State-wise transaction performance
* Weekly transaction trends
* Card category performance
* Customer segment contribution
* Major sources of revenue

### 🔍 Key Findings

* Total revenue generated during 2023 was approximately **$55M**.
* Transaction amounts accounted for approximately **$44.5M**.
* Interest earned contributed approximately **$7.8M**.
* Male customers generated approximately **$30M** in transaction spending, compared with approximately **$25M** from female customers.
* **California, Texas, and New York** were among the highest-performing states by transaction amount.
* **Platinum cardholders** recorded the lowest transaction amount among the analyzed card categories.

---

## 2️⃣ Credit Risk Analysis

The second dashboard page focuses on **customer credit behavior and delinquency-related indicators**.

### Key Areas

* Credit Utilization Ratio
* Revolving Balance
* Credit Limit
* Delinquent Accounts
* Personal Loans
* Customer Occupation
* Customer Financial Characteristics
* Customer Service Period

### 🔍 Key Findings

* The average credit utilization ratio was approximately **27.5%**.
* Approximately **6.1% of accounts were delinquent**.
* Customers with higher revolving balances generally showed higher interest earned.
* Higher credit limits did not show a direct relationship with higher delinquency rates in the analyzed data.
* Government employees, self-employed customers, and retirees collectively accounted for approximately **20% of delinquent accounts**.
* Customers with personal loans displayed a broadly similar delinquency pattern to customers without personal loans.
* Customers who began using the service during **July–December** recorded higher satisfaction scores compared with customers who started earlier in the year.

---

# 🧮 Key KPIs

The dashboard incorporates several business and risk-related metrics, including:

* **Total Transaction Amount**
* **Total Interest Earned**
* **Annual Fees**
* **Total Revenue**
* **Average Credit Utilization**
* **Total Revolving Balance**
* **Delinquency Rate**
* **Credit Limit**
* **Transaction Count**

These KPIs provide a high-level view of customer activity while allowing deeper analysis through dashboard filters and visualizations.

---

# 📈 Business Value

The analysis can help a credit card business:

* Identify high-value customer segments
* Monitor customer spending behavior
* Understand major revenue contributors
* Compare card category performance
* Track credit utilization
* Examine delinquency patterns
* Identify customer groups requiring closer monitoring
* Analyze geographic differences in transaction activity
* Support data-driven business and risk-management decisions

---

# 🗂️ Project Structure

```text
Credit-Card-Customer-Business-Analytics-Dashboard/
│
├── Screenshots/
│   ├── Customer Spending & Revenue.png
│   └── Credit Risk Indicators.png
│
├── SQL/
│   └── SQL Queries
│
├── Credit Card Customer Business Analytics Dashboard.pbix
│
└── README.md
```

---

# 📸 Dashboard Preview

### Customer Spending & Revenue

The dashboard provides an overview of transaction performance, revenue generation, customer spending, geographic trends, and card category performance.

### Credit Risk Indicators

The second page focuses on credit utilization, revolving balances, credit limits, delinquency, and customer-level risk indicators.

---

# 🏁 Conclusion

This project demonstrates how **SQL, PostgreSQL, Power Query, DAX, data modeling, and Power BI** can be combined to convert raw credit card data into meaningful business insights.

The analysis highlights differences in customer spending across segments and geographic regions, identifies major revenue contributors, and provides visibility into credit utilization and delinquency behavior.

Overall, the dashboard provides a consolidated analytical view that can support **customer segmentation, revenue analysis, performance monitoring, and credit-risk assessment**.

---

## 👨‍💻 Skills Demonstrated

**Data Analytics:** SQL, Data Cleaning, Exploratory Data Analysis
**Power BI:** Power Query, DAX, Data Modeling, Interactive Dashboards
**Database:** PostgreSQL
**Visualization:** Power BI
**Tools:** Git, GitHub, VS Code
