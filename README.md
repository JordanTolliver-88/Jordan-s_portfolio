# Project Background

This project analyzes the Warehouse and Retail Sales data from Montgomery County, Maryland, focusing on understanding seasonal sales trends, product performance, and market fluctuations over the period from 2017 to 2020.

Insights and recommendations on the following key areas
-	**Growth Rate by Year**: Examines the year-over-year growth rates, 
-	**Sales Change by Year**: Explores how seasonality affects product movement, 
-	**Top 5 Suppliers & Seasonal Item Sales Trends**: Identifies suppliers contribute most to overall revenue. 
-	**Seasonal Item Sales Trends**: Identifies which products contribute most to overall revenue and addresses the impact of external events, such as the COVID-19 pandemic, on consumer behavior and retail performance. 
-	**Retail vs Warehouse Movement**: helps identify distribution patterns, inventory management efficiencies, and potential misalignments between warehouse stock and retail demand.

An interactive Tableau Dashboard can be downloaded [Here](https://public.tableau.com/app/profile/jordan.tolliver/viz/MontgomeryCountyMarketPerformanceTrends/Dashboard1) 

The SQL queries utilized to impact and perform quality checks can be accessed [Link](https://github.com/JordanTolliver-88/Prod_1_Queries/tree/main) 

The SQL queries utilized to clean, organize, and prepare data for the dashboard can be accessed [Link](https://github.com/JordanTolliver-88/Prod_1_Queries/tree/main) 

Targeted SQL queries regarding various business questions can be found [Link](https://github.com/JordanTolliver-88/Prod_1_Queries/tree/main) 

# Data Structure & Initial Checks
The company's main database structure, as seen below, consists of four tables: table1, table2, table3, and table4, with a total row count of X records. A description of each table is as follows
Access this link to see more details about the data. [Link]

# Executive Summary
**Overview of Findings**
This analysis highlights significant sales fluctuations, with a sharp decline in 2020 (-60% on average across categories), likely due to COVID-19. Beer, liquor, and wine experienced strong growth in 2019 (+400%), driven by consumer demand, but saw a reversal in 2020. Stakeholders should leverage insights on seasonality and economic disruptions to optimize inventory planning, marketing strategies, and revenue forecasting. 

Below is the overview page from the Tableau dashboard, and more examples are included throughout the report. The entire interactive dashboard can be downloaded [Here](https://public.tableau.com/app/profile/jordan.tolliver/viz/MontgomeryCountyMarketPerformanceTrends/Dashboard1)

![Dashboard 1](https://github.com/user-attachments/assets/37351181-4b90-473f-9069-6cabf877c09a)

**Sales Trends**

- **Major Sales Fluctuations in 2020 Reflecting the COVID-19 Impact** The analysis highlights a sharp decline in retail sales in 2020, with almost all product categories, including beer, liquor, and wine, significantly affected by the COVID-19 pandemic. In 2019, these categories saw strong growth, but by 2020, year-over-year growth rates dropped by an average of -60%, reflecting the pandemic's impact on consumer behavior.

- **Exceptional Growth in 2019 Amidst Strong Consumer Demand** In 2019, there was a remarkable rebound in retail sales, especially in beer, liquor, and wine, with some categories seeing over 400% growth. This surge suggests strong consumer demand, possibly driven by events or promotions. The stark contrast between 2019 and 2020 highlights the volatility of consumer spending, particularly in retail sectors vulnerable to external shocks.

![Rates](https://github.com/user-attachments/assets/28140acb-9d3a-4861-b258-f3e2cd7aa31e)

**Seasonal Product Movement Patterns**

Retail sales in Montgomery County, particularly in categories such as beer, liquor, and wine, exhibit clear seasonal trends that align with holiday periods and key consumer events. The holidays are historically high-demand periods for these product categories, with consumers purchasing alcohol for gatherings, parties, and celebrations. Key periods that influence sales include:

**End-of-Year Holidays (November - December):**
-   Thanksgiving and Christmas consistently drive higher sales in liquor and wine. Consumers tend to purchase larger quantities during these periods, especially in categories like wine and premium liquor for gifts and celebrations.
-    New Year’s Eve is another critical period, particularly for champagne, sparkling wines, and spirits. These sales spikes are significant and can sometimes account for a large portion of Q4 sales.
**Spring Holidays (March - April):**
-   The period around Easter also sees increased consumption of wine and liquor, with Easter brunches and family gatherings encouraging more sales in these categories. Sales of sweet wines and rosé tend to increase during this time.
**Summer Holidays (June - August:**
-   Memorial Day, 4th of July, and Labor Day are major drivers of beer sales, particularly with BBQs and outdoor gatherings. Beer tends to be the beverage of choice for casual gatherings and is likely to show the highest volume during these months.
-   Rosé and light wines also see increased sales in the summer as people enjoy more outdoor social events and picnics.

![Seasonal Trends](https://github.com/user-attachments/assets/46b1f693-de1e-4402-9650-6a677a7995bf)

**Impact of Retail vs. Warehouse Sales**

The split between retail and warehouse sales also highlighted trends in distribution patterns. Some items, particularly those with higher warehouse sales, might be distributed to multiple locations, or might be related to larger wholesale operations rather than direct consumer sales. Products with low retail sales but high warehouse sales suggest potential inefficiencies or misalignments in demand forecasting and distribution strategies.

**Some Strategic Implications for Stakeholders**
- **Retailers:** Insights into seasonality and consumer behavior shifts are crucial for future inventory planning and sales strategies. Retailers can use these insights to optimize stock levels, target marketing campaigns during peak demand periods, and manage supply chain risks more effectively.
- **Policymakers and Economic Planners:** The trends in consumer spending and market volatility provide valuable insights for tax revenue forecasting, local business support programs, and economic development strategies. Understanding the cyclical nature of sales allows for more accurate budget planning and policy development.

![Retailvs dash](https://github.com/user-attachments/assets/71c60f38-28c9-4140-ba9e-fa6027eaab75)

**Recommendations**

1.	**Seasonal Inventory Planning and Promotion Strategy:** Retailers and suppliers should align inventory and promotion strategies with seasonal sales patterns, stocking high-demand products well in advance. For example, beer sales peak around summer holidays, while wine and liquor sales increase during winter holidays.
2.	**Optimize Supply Chain During Peak Times**: Business continuity planning must account for disruptions like the COVID-19 pandemic, which significantly impacted retail sales in 2020. Suppliers should optimize supply chains to ensure high-demand products are available during peak periods and avoid inventory bottlenecks.
3.	**Forecasting and Adjustments for Economic Shocks:** Forecasting models should include flexibility to adjust for external shocks, such as pandemics or natural disasters. Historical trends and economic indicators can help businesses adapt forecasts and strategies during volatile market conditions.
4.	**Enhance Consumer Behavior Insights:** Tracking sales volume alongside demographic trends helps businesses understand shifting consumer preferences, such as increased wine consumption during the pandemic. This allows businesses to adjust product offerings and marketing strategies accordingly.
5.	**Tailored Marketing Campaigns for Key Events**: Retailers should develop targeted campaigns around specific events, such as the Super Bowl or holidays, to drive consumer traffic. Focusing on product promotions during these key moments can improve conversion rates and customer loyalty.

**Assumptions and Caveats**

1.	**Impact of COVID-19:** The COVID-19 pandemic led to significant sales declines in 2020, which may not reflect long-term trends. Future forecasts should consider post-pandemic recovery and changing consumer behavior.
2.	**Data Quality and Accuracy:** The analysis assumes data accuracy, but errors or outliers in the dataset may distort trends. Growth rates, particularly in 2018-2019, should be validated before making strategic decisions.
3.	**Seasonality and External Factors:** The analysis assumes that seasonal trends will continue, but changes in market conditions could alter consumer behavior. Businesses should be ready to adjust strategies in response to external factors.
4.	**Forecasting Limitations:** Forecasting relies on historical trends, but shifts in consumer preferences or market conditions can affect future performance. Any forecast should be treated as a projection, not a guarantee.
5.	**Regional Variations:** Trends observed in Montgomery County may not apply to other regions due to differences in local events and consumer preferences. Stakeholders should assess regional factors when using strategies.














