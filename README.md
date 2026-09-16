# 💰 Bank Loan & Risk Performance Analysis

## 📊 Data Analytics Project — Excel | SQL | Power BI | Python

A data analytics project focused on analyzing **bank loan applications, repayment behavior, loan performance, and credit risk**.

The project transforms raw loan data into meaningful business insights using **Python for data preparation and analysis, SQL for data querying, Excel for detailed analysis and reporting, and Power BI for interactive visualization**.

---

## 🎯 Project Objective

The main objective of this project is to understand the performance and risk of a loan portfolio and answer important business questions such as:

* How many loan applications were received?
* What percentage of loans defaulted?
* Which credit grades have higher default rates?
* Which loan purposes receive the highest funding?
* How has lending changed over time?
* Does borrower income relate to default behavior?
* How does DTI affect loan risk?
* Which segments of borrowers require closer monitoring?

---

## 🛠️ Tools & Technologies

| Tool                     | Purpose                                                |
| ------------------------ | ------------------------------------------------------ |
| **Python**               | Data cleaning, transformation and exploratory analysis |
| **Pandas / NumPy**       | Data manipulation and analysis                         |
| **Matplotlib / Seaborn** | Exploratory data visualization                         |
| **SQL**                  | Data querying, filtering, aggregation and validation   |
| **Microsoft Excel**      | Data analysis, Pivot Tables, KPIs and reporting        |
| **Power BI**             | Interactive dashboard and business visualization       |
| **DAX**                  | KPI and risk calculations                              |

---

# 📁 Dataset

The analysis is based on a loan dataset containing information about loan applications, borrowers, loan characteristics, repayment status, and credit risk.

Important columns include:

* `id`
* `loan_amnt`
* `term`
* `int_rate`
* `installment`
* `grade`
* `emp_length`
* `home_ownership`
* `annual_inc`
* `verification_status`
* `issue_d`
* `loan_status`
* `purpose`
* `dti`
* `delinq_2yrs`
* `open_acc`
* `pub_rec`
* `revol_bal`
* `revol_util`
* `total_acc`

The dataset was analyzed from multiple perspectives to understand both **business volume and credit risk**.

---

# 🧹 Data Cleaning & Preparation

The raw dataset was first examined and cleaned before analysis.

The major steps included:

* Checking the dataset structure
* Identifying duplicate records
* Checking missing values
* Reviewing inconsistent values
* Converting columns to appropriate data types
* Standardizing categorical values
* Extracting useful information from date fields
* Creating additional analytical columns
* Validating the cleaned dataset

Additional derived fields were created for analysis, including:

* `Issue_Year`
* `Income_Band`
* `Interest_Rate_Band`
* `DTI_Band`
* `Default_Flag`

---

# 🐍 Python Analysis

Python was used for data preparation and exploratory analysis.

### Libraries Used

```text
Pandas
NumPy
Matplotlib
Seaborn
```

Python was used to:

* Load the raw dataset
* Inspect the data
* Identify missing values
* Detect duplicates
* Clean and transform columns
* Create derived variables
* Analyze distributions
* Explore relationships between loan characteristics and default behavior
* Generate exploratory visualizations

---

# 🗄️ SQL Analysis

SQL was used to perform structured analysis and validate important business metrics.

Examples of analysis included:

* Total loan applications
* Loan status distribution
* Default loan count
* Default rate
* Loan amount by purpose
* Loan performance by grade
* Year-wise lending
* Income-based risk analysis
* DTI-based analysis

SQL helped validate calculations and provided a structured way to analyze the loan portfolio.

---

# 📗 Excel Analysis

Excel was used for detailed analysis and reporting.

### Excel Features Used

* Pivot Tables
* Pivot Charts
* Calculated fields
* Filters
* KPIs
* Data cleaning
* Conditional analysis

Excel analysis was used to explore:

* Loan status
* Loan grade
* Loan purpose
* Annual income
* Interest rate
* DTI
* Default behavior
* Yearly lending trends

