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

# Data Structure & Initial Checks:
The company’s main database is structured into four key tables, each containing critical data related to warehouse and retail sales. These tables are designed to provide a comprehensive view of product sales, inventory movement, and supplier information across various time periods. Below is an overview of each table in the database, with a total row count of 307,646 records.
Access this link to see more details about the data. [Link](https://data.montgomerycountymd.gov/Community-Recreation/Warehouse-and-Retail-Sales/v76h-r7br/about_data)

# Executive Summary
## **Overview of Findings**

This analysis highlights significant sales fluctuations, with a **sharp decline in 2020 (-60% on average across categories)**, likely due to COVID-19. Beer, **liquor, and wine experienced strong growth in 2019 (+400%)**, driven by consumer demand, but saw a reversal in 2020. Stakeholders should leverage insights on seasonality and economic disruptions to optimize inventory planning, marketing strategies, and revenue forecasting. 

Below is the overview page from the Tableau dashboard, and more examples are included throughout the report. The entire interactive dashboard can be downloaded [Here](https://public.tableau.com/app/profile/jordan.tolliver/viz/MontgomeryCountyMarketPerformanceTrends/Dashboard1)

![Dashboard 1](https://github.com/user-attachments/assets/37351181-4b90-473f-9069-6cabf877c09a)

**Sales Trends:**

- **Major Sales Fluctuations in 2020 Reflecting the COVID-19 Impact** The analysis highlights a sharp decline in retail sales in 2020, with almost all product categories, including beer, liquor, and wine, significantly affected by the COVID-19 pandemic. In 2019, these categories saw strong growth, but by 2020, year-over-year growth rates dropped by an average of -60%, reflecting the pandemic's impact on consumer behavior.

- **Exceptional Growth in 2019 Amidst Strong Consumer Demand** In 2019, there was a remarkable rebound in retail sales, especially in beer, liquor, and wine, with some categories seeing **over 400% growth**. This surge suggests strong consumer demand, possibly driven by events or promotions. The stark contrast between 2019 and 2020 highlights the volatility of consumer spending, particularly in retail sectors vulnerable to external shocks.

![Dashboard 1](https://github.com/user-attachments/assets/85a01ae1-4342-4382-9d3a-6ed65da14b63)

**Seasonal Product Movement Patterns:**

Retail sales in Montgomery County, particularly in categories such as beer, liquor, and wine, exhibit clear seasonal trends that align with holiday periods and key consumer events. The holidays are historically high-demand periods for these product categories, with consumers purchasing alcohol for gatherings, parties, and celebrations. Key periods that influence sales include:

**End-of-Year Holidays (November - December):**
-   **Thanksgiving and Christmas** are consistently high-demand periods for liquor and wine, with wine showing a significant increase. For example, during **December 2019**, wine sales increased by **32%**, driven by gift purchases and holiday gatherings.
-    **New Year’s Eve** is a critical period, especially for champagne, sparkling wines, and spirits, where **sales can spike by over 50%** in some categories, representing a large portion of Q4 sales. **In 2020**, champagne sales alone accounted for **15%** of annual sales in the wine category during the holiday season.

**Spring Holidays (March - April):**

-   **Easter** leads to increased sales of sweet wines and rosé, with a **15% rise in rosé consumption during the Easter weekend**. This increase may be driven by brunches, family gatherings, and spring celebrations, where wine tends to be a preferred beverage for these social occasions.
-   **Liquor** also sees a notable uptick during this period, with whiskey and vodka **sales rising by 20%** during March and April compared to the average sales in the earlier months.

**Summer Holidays (June - August):**

-   **Memorial Day**, 4th of July, and Labor Day are significant drivers for beer sales, especially in categories like lager and light beer. **Beer sales typically surge by 25-30%** during these holidays due to BBQs and outdoor gatherings.
-   **Wines & Liquors** also see a rise in sales, with rosé particularly benefitting from summer events like picnics and outdoor festivals, **showing a 20% increase in sales during these months**.

![Seasonal Trends](https://github.com/user-attachments/assets/46b1f693-de1e-4402-9650-6a677a7995bf)

**Impact of Retail vs. Warehouse Sales**

The split between retail and warehouse sales also highlighted trends in distribution patterns. Some items, particularly those with higher warehouse sales, might be distributed to multiple locations, or might be related to larger wholesale operations rather than direct consumer sales. Products with low retail sales but high warehouse sales suggest potential inefficiencies or misalignments in demand forecasting and distribution strategies.

**Some Strategic Implications for Stakeholders:**
- **Retailers:** Insights into seasonality and consumer behavior shifts are crucial for future inventory planning and sales strategies. Retailers can use these insights to optimize stock levels, target marketing campaigns during peak demand periods, and manage supply chain risks more effectively.
- **Policymakers and Economic Planners:** The trends in consumer spending and market volatility provide valuable insights for tax revenue forecasting, local business support programs, and economic development strategies. Understanding the cyclical nature of sales allows for more accurate budget planning and policy development.

![Retailvs dash](https://github.com/user-attachments/assets/71c60f38-28c9-4140-ba9e-fa6027eaab75)

**Recommendations:**

1.	**Seasonal Inventory Planning and Promotion Strategy:** Retailers and suppliers should align inventory and promotion strategies with seasonal sales patterns, stocking high-demand products well in advance. For example, beer sales peak around summer holidays, while wine and liquor sales increase during winter holidays.
2.	**Optimize Supply Chain During Peak Times**: Business continuity planning must account for disruptions like the COVID-19 pandemic, which significantly impacted retail sales in 2020. Suppliers should optimize supply chains to ensure high-demand products are available during peak periods and avoid inventory bottlenecks.
3.	**Forecasting and Adjustments for Economic Shocks:** Forecasting models should include flexibility to adjust for external shocks, such as pandemics or natural disasters. Historical trends and economic indicators can help businesses adapt forecasts and strategies during volatile market conditions.
4.	**Enhance Consumer Behavior Insights:** Tracking sales volume alongside demographic trends helps businesses understand shifting consumer preferences, such as increased wine consumption during the pandemic. This allows businesses to adjust product offerings and marketing strategies accordingly.
5.	**Tailored Marketing Campaigns for Key Events**: Retailers should develop targeted campaigns around specific events, such as the Super Bowl or holidays, to drive consumer traffic. Focusing on product promotions during these key moments can improve conversion rates and customer loyalty.

**Assumptions and Caveats:**

1.	**Impact of COVID-19:** The COVID-19 pandemic led to significant sales declines in 2020, which may not reflect long-term trends. Future forecasts should consider post-pandemic recovery and changing consumer behavior.
2.	**Data Quality and Accuracy:** The analysis assumes data accuracy, but errors or outliers in the dataset may distort trends. Growth rates, particularly in 2018-2019, should be validated before making strategic decisions.
3.	**Seasonality and External Factors:** The analysis assumes that seasonal trends will continue, but changes in market conditions could alter consumer behavior. Businesses should be ready to adjust strategies in response to external factors.
4.	**Forecasting Limitations:** Forecasting relies on historical trends, but shifts in consumer preferences or market conditions can affect future performance. Any forecast should be treated as a projection, not a guarantee.
5.	**Regional Variations:** Trends observed in Montgomery County may not apply to other regions due to differences in local events and consumer preferences. Stakeholders should assess regional factors when using strategies.
