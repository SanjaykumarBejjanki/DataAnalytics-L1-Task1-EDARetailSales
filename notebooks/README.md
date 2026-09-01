# Retail Sales Exploratory Data Analysis

## 📊 Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset to identify sales patterns, customer characteristics, product category performance, and monthly sales trends.

The analysis was completed using Python, Pandas, NumPy, Matplotlib, and Seaborn in Jupyter Notebook.

## 🎯 Objectives

* Understand the structure and characteristics of the retail sales dataset.
* Clean and prepare the data for analysis.
* Analyze sales performance across product categories.
* Compare sales by gender.
* Examine customer age-group distribution.
* Analyze monthly sales trends.
* Identify useful patterns and business insights from the data.
* Create visualizations to communicate the findings clearly.

## 📁 Dataset

The dataset contains **1,000 retail transactions**.

### Columns

| Column           | Description                   |
| ---------------- | ----------------------------- |
| Transaction ID   | Unique transaction identifier |
| Date             | Date of the transaction       |
| Customer ID      | Unique customer identifier    |
| Gender           | Customer gender               |
| Age              | Customer age                  |
| Product Category | Category of purchased product |
| Quantity         | Number of units purchased     |
| Price per Unit   | Price of one unit             |
| Total Amount     | Total transaction amount      |

### Product Categories

* Beauty
* Clothing
* Electronics

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Git & GitHub

## 🔍 Data Analysis

### Data Quality

The dataset contains **1,000 records** and no missing values were found.

The main numerical variables include:

* Age
* Quantity
* Price per Unit
* Total Amount

The `Date` column was converted and used for monthly sales analysis.

## 📈 Exploratory Data Analysis

### 1. Sales by Product Category

Total sales by category:

| Product Category | Total Sales |
| ---------------- | ----------: |
| Electronics      |    ₹156,905 |
| Clothing         |    ₹155,580 |
| Beauty           |    ₹143,515 |

**Insight:** Electronics generated the highest total sales, closely followed by Clothing. Beauty had the lowest total sales among the three categories.

### 2. Sales by Gender

| Gender | Total Sales |
| ------ | ----------: |
| Female |    ₹232,840 |
| Male   |    ₹223,160 |

**Insight:** Female customers generated slightly higher total sales than male customers.

### 3. Monthly Sales Trend

The analysis shows variations in sales throughout the year.

The highest monthly sales were recorded in **May 2023**, while **September 2023** recorded the lowest sales among the main 2023 months.

The dataset also contains transactions from **January 2024**.

### 4. Customer Age Groups

Customers were grouped into five age ranges:

| Age Group | Customers |
| --------- | --------: |
| 18–25     |       169 |
| 26–35     |       205 |
| 36–45     |       202 |
| 46–55     |       229 |
| 56–64     |       195 |

**Insight:** The **46–55** age group contains the highest number of customers, while the **18–25** group contains the fewest.

### 5. Quantity by Product Category

Quantity purchased was also analyzed across product categories to understand purchasing behavior and category demand.

## 📊 Visualizations

The project includes the following visualizations:

* Sales by Product Category
* Sales by Gender
* Monthly Sales Trend
* Age Group Distribution
* Quantity by Product Category

The generated charts are available in the `outputs/` directory.

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
│   ├── README.md
│   └── Retail_Sales_EDA.ipynb
│
├── outputs/
│   ├── age_group_distribution.png
│   ├── monthly_sales_trend.png
│   ├── quantity_by_category.png
│   ├── sales_by_category.png
│   └── sales_by_gender.png
│
├── .gitignore
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/SanjaykumarBejjanki/DataAnalytics-L1-Task1-EDARetailSales.git
```

### 2. Navigate to the project

```bash
cd DataAnalytics-L1-Task1-EDARetailSales
```

### 3. Install required libraries

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter openpyxl
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open:

```text
notebooks/Retail_Sales_EDA.ipynb
```

Run the cells to reproduce the analysis.

## 💡 Key Business Insights

1. **Electronics** generated the highest total sales among the three product categories.
2. **Clothing** performed very close to Electronics in total sales.
3. **Female customers** generated slightly more revenue than male customers.
4. The **46–55 age group** had the highest number of customers.
5. Monthly sales varied considerably throughout the analyzed period.
6. **May 2023** recorded the highest monthly sales in the dataset's main 2023 period.
7. The analysis provides useful information for understanding customer demographics and product-category performance.

## 📌 Conclusion

The Retail Sales EDA project demonstrates how exploratory data analysis can be used to transform raw transaction data into meaningful business insights.

By analyzing customer demographics, product categories, transaction quantities, and sales trends, businesses can better understand purchasing behavior and identify areas that may require further investigation.

## 👨‍💻 Author

**Sanjay Kumar Bejjanki**

GitHub:
https://github.com/SanjaykumarBejjanki

## 📜 Internship Task

**OIBSIP — Data Analytics**

**Level 1 — Task 1: Exploratory Data Analysis on Retail Sales Data**
