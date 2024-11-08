# SuperStore Sales Dashboard


## About The Project
This Power BI dashboard provides a comprehensive view of sales performance for a superstore. It was developed to track and analyze sales data to help drive strategic decision-making, optimize operations, and boost profitability. Additionally, the dashboard utilizes time series analysis to forecast sales for the next **30 days**, offering predictive insights that aid in proactive business planning and resource management.



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
4. **Sales Forecast**: Implemented a model to forecast sales for the next 15 days based on historical data.

