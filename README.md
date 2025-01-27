# Data-Science-Assignment-eCommerce-Transactions-Dataset-Zeotap

## Project Overview
This project involves analyzing an eCommerce Transactions dataset comprising three files:

- *Customers.csv*: Information about customers.
- *Products.csv*: Details of products.
- *Transactions.csv*: Records of transactions.
  
Your tasks include performing exploratory data analysis (EDA), building predictive models, and deriving actionable insights. This assignment will test your skills in data analysis, machine learning, and business insights.

---
## Dataset Description
1. Customers.csv
CustomerID: Unique identifier for each customer.
CustomerName: Name of the customer.
Region: Continent where the customer resides.
SignupDate: Date when the customer signed up.

3. Products.csv
ProductID: Unique identifier for each product.
ProductName: Name of the product.
Category: Product category.
Price: Product price in USD.

5. Transactions.csv
TransactionID: Unique identifier for each transaction.
CustomerID: ID of the customer who made the transaction.
ProductID: ID of the product sold.
TransactionDate: Date of the transaction.
Quantity: Quantity of the product purchased.
TotalValue: Total value of the transaction.

---
## Assignment Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
Perform EDA on the provided dataset.
Derive at least 5 business insights from the EDA in short point-wise sentences (maximum 100 words per insight).
Deliverables:

A Jupyter Notebook/Python script containing your EDA code.
A PDF report summarizing your business insights (maximum 500 words).

### Task 2: Lookalike Model
Build a Lookalike Model to recommend 3 similar customers for each input customer based on their profile and transaction history. The model should:

Use both customer and product information.
Assign a similarity score to each recommended customer.
Deliverables:

A file named Lookalike.csv with a mapping: CustomerID → List[CustomerID, SimilarityScore] for the first 20 customers (CustomerID: C0001 to C0020).
A Jupyter Notebook/Python script explaining the model's logic.


### Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques, combining:

Profile information from Customers.csv.
Transaction data from Transactions.csv.
Requirements:

Use a clustering algorithm of your choice (2 to 10 clusters).
Calculate clustering metrics, including the DB Index.
Visualize the clusters using relevant plots.
Deliverables:

A report on clustering results, including:
Number of clusters formed.
DB Index value.
Other relevant metrics.
A Jupyter Notebook/Python script for clustering.

---



## How to Run the Code
Clone or download the repository containing this dataset and scripts.
Install the required Python libraries (pandas, numpy, matplotlib, scikit-learn, etc.).
Run the Jupyter Notebooks provided for each task.


---
![Screenshot 2025-01-27 234848](https://github.com/user-attachments/assets/c13aa1c5-9783-4bc8-869e-d811c392954b)

![Screenshot 2025-01-27 234919](https://github.com/user-attachments/assets/d906dfe0-4f10-4f62-8d4b-325f89e289a8)

![Screenshot 2025-01-27 234941](https://github.com/user-attachments/assets/4a3b37df-06ca-4ce6-a607-7de53b53912d)

![Screenshot 2025-01-27 235007](https://github.com/user-attachments/assets/45cd7e57-1114-42be-8cea-be08b2dc6eaf)

![Screenshot 2025-01-27 235024](https://github.com/user-attachments/assets/1995c03c-50a2-4932-b83f-1430a825d924)

![Screenshot 2025-01-27 235047](https://github.com/user-attachments/assets/b8a821a9-f222-435f-ae0a-183d65f83594)

![Screenshot 2025-01-27 235058](https://github.com/user-attachments/assets/3c07b285-7deb-4300-8778-907a61ada2d7)



