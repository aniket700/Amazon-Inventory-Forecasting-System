# Amazon-Inventory-Forecasting-System
Built a system to predict future inventory needs by analyzing historical sales data. Used Python for forecasting and SQL to manage large datasets. Created dashboards in Power BI to visualize stock levels and demand trends.

Tools: Python (NumPy, Pandas, Matplotlib), SQL, Power BI

Using Python, MySQL, and Power BI together for an Amazon Inventory Forecasting System ensures a robust, automated, and visualized data-driven approach
1. MySQL – Data Storage & Management
MySQL acts as the backend database, storing historical inventory and sales data efficiently.
Stores large datasets securely
Supports structured queries (SQL) for analysis
Ensures data integrity and prevents duplication
Allows real-time data updates for live forecasting

2. Python – Data Processing & Forecasting
Python is the brain of the system, handling data extraction, cleaning, transformation, and forecasting.
Reads and processes data from MySQL (using pymysql, SQLAlchemy)
Applies Machine Learning models (ARIMA, XGBoost, Prophet) for forecasting
Automates ETL pipelines for seamless integration

3. Power BI – Data Visualization & Reporting
Power BI creates interactive dashboards for stakeholders to monitor inventory trends and make decisions.
Connects directly to MySQL for real-time reporting
Provides dynamic visualizations (charts, graphs, heatmaps)
Enables business intelligence with KPI tracking
