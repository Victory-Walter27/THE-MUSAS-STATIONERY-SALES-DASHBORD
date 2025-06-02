# THE-MUSAS-STATIONERY-SALES-DASHBORD

**Project Backgound**

Since its inception in 2006, MUSAS Stationery has operated as a cornerstone of the local community, dedicated to empowering education. As a locally owned stationery store, our mission is to meticulously select and supply students, teachers, and parents with the precise tools and materials required to foster effective learning environments and achieve academic excellence.
This sales dashboard gives a clear summary of revenue, costs, and sales performance by salesperson, region, and product.

Insights and recommendation are provided in these areas;

- Data Overview and High-Level Metrics
- Trend Analysis: Sales Year by Revenue & Forecast
- Sales Representative Performance Analysis
- Product/Item Performance Analysis
-  Regional Performance & Item Distribution Analysis

  **DATA STRUCTURE**
  
The MUSAS STATIONERY database consists of six tables: OrderDate, Region, Reps, Items, Units, Unit Cost, Total with a total row count of 308 rows. 

Prior to beginning the analysis, a variety of checks were conducted for quality control and familization with the dataset and hypothese were formulated based on the dataset.

**EXECUTIVE SUMMARY**

   The business demonstrates healthy year-over-year revenue growth of approximately 12% from 2014 to 2015, driven primarily by the strong performance of "Binder" as the top-selling item, contributing nearly 50% of total listed item revenue. While overall profitability appears robust with a high gross margin, a significant performance disparity exists among sales representatives, with a few top performers driving the majority of sales. Additionally, the "East" region consistently shows lower unit sales across all product categories, indicating an area for strategic intervention and localized market analysis.

   **DASHBOARD/REPORT**
