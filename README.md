# SQL Data Analytics Project

## 📊 Project Overview
This project demonstrates end-to-end SQL-based data analysis on a structured sales dataset. It walks through everything from raw data ingestion to analytical queries, focusing on insights like customer behavior, product performance, profit trends, and segmentation — all using SQL.

> ❗ **Disclaimer**: This project is based on the original work by [Data With Baraa](https://github.com/DataWithBaraa/sql-data-analytics-project). It was recreated for educational purposes to strengthen SQL skills, improve data project organization, and present a clean version of the analysis structure.

## 🧱 Project Structure
```
SQL-data-analytics-project/
├── dataset/           # Cleaned CSV files used as source data
├── sql_scripts/       # All SQL scripts: setup, ETL, analysis
├── doc/               # Visuals, diagrams, and roadmap
└── README.md
```

## 🧠 Tools Used
- **SQL Server Management Studio (SSMS)**
- **Excel** (for pre-cleaning the data)
- **GitHub** (version control and collaboration)

## 📁 Folders Explained
### `/dataset/`
Contains the core data files used in the project:
- `Customer.csv`
- `Product.csv`
- `Sales.csv`

### `/sql_scripts/`
Contains all SQL scripts in logical order:
- `00_init.sql` – Creates the database and schema
- `01_create_tables.sql` – Defines staging and final tables
- `02_insert_data.sql` – Loads the raw data from CSVs
- `03_transformations.sql` – Converts raw into cleaned tables
- `04_create_views.sql` – Optional views used in reporting
- `05_profit_by_region.sql` – Insight query: regional profits
- `06_customer_demographics.sql` – Customer profile analysis
- `07_top_10_products.sql` – Best-selling products
- `08_sales_trends.sql` – Sales performance over time
- `09_product_category_analysis.sql` – Category trends
- `10_customer_segmentation.sql` – Segmenting based on sales
- `13_summary_report.sql` – Combined final report output

### `/doc/`
Visuals and supporting material:
- `project_roadmap.png` – Step-by-step project flow
- `erd_diagram.png` – Entity Relationship Diagram (schema design)


## 💡 Business Insights Extracted
- 🏆 Top-performing products by category and revenue
- 👥 High-value customer segments
- 📉 Profit dips by region
- 📈 Sales trends across time periods

## ✅ Key Skills Demonstrated
- Relational database design
- Writing optimized SQL queries
- Data transformation (ETL logic)
- Analytical thinking and KPI extraction
- Git-based project organization

## 📄 License
This project is licensed under the [MIT License](LICENSE).

## 🙏 Acknowledgements
- Original structure and concept by [Data With Baraa](https://github.com/DataWithBaraa/sql-data-analytics-project)
- Recreated and reorganized to demonstrate learning, SQL proficiency, and portfolio documentation standards.

## 🤝 Let's Connect
Have feedback or suggestions? Feel free to fork the repo or open a pull request!

---
Made with 💻 and a lot of SQL magic.



