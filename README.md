# Financial Performance Analysis of Major USA Companies(2009-2023) with PowerBI

Hi everyone! In this guide, I'll walk you through the process I used to create an interactive dashboard for analyzing the financial performance of major US companies from 2009 to 2023. I utilized Power BI and data sourced from Kaggle to build this visualization.

## Step 1: Data Acquisition and Preparation

* Downloading the Data: I downloaded the CSV file containing the financial reports from the Kaggle website (https://www.kaggle.com/datasets/rish59/financial-statements-of-major-companies2009-2023).
* Importing into Power BI: I opened Power BI Desktop and imported the downloaded CSV file using the "Get Data" -> "Text (CSV)" function.
* Transforming Data in Power Query:
  * I ensured that the columns with financial indicators (revenue, profit, etc.) were in numeric format, and the date column was in date format.
  * I created new calculated columns, such as "Gross Profit Margin" and "Net Profit Margin".

## Step 2: Creating Visualizations

* DAX Measures: For more complex calculations, I created measures using DAX:
  * "Total Revenue", "Total Gross Profit", "Total Net Profit" - for aggregating data by companies and categories.
  * "Average Profit Margin" - to calculate the average value across all companies.
  * "Year-over-Year Change" - to track the dynamics of indicators over time.
* Visualizations:
  * KPI Cards: To display key indicators ("Total Revenue", "Gross Profit", "Net Profit", "Profit Margin").
  * Histograms: To compare revenue, gross profit, and net profit across categories and companies.
  * Line Charts: To display trends of "Total Revenue", "EBITDA", and "Net Profit" over time.
  * ROI by Company Chart: To visualize the return on investment for each company.
    
## Step 3: Interactivity and Design

* Slicers (Filters): I added slicers to filter data by:
  * "Company"
  * "Category"
  * "Year"
* Cross-References: I configured interaction between visualizations so that when an element is selected in one visualization, others change automatically.
* Formatting:
  * I gave clear names to all visualizations and controls.
  * I used a consistent color scheme and fonts for a professional look.
  * I placed the visualizations logically and conveniently for perception.

## Step 4: Analysis and Conclusions

Based on the dashboard I created, I identified the following trends:

Overall Growth: In general, there is growth in revenue and profit of major US companies from 2009 to 2022.
Decline in 2023: However, in 2023, there is a noticeable decrease in key financial indicators, which may indicate unfavorable economic conditions or problems in certain industries.
Profitability Differences: The profitability of different companies varies significantly, which is reflected in different values of profit margin and ROI.
Impact of Categories: The choice of business category has a significant impact on the financial performance of the company.
Conclusion

This dashboard provides a convenient and interactive tool for analyzing the financial performance of major US companies. It allows you to identify trends, compare companies and categories, and filter data for more detailed study.

I hope this guide was helpful! If you have any questions, feel free to ask.

Let me know if you need any further assistance!
