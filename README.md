# Super Store Sales Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

---

## Project Overview

This analysis provides comprehensive insights into the sales performance, profitability, and customer behavior of the Super Store dataset. It explores trends in shipping modes, product performance, regional sales, and customer segmentation to identify actionable recommendations for business growth.

---

## Data Sources

- **Primary Dataset**: Super Store sales data containing 9994 rows and 20 columns, including details such as Order Date, Ship Date, Region, Category, Sales, Quantity, Discount, and Profit.
- **Date Range**: 2014-01-03 to 2017-12-30.

---

## Tools Used

- **Python**: Data cleaning, exploration, and visualization using Pandas, NumPy, and Matplotlib/Seaborn.
- **Jupyter Notebook**: Data analysis and iterative coding.
- **NumPy**: For numerical computing and working with arrays.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Plotly**: Interactive visualizations like treemaps and scatter plots.

---

## Data Cleaning and Preparation

Key steps in the data preparation process:
1. **Duplicates**: Removed 1 duplicate row.
2. **Null Values**: Verified no null values in the dataset.
3. **Column Removal**: Removed the 'Country' column as all orders were from the United States.
4. **Feature Engineering**: Calculated additional metrics such as profit margins and delivery times for deeper analysis.

---

## Exploratory Data Analysis

The analysis investigated:
1. **Product Categories and Sub-Categories**: Profitability, sales, and quantity trends.
2. **Seasonal Trends**: Monthly and quarterly sales performance.
3. **Customer Segments**: Contribution and profitability by Consumer, Corporate, and Home Office segments.
4. **Shipping Modes**: Distribution of shipping preferences.
5. **Regional Performance**: Sales and profit across regions.
6. **Discount Impact**: How discounts affect sales and profitability.

---

## Key Findings

1. **Shipping Insights**:
   - Standard Class is the most widely used mode (59.7%), while Same Day is the least (5.4%).
   - Faster shipping modes like First Class are significant in the West and East regions.

2. **Regional Analysis**:
   - The West region is the most profitable, followed by the East.
   - California and New York are top-performing states, while Texas and Pennsylvania incur severe losses.

3. **Product Performance**:
   - Technology is the most profitable category; Furniture is the least.
   - Copiers and Phones generate the most profit but sell in lower quantities.

4. **Discount Impact**:
   - High discounts correlate with lower profits. Discounts beyond 10-20% severely erode profitability.

5. **Customer Behavior**:
   - The Consumer segment forms the largest customer base but generates a lower profit margin compared to Corporate and Home Office segments.
   - Loyal customers like William Brown (37 orders) indicate strong engagement.

6. **Seasonal Trends**:
   - Q4 (holiday season) drives peak sales, highlighting opportunities for targeted promotions.

---

## Recommendations

1. **Optimize Discount Strategies**:
   - Cap discounts at 10-20% to avoid profit erosion.
   - Reduce or eliminate discounts in loss-incurring states like Texas and Pennsylvania.

2. **Focus on Profitable Categories**:
   - Promote high-profit items like Copiers and Phones.
   - Reevaluate or remove low-margin products like Tables and Bookcases.

3. **Leverage Seasonal Trends**:
   - Intensify marketing campaigns in Q4 and around holiday seasons.
   - Use targeted promotions to maximize revenue during peak periods.

4. **Regional Strategy**:
   - Increase investment in high-performing states like California and New York.
   - Reassess pricing and discounts in underperforming regions.

5. **Shipping Enhancements**:
   - Explore strategies to optimize the Standard Class shipping experience while catering to customers prioritizing speed.

6. **Customer Segmentation**:
   - Tailor strategies to high-value customers like Sean Miller ($25,043 spent).
   - Develop loyalty programs for repeat customers.

---

## Limitations

1. **Dataset Scope**:
   - Analysis limited to U.S.-based sales data.
   - Lack of detailed demographic information about customers.

2. **Seasonality Factors**:
   - Holiday-specific trends may not apply consistently year-over-year.

3. **Profit Erosion**:
   - The impact of external factors such as supplier costs or economic conditions was not analyzed.

---

## References

1. [Super Store Dataset Documentation](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/)
2. [Plotly Documentation](https://plotly.com/)
3. [Pandas Documentation](https://pandas.pydata.org/)
