# Customer_behaviour_analysis

📊 Customer Shopping Behavior Analysis
Overview

This project demonstrates a complete end-to-end data analytics workflow using Python, SQL Server, and Power BI. The goal of the project is to analyze customer shopping behavior, identify key business insights, and present findings through interactive dashboards and professional reports.

The project covers:

Loading and exploring raw data using Python
Performing Exploratory Data Analysis (EDA)
Cleaning and preparing the dataset
Running business queries using SQL Server
Building interactive dashboards in Power BI
Creating a final analytical report and presentation
Dataset

This project uses a customer shopping dataset containing information such as:

Customer demographics
Product categories
Purchase history
Payment methods
Discounts and promotions
Shopping frequency
Revenue and spending patterns

The dataset was analyzed to understand customer purchasing behavior and business performance.

Tools & Technologies
Python — Data analysis and preprocessing
Jupyter Notebook — Analysis environment
Microsoft SQL Server — Data querying
Power BI — Dashboard creation
Microsoft PowerPoint — Final presentation
Gamma — Presentation design
Python Libraries Used
Pandas
NumPy
Matplotlib
Seaborn
PyODBC / SQLAlchemy

Project Workflow

1. Data Loading
Imported the dataset into Python
Loaded data into DataFrames
Checked data structure and column information

2. Exploratory Data Analysis (EDA)
Performed detailed analysis to understand:

Missing values
Data distribution
Customer demographics
Purchase trends
Revenue patterns
Category-wise sales

3. Data Cleaning
Applied preprocessing techniques:

Removed duplicates
Handled missing values
Corrected data types
Standardized categorical values
Created derived metrics

4. SQL Analysis
Imported cleaned data into SQL Server and performed business analysis using SQL queries such as:

Top selling products
Customer segmentation
Revenue by category
Discount usage analysis
Payment method analysis
Purchase frequency analysis

5. Dashboard Development
Built an interactive Power BI dashboard including:

KPI cards
Revenue trends
Customer segmentation
Product performance
Discount analysis
Payment insights
Regional/customer behavior analysis

6. Reporting & Presentation
Created:

Detailed business report
Executive summary
Professional presentation using Gamma
Dashboard Highlights

Key dashboard metrics include:
Total Revenue
Total Customers
Average Order Value
Discount Usage Rate
Top Performing Products
Customer Segmentation
Purchase Trends
Key Results

Some major insights discovered:

✅ High discount usage significantly impacts purchase behavior
✅ Certain product categories generate most revenue
✅ Repeat customers contribute major sales volume
✅ Digital payment methods are preferred by most customers
✅ Seasonal shopping trends influence customer purchases

Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_data.csv
│
├── notebooks/
│   └── Customer_Shopping_behaviour_Analysis.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── reports/
│   ├── final_report.pdf
│   └── presentation.pptx
│
└── README.md
How to Run
Clone the repository
git clone <your-repository-link>
cd Customer-Shopping-Behavior-Analysis
Install dependencies
pip install pandas numpy matplotlib seaborn pyodbc sqlalchemy
Run analysis
jupyter notebook

Open:

Customer_Shopping_behaviour_Analysis.ipynb
SQL Analysis
Import cleaned dataset into SQL Server
Execute SQL scripts from sql/ folder
Power BI Dashboard
Open .pbix file in Power BI Desktop
Refresh data connections
Business Impact

This project demonstrates practical skills in:

Data Cleaning
Exploratory Data Analysis
SQL Querying
Business Intelligence
Data Storytelling
Reporting & Presentation
Author

Sathvika K
Aspiring Data Analyst | Python | SQL | Power BI | Business Analytics
