# eCommerce Transactions Analysis

This repository contains a comprehensive analysis of an eCommerce Transactions dataset, consisting of three files: **Customers.csv**, **Products.csv**, and **Transactions.csv**. The primary objective is to perform exploratory data analysis (EDA), build predictive models, and derive actionable insights.

## Dataset Links

- [Customers.csv](https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing)
- [Products.csv](https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing)
- [Transactions.csv](https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing)

## Files Description

1. **Customers.csv**
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

## Assignment Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
1. Perform EDA on the provided dataset, including visualizations.
2. Derive at least 5 business insights from the EDA.
   - Insights should be concise, with a maximum of 100 words per insight.
   - Deliverables include a Jupyter Notebook/Python script with EDA code and a PDF report with insights (maximum 500 words).
   - **Visualizations**: Include relevant plots such as histograms, bar charts, and box plots to illustrate findings.

### Task 2: Lookalike Model
- Build a Lookalike Model that recommends 3 similar customers based on user profiles and transaction history.
- Deliverables include:
  - A CSV file with the top 3 lookalikes and their similarity scores for the first 20 customers (CustomerID: C0001 - C0020).
  - A Jupyter Notebook/Python script explaining the model development.

### Task 3: Customer Segmentation / Clustering
- Perform customer segmentation using clustering techniques based on both customer profiles and transaction information.
- Deliverables include:
  - A report on clustering results, including the number of clusters formed and clustering metrics like the DB Index.
  - A Jupyter Notebook/Python script containing the clustering code.

## Submission Instructions
1. Upload all PDF and code files in a public GitHub repository.
2. Follow the naming convention for all files:
   - `Shiva_Kandimalla_EDA.pdf`
   - `Shiva_Kandimalla_EDA.ipynb`
   - `Shiva_Kandimalla_Lookalike.csv`
   - `Shiva_Kandimalla_Lookalike.ipynb`
   - `Shiva_Kandimalla_Clustering.pdf`
   - `Shiva_Kandimalla_Clustering.ipynb`

## Evaluation Process
Submissions will be evaluated based on the following criteria:

| Task                       | Weightage |
|----------------------------|-----------|
| Exploratory Data Analysis   | 25%       |
| Business Insights           | 15%       |
| Lookalike Model            | 30%       |
| Customer Segmentation       | 30%       |

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Special thanks to the contributors and data providers.
