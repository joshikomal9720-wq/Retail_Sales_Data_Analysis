# Retail Sales Data Analysis & Business Insights

### Retail Sales Data Analysis using Python, Pandas, Matplotlib and Seaborn

## 📌 Project Overview

This project focuses on analyzing retail sales transaction data to identify important sales trends, product performance, customer behavior, and country-level patterns.

The analysis was performed using Python and its data analysis and visualization libraries. The project includes data cleaning, exploratory data analysis (EDA), statistical analysis, and business insights.

## 🎯 Objectives

- Clean and preprocess retail transaction data
- Handle missing values, duplicate records, cancelled transactions, and invalid values
- Analyze sales, quantity, orders, products, customers, and countries
- Identify important sales trends and patterns
- Analyze product and customer performance
- Create meaningful data visualizations
- Generate useful business insights from the data

## 📊 Dataset

**Dataset:** UCI Online Retail Dataset

**Source:** UCI Machine Learning Repository

The dataset contains retail transactions with the following major attributes:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

The original dataset is not included in this repository. It can be downloaded from the UCI Machine Learning Repository.

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook
- GitHub

## 🧹 Data Cleaning

The following data-cleaning operations were performed:

- Removed records with missing product descriptions
- Removed cancelled transactions
- Removed duplicate records
- Removed transactions with non-positive quantities
- Removed transactions with non-positive unit prices
- Standardized product and country text
- Created a new `Sales` column using:

```python
Sales = Quantity × UnitPrice
