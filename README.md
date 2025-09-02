# Vendor_Performance_Analysis_project
This project showcases the Fiscal analysis of the Liquor Vendors and aims to answer some key questions to enhance productivity and scale business .


Vendor Performance Analysis Project:



🔎 Overview:-
-This project analyzes vendor and brand performance using transactional data to uncover insights that drive purchasing, pricing, and promotional strategies. The workflow integrates SQLite for structured storage and query optimization, Python for data ingestion, transformation, and exploratory analysis, and Power BI for interactive dashboards and reporting.
-The goal is to evaluate vendors’ contribution to sales and profitability, measure efficiency through inventory turnover, and highlight underperforming brands requiring business intervention.



🛠 Tech Stack:-
-SQLite → database for storing raw tables (purchases, sales, invoices, pricing) and performing initial filtering/aggregation.

-Python (pandas, matplotlib, seaborn, numpy, sqlite3) → active scripting, data cleaning, exploratory analysis, and statistical calculations.

-Power BI → interactive dashboards and final reporting layer for business users.



🎯 Key Business Questions Answered:-
-Identify underperforming brands that require promotional or pricing adjustments.

-Determine the top vendor contributing to sales & gross profit.

-Analyze the impact of bulk purchasing on cost savings and margins.

-Assess inventory turnover to reduce holding costs & improve efficiency.

-Investigate profitability variance between high-performing and low-performing vendors.



📂 Project Workflow:-
-Data Ingestion & Storage

-Raw data loaded into SQLite for structured storage.

-SQL used for joins, filtering, and summarization of vendor-level data.

-Data Exploration with Python

-Extracts summary tables from SQLite.

-Cleans and enriches datasets (profit margin, gross profit, sales-to-purchase ratios, stock turnover).

-Statistical analysis: confidence intervals for profit margins, Pareto analysis, vendor ranking.

-Visualization & Reporting

-Python-generated visualizations (Pareto charts, contribution analysis, donut charts).

-Final reporting & dashboards built in Power BI, integrating KPIs and drill-down capability.



📊 Outputs:-
-Python Notebook: Data cleaning, feature engineering, and exploratory plots.

-SQLite Database: Vendor, purchase, and sales transaction history.

-Power BI Dashboard: Vendor performance analysis, profitability insights, turnover efficiency.

-Final Report: Business recommendations answering the key questions.



🚀 How to Use:-
-Clone this repository.

-Load raw datasets into SQLite (inventory.db).

-Run the Python scripts for cleaning, transformations, and exploratory analysis.

-Open the Power BI dashboard (.pbix) for interactive exploration.



📈 Example Insights:-
-Pareto analysis showing that ~20% of vendors contribute 80% of purchase value.

-Identification of low-performing brands requiring promotional adjustments.

-Comparison of profit margins between top 10 vendors vs bottom 10 vendors.

-Inventory turnover ratio analysis for efficiency improvements.