----
![Screenshot 2024-09-03 122531](https://github.com/user-attachments/assets/f86d8eb5-09cb-4f2d-97c0-ac8a45c3e66e)

   
**Insights Deep Drive**

This includes providing a solid foundation for more in-depth strategic analysis and informed decision-making.

**1. Data Overview and High-Level Metrics:**
   
   - Total Gross Income: $19,627.88 - This is the top-line revenue generated. It's a healthy figure, but needs context from costs and profitability.
   - Cumulative Cost: $873.27 - Represents the total cost incurred. This seems relatively low compared to gross income, which is a positive indicator for gross margins.
   - Total Units Sold: 2121 - Provides volume context. An average selling price per unit can be derived ($19,627.88 / 2121 units = ~$9.25/unit). This average price can be a benchmark for new product introductions or pricing strategies.

Initial Thoughts/Hypotheses:

- The business appears to have a good gross profit margin given the high gross income relative to cumulative cost.
- The average unit price suggests a mix of low-cost, high-volume items and potentially some higher-value items.

**2. Trend Analysis: Sales Year by Revenue & Forecast:**

   - 2014 Revenue: $9,258.34
   - 2015 Revenue: $10,369.54
     
Year-over-Year (YoY) Growth (2014 to 2015): (($10,369.54 - $9,258.34) / $9,258.34) * 100% = ~12.00% growth

Observations:

- A clear positive trend in revenue from 2014 to 2015. This indicates business growth.
- The line graph for "Sales Year by Revenue" shows a generally upward slope, reinforcing the growth.
- The "Forecast by Sales Year and Revenue" chart seems to show actuals (blue) largely meeting or slightly exceeding forecasts (green).
  
Insights & Hypotheses:

- The 12% growth is a strong indicator of a healthy, expanding business.
- What drove this growth? Was it increased unit sales, higher pricing, entry into new markets/regions, or new product introductions?
- The accurate forecasting suggests a good understanding of market dynamics or a conservative forecasting approach. A deeper dive into forecast variance (actual vs. forecast deviation) would be beneficial.

**3. Sales Representative Performance Analysis**

- Top 4 Reps by Revenue: Parent ($3,102), Krivell ($3,109), Jardine ($2,812), Jones ($2,363)
- Bottom 3 Reps by Revenue: Andrews ($438), Howard ($537), Sorvino ($1,284)
  
Observations:

- There's a significant performance gap among sales representatives. Parent and Krivell are the top performers, accounting for a substantial portion of overall revenue.
- Andrews and Howard are significantly underperforming, with revenue less than a quarter of the top performers.
- The revenue distribution among reps is skewed; a few top performers drive a disproportionately large share of sales.
  
Insights & Hypotheses:

- Talent Concentration: The business heavily relies on its top sales talent. This is a strength but also a risk if these individuals leave.
Performance Disparity: This large gap warrants immediate investigation.

Hypotheses:
- Are low performers (Andrews, Howard) assigned to less lucrative territories?
- Do they lack specific training in product knowledge or sales techniques?
- Are there external factors impacting their sales (e.g., specific market conditions, competition)?
- Could there be a data quality issue for these reps (e.g., sales not properly attributed)?

Actionable Insight: Implement a "best practices" sharing program from top performers. Provide targeted coaching and development for underperforming reps. Consider re-evaluating territory assignments or sales targets.

**4. Product/Item Performance Analysis**

- Top Item by Revenue: Binder ($9,578) - Almost 50% of the listed item revenue.
- Other Key Items: Pen Set ($4,170), Pencil ($2,135), Pen ($2,045), Desk ($1,700)
  
Observations:

- "Binder" is the clear superstar product, generating almost half of the total revenue from listed items.
- There's a significant drop-off in revenue from "Binder" to the next best-selling item, "Pen Set."
- "Desk" is the lowest revenue-generating item.
  
Insights & Hypotheses:

- Product Dependency: The business appears heavily reliant on "Binder" sales. While good, this can be a risk if demand shifts or competition intensifies.
- Pricing Strategy: Is "Binder" priced optimally? Could its price be slightly increased without impacting volume given its popularity?
- Cross-selling/Upselling: Are there opportunities to bundle "Binder" with "Desk" or "Pen" to boost sales of lower-performing items?
- Marketing Focus: Marketing efforts should heavily promote "Binder" while exploring new strategies for "Desk" and "Pen."
  
Hypotheses:

- Is "Binder" a high-margin product? (Dashboard shows revenue, not profit by item).
- Are "Desk" and "Pen" facing stiff competition or a lack of market demand?
- Do "Desk" and "Pen" require a different sales approach or target audience?

**5. Regional Performance & Item Distribution Analysis**

Units of Items Sold by Region:

- Central: Strong in Binder (8 units), moderate in Pen Set (3 units), Pencil (2 units).
- East: Weak across the board (Binder: 2 units, Desk: 1 unit, Pen: 1 unit, Pen Set: 1 unit).
- West: Strongest in Pencil (9 units), also good in Binder (4 units), Desk (2 units), Pen (3 units), Pen Set (2 units).

Observations:

Regional Dominance: The "West" region is a strong performer, especially for "Pencil." "Central" is strong for "Binder."
East Region Weakness: The "East" region is consistently the lowest performer in terms of units sold across all displayed items.
Product-Region Fit: There appears to be a good product-market fit for "Pencil" in the West and "Binder" in Central.

Insights & Hypotheses:

Targeted Strategies: Sales and marketing strategies should be localized. "Pencil" campaigns for the West, "Binder" campaigns for Central.
East Region Intervention: The "East" region is a critical area for investigation.

Hypotheses:
- Why is the "East" region underperforming? Is it market saturation, a less effective sales team, stronger competition, or different customer demographics/needs in that region?
- Are there opportunities to replicate the success of "Pencil" in the West and "Binder" in Central in other regions?
- Are the top sales reps (Parent, Krivell) concentrated in the "Central" or "West" regions? (This connection can be explored with the filters).

**Recommendation**

- This sales dashboard reveals a growing business with strong performers (both reps and products) but also significant areas for improvement, particularly concerning underperforming sales representatives and the consistently low performance in the "East" region. 
- The dominance of "Binder" as a revenue driver is a key insight, highlighting both a strength and a potential over-reliance. Future analysis should focus on understanding the root causes of underperformance and leveraging the success factors of high performers and top-selling products. 
- The next steps would involve drilling down into the identified areas, possibly through new custom reports or by accessing the raw data for more granular analysis.






