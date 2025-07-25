# Company-Finacial-Performance
This project analyzes a company's financial performance by evaluating key metrics such as revenue, profitability, liquidity, and efficiency to assess its overall financial health and business sustainability.
![](https://github.com/Thetelegram212/Company-Finacial-Performance/blob/main/Statutory%20Accounts_%20Comprehensive%20Financial%20Reporting.jpeg)
## Introduction

As a data analyst, I conducted a detailed financial performance analysis using a dataset consisting of sales and profit data segmented by market and country/region. The project involved importing the dataset as CSV files into Power Query in Excel, where I carried out data cleaning, transformation, and exploration. Following the six stages of the data analytics process — Ask, Prepare, Process, Analyze, Share, and Act — I leveraged Excel tools to uncover key insights related to revenue trends, profitability by region, and efficiency across segments, enabling data-driven recommendations for business growth and sustainability.

---

 ## Ask

 **Problem Statement**

In this stage, the focus was on clearly understanding the business problem and defining the key questions to guide the analysis. The primary objective was:

"How is the company performing financially across different market segments and regions, and where can improvements be made to boost profitability and efficiency?"

* Key guiding questions included:

* Which market segments and regions generate the highest sales and profits?

* Are there regions or segments underperforming financially?

* What trends can be observed in revenue and profit over time?

* How can insights from the data support better decision-making?

This stage helped align the analysis with business goals and ensured that the insights would be relevant and actionable.

---

## Prepare

**Data Collection and Understanding**

In this stage, I gathered and reviewed the dataset to understand its structure, variables, and relevance to the business objective. The dataset was imported from a CSV file into Power Query in Microsoft Excel, where initial exploration was carried out.

The dataset contains 22 columns and 638 rows, representing sales and profit data across different countries, market segments, and time periods.

#### Dataset Description
* Segment – The business or customer segment (e.g., Consumer, Corporate, Home Office).

* Country – The geographic location where the sale occurred.

* Product – The specific item or product sold.

* Discount Band – The category of discount applied (e.g., None, Low, High).

* Units Sold – Total quantity of the product sold.

* Manufacturing Price – Cost to produce a single unit of the product.

* Sale Price – Selling price per unit before discounts.

* Gross Sales – Total revenue before applying discounts (Sale Price × Units Sold).

* Discounts – Total value of discounts given.

* Sales – Net sales amount after applying discounts.

* COGS (Cost of Goods Sold) – Total cost to produce the units sold.

* Profit – Net gain from the sale (Sales - COGS).

* Date – The specific date of transaction or record.

* Month Number – Numerical representation of the month (e.g., 1 for January).

* Month Name – Text format of the month (e.g., January, February).

* Year – The year the sale took place.

* Month Sort – A custom column used to help sort the months chronologically.

* Profit Margin – Percentage of profit from the sales (Profit ÷ Sales).

* Average Revenue Per Unit – Average revenue earned for each unit sold.

* Discount Rate – Percentage of discount applied.

This stage helped confirm the completeness and relevance of the data before proceeding to transformation and analysis.


---

## Process

**Data Tranformation**

In this stage, I focused on collecting and preparing the data for analysis to ensure accuracy and consistency. The dataset, which contained sales and profit data across various market segments and regions, was imported as CSV files into Power Query in Excel for cleaning and transformation.

Key steps taken during this phase included:

* Reviewed and corrected column names to fix any errors or inconsistencies at the point of import.

* Removed unwanted characters such as the '$' sign and '-' from relevant columns to standardize the values.

* Changed data types from text (object) to integers or decimals to enable accurate numerical analysis.

* Removed commas (",") from numerical values to ensure they were correctly recognized as numbers by Excel.

These preparation steps helped create a clean, well-structured dataset ready for in-depth exploration and analysis.


---


##  Analyze

**Exploring the Data and Generating Insights**

In this stage, I explored the cleaned dataset by applying Excel-based visualizations and dashboards to uncover trends, patterns, and relationships relevant to the financial performance of the company. The analysis focused on the Government segment in the year 2013, and key insights were derived from the dashboard metrics and charts.

📌 **Key Insights from the Analysis: Overall Financial Performance (2013 – Government Segment):**

* Total Profit: $8.5M (+195% vs last year)

* Sales Revenue: $39.4M (+201% vs LY)

* Profit Margin: 29.2% (slightly down -1% vs LY)

* Cost of Goods Sold (COGS): $30.9M (+203% vs LY)

* Units Sold: 347.2K (+181% vs LY)

* Average Revenue per Unit: $116.3 (-1% vs LY)

* Total Discount Given: $3.0M (+224% vs LY)

📊 **Visual Breakdown & Trends:**
Yearly Trends:

Both profit and sales peaked significantly in October and December, suggesting seasonal spikes in government purchases.

Top Countries by Sales & Profit:

Germany led in performance with $5.7M sales and $1.1M profit.

Other top markets included the USA, France, Canada, and Mexico.

**Product Performance:**

Paseo and Amarilla had the highest COGS and sales figures, with Paseo reaching almost $16M in COGS.

Velo and Paseo received the highest unit discounts, totaling $536.6K and $527.2K respectively.

Profit Margin by Product:

VTT (40.3%), Paseo (37.4%), and Velo (35.2%) had the highest profit margins.

Amarilla had the lowest margin at 18.9%, indicating a possible pricing or cost challenge.

![](https://github.com/Thetelegram212/Company-Finacial-Performance/blob/main/Screenshot%202025-07-23%20191203.png)


---

## Share

**Communicating Insights and Findings**

In this stage, I focused on effectively presenting the insights uncovered during analysis to stakeholders in a clear, concise, and actionable format. Using Excel dashboards and visuals, I transformed raw data into meaningful narratives tailored to the business objective.

 **Communication Tools Used:**
Interactive Dashboard in Excel: Incorporated slicers for Segment and Year filters, enabling users to explore financial performance dynamically.

Visual Charts: Used a combination of line graphs, bar charts, and donut charts to present:

* Yearly trends in Sales and Profits

* COGS by Product

* Profit Margins by Product

* Sales & Profits by Country

* Unit Discount Distribution

**Summary of Findings Shared:**
* Government Segment (2013) experienced strong financial growth, with profits up 195% and sales up 201% vs. the previous year.

* Key markets like Germany and USA drove profitability, while products like VTT and Paseo maintained high margins.

* Some products (e.g., Amarilla) showed low margins despite high COGS, signaling potential areas for strategic review.

* Seasonal trends suggest focusing sales efforts during high-performing months like October and December.

**Stakeholder Relevance:**
The visual report and dashboard enabled non-technical stakeholders to:

* Identify top-performing regions and products

* Spot inefficiencies (e.g., high discounting, low-margin products)

* Make informed decisions regarding pricing, promotions, and inventory planning


---

##  Act 

**Driving Business Decisions and Taking Action**

In the final stage, I translated analytical insights into strategic recommendations to guide the company's financial and operational decisions for sustained performance improvement.


**Strengthen High-Performing Product Lines**:

* Invest in products like Paseo, Velo, and VTT which showed high profit margins and strong sales volumes.

* Consider expanding distribution or bundling offers around these top products.

**Optimize or Review Low-Margin Products**:

* Amarilla, despite decent sales, has the lowest profit margin (18.9%).

* Conduct a cost review or consider pricing adjustments to improve profitability.

**Target High-Yield Markets**:

* Focus sales and marketing campaigns on Germany and the United States, which delivered the highest returns.

* Leverage the strong performance in these countries to pilot new offers or test pricing models.

**Leverage Seasonal Trends**:

* Allocate more budget and inventory in the last quarter (especially October and December), when sales and profits peak.

* Plan promotional campaigns around this period to maximize ROI.

**Evaluate Discounting Strategy**:

* Total discounts amounted to $3M, with significant portions applied to Velo and Paseo.

* Review discount policies to ensure they are yielding corresponding revenue growth and not eroding margins.

**Monitor Decline in Avg. Revenue per Unit**:

* Even with overall sales growth, average revenue per unit decreased by 1%.

* Consider whether bundling, upselling, or value-added services can help raise the per-unit revenue.


---

### **Conclusion**

This project provided a comprehensive analysis of the company’s financial performance within the **Government segment for the year 2013**, using Excel as the primary tool. Through the application of the six stages of the data analytics process — **Ask, Prepare, Process, Analyze, Share, and Act** — I transformed raw sales data into actionable insights.

Key findings revealed significant year-over-year growth in **profits (↑195%)** and **sales (↑201%)**, with strong contributions from high-performing products like **Paseo** and regions like **Germany**. However, the analysis also identified areas for improvement, such as declining **average revenue per unit**, **high discounts**, and **low-margin products** like Amarilla.

By visualizing trends and performance drivers through a well-structured dashboard, this analysis equips decision-makers with clear direction for optimizing pricing strategies, enhancing product profitability, and maximizing market opportunities.

Overall, the insights derived from this project will support more informed, data-driven business decisions and contribute to sustained financial growth.








