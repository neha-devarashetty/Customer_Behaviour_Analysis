# Customer_Behaviour_Analysis
Customer Shopping Behavior Analysis project analyzing 3,900 transactions to uncover spending trends and customer insights. Performed data cleaning and feature engineering using Python (Pandas), conducted SQL-based analysis on revenue, subscriptions, and segmentation, and built an interactive Power BI dashboard for business decision-making.

Customer Shopping Behavior Analysis
-> Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segmentation, subscription impact, and product performance. The workflow covers end-to-end data analytics — from data loading and cleaning in Python to SQL-based business analysis and dashboard creation in Power BI.

-> Dataset
~3,900 transaction records
18 features including:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item, Category, Amount, Season, Size, Color)
Behavioral metrics (Discount Applied, Shipping Type, Review Rating, Previous Purchases)

-> Tools & Technologies

Python (Pandas, NumPy)
SQL (MySQL / PostgreSQL / SQL Server)
Power BI
Jupyter Notebook
Gamma (for presentation)

🔎 Project Steps
1️⃣ Data Loading & EDA (Python)
Loaded dataset using Pandas
Performed exploratory data analysis
Handled missing values
Standardized column names
Created new features (e.g., age_group, purchase_frequency_days)

2️⃣ Data Cleaning & Transformation
Checked data consistency
Removed redundant columns
Prepared structured dataset for SQL analysis

3️⃣ SQL Business Analysis
Executed analytical queries to answer key business questions:
Revenue by gender
Subscribers vs non-subscribers comparison
High-spending discount users
Top-rated products
Customer segmentation (New, Returning, Loyal)
Revenue contribution by age group

4️⃣ Power BI Dashboard
Built an interactive dashboard displaying:
Total customers
Average purchase amount
Revenue by category
Sales by age group
Subscription distribution
Shipping type comparison

5️⃣ Reporting
Created structured project report
Designed presentation (PPT) using Gamma

📈 Key Results
Loyal customers form the largest segment.
Young adults contribute the highest revenue.
Non-subscribers generate higher total revenue.
Certain products show high discount dependency.
Express shipping users have slightly higher average purchase value.

-> How to Run
Clone the repository
Install required Python libraries:
pip install pandas numpy sqlalchemy pymysql
Run the Jupyter Notebook for data cleaning & transformation
Execute SQL scripts in your database (MySQL/PostgreSQL/SQL Server)
Open the Power BI .pbix file to explore the dashboard

-> Business Recommendations
Strengthen subscription benefits to increase recurring revenue
Introduce loyalty reward programs
Optimize discount strategy for margin control
Focus marketing efforts on high-revenue age groups

