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



📖 Data Storytelling: Superstore Sales Dashboard
The Superstore dashboard tells a clear, compelling story about how the business performs across time, products, and regions. By transforming raw data into visuals, we uncover patterns that help leaders make smarter decisions.

⭐ 1. The Big Picture: How is the business performing overall?
The KPI section at the top gives an instant snapshot of Superstore’s performance:
Total Sales reveal the scale of revenue
Total Profit shows how efficiently the company converts sales into earnings
Total Orders help us understand customer purchasing behavior
Average Order Value (AOV) reveals how much customers spend per order
Profit Ratio indicates how profitable each sale is
These metrics set the stage for deeper analysis.
The KPIs immediately show that while sales volume is strong, profit margins vary widely across the business.

⭐ 2. Sales Over Time: When does the business perform best?
The Sales Trend line chart uncovers patterns across months and years:
Some months consistently outperform others, suggesting seasonal demand
Sales show growth over time, indicating a healthy upward trend
Spikes and dips reveal periods where promotions or external factors influenced purchasing behavior
This time-based view helps forecast future demand and plan inventory and marketing.

⭐ 3. Category Performance: What products drive revenue?
The horizontal bar chart for Sales by Category reveals:
Technology leads in both sales and profit
Office Supplies sells frequently but at lower margins
Furniture, while high in revenue, shows inconsistent profit due to discounting
This insight encourages exploring pricing strategies or cost optimization for certain categories.

⭐ 4. Geographic Insights: Where is the business strong or weak?
The Sales by Region Map quickly highlights:
High sales concentration in specific states such as California and New York
Underperforming areas in the Central and Southern regions
Profit margins differ by state, showing that high sales don’t always mean high profitability
These patterns help target high-value areas and improve weak regions with better marketing or logistics.

⭐ 5. Sub-Category Breakdown: What specific items matter most?
The Tree Map reveals which sub-categories contribute the most:
Products like Phones, Chairs, and Binders dominate sales
Smaller segments like Fasteners, Copiers, and Supplies contribute less
The size of each block instantly communicates contribution to revenue
This helps managers decide which products deserve more focus and which need strategic reassessment.

⭐ 6. Understanding Customer Preferences: Who are the buyers?
Using slicers and filters:
Segment analysis shows that Consumer customers make the highest number of purchases
Corporate customers often have higher AOV
Home Office segment shows moderate but consistent behavior
This segmentation helps tailor promotions and improve customer experience.

⭐ 7. Key Business Insights Uncovered
From the combined visuals, the data tells a powerful story:
🔍 Insight 1: Sales are growing, but profit margins are not uniform.
Some categories and regions generate strong revenue but weak profitability.

🔍 Insight 2: Technology leads revenue, Furniture struggles with profit.
High discounts and shipping costs impact margin in certain product groups.

🔍 Insight 3: Western and Eastern regions perform best.
These areas are the backbone of Superstore’s sales performance.

🔍 Insight 4: Seasonal trends guide inventory planning.
Sales peaks highlight periods where stock and staffing need to be optimized.

🔍 Insight 5: Customer segments behave differently.
Consumers buy more frequently; Corporate buyers spend more per order.
