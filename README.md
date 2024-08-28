# Sales Data Analysis with Power BI ![PowerBI Icon](https://github.com/srheegit/Sales-Data-Analysis-with-Power-BI/blob/main/Icons/PowerBI%20icon%20small.png)
We analyze a delivery service company's sales data using Power BI, creating a Power BI Report that answers relevant business questions that are outlined in the [Goal of the Power BI Report section](#Goal-of-the-Power-BI-Report).

![Main Dashboard Screenshot](https://github.com/srheegit/Sales-Data-Analysis-with-Power-BI/blob/main/Screenshots/Main%20Dashboard.png)

## Business Requirement Document

We work with our delivery service company's data. There are four policies that the company is governed under:

1. Customers can place orders for various products sold by the company online.
2. Company delivers the product in least possible time depending upon the customers address.
3. Customers can choose either cash on delivery option or they can pay online while placing the order.
4. Company follows 10 days return policy.

## Dataset Description

The dataset consits of 4 csv files containing sales data for 4 months, with one csv file corresponding to one month of the following: January 2019, February 2019, Marhc 2019, and April 2019.

Each csv file contains the following columns:

1. Order ID
2. Product: the ordered product's name
3. Quantity delivered
4. Price Each
5. Order Date
6. Purchase address: customer's address

## Goal of the Power BI Report

We shall seek to create a Power BI Report that answers the following questions:

1. [What are top/bottom 5 products by sales?](#Top-Bottom-5-Products-By-Sales)
2. [Sales by region](#Sales-By-Region)
3. All details about the products ordered in a given order
4. Number of orders by date
5. Sales by month
6. Number of orders by month
7. Relationship between sales and quantity ordered

## Process of Creating the Power BI Report

I first divided the dashboard into three sections: the top for the company's logo and titole, the left section for sliders, and the rest for KPIs, maps, and charts. To add visual engagement, I imported and included several small icons relevant to several KPIs, such as money bag for sales and a box for the number of products sold.

For coherence in design, I used yellow and blue, the two colors prominent in the company's logo, throughout my visualization.

## Individual Graphs and Maps & Business Insights

Here, we provide magnified/detailed rendering of each graph and/or map in our main dashboard. We shall provide answers to the business questions based on the graphs.

### Top/Bottom 5 Products By Sales (#Top-Bottom-5-Products-By-Sales)

![Top 5 products by sales]()

![Bottom 5 products by sales]()

We see that the top five products are as follows:

1. Macbook Pro Laptop ($183.6K)
2. iPhone ($116.9K)
3. Google Phone ($88.2K)
4. ThinkPad Laptop ($86K)
5. 34K Ultrawide Monitor ($50K).

We also see taht the bottom five products are as follows:

1. AAA batteries, 4 pack ($2.1K)
2. AA batteries, 4 pack ($2.4K)
3. Wired Headphones ($5.4K)
4. USB-C Charging Cable ($6.8K)
5. LG Dryer ($7.2K)

### Sales By Region

![Sales by region]()

Looking at the generated map, we see that regions such as San Francisco and Los Angeles see the biggest sales, followed by regions such as New York City and Boston. At the lower end we have Austin and Dallas having the lowest sales. The specific total sales amount for each region can be seen by hovering our mouse over specific region in the PowerBI Report.

### All details about the products ordered in a given order

We may apply various filters through the sliders on the left hand side of the main dashboard to see the values for specific product, range of dates, region, and order IDs.

### Number of orders by Date / Month

![Feb 15th - Mar 15th Total Number of Orders]()

We may again use the slider to select a range of dates to see the total number of orders. The above is the result of applying the slider for the interseasonal period, between February 15th to Marhc 15th, inclusive.

### Sales by Month

![Sales by Month]()

Based on the graph above, we see that we saw an increase in sales from January through March and saw a step decline in April.

### Relationship between Sales and Quantity Ordered

![Sales vs. Quantity Ordered]()

From the visual, we see that, in general, there is an inverse relationship between the sales and the quantity ordered: in general, the lower the amount of sales, the higher the quantity ordered; and, in general, the higher the amount of sales, the lower the quantity ordered. This is expected, as not all customers have financial capacity or have immediate need to order an expensive item in large quantities.
