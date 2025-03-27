# Online  E-Commerce Sales Data Insights & Analysis

 # Introduction

 In the rapidly evolving digital marketplace, understanding sales performance is crucial for making data-driven business decisions. This project focuses on analyzing e-commerce sales data to uncover key insights into customer behavior, product performance, and revenue trends.
Using Python and data analysis techniques, I explored various aspects of the dataset, such as sales distribution, seasonal trends, and customer purchase patterns. Techniques like data cleaning, visualization, and statistical analysis were applied to derive meaningful conclusions. The analysis provides valuable insights that can help businesses optimize their sales strategies, improve customer targeting, and maximize profitability.
This project demonstrates my ability to work with real-world datasets, apply analytical techniques, and generate actionable business insights—key skills for a data analyst role.

# Tools Used

**Dataset**: E-Commerce Store dataset with 9,994 rows and 21 columns.

**Programming Language**: Python.

**Visualization Library**: Used Plotly for statistical insights. Learn more about Plotly https://plotly.com/python/

**Development Environment**: Google Colab for coding.

# Data Cleaning

First, I identified and removed duplicate rows to ensure data integrity and prevent skewed analysis. Then, I checked for missing values across all columns. Missing values in numerical columns were filled with the median or mean, while categorical columns were imputed using the mode or removed if they were deemed non-essential.
Next, I correctly assigned the appropriate data types to the Order Date and Ship Date columns. Finally, I extracted and created new columns for Year, Day, and Day of the Week from the Order Date to facilitate further analysis.

 # Statistical Charts & Insights 

* Analyze Yearly Sales and Profit trends

![year](https://github.com/user-attachments/assets/09174872-4b2f-46cc-b04a-de97d13d2e90)

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

![sub-category](https://github.com/user-attachments/assets/47fe0065-fb44-4d31-befe-b997a700b6c7)

The chart highlights key insights into sales and profitability across various sub-categories. Chairs, Phones, and Binders generate the highest sales, but their profit margins vary significantly. Phones and Binders are relatively profitable, whereas Chairs have lower profitability despite high sales. Copiers and Accessories also show strong sales with moderate profits. However, Tables have negative profits despite significant sales, indicating inefficiencies or high costs. Sub-categories like Fasteners and Bookcases contribute minimal revenue and profit.

* Analyze the sales and profit by customer segment

![Screenshot 2025-03-25 122750](https://github.com/user-attachments/assets/c9a5650c-86a6-44a8-a58b-b3dc02b14547)

The chart reveals that the Consumer segment generates the highest sales, followed by Corporate and Home Office. However, despite leading in sales, the Consumer segment also contributes the highest profit, indicating strong profitability. The Corporate segment has moderate sales and profits, suggesting stable performance. Meanwhile, Home Office has the lowest sales and profit, possibly due to lower purchasing power or fewer bulk orders.

* Sales Trends from Each Region of Country

![Screenshot 2025-03-25 123054](https://github.com/user-attachments/assets/7de2fe14-54d6-420c-93d9-3f6772245aec)
  
The Sales by Region chart reveals that the West (31.6%) and East (29.5%) regions contribute the highest sales, making up over 60% of total sales. The Central region (21.8%) follows, while the South (17%) has the lowest sales. 

* Analyze number of Sales of  each State
  
![Screenshot 2025-03-25 123502](https://github.com/user-attachments/assets/ce8b5314-635e-4e83-af7d-1e459a0fa1a6)

Sales in the West region were higher due to large states like California and Washington. In the East region, sales were similar in volume, primarily driven by major cities like New York. The Central region also had a sales count comparable to the East. However, sales in the South region were lower due to the absence of major cities. 

#  Strategic decisions  base on analysis

 * Plan seasonal marketing campaigns mainly November and December like Chirstmas Time. Aslo give discounts to boost sales during slow months.

 * Prioritize stocking high-selling products and reduce inventory for low-demand items. Increase Technology products sales with offers cause most of the sales is for technology    iteams. Offer discounts or bundle deals on slow-moving products to clear stock .

 * implement a loyalty program for repeat customers.Offer personalized recommendations and discounts for high-value customers. Target increase supply of home-office.

 * Focus advertising and promotions in high-sales regions. Like West, East Region has big states.

 *  Optimize ad spend and promotions during high-traffic periods . Like New Year Time need to advertise more.

# Reference 

Get Full Dataset https://www.kaggle.com/datasets/arunabha9163/online-e-commerce-data-for-analysis

Get Statistical Concept https://www.atlassian.com/data/charts/essential-chart-types-for-data-visualization
