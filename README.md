# ElevateLabs_submissions
# 📊 45-Day Data Analytics Internship – Daily Task Repository

This repository contains all the work completed during my **45-day Data Analytics and Visualization Internship**.  
Each day is organized into a dedicated folder that includes the task, solution files, datasets (if applicable), and screenshots.


🛠 Tools & Technologies Used
- Power BI  
- Excel  
- Python  
- Tableau  
- GitHub  
- Data Cleaning & ETL  
- DAX for Measures  
- Data Storytelling  

🎯 Internship Goals
- Learn and apply data cleaning techniques  
- Develop dashboards using Power BI/Tableau  
- Perform exploratory data analysis  
- Build DAX measures and advanced visuals  
- Present insights using storytelling techniques  
- Use GitHub for daily documentation  

Final Project Output
Available inside the `final_project/` folder:
- `dashboard.pbix`
- `final_report.pdf`
- `presentation.pptx`
- `insights.md`


Task 1: Data Cleaning and Preprocessing
Data Cleaning Summary:
- Removed 2 duplicate rows
- Formatted Orderdate to dd-mm-yyyy
- Standardized all values using Proper Case
- Converted all headers to lowercase with underscores
- Verified data types for all numeric and date fields

Task 2: Data Visualization and Storytelling
Dataset Name: Sample - Superstore
The dataset contains:
- Order & shipping details
- Sales, quantity, discount, and profit
- Customer & segment information
- Region, state, and city details
- Product categories and sub-categories

Data Visualization steps :
Step 1: Data Loading & Cleaning
Imported the Sample - Superstore.csv file into Power BI
Verified column data types (Date, Number, Text)
Removed blanks and corrected formatting
Ensured consistency in the dataset

Step 2: Created DAX Measures
Below are the key measures created for dashboard analysis:
Total Sales = SUM('Sample - Superstore'[Sales])
Total Profit = SUM('Sample - Superstore'[Profit])
Total Quantity = SUM('Sample - Superstore'[Quantity])
Total Orders = DISTINCTCOUNT('Sample - Superstore'[Order ID])
Profit Ratio = DIVIDE([Total Profit], [Total Sales], 0)
AOV = DIVIDE([Total Sales], [Total Orders], 0)

Step 3: Built Visualizations
The following visuals were added to the dashboard:
1. KPI Cards
- Total Sales
- Total Orders
- Profit Ratio
2. Sales Trend Line Chart: Shows sales over time (Month/Year) and helps identify seasonal patterns & trends
3. Sales by Category (Bar Chart): Compares the performance of Furniture, Office Supplies, and Technology
4. Sales by Region (Filled Map / Bubble Map): Visualizes geographic sales distribution across states
5. Sub-Category Performance (Tree Map): Identifies top-performing product sub-categories
6. Slicers (Filters): Order Date, Segment, Category, and Region
