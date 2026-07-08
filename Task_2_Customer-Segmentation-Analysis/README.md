# Customer Segmentation Analysis Using K-Means Clustering

## Project Overview

This project performs Customer Segmentation on an e-commerce dataset using RFM (Recency, Frequency, Monetary) Analysis and the K-Means Clustering algorithm. The objective is to identify different customer groups based on their purchasing behavior, enabling businesses to create targeted marketing strategies and improve customer retention.

---

## Objective

- Analyze customer purchasing behavior.
- Create RFM (Recency, Frequency, Monetary) features.
- Standardize customer features using StandardScaler.
- Determine the optimal number of clusters using the Elbow Method.
- Apply K-Means Clustering.
- Visualize customer segments.
- Generate business insights for each customer segment.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

- Load dataset
- Inspect data structure
- Check data types

### 2. Exploratory Data Analysis (EDA)

- Dataset information
- Summary statistics
- Missing values
- Duplicate records

### 3. Data Cleaning

- Remove missing Customer IDs
- Remove duplicate records
- Remove invalid Quantity values
- Remove invalid Price values
- Convert InvoiceDate to datetime format

### 4. Feature Engineering

Created:

- TotalAmount = Quantity × Price

---

### 5. RFM Analysis

Generated three customer behavior metrics:

- **Recency** – Days since last purchase
- **Frequency** – Number of unique purchases
- **Monetary** – Total customer spending

---

### 6. Data Standardization

Used:

- StandardScaler

to normalize RFM features before clustering.

---

### 7. K-Means Clustering

- Applied Elbow Method
- Selected optimal K = 3
- Built K-Means clustering model
- Assigned cluster labels to customers

---

### 8. Cluster Profiling

Calculated average:

- Recency
- Frequency
- Monetary

for each cluster.

---

### 9. Data Visualization

The project includes:

- Elbow Method
- Customers per Cluster
- Average Recency by Cluster
- Average Frequency by Cluster
- Average Monetary by Cluster
- Recency vs Monetary Scatter Plot
- Frequency vs Monetary Scatter Plot
- Recency vs Frequency Scatter Plot

---

## Results

Three customer segments were identified.

### Cluster 0 – Regular Customers

Characteristics:

- Moderate recency
- Moderate purchase frequency
- Moderate spending

Business Strategy:

- Loyalty programs
- Personalized recommendations
- Seasonal offers

---

### Cluster 1 – Lost Customers

Characteristics:

- Long time since last purchase
- Low purchase frequency
- Low spending

Business Strategy:

- Win-back campaigns
- Discount coupons
- Reminder emails

---

### Cluster 2 – VIP Customers

Characteristics:

- Recent purchases
- Very high purchase frequency
- Highest spending customers

Business Strategy:

- VIP rewards
- Premium customer support
- Exclusive offers
- Early access to products

---

## Business Insights

Customer segmentation helps businesses:

- Improve customer retention
- Increase sales
- Identify high-value customers
- Reduce marketing costs
- Create personalized marketing campaigns

---

## Project Structure

```
Customer-Segmentation-Analysis
│
├── data
│   └── online_retail_II.csv
│
├── notebook
│   └── Customer_Segmentation.ipynb
│
├── images
│   ├── elbow_method.png
│   ├── customers_per_cluster.png
│   ├── average_recency.png
│   ├── average_frequency.png
│   ├── average_monetary.png
│   ├── recency_vs_frequency.png
│   ├── recency_vs_monetary.png
│   └── frequency_vs_monetary.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Author

**MD AMIR**