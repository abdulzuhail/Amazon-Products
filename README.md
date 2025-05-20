# Amazon Sales Analysis Dashboard

**Interactive Power BI Dashboard for E-commerce Performance Insights**

---

## Project Objective

The objective of this project is to design and develop a dynamic Amazon Sales Analysis Dashboard using Power BI. This interactive dashboard enables business analysts, sales teams, and e-commerce stakeholders to monitor sales trends, track top-performing product categories, analyze customer behavior, and evaluate engagement metrics like reviews. The dashboard presents key performance indicators (KPIs) such as YTD sales, QTD sales, units sold, and reviews, and visually breaks down sales across time and product hierarchies to support data-driven decision-making.

---

## Dataset Used

The dataset used for this project is the **Amazon Sales Dataset**, which includes product category, sales figures, units sold, reviews, and timestamps.

You can download or view the dataset here:  
[Amazon_Data.xlsx](https://github.com/abdulzuhail/Amazon-Products/blob/main/Amazon_Data.xlsx)

---

## Key Business Questions (KPIs)

- What is the total YTD and QTD revenue?  
- Which product categories are driving the most sales?  
- Which individual products are top-performing in terms of sales and reviews?  
- Which months and weeks show peak sales?  
- Are there specific timeframes (quarters or months) that show higher sales volumes?  
- What insights can be drawn about customer behavior through product reviews?  
- How can we optimize the inventory strategy based on product demand and sales distribution?

---

## Process Overview

1. **Data Cleaning & Preparation**  
   - Removed duplicates and handled null values in sales and review columns.  
   - Standardized date and time formats for monthly and weekly aggregations.  
   - Created new columns such as Month, Week Number, and Quarter.  
   - Ensured all numerical values were properly formatted.

2. **Data Modeling in Power BI**  
   - Loaded cleaned dataset into Power BI.  
   - Created DAX measures for YTD & QTD Sales, Total Products Sold, Total Reviews, Top Products, and Percentage contribution by category.  
   - Built hierarchies (Year → Quarter → Month → Week) for time-based analysis.  
   - Established category-based relationships for filtering and drill-through.

3. **Visualization & Dashboard Design**  
   - Developed a single-page interactive dashboard consolidating all KPIs, charts, and filters.  
   - Included slicers for Product Category and Quarter.  
   - Applied consistent theme and accessible color palette with interactive tooltips.

---

## Dashboard Highlights

- **KPI Cards:** YTD Sales ($2.18M), QTD Sales ($811.09K), Products Sold (27.75K), Total Reviews (19.42M)  
- **Time-Based Trends:** Monthly sales peaks in September and December; weekly breakdown showing promotional spikes.  
- **Top Products:** Nikon Wide Lens tops sales at $34K; SanDisk 16GB leads in reviews with 402.83K.  
- **Category Sales:** Men Shoes (43.18%) and Camera (22.62%) dominate sales.  
- **Filters:** Category dropdown and Quarter slicer for dynamic analysis.

---

## Key Insights

- Men’s Shoes and Camera categories contribute ~66% of total sales.  
- Sales peak during Q3 and Q4, matching seasonal shopping trends.  
- High customer engagement on tech products like SanDisk.  
- Mobile & Accessories segment shows underperformance — opportunity for targeted marketing.  
- Recommended promotional campaigns during September and December.

---

## Conclusion

This Amazon Sales Analysis Dashboard simplifies complex sales data into actionable insights, empowering stakeholders to optimize product strategies, identify peak sales seasons, and allocate marketing budgets effectively. It serves as a foundational tool for scalable business intelligence in the e-commerce domain, with potential for future enhancements like profit margin analysis, regional trends, and forecasting.

---

