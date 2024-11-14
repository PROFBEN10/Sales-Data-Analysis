# Sales Data Analysis
## Exploratory Data Analysis, Correlation Analysis and Sales Forecast

# Project Overview
This project analyzes factors influencing sales within a retail environment, including Marketing Spend, Store Visitors, and Discount Offered, to understand their relationships with Sales and identify predictive factors. The objective is to inform strategic decisions that can optimize marketing investments and improve sales outcomes.

# Objectives
Investigate the relationship between Marketing Spend and Store Visitors.
Identify key drivers of Sales to enable more accurate sales predictions.
Key Questions
How does Marketing Spend affect Sales?
Which factors most strongly impact Sales?

# Approach to Analysis
## Data Cleaning

Handled missing values by replacing them with the column mean.
Corrected a single erroneous negative value in the Marketing Spend column.
Outlier Handling

Addressed outliers in the Store Visitors column to ensure accurate analysis.

## Exploratory Data Analysis (EDA)

Analyzed Sales trends by season and month to identify peak sales periods.
## Correlation Analysis

Assessed the relationships between Marketing Spend, Store Visitors, Discount Offered, and Sales to guide decision-making.
## Regression Model

Built a regression model with Marketing Spend as the predictor for Sales since it was the only factor with a positive correlation.

## Sales Forecast

Used Excel’s Forecast tool to project Sales for the next 6 months.

# Correlation Analysis
## Factor Relationship	Correlation	Interpretation
Marketing Spend vs. Store Visitors:	-0.04	Weak, negative correlation indicating minimal relationship.
Marketing Spend vs. Sales:	0.06 Weak, positive correlation suggests a limited direct impact on Sales.
Discount Offered vs. Sales:	-0.05	Weak, negative correlation; discounts do not strongly drive Sales.
Store Visitors vs. Sales:	-0.09	Weak, negative correlation; increased foot traffic does not directly correlate to higher Sales.
# Seasonality Analysis
Seasonal Sales Trends: Summer and Spring show the highest sales, with January as the peak sales month.
Yearly Sales Trends: Sales increased from 2020 to 2022, with 2022 as the highest year. There was a slight drop in 2023, likely due to incomplete data up to October.

# Key Insights
Marketing Spend is the only factor showing a slight positive influence on Sales.
Sales peak during Summer and Spring, aligning with higher marketing investments in these periods.
Winter shows moderate sales on a lower marketing budget, while Autumn sees lower sales despite higher spending.

# Recommendations
Increase Marketing Spend in Peak Seasons

Focus marketing efforts during Summer and Spring for maximum impact.
Enhance In-Store Experience

Since foot traffic alone does not drive Sales, improve store environments to convert visitors into buyers.
Limit Discounts to High-Traffic Periods

Use discounts strategically when store traffic is high to avoid eroding profit margins.
Consider Broader External Factors

Since correlations are weak, explore additional factors such as product offerings, economic conditions, and online marketing for deeper insights.
Reallocate Marketing Budget

Focus marketing resources in Summer and Spring while considering reallocating some Autumn spending to Winter for potentially stronger returns.
Conclusion
The analysis suggests that targeted marketing in peak seasons and enhanced in-store experiences could improve Sales. However, due to weak correlations, a broader approach, potentially involving new variables, may better explain and drive Sales growth.
