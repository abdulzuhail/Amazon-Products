# 🛒 Amazon Sales Analysis Dashboard  
*Interactive Power BI Dashboard for E-commerce Performance Insights*

---

## 🎯 Project Objective  
This project delivers a dynamic, single-page Amazon Sales Analysis Dashboard built in Power BI. It enables business analysts, sales teams, and e-commerce stakeholders to monitor sales trends, track top-performing products and categories, analyze customer behavior, and evaluate engagement metrics like reviews — all on one consolidated page. The dashboard features key performance indicators (KPIs) such as YTD sales, QTD sales, units sold, and reviews, with detailed visual breakdowns across time and product hierarchies to drive data-informed decisions.

---

## 📊 Dataset Used  
[Amazon_Data.xlsx](https://github.com/abdulzuhail/Amazon-Products/blob/main/Amazon_Data.xlsx)  

---

## 🧩 Key Business Questions (KPIs)  
- 💰 What is the total YTD and QTD revenue?  
- 📦 Which product categories drive the most sales?  
- 🔝 Which individual products are top-performing by sales and reviews?  
- 📈 What months and weeks exhibit peak sales?  
- 🕒 Which quarters or months show higher sales volumes?  
- 🧠 What insights can product reviews provide about customer behavior?  
- 🛍️ How to optimize inventory based on product demand and sales distribution?

---

## ⚙️ Process  

1. **Data Cleaning & Preparation**  
   - Removed duplicates and handled nulls in sales and reviews.  
   - Standardized date/time formats for monthly and weekly aggregation.  
   - Created new columns: Month, Week Number, Quarter.  
   - Ensured numerical data is correctly typed and formatted.

2. **Data Modeling in Power BI**  
   - Imported cleaned data into Power BI.  
   - Developed DAX measures: YTD/QTD Sales, Total Units Sold, Total Reviews, Top 5 Products by Sales & Reviews, Category Contribution %.  
   - Built time hierarchies (Year → Quarter → Month → Week).  
   - Created category relationships for filtering and drill-through.

3. **Visualization & Dashboard Design**  
   - Designed a **single-page dashboard** integrating all key insights.  
   - Included slicers for Product Category and Quarter (Q1–Q4).  
   - Applied consistent theme, intuitive layout, interactive tooltips, and dynamic filtering.

---

## 📊 Dashboard Overview  

### 🔹 KPI Cards  
- YTD Sales: $2.18M  
- QTD Sales: $811.09K  
- Products Sold: 27.75K  
- Total Reviews: 19.42M  

### 📈 Time-Based Charts  
- **Sales by Month (Line Chart):** Shows revenue trends with peaks in September ($1.25M) and December ($1.35M).  
- **Sales by Week (Bar Chart):** Weekly sales breakdown highlighting promotional and seasonal spikes.

### 🧮 Engagement & Contribution  
- **Top 5 Products by YTD Sales:** Nikon Wide Lens leads with $34K.  
- **Top 5 Products by Reviews:** SanDisk 16GB tops with 402.83K reviews.

### 📂 Sales by Product Category (Bar Chart with % Contribution)  

| Product Category     | Sales (USD)   | Contribution |
|----------------------|---------------|--------------|
| Men Shoes            | $940,266.00   | 43.18%       |
| Camera               | $492,521.00   | 22.62%       |
| Men Clothes          | $357,644.00   | 16.42%       |
| Car Accessories      | $237,290.00   | 10.90%       |
| Toys                 | $110,839.00   | 5.09%        |
| Mobile & Accessories | $39,178.00    | 1.80%        |

---

## 🧭 Filters  
- **Category Filter (Dropdown):** Analyze data by specific product categories.  
- **Quarter Filter (Slicer):** Compare performance across Q1 to Q4.

---

## 📌 Dashboard Insights  

- 🥇 Men’s Shoes and Camera categories generate about 66% of total sales, highlighting key revenue drivers.  
- 📊 Sales peak notably in Q3 and Q4, aligning with seasonal shopping and promotional events in September and December.  
- 💬 High customer engagement is evident in tech products, with SanDisk 16GB receiving substantial reviews.  
- 📉 Mobile & Accessories underperform, signaling potential for marketing improvements or inventory reassessment.  
- 📅 Recommended to focus promotions during September and December to maximize sales momentum.

---

## ✅ Final Conclusion  
The Amazon Sales Analysis Dashboard consolidates vital e-commerce performance data into a single interactive page, empowering stakeholders to:  

- Optimize product strategies based on sales and customer engagement.  
- Identify peak sales seasons for targeted marketing campaigns.  
- Efficiently allocate resources and inventory to high-demand categories.  

The dashboard lays a strong foundation for future enhancements like profit margin analysis, regional sales trends, and forecasting capabilities — supporting scalable and data-driven business growth.

---

![Dashboard Insights](https://github.com/abdulzuhail/Amazon-Products/blob/main/Amazon%20Products.png?raw=true)
