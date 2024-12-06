# Sales-Dashboard

### Dashboard Link: https://app.powerbi.com/groups/me/reports/9e27113b-ca7b-4987-b06e-14e23e277535/8b169f976095473ec664?experience=power-bi

### Problem Statement
This dashboard provides an in-depth analysis of sales performance and customer data, enabling businesses to make informed decisions. By visualizing key metrics like sales trends, revenue distribution, and product performance, it highlights areas of strength and opportunities for improvement.

#### Key questions addressed by the dashboard:
a) Which products or categories contribute most to revenue?

b) How do sales trends vary by region, month, or salesperson?

c) What are the top-performing sales channels or customer segments?

With this actionable insight, businesses can identify growth opportunities, optimize inventory, and refine sales strategies.

Steps Followed

A) Data Preparation

a) Data Loading: Imported sales data from CSV/Excel into Power BI Desktop.

b) Data Cleaning:Used Power Query to check "Column Distribution," "Column Quality," and "Column Profile."

c) Handled missing/null values and ensured data integrity across columns.
 Data Transformation:

d) Created calculated columns (e.g., "Profit Margin," "Sales Growth %").
Grouped data into meaningful categories like product types, regions, and customer segments.


### Report Development
#### Theming and Layout:

a) Applied a professional theme for consistency.

b)Used shapes and images for branding (e.g., company logo and tagline).

#### Visual Filters (Slicers):

a) Added slicers for key fields like "Region," "Salesperson," "Product Category," and "Customer Segment."

####Visuals and Metrics:

1. Cards: Highlighted total sales, revenue, profit margin, and average order value.

2. Bar Charts: Displayed product performance by category and region.
3. Line Chart: Illustrated monthly sales trends.
4. Pie Charts: Showed revenue contribution by sales channel and customer type.
5. Tables: Summarized detailed transaction data.
6. DAX Calculations:
7. Created measures for total revenue, profit margin, and YOY growth rates:
                            #### DAX

Total Revenue = SUM(Sales[Revenue])  
Profit Margin = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Revenue])) * 100  
YOY Growth = (DIVIDE(Sales[This Year], Sales[Last Year]) - 1) * 100  

#### Publishing:

A) Published the dashboard to Power BI Service for sharing and collaboration.
Insights

### Key Metrics

a. Sales, Quantity sold and Proit by regions

b. Economic spread  across country

c. State wise analysis of profit

d. reginonal insights to help un decision making

c. Comaparing amounts with previous year lead to insights in profit trends

### Snapshots

1. ![image](https://github.com/user-attachments/assets/02e0b40b-ff0e-4e3e-b042-e2a810e0fd87)

2. ![image](https://github.com/user-attachments/assets/fe59161b-3167-4d2e-9078-684f181ede71)

3. ![image](https://github.com/user-attachments/assets/d38aea52-8624-4a39-ae44-73bf6060cd05)


 





