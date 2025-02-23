# Zomato-Data-Analysis-Project

Project Overview:
This project analyzes a dataset from Zomato to explore various factors influencing restaurant ratings and customer engagement. The dataset includes information on restaurant names, online ordering and table booking availability, customer ratings, votes, approximate costs for two people, and restaurant types.

Key Features of the Dataset:

Columns:
name: Restaurant name
online_order: Availability of online ordering
book_table: Availability of table booking
rate: Average customer rating
votes: Total number of votes or reviews
approx_cost(for two people): Estimated cost for two people
listed_in(type): Category or type of restaurant

Analysis Highlights:

Restaurants Offering Services:

7 restaurants allow both online ordering and table booking.

Average Ratings:

Restaurants with online ordering have an average rating of 3.86, while those with table booking have an average rating of 4.19.
The restaurant type with the highest average rating is "other" with a rating of 3.91.

Statistical Testing:

A t-test revealed a statistically significant difference in ratings between restaurants offering online ordering and those offering table booking.

Cost Analysis:

Average costs for restaurants with online ordering are higher (510.34) compared to those without (358.89).
Average costs for restaurants with table booking are also higher (693.75) compared to those without (402.50).

Data Visualizations:

Various visualizations were created using Matplotlib, Seaborn, and Plotly to illustrate:

Average costs based on service availability.
Distribution of ratings by online ordering and table booking.
Scatter plots showing the relationship between cost and ratings.
Conclusion: The analysis indicates that restaurants offering online ordering and table booking tend to have higher average ratings. However, there is no strong correlation between the cost of dining and customer ratings, suggesting that factors such as food quality and service are more critical to customer satisfaction. The findings provide valuable insights for restaurant owners to enhance customer engagement and satisfaction.
