# Restaurant Sales Analysis

A college mini-project developed by a team of 4 to analyze restaurant sales data using **Data Warehousing and Data Mining** techniques.

## 📌 Project Overview

The project involves transforming raw restaurant transaction data into a structured **Star Schema Data Warehouse** and applying **Data Mining** techniques to identify useful sales patterns.

### 🔹 Data Warehousing

* Designed a **Star Schema**
* Created Fact & Dimension tables
* Performed **ETL** using KNIME
* Conducted **OLAP analysis** using SQL
* Implemented Roll-up, Drill-down, Slice, Dice and Ranking operations

### 🔹 Data Mining

* Applied the **Apriori Algorithm**
* Performed **Market Basket Analysis**
* Generated association rules using:

  * Support
  * Confidence
  * Lift

One example of an identified association was:

`Brownie + Pizza → Burger`

> **Note:** The dataset contains relatively few multi-item orders, so the association rules should be treated as preliminary patterns rather than statistically strong conclusions.

## 🛠️ Tools & Technologies

**Python • Pandas • Jupyter Notebook • SQL • SQLite • KNIME • Apriori**

## 📂 Project Structure

```text
Restaurant-Sales-Analysis/
│
├── Data_Mining/
│   ├── DWDM_RESTO_final.ipynb
│   ├── restaurant_sales_raw.csv
│   └── association_rules.csv
│
├── Data_Warehousing/
    ├── Customer_Dim.csv
    ├── Date_Dim.csv
    ├── Payment_Dim.csv
    ├── Product_Dim.csv
    ├── Sales_Fact.csv
    ├── Restaurant_DW.knwf
    └── Restaurant_DW_Report.pdf
```

## 👥 Team

**Team of 4**

* Pooja Gosavi
* Pranjal Damgude
* Filza Khan
* Matun Adak

## 🎓 Project Type

**College Mini Project | Data Warehousing & Data Mining**
