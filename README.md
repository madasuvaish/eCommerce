# E-Commerce Transactions Analysis & Customer Insights

## Project Overview

### Objective:
This project aims to analyze eCommerce transaction data and derive actionable business insights. The goal is to:
1. Perform Exploratory Data Analysis (EDA) to understand customer behavior and transaction trends.
2. Build a Lookalike Model to recommend similar customers based on transaction history and profiles.
3. Segment customers into distinct groups using clustering techniques and analyze their purchasing patterns.

### Dataset:
The dataset consists of three CSV files:
- **Customers.csv**: Contains customer profile information.
- **Products.csv**: Contains details about products sold in the eCommerce store.
- **Transactions.csv**: Contains transaction records, including product purchases by customers.

---

## Tasks

### 1. Exploratory Data Analysis (EDA):
In this step, the data will be cleaned and explored to understand patterns in customer behavior, product preferences, and transaction trends. The key insights to derive include:
- **Most Popular Products**: Identifying products with the highest sales.
- **Revenue by Region**: Analyzing revenue distribution across different regions.
- **High-Value Customers**: Identifying top customers based on their transaction history.
- **Seasonal Trends in Transactions**: Analyzing the seasonal patterns in sales.

### 2. Lookalike Model:
A model is built to recommend similar customers based on their profile and transaction history. The model calculates a similarity score for each customer and provides the top 3 similar customers for the first 20 customers.
- **Output**: A CSV file (`Lookalike.csv`) containing customer IDs and their top 3 similar customers, along with the similarity scores.

### 3. Customer Segmentation / Clustering:
Using customer profile and transaction data, customers will be grouped into distinct segments based on their behavior. Clustering techniques like **K-Means** or **DBSCAN** will be applied, and clusters will be evaluated using the **DB Index**.
- **Analysis**: The clusters will be analyzed to understand customer behavior such as high-spending or frequent-buying patterns.
- **Visualization**: Cluster visualization will be provided to better understand the segmentation.

---

## File Structure

The project contains the following files:

- **Customers.csv**: Contains details of each customer (e.g., customer ID, demographics).
- **Products.csv**: Contains information about products (e.g., product ID, name, category).
- **Transactions.csv**: Records of transactions made by customers (e.g., customer ID, product ID, transaction amount).

---

## Technologies/Tools Used

- **Python**: Main programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **Scikit-learn**: Machine learning library for clustering and similarity modeling.
- **Matplotlib**: Data visualization.
- **Seaborn**: Advanced statistical data visualization.

---

## How to Run the Project

To set up and run this project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/ecommerce-transactions-analysis.git
   cd ecommerce-transactions-analysis
pip install -r requirements.txt
python eda.py
python lookalike_model.py
python clustering.py
