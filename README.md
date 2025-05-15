**Business Insights 360**

I worked on this project by following the Codebasics Power Bi Course, Link to the course is     (https://prod4.codebasics.io/)

Live Power BI Project Link : (https://app.powerbi.com/links/XjxtLXamvG?ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4&pbi_source=linkShare&bookmarkGuid=71b8878d-d1bc-4495-a327-6ad629916885)

Dashboard in PDF : (https://smallpdf.com/file#s=a83dca1c-e9ec-436d-bc3f-20c4695b1263)

**🛠️Tools:**

  1)Excel-Data cleaning and transformation, Pivot Table, Power Query.
  
  2)SQL-Data Retrieval, Aggregation, Data Integration.
  
  3)Power BI Desktop -Data Modelling, Dax, Power Query (M Language).
  
**A)🏬Company Overview:**

AtliQ Hardware (imaginary company) is a rapidly growing electronics company specializing in hardware products, including PC accessories, printers, and more. Over the years, AtliQ has expanded significantly, establishing a strong global presence in key regions such as APAC, North America, Latin America, and the European Union.

**2 Primary sales platforms:**

   1)Brick-and-Mortar Stores – Partnering with physical retail outlets like Croma and Best Buy.
   
   2)E-Commerce Platforms – Selling through online giants like Amazon and Flipkart.
   
**3 Multiple sales channels:**

   1)Retailers – Third-party sellers, both online and offline, that stock and sell AtliQ’s products.
   
   2)Direct Stores – AtliQ’s own branded stores, where consumers can purchase directly.
   
   3)Distributors – In restricted markets like China and South Korea, AtliQ collaborates with large      
    distributors to ensure product availability.
       
Note: AtliQ’s customers are retailers and distributors, while the consumers are the end users.

**B)🔎 Problem Statement:**

AtliQ Hardware (a mock enterprise) faced major losses due to inefficient decision-making caused by scattered Excel sheets. Competitors using advanced analytics gained an edge, leaving AtliQ struggling with outdated methods. To stay competitive, AtliQ launched a data analytics project to make data driven decision making & strategic growth.

**C)🎯Project Objective:**

To develop an intuitive dashboard that delivers actionable insights for finance, sales, marketing, and supply chain teams, along with an executive and key performers view. This will enhance transparency, improve data accessibility, and empower stakeholders to make informed, data-driven decisions for strategic growth and efficiency.

**D)🛢Data Overview:**

**3 Excel files:**

    1)Operating Expenses,
    
    2)Targets (available only for FY 2022),
    
    3)Market Share (limited to the Personal Computer division).
    
**2 databases:**

    1)gdb041:
		
      1.1) Fact tables: fact_forecast_monthly, fact_sales_monthly.
			
      1.2) Dimension tables: dim_customer, dim_market, dim_product.
			
    2)gdb056:
		
      2.1) Supporting tables: freight_cost, gross_price, manufacturing_cost, post_invoice_deductions and pre_invoice_deductions.

 AtliQ’s fiscal year runs from September to August, and the dataset covers actual sales from  September    1 , 2017, to December 31, 2021.
 
 NOTE: Since this is a bootcamp project, the data files cannot be shared.

**E)📑Importing data into PowerBi:**

       Imported datasets from MySQL Database to Power BI.

**F)🧹️Data Cleaning & Transformation**:

**Standardized & Trimmed Data:**

      1)Removed leading and trailing spaces from text fields.
			
      2)Standardized naming conventions for consistency.
			
**Data Structuring & Optimization:**

      1)Created a dim_date table for better time-based analysis.
			
      2)Merged fact_sales_monthly and fact_forecast_monthly into a single table,   fact_actual_estimates, to simplify calculations.
			
      3)Added calculated fields in fact_actual_estimates using data from relevant tables (e.g., deriving pre-invoice deductions using percentage values from the pre_invoice_deductions table).
			
      4)Disabled load for tables that were used to derive calculations in fact_actual_estimates to optimize performance and reduce the Power BI report size.

**G) 🛢 Data Model:**

        Snowfall data modeling method.

