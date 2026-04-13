# Global Superstore Sales Analysis — Data Visualization Project

## Project Overview
This project explores the Global Superstore dataset using structured data visualization techniques to extract actionable business insights. The focus is not on creating charts for display, but on answering real analytical and business questions using data.

Each visualization is designed to answer a specific question related to sales, profit, shipping behavior, customer segments, and product performance.

---

## Objectives
- Analyze sales trends over time
- Evaluate regional and country-level performance
- Understand category and sub-category contribution to sales and profit
- Investigate relationship between shipping mode, cost, and order priority
- Compare customer segments based on performance
- Apply structured, insight-driven data visualization

---

## Dataset
- Global Superstore Dataset (Kaggle)
- Key features:
  - Order Date
  - Sales
  - Profit
  - Quantity
  - Region
  - Country
  - Category
  - Sub-Category
  - Segment
  - Ship Mode
  - Order Priority
  - Shipping Cost

---

## Tools & Libraries
- Python
- Pandas (data manipulation)
- Matplotlib (visual structure and control)
- Seaborn (statistical visualization)

---

## Key Analyses & Visualizations

### 1. Sales Trend Analysis
- Line chart of sales over time
- Identifies growth patterns and seasonal spikes

Insight Focus:
- Long-term sales direction
- Seasonal fluctuations
- Anomalies in sales behavior

---

### 2. Regional Performance
- Bar charts and boxplots for regional sales comparison

Insight Focus:
- Top-performing regions
- Revenue distribution imbalance
- Stability vs volatility across regions

---

### 3. Category & Sub-Category Analysis
- Sales and profit aggregated by category and sub-category
- Top 10 sub-categories analyzed

Insight Focus:
- Revenue vs profit mismatch
- High-volume vs high-margin products
- Inefficient product categories

---

### 4. Segment Analysis
- Sales and profit comparison across customer segments

Insight Focus:
- Most profitable segment
- Revenue efficiency differences
- Strategic segment importance

---

### 5. Shipping Mode Analysis
- Boxplots and bar charts for shipping cost, discount, and order priority

Insight Focus:
- Cost variation across ship modes
- Relationship between urgency and cost
- Pricing and logistics inefficiencies

---

### 6. Country-Level Analysis
- Top countries ranked by sales and profit

Insight Focus:
- Revenue concentration in key markets
- Profit efficiency differences across countries
- Market dependency risks

---

### 7. Advanced Analysis (FacetGrid)
- Multi-dimensional comparison of shipping cost across categories and ship modes

Insight Focus:
- Category-based structural differences
- Hidden distribution patterns
- Consistency of shipping cost behavior

---

## Visualization Techniques Used
- Line Charts → trend analysis
- Bar Charts → category comparison
- Boxplots → distribution and outliers
- Violin Plots → density-based distribution analysis
- Heatmaps → correlation analysis
- FacetGrid → multi-dimensional segmentation

---

## Key Insights
- Sales show clear trend patterns with seasonal variations
- Profit is not always proportional to sales
- Some sub-categories generate high revenue but low profit
- Shipping cost varies significantly based on ship mode and category
- A small number of countries dominate revenue generation
- Segment performance varies significantly in efficiency

---

## Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Data aggregation and grouping
- Business-focused data visualization
- Insight generation from statistical patterns
- Multi-dimensional analysis using FacetGrid
- Dashboard-style analytical thinking

---

## Future Improvements
- Build interactive dashboard using Plotly or Power BI
- Add predictive modeling for sales forecasting
- Perform profit optimization analysis
- Automate insight generation pipeline

---

Global_Superstore_analysis/
│
├── data/
│   └── Global_Superstore.xls
│
├── notebooks/
│   └── Global_Superstore_analysis.ipynb
│
├── images/
│   └── 
│
└── README.md


## Conclusion
This project demonstrates structured analytical thinking using data visualization. Every chart is designed to answer a business question, not just display data.


## 🚀 How to Run
1. Clone the repo
2. Open notebook
3. Run all cells