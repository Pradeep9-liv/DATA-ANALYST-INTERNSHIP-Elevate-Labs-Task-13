# DATA-ANALYST-INTERNSHIP-Elevate-Labs-Task-13

# Global Superstore Sales Dashboard - Power BI

## Project Objectives
- Create KPI metrics to monitor business performance.
- Analyze **Sales** and **Profit** trends over time.
- Compare performance across categories and regions.
- Identify top-performing products.
- Build an interactive dashboard using slicers and visuals.

---

## Dataset
**Name:** Global Superstore Retail Sales Dataset  

### Key Fields Used
- `Order Date`
- `Sales`
- `Profit`
- `Category`
- `Sub-Category`
- `Region`
- `Product Name`
- `State / Country`

---

## Tools & Technologies
- Microsoft Power BI
- Data Modeling & DAX
- Data Visualization

---

## KPI Measures (DAX)
```DAX
Total Sales = SUM('superstore'[Sales])
Total Profit = SUM('superstore'[Profit])
Profit Margin = DIVIDE([Total Profit],[Total Sales],0)

---

## Dashboard Features
- KPI Cards (Total Sales, Total Profit, Profit Margin)
- Sales Trend Line Chart
- Category Breakdown Bar Chart
- Region Performance Map (Colored Bubbles)
- Top 10 Products Table
- Interactive Slicers (Region, Date, Category)
- Insights Text Section

---

## Key Insights
- Technology category generates the highest sales.
- West region shows strong performance.
- Top products contribute significantly to total revenue.
