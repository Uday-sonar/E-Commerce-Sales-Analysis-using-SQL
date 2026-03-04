# E-Commerce Data Analysis using Python and MySQL

## 📌 Project Overview

This project demonstrates complete data preprocessing, cleaning, transformation, and analysis of an E-Commerce dataset using **Python (Pandas)** and **MySQL**. The objective is to prepare raw data, store it in MySQL, and perform SQL analysis to extract meaningful business insights.

---

## 📂 Dataset Information

The dataset contains transactional records with the following columns:

* InvoiceNo – Transaction ID
* StockCode – Product ID
* Description – Product description
* Quantity – Number of units sold
* InvoiceDate – Transaction date
* UnitPrice – Price per unit
* CustomerID – Customer ID
* Country – Customer country

---

## 🛠 Technologies Used

* Python
* Pandas
* MySQL
* MySQL Workbench
* GitHub
* Microsoft Word

---

## 🧹 Data Cleaning Steps

The following preprocessing steps were performed:

* Fixed encoding issues using latin1 encoding
* Converted mixed datatype columns to numeric format
* Replaced non-numeric values with mode values
* Removed time component from InvoiceDate
* Replaced null values in Description with "No description"
* Converted datatypes to match MySQL schema
* Exported cleaned dataset for MySQL import

---

## 🗄 MySQL Table Schema

| Column      | Datatype |
| ----------- | -------- |
| InvoiceNo   | BIGINT   |
| StockCode   | BIGINT   |
| Description | TEXT     |
| Quantity    | BIGINT   |
| InvoiceDate | DATETIME |
| UnitPrice   | DOUBLE   |
| CustomerID  | BIGINT   |
| Country     | TEXT     |

---

## 📊 SQL Analysis Performed

### Basic Analysis

* Total number of transactions
* Total revenue
* Total customers
* Total products
* Average order value

### Intermediate Analysis

* Revenue by country
* Top 10 customers by revenue
* Top selling products
* Monthly revenue analysis
* Orders per country

### Advanced Analysis

* Repeat customers identification
* Top revenue generating countries
* Highest value transaction
* Average quantity per order
* Revenue per customer
* Total orders per customer
* Best selling country by quantity
* Customers who spent above average

---

## ▶ How to Run the Project

### Step 1: Install dependencies

```bash
pip install pandas mysql-connector-python
```

### Step 2: Run Python preprocessing script

```bash
python preprocessing.py
```

### Step 3: Import cleaned CSV into MySQL

* Open MySQL Workbench
* Use Table Data Import Wizard
* Select clean_data.csv

### Step 4: Run SQL queries

Execute the SQL queries in MySQL Workbench.

---

## 📈 Key Insights

This project helps identify:

* Most valuable customers
* Best selling products
* Revenue trends over time
* Country-wise sales performance
* Customer purchasing behavior

---

## 📁 Project Structure

```
Ecommerce-SQL-Analysis/
│
├── ecommerce_sql_report.docx
├── README.md
└── Ecommerce-sql-queries.pdf
```


## ⭐ Conclusion

This project demonstrates real-world skills including:

* Data cleaning using Python
* Database integration using MySQL
* Writing basic to advanced SQL queries
* Extracting meaningful business insights

---

If you want, I can also give a **short 3-line README version for resume projects section**.
