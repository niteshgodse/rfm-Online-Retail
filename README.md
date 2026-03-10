# RFM Customer Segmentation using Retail Shopping Data

This project performs **RFM (Recency, Frequency, Monetary) analysis** on retail shopping data to understand customer purchasing behavior and identify valuable customer segments.

RFM analysis is widely used in **customer analytics, marketing strategy, and business intelligence** to detect loyal customers and improve retention strategies.

---

## Project Objective

The goal of this project is to analyze customer transaction data and segment customers based on:

- **Recency (R)** – How recently a customer made a purchase
- **Frequency (F)** – How often a customer makes purchases
- **Monetary (M)** – How much money a customer spends

These metrics help businesses identify **high-value customers, regular buyers, and low-engagement customers**.

---

## Dataset

The dataset contains retail shopping transaction data with the following information:

- Customer ID
- Invoice number
- Product category
- Quantity purchased
- Price
- Payment method
- Shopping mall
- Purchase date
- Customer demographics (age, gender)

---

## Methodology

The analysis follows these steps:

1. Load and explore the dataset using **pandas**.
2. Perform **data cleaning and preprocessing**.
3. Calculate **Recency** based on the most recent purchase date.
4. Calculate **Frequency** by counting the number of transactions per customer.
5. Calculate **Monetary value** by summing total purchase value.
6. Rank customers based on RFM metrics.
7. Normalize the rankings for comparison.
8. Compute an **average RFM score** to evaluate overall customer value.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Key Insights

RFM analysis helps businesses:

- Identify **loyal and high-value customers**
- Detect **inactive customers**
- Improve **targeted marketing campaigns**
- Support **data-driven business decisions**

