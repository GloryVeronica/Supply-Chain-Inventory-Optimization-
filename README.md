# Supply Chain & Inventory Optimization (OptiStock)

**Supply Chain & Inventory Optimization (OptiStock)**

**Project Overview**

OptiStock is a Power BI–based Supply Chain & Inventory Optimization dashboard designed to improve inventory visibility, reduce stockouts, minimize overstock, and optimize working capital.

The solution integrates Sales, Inventory, and Purchase Order data into a structured star schema model and delivers interactive insights for data-driven supply chain decision-making.

---

**Business Objectives**

- Reduce stockouts and overstock situations  
- Improve Sell-Through Rate  
- Optimize inventory turnover  
- Enable demand forecasting  
- Implement ABC-based product prioritization  
- Improve working capital efficiency  

---

**Data Model**

The dashboard is built using a Star Schema approach.

**Fact Tables**
- fSales
- fInventorySnapshots
- fPurchaseOrders

**Dimension Tables**
- dProduct
- dSupplier
- dWarehouse
- dDate

**Key DAX Measures**
- Total Sales  
- Total COGS  
- Inventory Value  
- Units Sold  
- Units Received  
- Sell-Through %  
- Stock Turn  
- Days on Hand (30-Day Trend)  
- ABC Classification  

---

**Dashboard Pages**

**1. KPI Overview**
- Total Sales: 1.05bn  
- Total COGS: 734.44M  
- Inventory Value: 193.68bn  
- Profit: 315.68M  
- Sell-Through Rate: 0.67%  
- Stockouts: 16  

**Insight:**  
Units Received significantly exceed Units Sold, indicating potential overstock.

---

**2. Inventory Overview**
- Inventory Value by Category  
- Units Sold by Category  
- Inventory Value by City  
- Avg Daily Sales (30D) by Category & Country  

**Insight:**  
Electronics holds the highest inventory value. Mumbai is the major inventory hub.

---

**3. Inventory Health**
- Scatter Plot: Days on Hand vs Units Sold  
- ABC Classification (A, B, C Products)  
- Stock Health Indicator  
- Product-Level Detail Table  

**Insight:**  
High Days on Hand and low Sell-Through confirm overstock risk across multiple products.

---

**4. Demand Forecast**
- Monthly Sales Trend  
- Forecast using Power BI Analytics Pane  
- 95% Confidence Interval  
- Automatic Seasonality Detection  

**Insight:**  
Forecast shows stable demand, but current inventory levels exceed projected needs.

---

**Key Insights**

- Low Sell-Through Rate (0.67%) indicates excess inventory  
- High Days on Hand confirms slow stock movement  
- ABC Analysis enables better prioritization  
- Forecasting supports proactive procurement planning  
- Inventory capital optimization opportunity identified  

---

**Tools & Technologies**

- Power BI Desktop  
- DAX (Advanced Measures & Time Intelligence)  
- Star Schema Data Modeling  
- Power BI Service (Cloud Publishing)  
- Scheduled Data Refresh  

---

**Strategic Recommendations**

- Align procurement with forecasted demand  
- Reduce overstock through targeted clearance strategies  
- Implement ABC-based inventory control  
- Monitor Days on Hand regularly  
- Improve Sell-Through via pricing and promotions  

---

**Conclusion**

The OptiStock dashboard transforms operational data into actionable supply chain intelligence.  
It enables better inventory control, reduces working capital lock-in, and supports strategic procurement decisions through data-driven insights and forecasting.
