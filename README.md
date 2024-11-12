# HR Summary & Details Dashboard 

# Table of Contents
* [Project Background](#project-background)
* [Data Structure](#data-structure)
* [Executive Summary](#executive-summary)
* [Recommendations](#recommendations)

# Project Background 
Maven Roasters is a fictitious coffee shop operating across three locations in New York City. The dataset includes transaction records, timestamps, location details, and product-level information. This project aims to analyze sales performance and customer behavior by examining key metrics such as transaction trends, product performance, and customer order patterns. Through the development of interactive dashboards, the project will provide valuable insights to optimize sales strategies, improve operational efficiency, and enhance customer satisfaction across Maven Roasters' locations.

Insights and recommendations are provided on the following key areas : 

- **Total Revenue, Orders, AOV, Peak Location**: A comprehensive evaluation of historical sales data, focusing on key metrics such as Total Revenue, Order Volume, Average Order Value (AOV), and the identification of peak sales locations.

Detailed Resources: 

- The Pre-Processing process utilized can be found [here](https://github.com/karlyndiary/Coffee-Shop-Sales-Analysis/blob/main/EDA.ipynb). 
- An interactive Streamlit dashboard can be viewed [here](https://coffee-shop-sales-analysis.streamlit.app/).

# Data Structure

HR's database structure as seen below consists of one table: HR Data with 8950 records.

# Executive Summary 

### Overview of Findings 

Total revenue of $698K was generated from 149K orders, with June being the peak month at $166K. Hell's Kitchen led all locations with $236K in revenue, while Barista Espresso topped the product list with $91K in sales. Coffee Beans showed the highest AOV at $22, and Coffee emerged as the most popular category. Sales peak at 10 AM, with steady performance across all weekdays and Gourmet Brewed Coffee leading in popularity.

Below is the overview page from the Streamlit dashboard and more examples are included throughout the report. The interactive dashboard can be viewed [here](https://coffee-shop-sales-analysis.streamlit.app/).

### HR Summary Dashboard
- With total hired employees being 8950, out of which 7984 active employees and 966 terminated employees.
- There are 7 departments in total with majority of the employees in operations at 2429 hired employees. The least no of employees are in finances and hr departments with 389 and 152 hired employees respectively. The no of terminated employees in all departments are less than 3%.
- New York is the HQ with a total no of employees being 6270 and 7 other state being the branch with 2680 hired employees. 
- 54% male and 46% females with 89% hired and 11% terminated in each demographic.
- 5416 hired employees are from bachelors background, followed by school at 1819 and masters 1237, 478 PhD.
- 

![HR Summary](https://github.com/user-attachments/assets/17c71345-09e0-4838-8cd7-9a78c1582d65)

### HR Details Dashboard

![HR Details](https://github.com/user-attachments/assets/39ae628c-77d1-443a-9769-8598fd2f28e5)

# Recommendations

Based on the uncovered insights, the following recommendations have been provided : 

- **Target High-Value Products:** Coffee Beans, being the top-performing product, can benefit from a seasonal "Buy One Get One Free" offer. This would encourage bulk purchases, especially during colder months when customers are more likely to brew coffee at home. Introducing this deal a month in advance would help maximize sales.
