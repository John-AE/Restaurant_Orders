# Project Title: Restaurant Business Analysis

### Description

This project was undertaken to demonstrate my SQL skills and techniques to explore the records in database tables and analyze the a Restaurant Business data. The project involved setting up a restaurant database using MYSQL Workbench, performing exploratory data analysis (EDA), and answering specific business questions through SQL queries.

### Objectives
1.	Explore the Menu Items Table
2.	Explore the Orders Table
3.	Analyze Customer Behavior

### Environments and Tools Used
- Windows 10
- MySQL Workbench

## Data Science Analysis Walk-Through

### Database and Tables Creation
##### Database: restaurant_db
The project was started by creating a database named restaurant_db. Afterwards, two tables were created. A table named menu_items was created to store the menu items data. The table structure includes columns for menu_item_id, item_name, category and price. Another table called order_details was created to store the details of orders. It comprised five columns titled order_details_id, order_id, order_date, order_time and item_id.

![Creating Database and Tables](pjc_02_01.JPG)

### Exploring the Menu Items Table
During the exploration, some questions were answered such as:
- What are the least and most expensive items on the menu?
- How many italian dishes are on the menu?
- What are the least and most expensive Italian dishes on the menu?
- What is the average dish price within each category?
- How many dishes are in each category?


![Exploring the menu items table](pjc_02_02.JPG)

### Exploring the Orders Table
During the exploration, some questions were answered such as:

- What is the date range of the table?
- How many orders were made within this date range?
- How many items were ordered within this date range?
- Which orders had the most number of items?
- How many orders had more than 12 items?


![Exploring the orders table](pjc_02_03.JPG)

### Analyzing Customer Behavior
During the exploration, some questions were answered such as:
- What were the least and most ordered items? What categories were they in?
- What were the top 5 orders that spent the most money?
- Determining the details of the top 5 highest spend and gathering insights can you gather from the results?

![Analyzing the behavior of customers](pjc_02_04.JPG)
