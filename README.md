# 📊 Power BI Retail Analytics: End-to-End Business Intelligence

This project transforms 500,000+ raw retail transactions into a professional business intelligence suite. The solution moves beyond simple reporting to provide actionable insights on customer behavior, product performance, and sales trends.

---

## 1. Executive Overview Dashboard
**Purpose:** A high-level command center for stakeholders to monitor business health at a glance.

![Executive Dashboard](dashboards/Executive Overview Dashboard.png)

* **Key KPIs:** Tracks Total Revenue ($9.75M), Order Volume, and AOV ($410) with dynamic MoM growth indicators.
* **Revenue Trends:** Visualizes monthly performance to identify macro-trends and seasonality.
* **Top Performers:** Highlights top-selling products and key international markets (led by the UK).
* **Customer Split:** Instantly shows the revenue contribution between Retail and Wholesale segments.

---

## 2. Sales & Time Intelligence Dashboard
**Purpose:** Advanced temporal analysis to identify *when* customers shop and seasonal patterns.

![Sales Time Intelligence](link_to_your_time_intelligence_image.png)

* **Seasonal Heatmap:** A matrix visual highlighting peak sales periods (Day of Week vs. Month), revealing strong Q4 activity.
* **Hourly Operations:** Analysis of sales by hour (6 AM – 8 PM) to optimize staffing and warehouse operations.
* **Time Intelligence:** compares current performance against rolling 3-month averages to smooth out volatility and identify true trends.
* **Quarterly Performance:** Clear comparison of revenue across fiscal quarters.

---

## 3. Customer Analytics Dashboard
**Purpose:** Understanding *who* the customers are using advanced segmentation logic.

![Customer Analytics](link_to_your_customer_analytics_image.png)

* **RFM Analysis:** A "Whale Detector" scatter plot segmenting customers by Recency and Monetary value to identify VIPs vs. Churned users.
* **Customer Health:** Tracks New vs. Returning customer rates and calculates Historic Customer Lifetime Value (CLV).
* **Segmentation:** Breaks down the user base into actionable cohorts (Champions, At Risk, New Customers) to drive marketing strategies.
* **Behavioral Insights:** Analyzes purchase frequency to distinguish one-time buyers from loyal repeat purchasers.

---

## 4. Product Performance Dashboard
**Purpose:** A deep dive into inventory efficiency and profit drivers.

![Product Performance](link_to_your_product_performance_image.png)

* **Pareto Analysis (80/20 Rule):** A combo chart combining Revenue bars with a cumulative % line, identifying the "Vital Few" products that drive 80% of revenue.
* **Product Matrix:** A cross-tabulation of top products against key countries, helping to tailor regional inventory.
* **Scatter Plot:** A detailed view of Quantity Sold vs. Total Revenue to spot high-volume/low-margin items vs. low-volume/high-ticket items.
* **"Dead Stock" Analysis:** Identification of the bottom-performing products to assist with inventory rationalization.

---

## 🛠 Technical Skills Demonstrated
* **Data Modeling:** Built a Star Schema (Fact/Dimension) model in SQL Server.
* **Advanced DAX:** Implemented Time Intelligence (`TOTALYTD`, `SAMEPERIODLASTYEAR`), Ranking (`RANKX`), and complex segmentation logic (`CALCULATE`, `FILTER`).
* **Data Engineering:** Created a Medallion Architecture (Bronze/Silver/Gold) using T-SQL stored procedures.
* **UX Design:** Designed a clean, consistent navigation experience with drill-through capabilities and dynamic filtering.# online_retail_dashboards
Power BI Retail Analytics: End-to-End Business Intelligence
