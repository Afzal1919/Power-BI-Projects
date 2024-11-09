# SuperStore Sales Dashboard


## About The Project
This Power BI dashboard provides a comprehensive view of sales performance for a superstore. It was developed to track and analyze sales data to help drive strategic decision-making, optimize operations, and boost profitability. Additionally, the dashboard utilizes time series analysis to forecast sales for the next **30 days**, offering predictive insights that aid in proactive business planning and resource management.

![Alt text](https://github.com/Afzal1919/Power-BI-Projects/blob/main/SuperStore%20Sales%20Dashboard/Dashboard.png?raw=true)

## Dataset Overview
The dataset used in the Superstore Sales Dashboard includes a comprehensive list of sales transactions with the following fields:

- **Order ID**: Unique identifier for the order.
- **Order Date**: The date when the order was placed.
- **Ship Date**: The date when the order was shipped.
- **Ship Mode**: The mode of shipping used for the order delivery.
- **Customer ID**: Unique identifier for the customer.
- **Customer Name**: Name of the customer.
- **Segment**: Market segment to which the customer belongs.
- **Country**: Country of the customer.
- **City**: City of the customer.
- **State**: State where the customer resides.
- **Region**: Region where the customer resides.
- **Product ID**: Unique identifier for the product.
- **Category**: General category of the product.
- **Sub-Category**: Specific category under the main category.
- **Product Name**: Name of the product.
- **Sales**: Total sales amount for the transaction.
- **Quantity**: Number of items sold in the transaction.
- **Profit**: Profit made from the transaction.
- **Returns**: Indicates if the product was returned.
- **Payment Mode**: Payment method used by the customer.

### Sample Data Row
Here is an example of how the data appears in the dataset:

| Order ID       | Order Date | Ship Date  | Ship Mode       | Customer ID | Customer Name  | Segment   | Country       | City          | State     | Region | Product ID        | Category  | Sub-Category | Product Name                                        | Sales | Quantity | Profit | Returns | Payment Mode |
|----------------|------------|------------|-----------------|-------------|----------------|-----------|---------------|---------------|-----------|--------|-------------------|-----------|--------------|----------------------------------------------------|-------|----------|--------|---------|--------------|
| CA-2019-160304 | 01-01-2019 | 07-01-2019 | Standard Class  | BM-11575    | Brendan Murry  | Corporate | United States | Gaithersburg  | Maryland  | East   | FUR-BO-10004709   | Furniture | Bookcases    | Bush Westfield Collection Bookcases/Medium Cherry | 73.94 | 1        | 28.27  | 0       | Online       |

This sample provides a clear snapshot of the type of data you can expect in the complete dataset, facilitating a better understanding and analysis.


## Steps Involved in the Analysis
1. **Loaded and Transformed Data**: The raw data was imported into Power BI and transformed to a format suitable for analysis.
2. **Added Relevant Columns Using DAX**: New columns, such as "Average Delivery Time," were created to enhance the data's analytical value.
3. **Crafted Engaging Visuals**: Various visuals like area charts, donut charts, and cards were used to represent the data effectively.
4. **Sales Forecast**: Implemented time series analysis to forecast sales for the next 30 days based on historical data.


## 📊 Dashboard Overview

The SuperStore Sales Dashboard provides the following key insights and visualizations:



1. **Key Performance Indicators (KPIs)**
   - **Total Sales**: $1.6M
   - **Total Profit**: $175.3K
   - **Total Orders**: 22.3K
   - **Average Ship Days**: 4

2. **Sales Breakdown**
   - **By Region**: Visualizes the sales distribution across regions (West, East, Central, and South).
   - **By Payment Mode**: Highlights customer payment preferences, including Cash on Delivery, Online, and Card payments.
   - **By Segment**: Divides sales into Consumer, Corporate, and Home Office segments.
   - **By Category & Sub-Category**: Breaks down sales by top categories (e.g., Office Supplies, Technology, Furniture) and sub-categories (e.g., Phones, Chairs, Binders).

3. **Year-over-Year Analysis**
   - **Monthly Sales Comparison**: Compares monthly sales between 2019 and 2020 to spot trends and seasonal patterns.
   - **Monthly Profit Comparison**: Shows profit trends across months, providing insight into the most profitable periods.

4. **Shipping and Profit Insights**
   - **Sales by Ship Mode**: Examines the popularity of shipping options (Standard Class, Second Class, First Class, Same Day).
   - **Profit and Sales by State**: Displays a map of profit distribution, helping to identify high-revenue areas.

## 🔍 Key Insights

- **Regional Performance**: The West region has the highest sales share (33%), while the South region has the lowest (16%), indicating potential growth opportunities in the South.
- **Payment Preferences**: COD is the preferred payment mode (43%), which may suggest customer hesitancy toward online transactions.
- **Segment Dominance**: The Consumer segment is the largest, accounting for 48% of total sales.
- **Category Sales**: Office Supplies is the top-selling category, indicating demand from corporate or business customers.
- **Shipping Preferences**: Standard Class is the most popular shipping mode, while Same Day has the lowest share, reflecting cost sensitivity in shipping choices.

## 💡 Additional Observations

- **Seasonal Trends**: Both sales and profits tend to increase significantly in November and December, likely due to holiday shopping.
- **Potential Growth in Online Payment**: Since COD is highly favored, consider strategies to encourage online payments, such as offering discounts or loyalty rewards.
- **Focus on Consumer Segment**: As the Consumer segment contributes almost half of the sales, personalized marketing and loyalty programs may help retain this customer base and increase purchase frequency.

## 📂 Repository Structure

