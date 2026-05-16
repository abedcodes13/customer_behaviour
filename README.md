# Customer Shopping Behaviour Analysis

## Overview

This project focuses on analyzing customer shopping behaviour using Python, SQL, and Power BI. The workflow includes loading and exploring the dataset, cleaning and preparing the data, performing exploratory data analysis (EDA), running analytical SQL queries in PostgreSQL, and building an interactive Power BI dashboard to visualize key business insights.

The project demonstrates practical data analytics skills including:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* SQL querying and business reporting
* Data visualization and dashboard creation
* Insight generation for decision-making

---

## Dataset

The dataset contains customer shopping behaviour information, including:

* Customer demographics
* Purchase history
* Product categories
* Spending patterns
* Shopping frequency
* Payment methods

The data was analyzed to identify trends, customer behaviour patterns, and business insights.

---

## Tools & Technologies

The following tools and technologies were used throughout the project:

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **Jupyter Notebook**
* **PostgreSQL**
* **SQL**
* **Power BI**

---

## Project Workflow

### 1. Data Loading

* Imported the dataset into Python using Pandas
* Inspected dataset structure, columns, and data types

### 2. Data Cleaning

* Handled missing values
* Removed duplicates
* Standardized column formats
* Corrected inconsistent data entries

### 3. Exploratory Data Analysis (EDA)

Performed analysis to understand:

* Customer demographics
* Spending distribution
* Most purchased categories
* Purchase frequency
* Relationship between age, gender, and spending behaviour

Visualizations were created using Matplotlib and Seaborn.

### 4. SQL Analysis (PostgreSQL)

The cleaned dataset was imported into PostgreSQL for advanced querying and reporting.

SQL queries were used to:

* Calculate total sales and revenue
* Identify top-performing product categories
* Analyze customer purchasing behaviour
* Generate business performance summaries

### 5. Power BI Dashboard

An interactive Power BI dashboard was created to present:

* Sales overview
* Customer insights
* Product category performance
* Spending trends
* Key KPIs and visual reports

---

## Dashboard Features

The Power BI dashboard includes:

* Interactive filters and slicers
* KPI cards
* Bar charts and pie charts
* Customer segmentation insights
* Sales trend analysis

---

## Key Results & Insights

Some major insights identified from the analysis include:

* High-performing product categories contributed significantly to overall revenue
* Certain customer age groups showed higher spending behaviour
* Seasonal and purchasing trends were identified
* Customer segmentation helped reveal different shopping patterns

These insights can support data-driven business decisions and marketing strategies.

---

## Project Structure

```bash
├── Customer_Shopping_Behaviour.ipynb
├── customer_behaviour_queries.sql
├── dashboard.pbix
├── dataset.csv
└── README.md
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <repository-link>
cd <project-folder>
```

### 2. Install Required Libraries

```bash
pip install pandas psycopg2
```

### 3. Run the Jupyter Notebook

Open the notebook using Jupyter:

```bash
jupyter notebook
```

Then run:

```bash
Customer_Shopping_Behaviour.ipynb
```

### 4. Run SQL Queries

* Import the cleaned dataset into PostgreSQL
* Execute the SQL queries from:

```bash
customer_behaviour_queries.sql
```

### 5. Open Power BI Dashboard

Open the `.pbix` file in Power BI Desktop to explore the interactive dashboard.

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, SQL, PostgreSQL, and Power BI. It highlights the ability to clean, analyze, and visualize data while generating actionable business insights through both technical analysis and dashboard reporting.