---

# 📊 Power BI Dashboard

The final interactive dashboard was developed using **Microsoft Power BI**.

The dashboard provides an overview of the loan portfolio and allows users to analyze different borrower and loan segments.

---

# 📌 KPI Cards

## 1. Average Interest Rate

**Value: ~13.31%**

Represents the average interest rate across the analyzed loan applications.

### Why is it important?

Interest rate is an important factor in understanding loan pricing and the overall characteristics of the lending portfolio.

---

## 2. Default Rate

**Value: ~14.17%**

Calculated as:

```text
Default Loans ÷ Total Applications × 100
```

### Why is it important?

Default rate provides an overview of the proportion of loans classified as defaults in the analyzed portfolio.

---

## 3. Average DTI

**Value: ~13.31**

DTI represents the relationship between a borrower's debt obligations and income.

### Why is it important?

It helps analyze the financial burden of borrowers and can be used as one factor in credit-risk analysis.

---

## 4. Total Applications

**Value: 39,717**

Represents the total number of loan applications analyzed in the project.

---

# 🎛️ Dashboard Slicers

The dashboard contains interactive slicers for:

### Issue Year

Used to analyze lending activity across different years.

### Grade

Credit grades:

```text
A | B | C | D | E | F | G
```

Used to compare loan performance and default behavior across credit grades.

### Term

Loan duration:

```text
36 Months
60 Months
```

Used to compare loan performance based on repayment duration.

### Income Band

Borrowers are grouped into income categories such as:

```text
Low
Medium
High
```

Used to analyze loan behavior across income segments.

### Interest Rate Band

Used to group borrowers according to their loan interest rates.

### DTI Band

Used to categorize borrowers based on their debt-to-income ratio.

---

# 📈 Dashboard Visualizations

## 1. Total Loan Status Distribution

### Chart Type

**Clustered Column Chart**

### Analysis

Compares the number of loans across:

* Current
* Default
* Paid

### Why this chart?

A column chart makes it easy to compare the size of different loan-status categories.

### Business Purpose

Helps understand the overall repayment status and portfolio composition.

---

# 2. Default Rate by Grade

### Chart Type

**Horizontal Bar Chart**

### Analysis

Compares default rates across grades:

```text
A → B → C → D → E → F → G
```

### Why this chart?

Horizontal bars make category comparison and ranking easier when there are multiple categories.

### Business Purpose

Helps identify credit-grade segments with higher observed default rates.

---

# 3. Loan Amount by Purpose

### Chart Type

**Pie Chart**

### Analysis

Shows how the total loan amount is distributed across different purposes.

Examples include:

* Debt Consolidation
* Credit Card
* Home Improvement
* Other purposes

### Why this chart?

The purpose of this visualization is to show the proportional contribution of different loan purposes to the overall loan amount.

### Business Purpose

Helps understand why customers are borrowing and where lending is concentrated.

---

# 4. Yearly Lending Trend

### Chart Type

**Line Chart**

### Analysis

Shows the total loan amount issued across different years.

### Why this chart?

A line chart is appropriate for showing changes and trends over time.

### Business Purpose

Helps management understand how lending activity has changed historically.

---

# 5. Default Rate by Income Band

### Chart Type

**Column Chart**

### Analysis

Compares default rates across:

* Low Income
* Medium Income
* High Income

### Why this chart?

There are only a few categories, making a column chart easy to read and compare.

### Business Purpose

Helps analyze differences in observed default rates across borrower income groups.

---

# 📊 Business Questions Answered

| Business Question                                    | Analysis                    |
| ---------------------------------------------------- | --------------------------- |
| How healthy is the loan portfolio?                   | Loan Status Distribution    |
| Which credit grades show higher default rates?       | Default Rate by Grade       |
| Why are customers borrowing?                         | Loan Amount by Purpose      |
| How has lending changed over time?                   | Yearly Lending Trend        |
| How does observed default rate vary by income group? | Default Rate by Income Band |
| What is the overall portfolio default rate?          | Default Rate KPI            |
| What is the average loan interest rate?              | Average Interest Rate KPI   |
| What is the average borrower DTI?                    | Average DTI KPI             |

