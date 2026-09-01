# OIBSIP Data Analytics — Retail Sales EDA

## 📊 Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset to understand sales performance, customer demographics, product categories, purchasing behavior, and monthly sales trends.

The project was completed as part of the **Oasis Infobyte Internship Program (OIBSIP) — Data Analytics Track, Level 1 Task 1**.

## 🎯 Objectives

* Understand the structure of the retail sales dataset.
* Clean and validate the data.
* Analyze sales performance by product category.
* Analyze sales by gender.
* Study monthly sales trends.
* Analyze customer age groups.
* Identify important business insights.
* Create visualizations to communicate the findings.

## 📁 Dataset

The dataset contains **1,000 retail transactions** with the following columns:

* Transaction ID
* Date
* Customer ID
* Gender
* Age
* Product Category
* Quantity
* Price per Unit
* Total Amount

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* VS Code

## 🔍 Data Analysis

The following analyses were performed:

### 1. Data Inspection

Checked:

* Dataset shape
* Column names
* Data types
* Missing values
* Duplicate records
* Statistical summary

### 2. Product Category Analysis

Total sales by category:

| Product Category | Total Sales |
| ---------------- | ----------: |
| Electronics      |    ₹156,905 |
| Clothing         |    ₹155,580 |
| Beauty           |    ₹143,515 |

**Insight:** Electronics generated the highest total sales.

### 3. Gender Analysis

| Gender | Total Sales |
| ------ | ----------: |
| Female |    ₹232,840 |
| Male   |    ₹223,160 |

**Insight:** Female customers generated slightly higher total sales.

### 4. Monthly Sales Analysis

The highest monthly sales were recorded in **May 2023**, with total sales of **₹53,150**.

### 5. Age Group Analysis

| Age Group | Transactions |
| --------- | -----------: |
| 18–25     |          169 |
| 26–35     |          205 |
| 36–45     |          202 |
| 46–55     |          229 |
| 56–64     |          195 |

**Insight:** The 46–55 age group had the highest number of transactions.

## 📈 Visualizations

The project includes visualizations for:

* Total Sales by Product Category
* Total Sales by Gender
* Monthly Sales Trend
* Customer Distribution by Age Group
* Quantity Sold by Product Category

The charts are available in the `outputs` folder.

## 💡 Key Business Insights

1. **Electronics** was the highest-revenue product category.
2. **Beauty** generated the lowest revenue among the three categories.
3. **Female customers** contributed slightly more total sales than male customers.
4. **May 2023** recorded the highest monthly sales.
5. The **46–55 age group** had the highest number of transactions.
6. The business can improve performance by targeting high-performing customer segments and optimizing promotions for lower-performing categories.

## 📌 Business Recommendations

* Maintain sufficient inventory for high-performing Electronics products.
* Use promotions and bundles to improve Beauty category sales.
* Develop targeted marketing campaigns for the 46–55 customer segment.
* Investigate the factors behind the strong sales performance in May.
* Use customer demographic information to develop personalized marketing strategies.

## 📂 Project Structure

```text
DataAnalytics-L1-Task1-EDARetailSales/
│
├── data/
│   ├── raw/
│   │   └── retail_sales_dataset.csv
│   │
│   └── processed/
│       └── retail_sales_cleaned.csv
│
├── notebooks/
│   └── Retail_Sales_EDA.ipynb
│
├── outputs/
│   ├── sales_by_category.png
│   ├── sales_by_gender.png
│   ├── monthly_sales_trend.png
│   ├── age_group_distribution.png
│   └── quantity_by_category.png
│
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd DataAnalytics-L1-Task1-EDARetailSales
```

### 3. Start Jupyter Notebook

```bash
python -m jupyter notebook
```

### 4. Open the notebook

Navigate to:

```text
notebooks/Retail_Sales_EDA.ipynb
```

Run the notebook cells from top to bottom.

## 👨‍💻 Author

**Bejjanki Sanjay Kumar**

GitHub: `https://github.com/SanjaykumarBejjanki`

## 📜 Internship

**Oasis Infobyte Internship Program (OIBSIP)**
**Track:** Data Analytics
**Level:** Level 1
**Task:** Exploratory Data Analysis on Retail Sales
