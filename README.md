# Customer Behaviour Analysis

End-to-end data analytics project on retail customer shopping behaviour — from data cleaning and exploratory analysis to SQL insights, Power BI dashboard, and business reporting.

## Project Overview

Goal is to convert raw retail data into business intelligence:

- Data Preparation & EDA (Python): clean and explore the raw dataset
- Data Analysis (SQL): answer business questions on segments, loyalty, discounts, shipping, and revenue drivers
- Visualization (Power BI): interactive dashboard for key patterns and trends
- Report and Presentation: summary of findings and recommendations

## Repository Contents

- `customer_shopping_behavior.csv` — raw dataset
- `Customer_Shopping_Behavior_Analysis.ipynb` — Python cleaning + EDA + DB load
- `customer_behavior_sql_queries.sql` — 10 business SQL queries
- `customer_behavior_dashboard.pbix` — Power BI dashboard
- `Customer Shopping Behavior Analysis.pdf` — analysis report
- `Business Problem  Document.pdf` — problem statement
- `Customer-Shopping-Behavior-Analysis.pptx` — presentation deck

## How to Use

1. Clone the repository
   ```bash
   git clone https://github.com/Mukul-prasad89/Customer_behaviour_analysis.git
   cd Customer_behaviour_analysis
   ```

2. Open `Customer_Shopping_Behavior_Analysis.ipynb`
   - Data import
   - Data exploration
   - Data cleaning
   - Load to SQL database

3. Load data into MySQL / PostgreSQL / SQL Server
   - Create a database
   - Run notebook code to load data
   - Open `customer_behavior_sql_queries.sql` to run business queries

4. Open `customer_behavior_dashboard.pbix` in Power BI for dashboard

5. See PDF report and PPTX for findings and recommendations

## Tools

Python (pandas, sqlalchemy), SQL, Power BI

## Author

Mukul Prasad

## License

MIT — see `LICENSE`.
