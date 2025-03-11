# ***Production Optimization and Downtime Reduction***

![Project Overview](https://github.com/PrathamAnalytics/Plant-Performance-Report-Power-BI-Project/blob/main/Image.png?raw=true)

# *Project Overview* 
This project analyzes operational and sales performance data for a plant's product portfolio over a two-year period. By leveraging data-driven insights, the project aims to identify trends, inefficiencies, and opportunities for strategic decision-making.

- **Data Sources:** [Plant_DTS.csv](https://github.com/PrathamAnalytics/Project-Production-Efficiency-and-Downtime-Analysis-for-Operational-Improvement/blob/main/Plant_DTS.csv).

  
# *Purpose of the Data* 
The primary purpose of the dataset is to:

1. Evaluate product-level performance in terms of sales, quantity, and profitability.
2. Understand customer-level buying patterns and associated revenue contributions.
3. Identify cost inefficiencies and pricing anomalies to improve overall margins.

# *Data Description* 
The dataset comprises 2,440 records with the following attributes:

- *Product_id* : Unique identifier for each product.
  
- *Sales_USD* : Revenue generated in USD.
  
- *quantity* : Number of units sold.
  
- *Price_USD* : Selling price per unit in USD.

- *COGS_USD* : Cost of Goods Sold (COGS) in USD.
  
- *Date_Time* : Transaction date.
  
- *Account_id* : Unique customer account identifier.

The data spans from **January 1, 2022, to April 14, 2024**, offering a comprehensive view of plant operations over 28 months.

# *Technical Overview* 
The project uses:

### *Data Analysis* :

- Statistical summaries to identify trends and anomalies.
- Temporal analysis to uncover seasonality or demand cycles.

### *Visualization* :

- Power BI report for dynamic insights and stakeholder presentations.

### *Metrics Computed* :

- Average sales per product.
- Profit margins (calculated as Sales - COGS).
- Product price variability and customer contribution analysis.

# *Executive Summary* 
The plant's product portfolio demonstrates a mixed performance with:

### *Average Sales* :

**$12,326.35** per product, with peak sales nearing **$19,993.98**.

### *Cost Efficiency* :

COGS averages **$7,423.59**, leaving room for potential margin improvements.

### *High Variability* :

Product pricing ranges from **$5.13 to $1,652.59**, indicating possible inefficiencies or premium pricing strategies for specific items.

### *Temporal Insights* :

- A steady sales growth trend is observed, especially in Q3 and Q4 of each year.
- Seasonal dips in early Q1 indicate potential off-peak demand challenges.

# *Top Insights* 
### **Revenue Leaders**:

Products in the top **10%** contribute over **40%** of total revenue.

### **Profitability**:

High-margin products **(>30%)** show a positive correlation with higher price points.

### **Customer Distribution**:

**20%** of customers contribute to **80%** of sales, confirming a Pareto distribution.

# *Key Insights*

### *Sales Dynamics* :

- Peak months: November and December, likely driven by holiday demand.
- Lowest sales: February, consistent with post-holiday slowdowns.

### *Product Performance* :

- **15%** of products are unprofitable due to high COGS exceeding sales.
- Products priced above **$50** have consistently higher margins.

### *Customer Insights* :

- Top 5 customers account for **25%** of total revenue.
- New customer acquisition rates have plateaued, indicating potential market saturation.

# *Recommendations* 

### 1. *Pricing Strategy* :

- *Reassess Low-Priced Products* :

Products priced below **$10**, while potentially driving volume, appear to contribute disproportionately to costs, making them potential loss leaders. These products should be reevaluated for their strategic purpose in the portfolio. Are they driving customer acquisition, or are they diluting margins without adding value? If the latter, consider phasing them out or increasing their price to align better with cost structures.

- *Dynamic Pricing Implementation* :

Seasonal demand trends show a marked increase in sales during Q4, especially in November and December. Implementing dynamic pricing during these months could help capitalize on heightened demand. For instance, increasing prices for high-demand products by **5-10%** during peak seasons could lead to a substantial uplift in revenue without significant volume reduction.

- *Premium Product Optimization* :

Products priced above **$50** consistently demonstrate higher margins. The plant should explore expanding this segment by introducing more premium-priced products or enhancing the perceived value of mid-tier products through bundling, improved packaging, or value-added features.

### 2. *Cost Management* :

- *Investigate COGS for Underperforming Products* :

Approximately **15%** of products have a negative margin where the COGS exceeds sales revenue. A detailed review of these products' supply chain, production processes, and raw material costs is critical. Identify if inefficiencies, such as outdated manufacturing methods or unoptimized supplier contracts, are driving these costs.

- *Renegotiate Supplier Agreements* :

For products with consistently thin margins, the plant should renegotiate terms with suppliers. Exploring bulk discounts, alternative sourcing options, or vertical integration (e.g., in-house production of certain components) could reduce costs by **5-15%**, depending on the supplier leverage.

- *Leverage Automation* :

If production processes rely heavily on manual operations, consider automating repetitive tasks to reduce labor costs and improve consistency in quality. The initial investment in automation may be offset by long-term cost savings.

### 3. *Customer Focus* :

- *Loyalty Program Development* :

With **20%** of customers contributing to **80%** of revenue, a targeted loyalty program can strengthen these relationships. Offering tiered benefits, such as discounts on bulk purchases, exclusive product access, or early sales notifications, can incentivize repeat purchases and solidify these high-value relationships.

- *Reactivation of Dormant Accounts* :

A significant portion of customers **(bottom 80%)** contribute minimally to overall revenue. Crafting tailored marketing campaigns, such as offering discounts on their next purchase or introducing them to new product lines, could re-engage these accounts and boost sales.

- *Customer Feedback Integration* :

Engage with key customers through surveys or interviews to understand their pain points and expectations. Insights gathered can guide product improvements, new offerings, or service enhancements, fostering loyalty and increasing satisfaction.

### 4. *Seasonal Preparedness* :

- *Inventory Planning for Peak Periods* :

Data shows that Q4 accounts for the highest sales volume, especially in November and December. The plant should ensure sufficient stock of top-performing products by Q3 to avoid missed sales opportunities due to stockouts. Collaborate with suppliers to guarantee timely deliveries and maintain buffer inventory for unexpected surges.

- *Promotions in Off-Peak Periods* :

Q1 consistently experiences the lowest sales, particularly in February. Introduce targeted promotions, such as discounts or bundled offers, during these months to stimulate demand. For example, a "New Year Savings" campaign could entice budget-conscious customers post-holiday season.

- *Season-Specific Marketing* :

Leverage the seasonality trends by creating campaigns that align with customer behavior. For example, "Back-to-School" promotions in August or "Holiday Specials" in December could drive increased traffic and sales.



# *Data Limitations* 
### *Granularity* :

The dataset lacks specific details on customer demographics and product categories.

### *Outdated Records* :

Data ends in April 2024, missing potential trends from the latter part of the year.

### *External Factors* :

No information on market conditions or competitors that could influence sales.

# *Conclusion*
This project highlights key strengths and weaknesses in the plant's operations. With actionable insights, such as revising pricing strategies, optimizing COGS, and targeting key customers, the plant is well-positioned to improve profitability and sustain growth. Addressing data limitations and incorporating external market insights will further refine strategic planning.
