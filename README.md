# Customer Shopping Behavior Analysis

An end-to-end Data Analytics project demonstrating a complete analytics workflow using **Python, PostgreSQL, SQL, and Power BI**. The project focuses on transforming raw customer shopping data into actionable business insights through data cleaning, exploratory analysis, SQL-based querying, and interactive dashboarding.

---

## 📌 Project Overview

This project simulates a real-world data analytics pipeline followed by data analysts in industry.

The workflow includes:

- Loading raw customer shopping data
- Data cleaning and preprocessing using Python (Pandas)
- Exploratory Data Analysis (EDA)
- Feature engineering
- Loading cleaned data into PostgreSQL
- Writing SQL queries to answer business questions
- Building an interactive Power BI dashboard
- Summarizing findings in a business report and presentation

---

## 📂 Dataset

**Dataset:** Customer Shopping Behavior Analysis

The dataset contains customer purchase information including:

- Customer demographics
- Product categories
- Purchase amount
- Discounts
- Shipping methods
- Review ratings
- Previous purchases
- Subscription status
- Payment methods
- Purchase frequency
- Seasonal purchases

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|-------|---------|
| Python | Data Cleaning & EDA |
| Pandas | Data Manipulation |
| NumPy | Feature Engineering |
| PostgreSQL | Data Storage |
| SQL | Business Analysis |
| Power BI | Dashboard Development |
| Jupyter Notebook | Analysis Environment |
| Git & GitHub | Version Control |
| Gamma | Presentation |

---

## 📁 Project Structure

```text
Customer_Shopping_Behavior_Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── dashboard/
│   └── Customer_Shopping_Dashboard.pbix
│
├── reports/
│   ├── Business_Report.pdf
│   └── Presentation.pptx
│
├── outputs/
│
└── README.md
```

---

## 🔄 Project Workflow

### 1. Data Loading

- Imported dataset using Pandas
- Verified data types
- Explored dataset structure

### 2. Data Cleaning

- Removed unnecessary columns
- Checked missing values
- Removed duplicates
- Standardized column names
- Fixed inconsistent values

### 3. Feature Engineering

Created additional business-friendly features such as:

- Age Groups
- Purchase Frequency (Days)
- Customer Segments
- Revenue Categories

### 4. Exploratory Data Analysis (EDA)

Performed analyses including:

- Customer demographics
- Revenue distribution
- Category performance
- Discount usage
- Subscription analysis
- Seasonal purchasing trends
- Purchase frequency

### 5. SQL Analysis

Loaded the cleaned dataset into PostgreSQL and answered business questions using SQL.

Examples include:

- Revenue by gender
- Revenue by age group
- Top-selling products
- Customer segmentation
- Discount analysis
- Category performance
- Ranking products using Window Functions
- CTE-based business analysis

Concepts used:

- GROUP BY
- CASE WHEN
- Aggregate Functions
- Window Functions
- DENSE_RANK()
- Common Table Expressions (CTEs)
- Filtering
- Sorting

### 6. Power BI Dashboard

Built an interactive dashboard featuring:

- KPIs
- Revenue Analysis
- Customer Segmentation
- Product Performance
- Category Analysis
- Filters & Slicers
- Interactive Visualizations

---

## 📊 Dashboard Preview

> Add screenshots of your Power BI dashboard here.

Example:

```
dashboard/dashboard_preview.png
```

---

## 📈 Key Business Insights

Examples of insights generated:

- Revenue contribution by customer segment
- Best-performing product categories
- Customer purchasing behavior
- Impact of discounts on purchasing
- Subscription vs Non-subscription spending
- Most frequently purchased products

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/customer-shopping-analysis.git
```

### Install Dependencies

```bash
pip install pandas numpy sqlalchemy psycopg2
```

### Run Notebook

Open:

```
notebooks/analysis.ipynb
```

and execute the cells sequentially.

### Load Data into PostgreSQL

Update the database credentials inside the notebook and execute the data loading section.

### Run SQL Queries

Execute the queries in:

```
sql/business_queries.sql
```

using PostgreSQL.

### Open Dashboard

Open:

```
dashboard/Customer_Shopping_Dashboard.pbix
```

in Power BI Desktop.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- SQL Query Writing
- PostgreSQL
- Window Functions
- Common Table Expressions (CTEs)
- Data Visualization
- Dashboard Development
- Business Storytelling





