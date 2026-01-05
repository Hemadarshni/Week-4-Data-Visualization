# Week-4-Data-Visualization
## 📊 Walmart Sales Data Analysis

## 📌 Project Overview

This project performs a **complete data analysis** on Walmart sales data to understand sales trends, store performance, seasonal patterns, and the impact of external factors such as temperature.

The project follows a full data analysis pipeline:
**Load → Clean → Analyze → Visualize → Report Insights**

This project was completed as part of **Week 4: Complete Data Analysis Project**.



## 🎯 Project Objectives

* Analyze Walmart weekly sales data across multiple years
* Identify monthly, quarterly, and yearly sales trends
* Compare performance across different stores
* Analyze the impact of extreme temperatures on sales
* Create at least two different types of visualizations
* Present clear insights with professional documentation



## 📂 Dataset Description

The dataset used in this project is **Walmart_sales_analysis.csv**, which contains historical weekly sales data.

Key columns include:

* Store_Number
* Date
* Weekly_Sales
* Temperature

Additional columns such as **Year**, **Month**, and **Quarter** were created during analysis for better insights.



## ⚙️ Setup and Installation Instructions

### Step 1: Install Required Libraries

Make sure Python is installed, then run:

```bash
pip install pandas matplotlib
```

### Step 2: Project Structure


walmart-sales-analysis/
├── README.md
├── E-commerce Sales Analysis.ipynb
├── requirements.txt
├── data/
│   └── Walmart_sales_analysis.csv
├── visualizations/
│   ├── impact_of_extreme_weather.png
│   ├── quarterly_sales_performance.png
│   └── total_sales_by_store.png
├── report/
│   └── final_report.md


### Step 3: Run the Project

* Open `analysis.ipynb` in **Jupyter Notebook**
* Run all cells sequentially from top to bottom



## 🧱 Code Structure Explanation

* **analysis.ipynb**: Contains all code for data loading, cleaning, analysis, and visualization
* **data/**: Stores the original dataset
* **visualizations/**: Contains charts generated using Matplotlib
* **report/final_report.md**: Written report with detailed insights and findings
* **requirements.txt**: Lists required Python libraries



## 📈 Analysis Performed

The following analysis steps were completed:

* Loaded data using Pandas
* Converted Date column to datetime format
* Created Year, Month, and Quarter columns
* Handled missing values and validated data types
* Calculated key metrics including:

  * Total sales
  * Monthly sales
  * Quarterly sales
  * Year-over-Year growth
  * Store-wise performance
  * Impact of temperature on sales



## 📊 Visualizations

The project includes multiple visualizations to support insights:

* **Bar Chart**: Store-wise total sales comparison
* **Line Chart**: Monthly and quarterly sales trends over time
* **Bar Chart**: Impact of extreme weather on Sales

All charts are saved in the **visualizations/** folder.



## ✅ Technical Requirements Fulfilled

✔ Complete data analysis pipeline implemented
✔ Pandas used for data loading and analysis
✔ Missing values handled and validated
✔ More than three metrics calculated
✔ At least two different chart types created
✔ Error handling and validation performed
✔ Professional documentation provided



## 📚 What I Learned

* How to perform an end-to-end data analysis project
* How to analyze real-world sales data
* How to visualize trends using Matplotlib
* How to extract meaningful business insights from data
* The importance of clear documentation in data projects



## 🏁 Conclusion

This project demonstrates a complete and structured approach to data analysis using Python. The insights derived from Walmart sales data highlight seasonal patterns, store-level performance differences, and the effect of external factors such as temperature on sales.

