# Sales Analysis

## Table of content

[Project Overview](#project-overview)

[Tools](#tools)

[Data cleaning](#data-cleaning)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data analysis](#data-analysis)

[Results and Findings](#results-and-findings)

[Recommendations](#recommendations)



### Project Overview

This project involves creating an interactive Sales Performance Dashboard in Power BI to analyze business revenue, profitability, customer activity, and purchasing patterns.
The dashboard will include four key KPIs: Total Sales (Revenue), Total Cost, Total Profit, and Total Customers, providing a quick overview of overall business performance.
To gain deeper insights, the dashboard will visualize Profit by Brand to identify the most profitable products, Total Purchases by Color to determine the best-selling color, and Yearly Revenue to analyze revenue trends over time. Monthly Customer Analysis will highlight customer trends and identify the worst-performing month, while Income Level by Profit will show which customer income groups contribute most to profitability.
The dashboard will also include two interactive slicers to allow users to filter and explore the data based on selected categories. The final dashboard is designed to present these insights in a clear, interactive, and visually appealing format for data-driven business decision-making.

### Tools

-Power BI - Data cleaning,data analysis,creating report

### Data cleaning

-Data loading and inspection. 

-Removal of error spaces

### Exploratory Data Analysis

The exploratory analysis focused on understanding sales performance, profitability, customer behavior, and purchasing patterns within the dataset. Key areas examined included total revenue, costs, profit, and customer volume to establish the overall business performance.
The analysis also explored brand profitability to identify high-performing products, color purchasing patterns to determine the most popular colors, and revenue trends across years and months. Customer performance was further examined by month and income level to identify periods of low customer activity and customer segments contributing most to profit.
These findings provide a foundation for identifying business trends, profitable products, customer preferences, and areas requiring improvement before making data-driven decisions.


### Data analysis

In calculating KPIs; 

```
profit
=(Sales[SalesAmount]-Sales[Unit Cost]*Sales[Quantity]
```

```
Total Cost
= Sales[Quantity]*Sales[Unit Cost]
```

```
Total Revenue
=Sum( Sales[Quantity]*Sales[Sales Amount])
```

### Results and Findings
Results & Findings
1.Overall Performance: The business generated $3.11M in revenue, with $2.17M in total costs and $931.91K profit from 250 customers.
2.Monthly Revenue: March recorded the highest revenue, while February was the lowest-performing month.
3.Yearly Revenue: Revenue declined from $1.15M in 2020 to $990K in 2021 and $960K in 2022, indicating a downward trend.
4.Popular Color: White was the most purchased color at 39.09%, followed by Gray (33.40%) and Black (27.51%).
5.Profit by Income Level: Medium-income customers generated the highest profit at approximately $346K, followed by high-income and low-income customers.
6.Most Profitable Brand: Apple generated the highest profit at approximately $200K, while Dell recorded the lowest among the brands displayed at about $130K.

### Recommendations
1.Investigate the yearly revenue decline and introduce targeted sales campaigns to reverse the trend.
2.Focus inventory and promotions on high-performing brands and popular colors, particularly Apple and White products.
3.Develop targeted offers for medium-income customers, who contribute the highest profit.
4.Analyze the causes of the February revenue decline and introduce promotions to improve sales during weaker months.
5.Review the performance of lower-profit brands and consider pricing, marketing, or product strategy adjustments.
