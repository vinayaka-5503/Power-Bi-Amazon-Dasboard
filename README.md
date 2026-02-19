# Power-Bi-Amazon-Dasboard
**Amazon Sales &amp; Logistics Performance Analysis**

This project features a comprehensive analysis of Amazon sales data, 
focusing on the intersection of sales revenue, customer segmentation, 
and logistics efficiency. By processing raw transactional data, 
I developed an interactive dashboard to visualize key performance indicators (KPIs) such as profit margins, 
shipping mode effectiveness, and regional sales distribution.

  !!!!!!! The goal of this analysis is to identify which product categories are most profitable and how 
  shipping discounts impact the bottom line across different US states. !!!!!!!!!

  The source data (Amazon_sales_Datasets.xlsx) 
  contains 20 columns of transactional data. 
  Below are the key fields used in the analysis:
  Column Name             TypeDescription             Order 
  ID                      String                      Unique identifier for each customer order.
  Category                String                      Product grouping (Furniture, Office Supplies, Technology).
  Sales                   Numeric                     Total gross revenue from the sale.
  Profit                  Numeric                     Net profit after accounting for costs and discounts.
  Discount%               Percentage                  The markdown applied to the product.
  Ship Mode               String                      Delivery method (Standard Class, First Class, Second Class, Same Day).
  Region                  String                      Geographic area (West, East, Central, South).
  Shipment Cost           Numeric                     The internal cost to ship the order to the customer.

🛠️ **Tech Stack**
$$ Data Source: Excel (cleaned and formatted)
$$ Analysis: Pivot Tables & Statistical Modeling
$$ Visualization: [Insert Tool: Power BI / Tableau / Excel Dashboards]
$$ Version Control: GitHub

🚀 **How to Use**
1)Clone the Repo:
  Bash
    git clone https://github.com/your-username/your-repo-name.git
2)Explore the Data: Open the Amazon_sales_Datasets.xlsx file in the /data folder.
3)Run the Analysis: If you use Python, you can load the data directly:
   Python
    import pandas as pd
    df = pd.read_csv('Amazon_sales_Datasets.csv')
    print(df.describe())

**Key Insights from the Data**
* Profit vs. Discount: High discount percentages (above 0.5) significantly correlate with negative profit margins in the Furniture category.
* Regional Dominance: The West region consistently outperforms others in both Sales volume and Profitability.
* Shipping Efficiency: "Standard Class" remains the most cost-effective shipping mode for high-volume consumer segments.

**🔍The Problem & Objective**
The primary goal of this analysis was to move beyond surface-level metrics to understand the "why" behind profit fluctuations.
 I aimed to identify which product categories—Technology, Office Supplies, or Furniture—yield the highest net margins and how
aggressive discounting strategies across different US states impact the bottom line. Furthermore, the project evaluates
logistics performance by analyzing the cost-to-delivery ratio of various shipping modes (Standard, First Class, etc.).

**🛠️Methodology & Tools**
The workflow involved extensive data cleaning and transformation using Python (Pandas) and Excel to handle null values and format
date-based logistics strings. Following the ETL (Extract, Transform, Load) phase, I developed an interactive dashboard to visualize
key performance indicators (KPIs). This visual layer allows stakeholders to drill down into regional performance, specifically 
comparing the high-volume West region against lower-margin territories.

📍**Key Findings**
The analysis revealed critical insights, such as the diminishing returns on specific furniture categories when discounts exceed 20%,
and the hidden overhead of "Same Day" shipping on low-value items. By centralizing these metrics, the project demonstrates
how data visualization can pinpoint operational inefficiencies.

🔗🗂️**Technical Impact**
This repository provides a blueprint for end-to-end sales analysis, offering a clean, 
documented dataset and a reproducible visualization framework suitable for retail analysts and supply chain managers.

<img width="770" height="432" alt="amazon dashboard " src="https://github.com/user-attachments/assets/3444bd62-ea08-4af1-8e96-e07cfef3e265" />
