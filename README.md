# 🏙️ TechMed Analysis Report 2023-2024
You are a business analyst for a pharmaceutical wholesaler with a portfolio of **3000 SKUs**, supplying various **clients** such as:
- General Practitioners (GPs)
- Specialist Doctors
- Pharmacies, and
- Supermarkets

Each customer segment has different purchasing behaviors and preferences. The GM wants to segment customers correctly to allow better service, price offering, and optimize product portfolio to increase revenue and profitability, focusing on the effectiveness of the product assortment for each customer segment.

---

##  🧼 Objectives

- Analyze the data provided and offer **insights** that can guide strategic decisions.
- Carry out data analysis and highlight the **assumptions** make to reach the conclusions.
- And what other data would help to **strengthen the analytics in the future**.

---

## 📈 KPI

- Monthly Trend: Total Sales / Qty per mth / yrs
- Min / Max Sales & Qty per yrs / group / customer
- Top Customer-Group by total Sales & Qty (Pareto line)
- Top 5 High-Spending Customers by each group
- Top N SKUs contribution to Total Sales (Pareto line)
- Top 15 High-Selling SKUs

---

## 📊 Analysis

**Pareto Principle (80/20 rules)**: **80% total sales** rely on **TOP 499** (out of 2,815) **SKUs** and **TOP 3** (out of 10) **Customer Group**
- `PH-CHAIN`
- `CLINIC-SP`
- `CLINIC-GP`

**Target on High-Spending Customers per Customer Group**, Eg:
- `PH-CHAIN` has ONLY 4 **loyalty** customer, but has the Top 1 total Sales and Top 1 total Qty.
- different **pricing strategy** given: promotions / discounts / bundle sales
  
| Group     | SKUs focus                         | Pricing strategy                                 |
|-----------|------------------------------------|--------------------------------------------------|
| PH        | branded                            | offer assortment full-upsell combos              | 
| CL        | antibiotics, painkillers           | focus on essentials                              | 
| SP        | injectables                        | bundle by specialty (cardio / derm...)           | 
| SPERMARKET| supplements, consumer health goods | push high-margin retail-friendly + low cost SKU  |


**Focus on Customers Group / customers / SKUs performance ranking**, which has similar HIGH Total Sales, but has **Highest / Lowest Qty**.
- Low QTY: more profit margin per SKU ? expensive?
- High QTY: no profit? cheaper? 

---

## 🛠 Future Improvement

- Predictive Modeling: Discounts / promotions / marketing campaigns / events time needed to understand the seasonality fluctuations
- SKU category: for segment-specific assortment planning, link top SKUs with customer type to guide assortment by segment
- SKU price & cost: calculate price elasticity / price sensitive analysis / gross margin analysis
- Customer Purchase channel (online/direct sales/...): help with analysis purchasing behaviour
- SKU Rationalization: highlight 0 or Negative sales/qty, flag for review / discontinuation






---

## 📁 Output File

- Python file: `TechMed.ipynb`
- CSV file saved as: `customer_data.csv` & `item_data.csv` 
- Excel file saved as: `customer_data.xlsx` & `item_data.xlsx`
- Excel file (2 worksheet in 1 Excel file) saved as: `combined_data.xlsx` 

Stored in the same working directory  

---

## 🔗 Tableau Dashboard

👉 [Open Dashboard in Tableau](https://public.tableau.com/views/TechMed/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---
