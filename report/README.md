# Sales Data Analysis Report
## 1. Introduction

This report documents the analysis performed on historical Walmart weekly sales data. The objective of this analysis is to identify trends, seasonal patterns, store performance differences, and the impact of external factors such as temperature on sales.

The analysis was conducted using Python and the pandas library, with results summarized through aggregated metrics and visual insights.

## 2. Dataset Description

The dataset (sales_data.csv) contains weekly sales records across multiple Walmart stores over several years. Key fields include:

Store_Number – Unique identifier for each store

Date – Week of recorded sales

Weekly_Sales – Total sales for the week

Temperature – Recorded temperature for the week

Holiday_Flag – Indicates whether the week included a holiday

Since the original dataset did not include a month or quarter column, these features were derived during preprocessing.

## 3. Data Preprocessing

The following preprocessing steps were applied:

Converted the Date column into a datetime format

Extracted Year, Month, and Quarter from the Date field

Handled missing values 

Categorized temperature values into:

Low (< 32°F)

Normal (32°F – 90°F)

High (> 90°F)

These steps ensured clean, consistent data suitable for analysis.

## 4. Analysis Performed

### 4.1 Monthly Sales Trends

Monthly aggregation revealed clear seasonality in sales:

December consistently recorded the highest sales across years

Q4 months showed stronger performance compared to other periods

Lower sales were observed in late summer and early fall

This suggests holiday shopping significantly impacts Walmart sales.

### 4.2 Yearly Sales and Growth

Total yearly sales were calculated to understand long-term trends:

Sales increased in 2011, showing positive growth

A decline in 2012 suggests possible economic or operational impacts

### 4.3 Store Performance Analysis

Sales were aggregated by store to identify high and low performers:

Store 20 generated the highest total sales

Several stores consistently underperformed, indicating potential location or demand issues

Sales distribution varied significantly across stores

This analysis helps identify stores for strategic investment or optimization.

### 4.4 Quarterly Sales Analysis

Quarter-wise aggregation showed:

Q4 produced the highest sales in most years

Q1 and Q2 remained relatively stable

Partial Q4 data in 2012 explains the lower Q4 total that year

Quarterly analysis reinforces the strong seasonal trend.

### 4.5 Impact of Temperature on Sales

Sales were analyzed by temperature category:

Low (<32°F)	1,050,918

Normal	1,054,495

High (>90°F)	796,966

Extremely high temperatures were associated with lower sales

Moderate and low temperatures showed stronger sales performance

This suggests weather conditions influence customer shopping behavior.

## 5. Key Metrics Calculated

The following metrics were calculated as part of the analysis:

Total and average weekly sales

Monthly and quarterly sales trends

Year-over-year growth percentage

Store-wise total sales

Temperature-based sales averages

These metrics satisfy the technical requirement of calculating multiple business insights.

## 6. Technical Requirements Fulfilled

✔ Used pandas for data loading and analysis
✔ Handled missing values appropriately
✔ Created derived features (Month, Quarter, Year)
✔ Calculated more than three analytical metrics
✔ Generated meaningful visualizations
✔ Followed required GitHub project structure

## 7. Conclusion

This analysis provided insights into Walmart’s sales performance across time, stores, and external factors. Strong seasonality was observed, with Q4 and December driving the highest revenue. Store-level disparities and temperature impacts highlight opportunities for targeted strategies.

Future analysis could include holiday-specific impact studies and predictive forecasting.

## 8. Screenshots

Screenshots of generated charts and outputs are stored in the visualizations/ directory and demonstrate the working analysis pipeline.

