# **Data Science Assignment - eCommerce Transactions Dataset**

## **Author:**
**Gaurav Sharan**

This repository contains solutions for three data science assignments related to an eCommerce transactions dataset, focusing on Exploratory Data Analysis (EDA), Lookalike Analysis, and Customer Segmentation. The dataset comprises customer profiles, product details, and transaction records to derive meaningful insights and support business decisions. The EDA phase analyzes customer demographics, product categories, and purchasing trends to uncover patterns. The Lookalike Analysis identifies customers with similar buying behaviors to enhance targeted marketing efforts. The Customer Segmentation task groups customers based on their transactional behavior, optimizing clusters using evaluation metrics such as the Davies-Bouldin Index, achieving a value of 0.518, which indicates well-separated clusters. The project follows the required submission structure and includes Jupyter Notebooks and corresponding PDF reports summarizing the findings. To run the project, clone the repository, install the required dependencies, and execute the provided notebooks to reproduce the results.

## **Dataset Description**
The following datasets were used across all assignments:

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

---

## **Project Structure**
The project files follow the required naming conventions:

- **Exploratory Data Analysis (EDA):**  
  - `GAURAV_SHARAN_EDA.ipynb` – Jupyter Notebook for EDA.  
  - `GAURAV_SHARAN_EDA.pdf` – EDA summary report.  

- **Lookalike Analysis:**  
  - `GAURAV_SHARAN_Lookalike.csv` – Lookalike analysis results.  
  - `GAURAV_SHARAN_Lookalike.ipynb` – Jupyter Notebook for analysis.  

- **Customer Clustering:**  
  - `GAURAV_SHARAN_Clustering.ipynb` – Notebook for clustering implementation.  
  - `GAURAV_SHARAN_Clustering.pdf` – Clustering results report.  

---

## **How to Run the Code**

1. Clone the repository using:

   ```bash
   git clone https://github.com/gaurav8707/Data-Science-Assignment-eCommerce-Transactions-Dataset.git
