# Sales & Profitability Dashboard: Distribution Challenge in Pennsylvania

This project explores sales and profitability patterns across U.S. states and cities using Tableau dashboards. By focusing on Pennsylvania, a high-sales but low-profit state, we investigate the possibility of improving profit margins by proposing a new distribution center near Philadelphia.

---
## Dataset
- **Source**: Superstore Orders (9,994 rows)
- **Fields**: Includes `Sales`, `Profit`, `Order ID`, `Customer`, `State`, `City`, `Order Date`, `Cost of Sales` (calculated), etc.

---
## Key Visualizations & Insights

### 1. **Sales by State**

![image](https://github.com/user-attachments/assets/1315ce82-1d75-47e4-b363-7596c9a4b3b9)


- **Insight**: Pennsylvania ranks among the top 5 states in total sales.
- **Takeaway**: Despite strong sales, deeper analysis is needed to assess whether sales are translating into healthy profits.

---

### 2. **Profit Distribution in Pennsylvania**

![image](https://github.com/user-attachments/assets/6bad3a78-9b31-4309-b8a4-1a9a755fdd65)


- **Insight**: A large number of orders in Pennsylvania result in **negative profit**.
- **Takeaway**: Profit leakage is frequent; this points to a systemic issue, possibly logistics-related.

---

### 3. **Sales vs. Cost of Sales**

![image](https://github.com/user-attachments/assets/fd153cab-ad39-4906-9771-3b5f27b879ea)


- **Insight**: Costs scale with sales, but in many cases, **costs exceed the revenue**.
- **Takeaway**: The break-even point isn't being met in high-volume orders, likely due to supply chain inefficiencies.

---

### 4. **Sales Distribution in Pennsylvania**

![image](https://github.com/user-attachments/assets/fbb4f427-0e8e-4ab7-ac14-fb69b0df8e10)


- **Insight**: A heatmap shows a sales concentration around **Philadelphia**.
- **Takeaway**: Philadelphia is a strategic location that could serve as a distribution hub to cut shipping costs.

---

### 5. **Sales vs. Profit by State**

![image](https://github.com/user-attachments/assets/86853d8b-b33a-4dec-b381-30b59a82c146)


- **Insight**: States like California and New York show strong **alignment** between high sales and high profits.
- **Takeaway**: Pennsylvania is an outlier—**high sales but negative profit**, highlighting a regional challenge.

---

### 6. **Sales Spread in Texas**

![image](https://github.com/user-attachments/assets/d6a07b41-d72d-4830-8c24-d80b2831894f)


- **Insight**: Texas has **well-distributed sales**, which helps spread logistical cost and increase profit margins.
- **Takeaway**: A similar structure might benefit Pennsylvania if logistics were improved.

---

## Monthly State-Level Sales & Profitability Analysis

![image](https://github.com/user-attachments/assets/dc2b1ee4-8a1c-4240-b786-29657657ca94)


---

## Data-Driven Findings

Tableau visualizations initially revealed a disconnect between sales and profit in Pennsylvania. Despite ranking among the top five states in total sales, a large number of orders generated negative profit, especially around the Philadelphia area.

To validate and expand on this observation, monthly state-level data was analyzed using SQL. The results confirmed that:

- **Pennsylvania’s cumulative profit** (`RunningProfitByState`) remained negative for five consecutive months—even as its order volume continued to grow.
- Its **average monthly profit** (`AvgProfitByState`) was **–$1,125**, significantly lower than that of **California (+$3,800)** and **New York (+$2,700)**.
- In terms of **monthly profit rank** (`ProfitRankThisMonth`), Pennsylvania consistently fell in the bottom third of all states—ranking **22nd and 26th** out of 30 in February and March, respectively.
