 Interactive Sales Dashboard-Tableau
 
Objective:
To design a dynamic and interactive dashboard for business stakeholders using Tableau, focused on analyzing sales performance, profitability, and growth over time. The dashboard empowers decision-makers to explore data through filters, KPIs, and charts.

Tools & Technologies
- Tool Used:Tableau Desktop
- Data Source:Sales/Financial dataset (from Kaggle)
- Language: No coding required – built fully with Tableau drag-and-drop UI

Dataset Overview
Name:Superstore Sales Dataset
Source:[Kaggle – Superstore Sales](https://www.kaggle.com/datasets)
Columns Used:  
  - Order ID, Order Date, Region, Category, Sub-Category  
  - Sales, Profit, Quantity, Discount, Customer Name  

 Dashboard Features
 KPIs (Cards):
- Total Sales– Sum of revenue  
- Total Profit – Sum of net profit  

 Charts:
Sales Over Time – Line chart for monthly trend  
Profit by Category – Bar chart showing contribution by product categories  

Filters (Slicers):
- Region  
- Category  
- Order Date (Range)

 Design Highlights:
- Clean layout: KPIs at the top, charts in the middle  
- Responsive slicers for interactivity  
- Time-series visualization using line charts  
- Consistent color palette across all visuals  
- Optimized for stakeholder presentations

Step-by-Step Development (Tableau)
1. Data Import: Connected Excel sheet to Tableau.
2. Created KPI Cards: 
   - Used `COUNTD(Order ID)` for Total Orders  
   - Used SUM for Sales and Profit  
3. Built Charts:  
   - Line chart for Sales Over Time  
   - Bar chart for Profit by Category  
4. Added Filters (Slicers):  
   - Dragged Region, Category, and Order Date to Filters shelf  
   - Right-click → Show Filter  
5. Dashboard Layout:
   - KPI Cards arranged in horizontal container  
   - Charts placed accordingly  

 Business Insights
- Technology drives highest sales and profit  
- Office Supplies segment shows low profit despite good sales  
- Central and West regions outperform others  
- Seasonal spikes visible in Q4 months

