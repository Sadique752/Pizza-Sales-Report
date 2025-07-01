# Pizza Sales Report Analysis

## Objective
- For the Maven Pizza Challenge, you’ll be playing the role of a BI Consultant hired by Plato's Pizza, a Greek-inspired pizza place in New Jersey. You've been hired to help the restaurant use data to improve operations, and just received the following note:
- Welcome aboard, we're glad you're here to help!
- Things are going OK here at Plato's, but there's room for improvement. We've been collecting transactional data for the past year, but really haven't been able to put it to good use. Hoping you can analyze the data and put together a report to help us find opportunities to drive more sales and work more efficiently.

## Problem Statements
### Some Insigts we need find out from Data
- What days and times do we tend to be busiest?
- How many pizzas are we making during peak periods?
- What are our best and worst-selling pizzas? 
- What's our average order value?
- Which month generated highest revenue?
- What is the highest pizza sold by category?
- Which pizza generated highest revenue?
- Which pizza category generated highest revenue in Percentage?

## Insights we get from Analysis
- July is the highest revenue generated month.
- Highest pizza sold by category is Classic.
- The Thai Chicken Pizza generated highest revenue.
- Classic Pizza has generated 26.91% of Total revenue.

## DAX Formula we used to find insights
- Total Order = DISTINCTCOUNT(pizza_sales[order_id])
- Total Pizza Sold = SUM(pizza_sales[quantity])
- Total Revenue = SUM(pizza_sales[total_price]) Avg Order Value = [Total Revenue] / [Total Order]
- Avg Pizza Per Order = [Total Pizza Sold] / [Total Order]

## Main Key Performing Indicators (KPIs) are
- Total Revenue
- Total Order
- Average Order Value
- Total Pizza Sold
- Average Pizza per Order

## Dashboard ScreenShots


![image](https://github.com/user-attachments/assets/2f69fafb-4bf0-4e80-a9c2-babae2f5dca3)


![image](www.linkedin.com/in/mdsadiqueofficial)

