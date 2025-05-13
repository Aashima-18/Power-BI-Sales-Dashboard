# Power-BI-Sales-Dashboard

This is the superstore.csv file from the Kaggle dataset store.

A screenshot of the visual dashboard created in Power BI is attached to this repository.

A step-wise, summarized description to create a visual representation of the sales dashboard in Power BI is given below--

1. Import and Clean Data:
-Load data from Excel/CSV.
-Format columns (Date, Sales, Profit, etc.).
-Remove nulls and duplicates.

2. Create Measures (KPIs):
-Total Sales = SUM(Sales)
-Total Profit = SUM(Profit)
-Units Sold = SUM(Quantity)
-COGS = SUM(Cost of Goods Sold)

3. Build a Date Table:
-Add Year, Quarter, and Month.
-Create relationship with main data table.

4. Add Slicers:
-Year
-Product
-Segment
-Date Range

5. Create Visuals:
-Cards for Sales, Profit, Units, and COGS.
-Map for Country-wise Sales.
-Line Chart: Sales & Profit over time.
-Bar Chart: Profit by Product.
-Donut Chart: Sales by Product.
-Bar Chart: Profit by Discount Band.
-Stacked Bar: Sales by Segment & Product.

6. Design and Format:
-Apply color themes and titles.
-Align visuals in grid layout.
-Enable interactivity between slicers and charts.
