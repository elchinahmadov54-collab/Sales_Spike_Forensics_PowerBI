
This project demonstrates the application of advanced Power BI features to conduct root-cause analysis on significant sales events. 
The goal was to move beyond descriptive statistics to determine why two major sales spikes occurred within a given period.

The methodology showcases the integration of data science techniques (Clustering) with Power BI's built-in AI tools (Analyze feature) to derive actionable business insights.

Technology and Methodology
Technology: Power BI Desktop (DAX, Power Query).
Data Model: Star Schema structure linking Sales, Order, and Customer dimension tables.

Key Analytical Steps
Time Series Analysis: Identified two critical days with the highest peaks in Order Total.

Product Clustering Products were grouped into 3 clusters based on their Order Total and Product Price. This provided a new dimension (Product Name (clusters)) to simplify the analysis of product groups.
Power BI Analyze Feature: The "Explain the Increase" function was used on both peak days to automatically generate visuals and determine contributing factors.

Key Insight Identification: The analysis successfully identified three shared contributory factors influencing both sales spikes: Payment Method, Product Category, and the custom Product Name (clusters) dimension.

Visualizations 
The report visualizes the key findings:
1)Sales Performance: Line Chart tracking daily Order Total.
2)Clustering: Scatter Chart showing the 3 clusters.
3)Top Contributors: Dedicated visuals (Donut Chart, Bar Chart, Treemap) were created to demonstrate the impact of the three identified key factors on total sales, ensuring the insights are clear and actionable.
