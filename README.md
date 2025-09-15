# Power-bi-sales-report
1. *Project Title* : Sales & Revenue Performance Dashboard
   Interactive Power BI dashboard analyzing revenue, profit, and margin% across multiple product categories, retailer types, and regions.

2. *Purpose*: This Power BI report provides a comprehensive view of revenue, profit, and margin performance for 2016 & 2017 across multiple product categories. It highlights monthly sales trends, compares performance by retailer type, urgency, and sales method, and offers regional insights through an interactive map. The dashboard enables stakeholders to quickly identify key drivers of revenue, track profitability, and make data-driven business decisions.
   
3. *Tech Stack* :
   1. Power BI Desktop – Used to design and build the interactive dashboard with visuals and KPIs.
   2. Power Query (M Language) – Performed data cleaning, transformation, and shaping before loading into the model.
   3. DAX (Data Analysis Expressions) – Created calculated columns, measures, and KPIs for revenue, profit, and margin analysis.
   4. Data Modeling – Built relationships between tables and applied star schema for efficient performance.
   5. Power BI Visuals – Designed charts, maps, and KPIs for trend analysis and regional insights.
  
4. *Business Problem*: The company operates across multiple product categories, sales channels, and geographies, but decision-makers lack a consolidated view of revenue performance. Without a unified dashboard, it is difficult to track how different categories, retailer types, and regions are contributing to overall growth. Seasonal fluctuations, urgent vs. non-urgent orders, and varying profit margins add complexity, making it challenging to identify trends or areas that require attention.

Additionally, leadership needs visibility into which categories or markets are underperforming, and how sales methods or retailer types affect profitability. Without these insights, resource allocation, demand planning, and pricing strategies risk being based on assumptions rather than data-driven evidence.

   *Goal of the dashboard*: The goal of this dashboard is to provide a centralized, interactive view of revenue performance across different dimensions — time, category, retailer type, urgency, and geography. By consolidating KPIs like revenue, margin%, and profit alongside detailed breakdowns, the dashboard enables users to drill down into what’s driving performance.

It helps business leaders quickly identify high-performing categories, seasonal trends, and regional opportunities while also spotting weak areas. This empowers the organization to make data-backed decisions around product strategy, marketing focus, and operational improvements, ultimately driving sustainable growth.

5. *Walkthrough of the key visuals*:

Top Section

   5a. *Chiclet Slicer* (Categories)
    Three categories available:
    
   i. Camping Equipment
      
   ii. Mountaineering Equipment
      
   iii. Outdoor Protection
      
   Acts as a filter to switch between different product categories and update the visuals accordingly.

 5b. *KPI Cards*
 
   i.Revenue: $180.3M
  
  ii.Margin %: 37.31%
  
  iii.Profit: $67.3M
  
These cards give a quick snapshot of overall financial performance for 2016.

Left Section (Top)

 5c. *Year & Metric Slicer* (Tile Buttons)
   
   i. Allows selection between 2016 / 2017.
   
   ii.Users can also toggle between Cost, Profit, Revenue.
   
   iii.Controls the data context for other visuals.

 5d. *Revenue by Month* (Line Chart)
  
  i. Displays monthly revenue trend for the selected year.
  
  ii. Key peaks: April (20.1M), dips: July (11M) in 2016.
  
  iii. Shows seasonality and performance fluctuations.

Right Section

 5e. *Bookmarks with 3 Buttons*
  Switch between different revenue breakdowns:
  
   i. By Product Type
   
   ii. By Urgency 
   iii. By Method Type

Makes the report interactive and flexible.

Left Section (Bottom)
 5f. *Revenue by Retailer Type* (Ribbon Chart)
   
   i. Breaks down revenue by retailer type (Outdoor Shop, Sports Store, Warehouse Store).
   
   ii. Visualizes which type of retailer dominates across months and how rankings change over time.

Right Section (Bottom)

 5g. *Map Visual* – Revenue by Countries

   i. Shows geographical distribution of revenue.
    
   ii. Highlights top regions such as North America and Europe.
   
   iii.Useful for identifying regional sales strengths.

*Business impact*:This dashboard empowers the business to make smarter, faster decisions by giving a clear view of revenue, profit, and margin trends across categories, channels, and geographies. With visibility into seasonal fluctuations, urgent vs. non-urgent demand, and retailer performance, leaders can optimize pricing, inventory, and sales strategies. Ultimately, it helps reduce missed opportunities, improve profitability, and allocate resources effectively to the right markets and product lines.

6. *Screenshot/Demo*:
   ![Dashboard Preview](https://github.com/anushagc04-pbi/Power-bi-sales-report/blob/main/Snapshot%20of%20the%20Sales%20Report.png)
