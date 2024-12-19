# NovaTech-Sales-Analysis
> [!NOTE]
This write up was written with the help of AI.
> 

### **Project Background**

Our company operates in the **retail and technology sector**, leveraging a **business-to-consumer (B2C) model** to distribute high-demand consumer products globally. Established over a decade ago, we have consistently grown into an industry leader with a focus on cutting-edge technology, diverse product categories, and a robust regional presence across North America, Europe, APAC, and emerging markets.

Key metrics that define our business include:

- Annual global revenue exceeding $10M.
- Focus on profitability goals, aiming for a **20% profit margin** across all regions.
- A data-driven approach to optimize sales, shipping, and regional performance.

As a **data analyst**, I am tasked with identifying trends, uncovering insights, and providing actionable recommendations across product categories, regional performance, seasonal trends, shipping optimizations, and customer segmentation.

The following report provides detailed insights and recommendations in these critical business areas based on historical performance data, sales trends, and shipping metrics.

---

### **Executive Summary**

### **Overview of Findings**

1. **Technology Leads Sales Globally:** Technology is our top-performing category, generating $4.7M in sales and $663.8K in profit, with **Phones** as the dominant subcategory. However, product returns and unprofitable items present risks requiring mitigation.
2. **APAC Sales Underperform Profit Goals:** APAC generated $3.59M in sales but fell 39.2% short of profitability goals. While the **Consumer segment** drives most sales, cost reductions and market-specific campaigns are necessary to improve profitability.
3. **Seasonal Peaks in Q4:** Sales peak for all years in December, November, September, and June, with the **fourth** **quarter (Q4)** contributing significantly due to holiday demand. **First quarter (Q1)** sales consistently lag behind, suggesting opportunities to optimize inventory management.
4. **Shipping Challenges:** Standard Class shipments dominate but lack profitability, and weekends show minimal shipping activity. Optimizing shipping costs and exploring weekend operations could yield significant improvements.

---

### Data Structure and Initial Checks

Our main database is structured into four key tables, totalling **1282250 records**:

- **Customers Table:**
    - Contains customer information such as their unique ID, name, location, and segmentation.
- **Orders Table:**
    - Tracks individual orders placed, including their timelines and priorities.
- **Products Table:**
    - Contains details of products sold, categorized by sub-category and broader category.
- **Sales Table:**
    - Stores transaction-level data, linking customers, orders, and products with financial metrics.
- **Date table(Calculated):**
*** Dedicated table containing a continuous range of dates that serves as the primary source for all date-related calculations and visuals

![Screenshot 2024-12-18 234114](https://github.com/user-attachments/assets/614c700d-2672-4b6b-a5d1-b81cd4cef329)

---

### Insights and Recommendations

### Product Category Performance

**Insights:**

1. **Technology leads in revenue and profit:** Sales of $4.7M and profit of $663.8K.
2. **Top-performing products:**
    - Canon image CLASS Copier ($25,199.94).
    - Cisco Smart Phone ($17,238.52).
    - Motorola Smart Phone ($17,027.13).
3. **Non Profitable products:** A substantial portion of products across all categories are operating at a loss, resulting in a total deficit of $926,000.

**Recommendations:**

- Focus marketing and inventory investments on the **Phones subcategory**.
- Schedule a meeting with the sales team to discuss and investigate the underlying reasons contributing to the significant profit losses.

**Visualization:**

![Screenshot 2024-12-19 024315](https://github.com/user-attachments/assets/8114e592-b064-474e-9e2e-16830b8c1d72)



---

### Regional Performance (APAC Focus)

**Insights:**

1. **APAC sales and profit:** $3.59M in sales and $436K in profit, falling 39.2% short of the goal.
2. **Top countries:** Australia, China, Indonesia, and India lead in sales.
3. **Consumer segment dominance:** Consumers are the largest contributors to all regional sales in  the following order(Most Sales to least Sales): APAC, EU, LATAM, US, EMA, Africa and Canada.

**Recommendations:**

- Develop **localized marketing strategies** for top-performing countries like Australia and China to increase market share.
- Explore cost-saving measures in all regions to improve profit margins.
- Expand product offerings tailored to the Consumer segment in all regions as the best performing segment overall.

**Visualization:**

![Screenshot 2024-12-19 024337](https://github.com/user-attachments/assets/adc7df15-88e4-4591-a5e9-509a7ce06b70)



---

### Seasonal Sales and Profitability Patterns

**Insights:**

1. **Peak months:** December, November, September, and June consistently perform well.
2. **Seasonal sales trends:** Forth quarter (Q4) sees the highest sales due to holiday demand, while first quarter (Q1) ,January in particular, experiences the lowest sales year-over-year.
3. **Year-over-year growth:** Sales increased by 26% and profit by 24% in 2014 compared to 2013, exceeding the goal of a 20% profit margin.

**Recommendations:**

- Allocate marketing budgets to maximize Q4 performance and replicate 2014's growth strategies.
- Reduce inventory during Q1 to minimize holding costs.
- Analyse underperforming months more with the sales team to identify potential opportunities for improvement.

**Visualization:**

![Screenshot 2024-12-19 024355](https://github.com/user-attachments/assets/e221e393-fe01-4345-95bb-82e2921cf45d)


---

### Shipping Optimization

**Insights:**

1. **Preferred shipping class:** Standard Class dominates but is less profitable.
2. **Low weekend activity:** Minimal shipments occur during weekends, with limited use of Critical Priority services.
3. **Profitability concerns:** Certain shipping practices have resulted in financial losses.

**Recommendations:**

- Reassess Standard Class pricing or introduce incentives for higher-margin shipment options.
- Conduct feasibility studies for increasing weekend shipping to cater to unmet demand.
- Investigate and address specific shipping inefficiencies to reduce costs and increase shipping revenue.

**Visualization:**

![Screenshot 2024-12-19 024411](https://github.com/user-attachments/assets/f5ef936d-2b7a-47e4-9033-7c4313063465)



---

### **Recommendations Summary**

1. **Product Optimization:** Focus on high-performing categories (Technology) and subcategories (Phones). Phase out unprofitable products and address return rate issues.
2. **Regional Strategy:** Improve profitability in all regions overall through cost management and localized marketing in high-performing countries.
3. **Seasonal Strategies:** Capitalize on Q4 sales peaks with targeted campaigns and inventory strategies. Reduce inventory in Q1 to lower holding costs.
4. **Shipping Improvements:** Explore weekend shipments, and promote higher-margin options to improve overall profitability.
5. **Customer Segmentation:** Enhance focus on the Consumer segment, particularly in the Central region, while leveraging Canada’s profitability strategies as a benchmark.

---

### **Assumptions**

**Profit Rounding**: Due to rounding profits to whole numbers, some products may display a profit of $0, despite having a fractional profit value.

**2015 Data Limitation**: Data from 2015 was excluded from certain visuals, as it only represents less than 30 recorded days and does not provide significant value to the overall analysis.

---

### Resources for further exploration:

Notebook for data inspection and cleaning: [here.](https://github.com/Lesedi-Cod3s/NovaTech-Sales-Analysis/blob/main/NovaTech_notebook.ipynb)
