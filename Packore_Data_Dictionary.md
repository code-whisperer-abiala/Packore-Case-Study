# 📄 Packore Dataset Dictionary (Mock)

This project was built on a recreated dataset inspired by a classroom case scenario. Due to licensing restrictions, the original data is not included in this repository. Below is a description of the dataset schema used for analysis.

---

## 📁 Dataset 1: FinancialSummary_Enriched.xlsx

| Column Name           | Data Type | Description                                  |
|-----------------------|-----------|----------------------------------------------|
| Customer_ID           | String    | Unique identifier for each customer          |
| Year                  | Integer   | Fiscal year (2016–2020)                      |
| Total_Revenue         | Float     | Total revenue earned from the customer       |
| Total_COGS            | Float     | Cost of goods sold                           |
| Activity_Cost         | Float     | Total servicing costs from activity drivers  |
| Profit                | Float     | Net profit (Revenue – COGS – Activity Cost)  |
| Profit_Margin         | Float     | Profit as a % of Revenue                     |
| Tier                  | String    | Customer profitability segment (Star, etc.)  |

---

## 📁 Dataset 2: Revenue_Cost_Activity_Analysed.xlsx

| Column Name           | Data Type | Description                                  |
|-----------------------|-----------|----------------------------------------------|
| Product_Category      | String    | Product line (e.g., Cor Bo, Ass Ca)          |
| Total_Revenue         | Float     | Sales revenue from product                   |
| COGS                  | Float     | Cost of goods sold                           |
| Design_Cost           | Float     | Design-related servicing costs               |
| Query_Cost            | Float     | Customer support/query costs                 |
| Order_Processing_Cost | Float     | Back-office processing costs                 |
| Shipping_Cost         | Float     | Delivery and logistics costs                 |
| Net_Profit            | Float     | Revenue – COGS – Servicing Costs             |
| Profit_Margin         | Float     | Net profit as % of revenue                   |

---

📌 This schema reflects the simulated structure used in Tableau for dashboard development. All values were recreated for educational purposes and are not tied to any real-world company or customer.
