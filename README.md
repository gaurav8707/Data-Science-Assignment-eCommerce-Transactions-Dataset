# Data-Science-Assignment-eCommerce-Transactions-Dataset

# **Customer Segmentation Project**

## **Author:**
**Gaurav Sharan**

## **Project Overview**
This project focuses on customer segmentation using clustering techniques based on customer profile and transaction data.  
The clustering was evaluated using the **Davies-Bouldin Index (DBI)** to ensure high-quality segmentation.

## **Dataset Description**
The project utilizes the following datasets:

### **Customers.csv** – Contains customer profile details such as:  
- `CustomerID`  
- `CustomerName`  
- `Region`  
- `SignupDate`  

### **Transactions.csv** – Provides transaction details, including:  
- `TransactionID`  
- `CustomerID`  
- `ProductID`  
- `TransactionDate`  
- `Quantity`  
- `TotalValue`  

---

## **Project Structure**
The project follows the naming convention as per submission guidelines:

### **Exploratory Data Analysis (EDA)**
- `GAURAV_SHARAN_EDA.ipynb` - Jupyter Notebook for EDA.  
- `GAURAV_SHARAN_EDA.pdf` - PDF report summarizing the EDA.  

### **Lookalike Analysis**
- `GAURAV_SHARAN_Lookalike.csv` - CSV file containing lookalike results.  
- `GAURAV_SHARAN_Lookalike.ipynb` - Jupyter Notebook for lookalike analysis.  

### **Customer Clustering**
- `GAURAV_SHARAN_Clustering.ipynb` - Jupyter Notebook for clustering implementation.  
- `GAURAV_SHARAN_Clustering.pdf` - PDF report summarizing clustering results.  

---

## **Clustering Methodology**

### **Data Preprocessing:**
- Encoding categorical features.  
- Aggregating transaction data.  
- Standardizing numerical values.  

### **Feature Engineering:**
- Signup year extraction.  
- Transaction count calculation.  

### **Clustering Algorithms Evaluated:**
1. **K-Means Clustering**  
2. **Gaussian Mixture Model (GMM)**  
3. **Agglomerative Clustering (Optimal selection)**  

### **Evaluation Metrics:**
- **Davies-Bouldin Index (Achieved: 0.518)**  
- **Cluster Distribution Analysis**  

---

## **Results and Findings**

- **Optimal Number of Clusters:** 3  
- **DB Index:** 0.518 (indicating well-separated clusters)  

### **Cluster Insights:**
- **Cluster 0:** Majority of customers.  
- **Cluster 1:** High-value customer.  
- **Cluster 2:** Low-engagement customers.  

---

## **How to Run the Code**

1. Clone the repository using:

   ```bash
   git clone https://github.com/gaurav8707/Data-Science-Assignment-eCommerce-Transactions-Dataset.git

