# Advanced Retail Analytics: Customer Segmentation & Retention

## Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on a dataset of over 540,000 historical e-commerce retail transactions. The objective is to extract actionable business intelligence by segmenting the customer base and analyzing purchasing lifecycles to optimize marketing spend and improve customer retention.

**Target Role:** Data Analytics Associate (DAA)  
**Domain:** Retail & E-Commerce Analytics  

---

## Business Value & Strategic Frameworks
Rather than focusing solely on aggregate sales volume, this analysis utilizes two highly respected consulting frameworks to evaluate individual customer behavior:

1. **RFM (Recency, Frequency, Monetary) Segmentation:** 
   Evaluated the customer base to identify high-value "Champions" and "At-Risk VIPs," allowing for targeted, budget-efficient marketing campaigns rather than generic mass-emailing.
2. **Time-Series Cohort Analysis:** 
   Tracked monthly customer retention rates from the date of their first purchase to visualize churn velocity and identify critical drop-off points in the customer lifecycle.

---

## Tech Stack
*   **Language:** Python 3
*   **Data Manipulation:** `pandas`, `numpy`
*   **Data Visualization:** `matplotlib`, `seaborn`
*   **Environment:** Jupyter Notebook

---

## Key Insights & Strategic Recommendations

### 1. The "Champion" Revenue Imbalance
*   **Finding:** A financial distribution analysis (boxplot) revealed that a very small fraction of customers (Champions and Loyal Customers) drives the vast majority of total revenue. 
*   **Action:** Marketing acquisition budgets should be immediately reallocated toward retention and VIP programs for these top-tier segments, as their lifetime value vastly outperforms newly acquired average customers.

### 2. The Month-One Retention Crisis
*   **Finding:** The Cohort Analysis heatmap exposed a severe customer churn rate, averaging an 80% drop-off in returning customers immediately after their first month of purchase.
*   **Action:** Implement an automated onboarding sequence and a targeted "Welcome Back" discount triggered exactly 14 days after a user's first purchase to bridge the month-one drop-off gap.

---

## Dataset Information
The analysis utilizes a publicly available Global E-commerce dataset containing over 540,000 transactional records. The dataset includes line-item details such as Invoice Number, Stock Code, Quantity, Invoice Date, Unit Price, and Customer ID.

---

## How to Run Locally

1. **Clone this repository:**
   ```bash
   git clone [https://github.com/Aditya-scp/Retail-Customer-Segmentation.git](https://github.com/Aditya-scp/Retail-Customer-Segmentation.git)

2. **Install the required libraries:**
   ```bash
   pip install pandas matplotlib seaborn

3. **Launch the analysis:**

Open Advanced_Retail_Analytics_Project.ipynb in Jupyter Notebook to view the code, visualizations, and business commentary.
   
