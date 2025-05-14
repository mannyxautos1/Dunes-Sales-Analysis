# Dunes Sales Analysis

## Table of Contents
- [Profect Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#project-cleaning/preparation)
- [EDA](#EDA)
- [Data Analysis](#data-analysis)
- [Results/Finding](#results/findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview

This repository contains an analysis of sales data related to Dune merchandise, aiming to uncover key trends, insights, make data-driven recommendation, and gain a deeper understanding of the company's performance.

### Data Sources

Sales Data: The primary dataset used in this analysis is the "Dune Sales Data.csv" containing detailed information on each sale made by the company including all the column features.

### Tools 
- Python was used for the preparation, cleaning, analyzing and visualization of the data [download here](https://jupyter.org/)

### Data Cleaning/ Preparations

In the data preparation stage I performed the follow tasks:
- Data Loading and Inspection.
- Handling Duplicated and Missing Values.
- Data Cleaning and Formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

1. Which Customer Age group generated highest revenue?
2. Which Customer Gender generated the largest revenue?
3. The top 10 States that generated the highest revenue?
4. Which Product category that completed the most transactions?
5. The top 10 highest transactions completed by the product sub-category?
6. The percentage of transactions completed by each payment options?
7. Transactions completed in each month?
8. Percentage of transaction by profit or loss?

### Data Analysis

Some interesting codes/ features I worked with

```Python
.value_counts()
.loc[]
.pd.to_datetime[]
.apply()
```

### Results/Findings

The analysis results are summarized as follows:
a. The low spec customers spend more with a value of 13041, fellowed by the medium spec customer and the high spec customers had a spending of 8899.
b. Cash has the highest percentage of transaction 45.63%, followed by POS 31.59% and lastly online which has 22.78%.
c. Accessories have the highest profit margin, despite having lower revenue than Phones. Accessories yield the highest profit. This suggests a better profit margin for this category.
d. 2016 starts with a much higher profit than 2015.While 2015 sees a significant recovery and rise in profit, it still ends lower than where 2016 ends. 2016 demonstrates more stability in profit throughout the year, but ends with a decline.
e. Age seems to influence profit more than gender overall. Within both male and female customer segments, there are noticeable differences in average profit across the age groups.
f. Cost and unit price move together; revenue increases with higher unit price and quantity; profit rises with revenue but falls with cost; year, month, and quarter show temporal patterns; customer age has a skewed distribution with weak correlations; and quantity is discrete.

### Recommendations

Based on the analysis, I recommend the following actions:
- Profit Optimization: Drive revenue growth while carefully managing costs to maximize profit.
- Trend Analysis: Examine sales data by year to identify long-term trends and adapt strategies accordingly.
- Seasonal Planning: Analyze sales patterns by month and quarter to optimize inventory and marketing efforts.
- Customer Segmentation: Further investigate customer behavior across different age groups to tailor marketing and product offerings.
- Quantity Optimization: Understand purchasing patterns related to quantity to inform bundling strategies or bulk discounts.
- Explore Volume Discounts: Investigate potential cost savings with larger sales volumes.

### Limitations

I had to remove all null values from row 34886, this is because I know they would not affect my entire data. The row affected contributed to less than 3% of the entire dataset. I had to correct the spelling of high on the customer column. Doing this realigned the data by giving it a more reliable value count on the customer column.

### References

1. Practical Statistics for Data Scientists by Peter Bruce, Andrew Bruce, and Peter Gedeck.
2. Python for Data Analysis by Wes McKinney.
3. Gemini.
  
