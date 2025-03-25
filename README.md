# Online  E-Commerce Sales Data Insights & Analysis

 # Introduction

 In the rapidly evolving digital marketplace, understanding sales performance is crucial for making data-driven business decisions. This project focuses on analyzing e-commerce sales data to uncover key insights into customer behavior, product performance, and revenue trends.
Using Python and data analysis techniques, I explored various aspects of the dataset, such as sales distribution, seasonal trends, and customer purchase patterns. Techniques like data cleaning, visualization, and statistical analysis were applied to derive meaningful conclusions. The analysis provides valuable insights that can help businesses optimize their sales strategies, improve customer targeting, and maximize profitability.
This project demonstrates my ability to work with real-world datasets, apply analytical techniques, and generate actionable business insights—key skills for a data analyst role.

# Tools Used

1. E-Commerce Store Dataset  with 9994 Rows and 21 Columns
  Get the full raw data from https://www.kaggle.com/datasets/arunabha9163/online-e-commerce-data-for-analysis
 
2. For Statistical insights I used  plotly Library Function.  Read about Plotly Library from here https://plotly.com/python/
3. I used Google Colab for Coding 

# Data Cleaning

First, I identified and removed duplicate rows to ensure data integrity and prevent skewed analysis. Then, I checked for missing values across all columns. Missing values in numerical columns were filled with the median or mean, while categorical columns were imputed using the mode or removed if they were deemed non-essential.
Next, I correctly assigned the appropriate data types to the Order Date and Ship Date columns. Finally, I extracted and created new columns for Year, Day, and Day of the Week from the Order Date to facilitate further analysis.

 # Statistical Charts & Insights 

* Analyze Yearly Sales and Profit trends

![Screenshot 2025-03-24 212747](https://github.com/user-attachments/assets/9c80d7f6-f7c4-454e-b500-2eaf66d2b17f)

The bar chart illustrates yearly sales and profit trends from 2014 to 2017. Sales and Profit consistently increased each year. The highest sales and profit were recorded in 2017.

* Analyze the Monthly sales of the store and identify trends of sales in every month

![Screenshot 2025-03-25 113423](https://github.com/user-attachments/assets/6b17c43a-1535-484e-a60e-ee8c62f5a2d3)

The line chart illustrates monthly sales trends, showing fluctuations throughout the year. Sales were lowest in February but rose significantly in March. After a slight decline in April, sales remained stable until August. A sharp increase occurred in September, followed by a dip in October. November recorded the highest sales, with a slight drop in December. The trend indicates seasonal variations and possible peak demand periods.

* Analyze Monthly profits Trend according to Sales

![Screenshot 2025-03-25 114447](https://github.com/user-attachments/assets/6cd1e383-6c84-4ad9-a00b-63314254b088)

The line chart shows monthly profit trends, with fluctuations throughout the year. The profit is directly influenced by sales, showing a simultaneous trend with the sales chart. As sales increase, profit follows a similar upward pattern, while declines in sales also result in lower profits, highlighting their strong correlation.

* Analyze the Sales based on Product Categories

![Screenshot 2025-03-25 120459](https://github.com/user-attachments/assets/d1e63183-7616-461f-a432-bbbd8057db5c)

The chart illustrates sales distribution across three categories. Technology leads with 36.4% of total sales, followed by Furniture at 32.3% and Office Supplies at 31.3%. The relatively balanced distribution suggests each category contributes significantly to overall revenue, with Technology dominating.

* Analyze Profits based on Product Categories

 ![Screenshot 2025-03-25 121322](https://github.com/user-attachments/assets/4eca022b-e125-42f3-b993-81936a643c08)

The chart reveals that Technology contributes the highest profits at 50.8%, followed by Office Supplies at 42.8%. Furniture lags significantly at only 6.44%, indicating potential inefficiencies or lower profit margins in that category despite its strong sales presence.

* Analyze Sales and Profit Trends on Sub-Category

![Screenshot 2025-03-25 121954](https://github.com/user-attachments/assets/003c8b1c-d625-4897-8948-c8124f1c3586)

The chart highlights key insights into sales and profitability across various sub-categories. Chairs, Phones, and Binders generate the highest sales, but their profit margins vary significantly. Phones and Binders are relatively profitable, whereas Chairs have lower profitability despite high sales. Copiers and Accessories also show strong sales with moderate profits. However, Tables have negative profits despite significant sales, indicating inefficiencies or high costs. Sub-categories like Fasteners and Bookcases contribute minimal revenue and profit.


