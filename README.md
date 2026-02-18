# Customer_behaviour_analysis
Analysing customer data using demographic, purchase history to draw insights on customer behavior


Overview
This project is an end-to-end data analytics solution designed to segment the customers and optimise the strategy for each cohort. It covers the entire data lifecycle: from raw data ingestion and cleaning in Python to deep-dive querying in SQL Server, and finally, executive-level visualization in Power BI.

📊 Dataset
Source: customer_analysis dataset

Description: Contains 3900 rows and 18 columns covering age,gender,products purchase, discounts, number of purchases, frequency of purchase

Format: csv

🛠 Tools Used
Data Processing: Python (Pandas, NumPy)

Storage & Querying: Microsoft SQL Server 

Visualization: Power BI (DAX)

Reporting: Microsoft PowerPoint, Word/PDF

🚀 Project Steps
1. Data Cleaning & EDA (Python)
Handled missing values using category-wise medians to maintain data distribution.

Performed Exploratory Data Analysis (EDA) and feature engineering to add more relevant features such as purchase_frequency_days, age_group

2. Database Migration & SQL Analysis
Ported the cleaned DataFrame from Jupyter Notebook to SQL Server using SQLAlchemy.

Wrote complex SQL queries (CTEs, Window Functions) to calculate:

Top product categories
Analysis for Discounts and subscription
Customer segementation basis the buying frquency
Revenue Analysis based on the demographics



3. Dashboard & Reporting
Created a multi-page Power BI Dashboard with interactive filters (Year, Quarter, Month).

Built a comprehensive Presentation (PPT) summarizing key insights and actionable business recommendations.

📈 Dashboard Preview

<img width="1111" height="602" alt="image" src="https://github.com/user-attachments/assets/89007f9c-9618-4592-ba0b-7ed5327ce935" />




⚙️ How to Run
Python: Open analysis.ipynb in Jupyter, update your database credentials, and run all cells to clean and port the data.

SQL: Run the scripts in the /SQL_Queries folder to generate the analytical views.

Power BI: Open the .pbix file. Ensure the data source points to your SQL Server instance to refresh the visuals.
