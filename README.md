# Task 15 — Customer Segmentation (RFM Analysis)

##  Project Overview

This project performs **customer segmentation using RFM (Recency, Frequency, Monetary) analysis** on an e-commerce dataset. The goal is to group customers based on their purchasing behavior and suggest business strategies for each segment.

RFM analysis helps businesses identify valuable customers and design targeted marketing campaigns.

---

##  Dataset

The dataset used is an **Online Retail e-commerce dataset** containing transaction records such as:

* Invoice number
* Product description
* Quantity purchased
* Invoice date
* Unit price
* Customer ID
* Country

---

##  Tools & Libraries Used

* Python
* Google Colab / Jupyter Notebook
* pandas
* numpy
* matplotlib

---

##  Steps Performed

1. **Data Loading** – Imported dataset using pandas.
2. **Data Cleaning**

   * Removed missing Customer IDs
   * Removed cancelled invoices
   * Converted invoice dates to datetime format
3. **Feature Engineering**

   * Created total purchase value column
4. **RFM Calculation**

   * Recency: Days since last purchase
   * Frequency: Number of purchases
   * Monetary: Total spending
5. **RFM Scoring**

   * Used quantile binning to assign RFM scores
6. **Customer Segmentation**

   * Grouped customers into segments such as:

     * Champions
     * Loyal Customers
     * Recent Customers
     * At Risk
7. **Visualization**

   * Bar chart of customer segments
8. **Export**

   * Saved segmented customer data as CSV

---

##  Business Insights

* Identified high-value customers (Champions)
* Detected customers at risk of churn
* Suggested marketing strategies for each segment

---

##  Deliverables

* `task15_rfm.ipynb` — Python notebook
* `rfm_segments.csv` — Segmented customer dataset

---

##  Outcome

This project demonstrates how RFM analysis can be used to:

* Understand customer behavior
* Improve customer retention
* Support data-driven marketing decisions

---

##  How to Run

1. Open Google Colab or Jupyter Notebook
2. Upload the dataset file
3. Run the notebook cells sequentially
4. Download the generated CSV file

---

##  Conclusion

RFM analysis is a powerful technique for customer segmentation. It enables businesses to create personalized marketing strategies and increase customer lifetime value.

---
