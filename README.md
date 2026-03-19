# ☕ Coffee Shop Sales Analysis: Interactive Dashboard

## 🎯 Objective
The primary goal of this project is to transform raw transactional data from **Maven Roasters** (three coffee shop locations in NYC) into an interactive and actionable Excel Dashboard. 

By analyzing six months of sales data (January – June 2023), this project aims to:

*   **Identify Trends:** Pinpoint peak sales hours and busiest days of the week to optimize staffing.
*   **Analyze Product Performance:** Determine which products (e.g., Brewed Chai Tea vs. Gourmet Coffee) drive the most revenue.
*   **Store Comparison:** Compare performance across the three different NYC locations.
*   **Data-Driven Decisions:** Provide the franchise owner with clear visuals to support inventory and marketing strategies.

## Dataset used
- <a href="https://github.com/shettyvicky993-maker/Coffee-Shop-Sales-Analysis-Project/blob/main/Coffee%2BShop%2BSales.zip">Dataset</a>
---

## 🛠️ Tools & Technologies Used  
- Microsoft Excel  
- PivotTables  
- Excel Formulas (`SUM`, `TEXT`, `IF`, etc.)  
- Data Cleaning Techniques  
- Dashboard Design  

---
## 🧹 Data Preparation  
- Reviewed and understood all dataset fields  
- Created additional columns from `transaction_date`:  
  - Month → `=TEXT(D2,"mmmm")`  
  - Day Name → `=TEXT(D2,"dddd")`  
- Created a **Revenue column** using:  
  - `=transaction_qty * unit_price`  
- Cleaned and structured the dataset for analysis  

---

## 📊 Dashboard Features  

- 🔍 **Interactive Filters (Slicers):**  
  - Location (Astoria, Hell’s Kitchen, Lower Manhattan)  
  - Month (Jan – Jun)  
  - Product  
---
- 📈 **Visualizations Included:**  
  - **Months vs Revenue** (Trend Analysis)  
  - **Day vs Transactions** (Weekly Pattern)  
  - **Hour vs Transactions** (Peak Hours)  
  - **Product vs Transactions** (Top Products)  
  - **Transaction vs Revenue** (Product Contribution)
---
## 📷 Dashb<img width="1870" height="777" alt="coffee dashboard" src="https://github.com/user-attachments/assets/7c5dc734-1167-4b23-a280-2526f11fd880" />
<img width="1870" height="777" alt="coffee dashboard" src="https://github.com/user-attachments/assets/7c5dc734-1167-4b23-a280-2526f11fd880" />
oard Preview  
![Dashboard]()

---
- **Revenue Trend:**  
  Revenue shows consistent growth, with **June being the highest (~$166K)**, indicating strong seasonal demand.  

- **Peak Days:**  
  Transactions are highest on **weekdays (especially Friday)**, showing strong commuter demand.  

- **Peak Hours:**  
  Sales peak during **morning hours (8 AM – 10 AM)**, highlighting breakfast-time demand.  

- **Top Products:**  
  - Coffee (**58,416 units**)  
  - Tea (**45,449 units**)  
  These two categories contribute nearly **70% of total sales**.  

- **Low Performing Products:**  
  Items like packaged chocolate and branded products have minimal sales.  
---
## 💡 Business Recommendations  

- **Bundle Strategy:**  
  Launch *“Morning Combo”* (Coffee + Bakery item) to increase average order value.  

- **Loyalty Programs:**  
  Introduce rewards like *“Buy 5 Teas, Get 1 Free”* to retain frequent customers.  

- **Upselling:**  
  Promote low-selling products alongside popular items.  

- **Staffing Optimization:**  
  Increase staffing during **morning peak hours and Fridays**.  

- **Seasonal Planning:**  
  Prepare inventory and workforce from **April onwards** to handle Q2 demand growth.  
---
## 📁 Dataset Description  
The dataset includes:  
- Transaction ID  
- Transaction Date & Time  
- Store Location  
- Product Name & Category  
- Quantity Sold  
- Unit Price  
- Revenue
---

## 🚀 Conclusion  
This project demonstrates how Excel can be effectively used to analyze business data and create interactive dashboards.  

The insights derived help improve operational efficiency, boost sales strategies, and support better decision-making.  

---

## 📌 Changelog  

### [1.0.0] - Data Preparation  
- Data cleaning and understanding  
- Created Month, Day, and Revenue columns  

### [1.1.0] - Dashboard Creation  
- Built interactive dashboard with slicers  
- Added charts for trends and performance  

### [1.2.0] - Final Insights  
- Extracted key insights  
- Added business recommendations  
- Finalized documentation
