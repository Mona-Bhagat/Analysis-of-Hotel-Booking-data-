# Project Overview
This data analysis involves creating, querying, and analyzing a database in SQL, integrating Power BI with the database, and creating visualizations

![hotel](https://github.com/Mona-Bhagat/Analysis-of-Hotel-Booking-data-/assets/148805047/06e065cb-f00b-4190-8247-565c9a0f20f6)


# Data Sources
Data: The primary dataset used for this analysis is the "hotel_revenue_historical_full-2" file.

# Tools

* Excel
* SQL
* Power BI 

# SQL 
The Excel sheet had three years on different tabs, as the first task, they were combined using the union command. 
Furthermore, There was no column containing revenue numbers hence a query to calculate the revenue was written in SQL:

*select 
arrival_date_year, hotel,
sum((stays_in_week_nights + stays_in_weekend_nights) * adr)
as revenue from hotels group by arrival_date_year, hotel*
 
  
# DAX query
Calculation of delivery days by taking the difference between the order and the ship date 

# Exploratory Data Analysis
EDA involved exploring the data to answer key questions, such as:
* Is the hotel revenue growing yearly?
* Which hotel type brings in the most revenue?
* Which room type is reserved most?
* What's the average daily rate?

# Results/Findings
The analysis results are summarized as follows:
* In the period from 2018 to 2019, there was a rise in revenue, but in the following year, from 2019 to 2020, there was a significant decline in revenue.
* Average length of stay was 3.65 days.
* Resorts are the best-performing category in terms of revenue
* Average daily rate is 104.44 dollars 
* Maximum number of guests belong to Portugal 
	 
# Recommendations
Based on the analysis, we recommend the following actions:
* Revenue showed signs of increasing from Jan 2020 but declined due to COVID-19, so management needs to refocus on bringing on promotions and advertisements which should bring in positive results.
* Resorts seem to be the preferred choice so focusing on promoting them might help increase revenue. 
* Major clientele seems to be from European countries, diverting promotion efforts to these countries also can help bolster revenue 
