# 🧩 Sales Spectrum Analysis (SQL + Analytics)

# 📝 Project Overview

Sales Spectrum Analysis is an end-to-end SQL analytics project focused on uncovering actionable business insights from retail sales data. Built using MySQL on a dataset of 1,987 transactions, the project demonstrates the complete data workflow—from raw data cleaning to KPI-driven exploratory analysis.The project identifies high-performing categories, customer buying patterns, and profit optimization opportunities, mimicking real-world analytical challenges faced in retail organizations.

# 🎯 Key Objectives
- Build and structure a **retail sales database** from raw transactional data.  
- Perform *data profiling, validation, and cleaning* to ensure consistency.  
- Execute *EDA using only SQL* — covering customer segmentation, product trends, and sales performance.  
- Derive *business insights* such as seasonal demand spikes and margin trends.  
- Create *optimized, reusable SQL queries* for long-term business reporting.  
- Maintain *clear documentation* for all steps to ensure reproducibility.

# 📌 Business Problem
  Retail and e-commerce companies often struggle to:
- Monitor *sales and profitability trends* across categories and seasons.  
- Detect *seasonal or demographic buying shifts*.  
- Identify *low-margin categories* for optimization.  
- Recognize *bulk-order and promotion-driven* purchasing behavior.

# 🛠️ Tech Stack
  | Tool | Purpose |
  |------|----------|
  | **MySQL Server** | Database engine for storage and processing |
  | **MySQL Workbench** | IDE for SQL query writing, testing, and visualization |
  | **Excel / CSV** | For intermediate data verification and export |
  | **GitHub** | Version control and project showcase |

# 🗂️ Data Preparation & Cleaning
-  Renamed ambiguous columns for consistent naming conventions  
-  Checked for and eliminated `NULL` values and duplicate transaction IDs  
-  Verified schema integrity and ensured valid data types  
-  Sorted transactions chronologically (`sale_date ASC`)  
- Exported the cleaned dataset for reproducibility and reporting

# 📈 Key Insights Summary
| Insight | Observation |
|----------|--------------|
| **Revenue Share** | Clothing contributed ~35% of total revenue |
| **Seasonality** | November showed a 15% seasonal lift in clothing sales |
| **Customer Demographics** | Age 20–29 group contributed ~40% of sales |
| **Bulk Orders** | 12% of transactions involved >3 items, indicating promotions |
| **Category Margins** | Electronics showed high sales but low margins (~8%) |
| **Gender Trends** | Females → Clothing/Footwear, Males → Electronics |

# 🧠 Key Learnings
-  Developed strong SQL query optimization and data profiling skills. 
-  Gained hands-on experience in data cleaning, transformation, and validation workflows. 
-  Learned to extract business KPIs and actionable insights using SQL alone. 
- Improved analytical storytelling—linking raw data to real business outcomes.
