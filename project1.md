
# Sales & Profit Analysis Dashboard

This is a project showing an interactive Tableau dashboard that explores profitability and sales trends across product categories and regions in the U.S. The dashboard allows users to identify key business drivers and underperforming areas by visualizing performance over time, across states, and among product categories.

---

## Data Source

The dataset contains **9,994 records** from a U.S. superstore and includes fields like:

- Order ID, Order Date, Ship Date
- Customer & Segment Info
- Product Category & Sub-Category
- Sales, Profit, Region, State, City

---

## Visualizations & Key Insights

### 1. Category-Level Profit Breakdown

![image](https://github.com/user-attachments/assets/1cd0ca91-fff7-491e-bda3-b5a36a7210cc)


- **What it shows**: Horizontal bar chart displaying profit by product sub-category, grouped by category.
- **Insight**:
  - *Technology* is the most profitable category, especially *Copiers* and *Phones*.
  - *Furniture* has mixed results—*Tables* lead to significant losses.
  - Helps identify which segments are driving profit vs. underperforming.

---

### 2. Profit by State

![image](https://github.com/user-attachments/assets/7f71b464-a445-4e81-bd62-830b40e620eb)


- **What it shows**: Choropleth map of U.S. states shaded by total profit.
- **Insight**:
  - Profitability varies geographically.
  - States like *California*, *New York*, and *Washington* are top performers.
  - States like *Texas*, *Illinois*, and *Pennsylvania* show consistent losses, indicating potential operational issues.

---

### 3. Profit Over Time

![image](https://github.com/user-attachments/assets/f38fd2a9-425b-4497-9e13-410f534f9930)


- **What it shows**: Line chart of profit by month over time.
- **Insight**:
  - High fluctuations suggest unstable profitability.
  - Occasional sharp dips may relate to specific sales events, operational costs, or seasonal demand shifts.
  - Useful for investigating time-based anomalies and trends.

---

### 4. Sales vs Profit (Scatter Plot)

![image](https://github.com/user-attachments/assets/fc0a92de-5f25-4100-a39e-47c635d7376f)


- **What it shows**: Each point represents a transaction, plotting sales (x-axis) against profit (y-axis).
- **Insight**:
  - A number of transactions result in *negative profit* despite *high sales*.
  - Reveals the importance of not assuming high sales always equate to profitability.
  - Helps identify potential loss-leading items or pricing inefficiencies.

---

## Summary

This dashboard helped uncover several key business insights:

- **Product Issues**: The *Tables* sub-category consistently results in negative profit, suggesting pricing or cost issues. It may require supplier negotiation, price adjustments, or discontinuation.
- **Regional Problems**: States like *Texas* and *Pennsylvania* have high sales but low or negative profit, indicating potential distribution or logistics inefficiencies.
- **Seasonality & Volatility**: Profit fluctuates sharply over time. Businesses should investigate periods of steep decline and consider inventory, marketing, or seasonal factors that may be influencing trends.
- **Sales ≠ Profit**: The scatter plot reveals that high sales volumes do not guarantee profitability. Some transactions incur a loss despite large sales numbers, highlighting the need to optimize the cost structure or discounting strategies.

## Suggested Solutions

Based on the insights uncovered in this dashboard, here are a few potential next steps:

- **Re-evaluate pricing or cost structure for Tables**  
  The consistently negative profit suggests Tables may be overpriced relative to their cost or discounted too heavily. Review sourcing costs, shipping fees, or consider bundling options to improve margins.

- **Investigate logistics in underperforming states**  
  States like Texas and Pennsylvania could be facing higher delivery costs or fulfillment delays. Consider analyzing shipping methods or exploring regional distribution centers to improve efficiency.

- **Analyze seasonal trends more closely**  
  The time-based profit fluctuations point to the need for better seasonal planning. Look into marketing campaigns, inventory levels, and staffing during peak and low months.

- **Set thresholds to flag unprofitable high-sales orders**  
  Introduce rules or dashboards that flag large orders with negative profit. This could help the sales team identify problematic SKUs or pricing strategies in real time.