---

# 🔍 Key Findings

Based on the dashboard analysis:

* The dataset contains **39,717 loan applications**.
* The average interest rate is approximately **13.31%**.
* The observed default rate is approximately **14.17%**.
* Debt consolidation represents a major share of the loan portfolio.
* Default rates vary across different credit grades.
* Lending activity changes over the analyzed years.
* Default rates also vary across income bands.

> **Note:** These findings describe patterns observed in this dataset. They should not automatically be interpreted as causal relationships.

---

# 🧠 Project Challenges

Some of the main challenges during the project included:

### 1. Data Cleaning

The raw dataset required checking for missing values, duplicates, inconsistent formats, and data-quality issues.

### 2. Creating Useful Categories

Raw numerical fields such as income, interest rate, and DTI were converted into meaningful bands for easier segmentation.

### 3. Risk Analysis

Understanding default behavior across different borrower segments required comparing multiple variables rather than relying on a single metric.

### 4. Connecting Multiple Tools

The project involved using Python, SQL, Excel, and Power BI for different stages of the analytical workflow.

---

# 🔄 End-to-End Workflow

```text
Raw Loan Dataset
       ↓
Data Inspection
       ↓
Python Data Cleaning
       ↓
Data Transformation
       ↓
SQL Analysis & Validation
       ↓
Excel Pivot Analysis
       ↓
Power BI Data Modeling
       ↓
DAX Calculations
       ↓
Interactive Dashboard
       ↓
Business Insights
```

---

# 📂 Suggested Repository Structure

```text
Bank-Loan-Risk-Analysis/
│
├── README.md
│
├── Dataset/
│   └── loan_data.csv
│
├── Python/
│   └── loan_risk_analysis.ipynb
│
├── SQL/
│   └── loan_analysis.sql
│
├── Excel/
│   └── Bank_Loan_Risk_Analysis.xlsx
│
├── PowerBI/
│   └── Bank_Loan_Risk_Dashboard.pbix
│
├── Screenshots/
│   ├── Dashboard.png
│   ├── Loan_Status.png
│   ├── Default_by_Grade.png
│   ├── Loan_Purpose.png
│   └── Lending_Trend.png
│
└── Documentation/
    └── Project_Report.pdf
```

> Update the filenames to match the actual files in your GitHub repository.

---

# 📸 Dashboard Preview

Add your actual Power BI screenshots here.

### Main Dashboard

```markdown
![Bank Loan Risk Dashboard](Screenshots/Dashboard.png)
```

### Default Rate by Grade

```markdown
![Default Rate by Grade](Screenshots/Default_by_Grade.png)
```

### Loan Amount by Purpose

```markdown
![Loan Purpose Analysis](Screenshots/Loan_Purpose.png)
```

---

# 🎓 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Exploratory Data Analysis
* SQL
* Microsoft Excel
* Pivot Tables
* Power BI
* Power Query
* DAX
* Data Visualization
* Data Modeling
* KPI Development
* Risk Analysis
* Business Intelligence
* Business Insight Generation

---

# 👩‍💻 Author

**Rutika Chinchkar**

**Data Analyst | Computer Science Postgraduate**

### Technical Skills

`SQL` · `Excel` · `Power BI` · `Python` · `Pandas` · `NumPy` · `DAX` · `Power Query` · `Data Visualization`

---

## ⭐ Project Summary

This project demonstrates how raw loan data can be transformed into an analytical solution using multiple data analytics tools.

The combination of **Python, SQL, Excel, and Power BI** provides an end-to-end workflow for understanding loan portfolio performance and identifying patterns in credit risk.

The final Power BI dashboard converts the analysis into an interactive format that can be explored using different borrower, loan, and time-based filters.
