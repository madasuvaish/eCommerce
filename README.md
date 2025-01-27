# Project Title

**Project Name**: eCommerce Transactions Analysis

This repository contains a detailed analysis of an eCommerce transactions dataset, comprising customer, product, and transaction information. The project is divided into three key tasks: **Exploratory Data Analysis (EDA)**, **Lookalike Model**, and **Customer Segmentation using Clustering**. The objective is to derive actionable insights from the data, build a model that recommends similar customers, and segment customers based on their transaction patterns.

## Project Overview

The dataset consists of three CSV files:

1. **Customers.csv**: Information about each customer.
2. **Products.csv**: Information about products sold in the eCommerce store.
3. **Transactions.csv**: Transaction details including product purchases by customers.

## Tasks

### 1. **Exploratory Data Analysis (EDA)**
- Perform data cleaning and exploration to understand patterns in customer behavior, product preferences, and transaction trends.
- Derive key business insights such as:
  - Most popular products
  - Revenue by region
  - High-value customers
  - Seasonal trends in transactions

### 2. **Lookalike Model**
- Build a model to recommend similar customers based on their profile and transaction history.
- The model calculates a similarity score for each customer and recommends the top 3 similar customers for each of the first 20 customers.
- Output: A `Lookalike.csv` file containing customer IDs and their top 3 lookalikes with similarity scores.

### 3. **Customer Segmentation / Clustering**
- Use customer profile and transaction information to segment customers into distinct groups based on their behavior.
- Apply clustering techniques such as **K-Means** or **DBSCAN** and evaluate clusters using the **DB Index**.
- Visualize the clusters and analyze their characteristics (e.g., high-spending customers, frequent buyers).


