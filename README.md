# 📊 E-Commerce Customer Churn Analysis

## 🧾 Overview

Analyzed 100,000+ real-world e-commerce transactions from Olist, a Brazilian marketplace, to identify customers at risk of churning using RFM (Recency, Frequency, Monetary) segmentation. Built an interactive Tableau dashboard to visualize customer behavior, segment distribution, and revenue impact.

---

## 🎯 Key Findings

- 41% of customers (38,343) are at risk of churning  
- At Risk segment represents over R$6M in potential revenue loss  
- Majority of customers are one-time buyers, indicating low retention  
- Champions spend ~3x more than average customers (R$480 vs R$158)  
- November 2017 (Black Friday) showed a ~50% surge in revenue  

---

## 🛠️ Tech Stack

- 🐍 **Python (Pandas, Matplotlib)** – Data cleaning, preprocessing, and exploratory data analysis  
- 🗄️ **SQL** – Data querying and aggregation  
- 📊 **Tableau Public** – Interactive dashboard development  
- ☁️ **Google Colab** – Development and analysis environment  

---

## 📁 Data Source

- **Dataset:** Olist E-Commerce Dataset (Brazil)  
- **Size:** 100,000+ transactions  
- **Contents:**  
  - Customer purchase behavior  
  - Order details and timestamps  
  - Payment and pricing data  
  - Product categories and transaction history  

The dataset enables behavioral segmentation and revenue analysis across different customer groups.

---

## 🚀 Features / Highlights

### 🔹 Business Problem

E-commerce platforms often struggle with customer retention and identifying churn risks early.  

Key questions addressed:
- Which customers are likely to churn?  
- How much revenue is at risk due to churn?  
- Which customer segments drive the most value?  
- How does customer behavior vary across segments?  

---

### 🔹 Goal of the Project

To build a data-driven solution that:
- Segments customers based on behavior using RFM analysis  
- Identifies high-risk and high-value customer groups  
- Quantifies revenue contribution across segments  
- Supports targeted retention and engagement strategies  

---

### 🔹 Walkthrough of Key Visuals

#### 🔸 Customer Segments Distribution
- Bar chart showing customer counts across segments such as At Risk, Champions, Loyal, Hibernating, and Lost  
- Helps identify the largest and most critical segments  

---

#### 🔸 Revenue by Segment
- Compares total revenue contribution across segments  
- Highlights high-value segments and revenue concentration  

---

#### 🔸 RFM Heatmap
- Visual representation of Recency, Frequency, and Monetary scores  
- Helps understand customer behavior patterns across segments  

---

#### 🔸 Recency vs Expenditure (Scatter Plot)
- Shows relationship between customer recency and spending  
- Identifies high-value customers and churn-prone users  

---

#### 🔸 Segment Breakdown
- Pie chart summarizing proportion of customers across segments  
- Provides a quick overview of customer distribution  

---

## 📈 Business Impact & Insights

- **Revenue at Risk:** A significant portion of revenue (R$6M+) is tied to at-risk customers  
- **Customer Retention Gap:** High proportion of one-time buyers indicates weak retention strategy  
- **High-Value Segments:** Champions and Loyal customers contribute disproportionately to revenue  
- **Behavioral Insights:** Recency strongly correlates with spending patterns  
- **Seasonal Trends:** Revenue spikes during major events like Black Friday  

---

## 💡 Business Recommendations

- Target At Risk customers with personalized discount campaigns to recover revenue  
- Reward Champions with loyalty programs to maintain high-value customers  
- Re-engage Hibernating customers through targeted email campaigns  
- Improve retention strategies to reduce one-time buyer drop-off  

---

## 📸 Dashboard / Demo

🔗 **View Live Tableau Dashboard:** *(Add your Tableau Public link here)*

---

## 📂 Project Structure

- `ecommerce_churn_analysis.ipynb` – Full analysis and RFM segmentation  
- `rfm_segments.csv` – Customer segmentation dataset  
- `distribution_plots.png` – Price, freight, and payment distributions  
- `monthly_revenue.png` – Revenue trend over time  
- `category_revenue.png` – Top product categories  
- `rfm_segments.png` – Segment visualization  

---

## 📊 RFM Segments Summary

| Segment            | Customers | Avg Spend | Total Revenue |
|------------------|----------|----------|---------------|
| Loyal Customers  | 31,582   | R$279    | R$8.8M        |
| At Risk          | 38,343   | R$158    | R$6.06M       |
| Champions        | 7,975    | R$480    | R$3.8M        |
| Hibernating      | 12,295   | R$72     | R$887K        |
| Lost             | 3,140    | R$48     | R$150K        |
