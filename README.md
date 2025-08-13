## Edibles Sales Performance Analysis (2021-2024)
Compiled by Mokutmfon Essien

### Table of Contents

- [Project Background and Overview](#project-background-and-overview)
- [Project Goals](#project-goals)
- [Data Structure Overview](#data-structure-overview)
- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
  - [Sales and Revenue Growth Trend](#sales-and-revenue-growth-trend)
  - [Product and Division Performance](#product-and-division-performance)
  - [Country Performance Analysis](#country-performance-analysis)
- [Recommendation](#recommendation)
- [Technical Details](#technical-details)
- [Caveats and Assumptions](#caveats-and-assumptions)

---

### Project Background and Overview

Edibles is a United States candy distribution company specializing in confectionaries such as candies, chocolates, and sweets. The company has demonstrated consistent growth from the period of 2021-2024, driven by market demand and consumption behaviour.

The KPIs that we are investigating are Total Revenue (TR), Average Order Value (AOV), Sales Growth Rate, Gross Profit Margin, and target sales attainment percentage. Recommendations from this analysis would be used by the sales and finance teams to utilize productive resources better and improve returns on inventory investment. Insights are delivered to the CEO, the head of sales, and regional heads.

---
### Project Goals

The main objectives are to:
1. Access Edibles’ sales performance from 2021 to 2024 to evaluate revenue health and budget resources effectively for inventories with profit-maximizing potential.
2. Identify seasonality patterns and key trends in monthly sales to drive revenue growth further and leverage consumer consumption patterns.
3. Provide actionable recommendations to the sales and finance team to better understand underperforming areas, enabling strategic adjustments.

---
### Data Structure Overview

The analysis employed synthetic data representing product name, division, country, state, sales, target, and transaction date from Jan 2021 to Dec 2024. Key data points include:

- Product data: Reference table that includes Product ID, Product name, and Division.
- Sales data: Each unique record represents a sales transaction, including information about the sales date, as well as the sale dates and products
- Target Data: Contains data on each product’s yearly target as well as the product’s division.

Data cleaning and transformation were conducted using Excel (Power Query and Power Pivot) to automate tasks such as date normalization, value formatting, and relational table merging. These steps ensured consistency and reduced manual processing time.
<img width="624" height="303" alt="erd" src="https://github.com/user-attachments/assets/b11d9f91-9199-4140-811b-c68d61d54933" />


---
### Executive Summary

Edibles have demonstrated steady growth and an increase in sales from **2021 to 2024**. The total sales amount is **$46K** for **2024**, with a steady growth rate of **27%** in **2023** and **2024**. This growth results from the chocolate division, contributing the most to sales with total sales of **$43k** in **2024**, and has driven **92%** of Edibles’ total sales consecutively for 4 years.

The yearly target of **$27k** has been surpassed by the Chocolate division by **61%** in **2024**, with the **United States** acting as a major contributor to this growth, and Triple Dazzle Caramel being the best-performing product from **2022 to 2024**. However, there have been very low sales, including periods of zero activity in the sugar division, driving less than 1% of total sales every year.

A downward trend exists every first quarter of the year, with **February** experiencing the lowest sales, accompanied by a consistent sales spike in **September** and a peak in **December**, aligning with holiday-driven consumer behaviour and demand surges. Further investigation into consumers’ preferences and consumption behaviour in the U.S. and Canada is recommended to better understand the reason for the dip in certain divisions.

---
### Insights Deep Dive

#### Sales and Revenue Growth Trend

**Insights**: There has been a steady increase in yearly revenue, ranging between **$28K and $46K** in four years, most recently **$46K**. Edibles has experienced a yearly growth rate of **27%** in the past two years and an annual profit margin of **66%** consistently for the past two years.

Monthly sales exhibit a consistent pattern every year from 2021 to 2024. Sales are at their lowest every February, yielding only **2%** of yearly sales in **2021-2022** and **3%** sales in **2023-2024**. This builds up as the year progresses, and a spike in sales is consistent every **September**, exceeding August levels by **73%** to **100%** over the past four years. This is possibly due to an expectation of October’s Halloween festivals.

Interestingly, October sales consistently declined despite the proximity to Halloween, suggesting that consumers may engage in pre-season stockpiling behaviour, purchasing in September in anticipation of October demand. Sales are usually at their highest in **December**, creating a very predictable pattern.

#### Product and Division Performance

**Insight**: Sales growth from **2021** to **2024** has primarily been driven by the Chocolate division, which accounted for **92%** of total revenue in 2024, generating an average of **$3.6k** in monthly revenue. Within this division, the Wonda Bar product line stands out, contributing **92%** to **96%** of sales across four years.

Top-performing products include **milk chocolate, scrumdiddlyumptious, triple dazzle caramel, fudge mallows, and the nutty crunch surprise**. Between the range of **92%** to **96%** of total sales are generated from the Wonda Bar product line, with **Triple Dazzle Caramel** as the best-performing product and top sales driver consistently for 4 years. The Triple Dazzle Caramel has also attained a growth rate of **33%** in **2024**.

Inversely, the sugar division has shown no productivity, driving less than **1%** of total sales and meeting only **1%** of the yearly sales target. Products such as **Everlasting Bobstopper, Hair Toffee, and Fun Drip** have had no sales in **2021** and **2022**and have struggled to gain momentum ever since.

#### Country Performance Analysis

**Insight**: The United States accounts for **92%** of total sales consistently for 4 years. It has emerged as the best-performing country with an average monthly revenue of **$2.4k** and total revenue of **$47k** in **2024**. The chocolate division thrives in the United States as compared to Canada, with **California, Texas, New York, Pennsylvania, and Illinois** being the top-performing states in the United States. These top-ranking sales are also the main demanders of triple Dazzle Caramel.

---
### Recommendation

- Given the upward trend in the top 5 products in the chocolate division, reallocate the budget for the next 3 years to focus on these products.
- Leverage the seasonality in sales during the holiday period by incorporating an incentives program such as bonuses, discounts, and offers to stimulate sales.
- Conduct market research by investigating the possible reasons for the dip in sales during the first quarter of the year and consider reconstructing marketing strategies for these underperforming months.
- Investigate the possible cause for the low demand for products in Canada, and also analyze market demand to understand consumer choice and preference in this region.

---
### Technical Details

The technical details involved:
Excel (Power Query and Power Pivot) for data cleaning, transformation, and automation of repetitive ETL tasks and also merging datasets, removing duplicates, and date normalization. Find the link to the dataset [here](https://1drv.ms/x/c/2af15b599922c5f6/ESAGlrRsLYNDhf5fJAw0B4QB8DftI9bevlURj8pgPsAOvQ?e=EqO4XP).

---
### Caveats and Assumptions
Some products in the sugar division show no recorded sales in certain years, and it is unclear whether this reflects a genuine absence of sales, discontinued products, or missing sales records. 