**H)📑 Report Inclusions:**

       Includes a PDF version of the Power BI report,
				
       1)Dashboard in PDF,(https://smallpdf.com/file#s=a83dca1c-e9ec-436d-bc3f-20c4695b1263)
			 
       2)Live Dashboard in Power Bi Service.(https://app.powerbi.com/links/XjxtLXamvG?ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4&pbi_source=linkShare&bookmarkGuid=71b8878d-d1bc-4495-a327-6ad629916885)
			 
**I)💡Insights:**

**Business Growth & Financial Performance:**

       1)Rapid expansion: Net Sales grew ~280% (FY 2019), ~140% (FY 2020), ~200% (FY 2021) and ~350% (FY 2022).
			 
       2)Net Profit % remains negative since 2020 due to high operational and marketing expenses,typical for a company in its growth phase.
			 
**Revenue & Market Trends:**

       1)APAC remained the largest market (FY 2019–FY 2022), led by India, while Latin America was the smallest.
			 
       2)Amazon was the top global customer in all years, while Nova (operating in Austria) was the smallest since FY 2020.
			 
       3)Notebook segment had the highest Revenue growth in all fiscal years but recorded the most negative Net Profit % in FY 2022, likely due to increased marketing spend.
			 
       4)Desktop had the lowest growth in FY 2019 & FY 2020, while Networking became the weakest segment in FY 2022.
			 
       5)USB flash drives underperformed in FY 2021 & FY 2022, signaling product or market challenges.
			 
**Sales & Customer Insights:**

       1)Flat post-discounting model for all products and customers within each market is significantly eroding Gross Margin %. A performance-based discounting strategy per product and customer within each market is recommended to optimize profitability.
			 
       2)Certain products, like AQ 5000 Series Electron 9 5900X, AQ MB Elite, and AQ Wi Power Dx1, had zero sales in FY 2022, likely due to demand shifts or outdated models.
			 
**Forecast Accuracy & Supply Chain Efficiency:**

       1)Forecast Accuracy (FCA%) dropped from ~86% (FY 2019) to ~73% (FY 2020) due to COVID-19 disruptions but improved to ~80% (FY 2021) and ~81% (FY 2022).
			 
       2)Excess inventory was a major issue in FY 2019–FY 2020, while stock shortages became a challenge in FY 2021–FY 2022.
			 
       3)Work-from-home demand surged in FY 2020, leading to stockouts for processors, keyboards, and WiFi extenders.
			 
**Competitive Position & Market Share:**

       1)Atliq’s PC market share grew from ~1% (FY 2021) to ~6% (FY 2022), though Dale remains the dominant player.
			 
       2)India was the fastest-growing market (~13% share in FY 2022).
          
			 3)Among subzones, North America had the highest revenue in FY 2022, but Atliq’s market penetration remained only ~5%.
		
**Operational & Strategic Insights:**

       1)Sales peaked from September to December across all years, likely due to festive and year-end promotions.
			 
       2)Retailers contributed ~72% of revenue in FY 2022.
			 
       3)The UK had the highest marketing costs, making it a key area for strategy review, followed by Germany (low revenue, high marketing spend).
			 
**J)📝 Recommendations:**

       1)Gradually reduce operational and marketing expenses after capturing significant market share to improve Net Profit %.
			 
       2)Shift from flat post-discounting to a performance-based model per product and customer in each market.
			 
       3)Expand distribution and targeted marketing in high-growth region like APAC and in APAC India.
			 
       4)Reevaluate the pricing or cost structure of the Notebook segment to enhance Net Profit %.
			 
       5)Investigate the underperformance of USB flash drives and consider repositioning, discontinuing, or introducing improved models.
			 
       6)Improve forecasting, especially for customers, by leveraging real-time data to minimize stock  imbalances and enhance supply chain efficiency.
			 
       7)Develop targeted strategies to increase market share in North America.
			 
       8)Focus on differentiation to strengthen competitiveness in the PC segment and challenge dominant players like Dale.
			 
       9)Optimize marketing spending in the UK and Germany to improve return on investment.
			 
       10)Align inventory planning and promotions with the September–December sales surge to maximize seasonal demand.
