# movie-analysis
# Objective:
The main objective of the project is to utilize SQL queries to extract and analyze meaningful insights from a movie dataset. The goal is to uncover trends, patterns, and correlations in the movie industry that can guide decision-making for stakeholders. It focuses on different aspects, including user behavior, subscription trends, and financial analysis.

# Project Overview:

# Title Filtering:
Write a query to select distinct movie titles from a specific table (table_4) that were released after 2018. These results are to be ordered chronologically and filtered to show the latest year of movie releases.

# Stored Procedures:
Create a procedure to store all the records inside a table where the type is marked as "movie." This procedure is designed to be reusable, ensuring the system efficiently tracks all movie data.
Call this procedure to ensure all relevant movie records are captured and stored.

# Viewership Insights:
Analyze the number of viewers by displaying the show ID and counting these IDs. The result is renamed as "no of viewers," and the query limits the results to only 5 records. This helps in understanding show popularity based on viewership data.

# Content Release Analysis:
A query is written to find the total number of TV shows and movies released each year, sorted by year. This identifies trends in content production and how they change over time.

# Cost-Based View Creation:
For business intelligence, create a view of the top 3 TV shows based on their standard cost per month. This gives insights into the most expensive shows in terms of subscription costs.

# Demographic and Subscription Analysis:
Create a pivot table to calculate the number of users based on their gender and subscription type, grouped by age ranges (under 30, 30-50, over 50). This helps in understanding user demographics and their subscription behavior.

# User Behavior Analysis:
A specific query identifies users who joined in 2022 and have a Standard subscription, and sorts them by join date. This is crucial for analyzing recent user growth.

# Subscription Duration:
Calculate the average duration of a subscription in months, categorized by subscription type. This metric helps assess user retention across different subscription plans.

# Revenue Analysis:
Compute the total monthly revenue generated by users, segmented by age groups (using 10-year intervals). This analysis provides insights into which age groups are generating the most revenue.

# User Age Analysis:
A query is designed to determine the average age of users, broken down by their subscription type and gender. This allows the stakeholders to understand how age influences subscription behavior.

# Premium Subscription Cost:
Calculate the total cost per month for Premium subscription in countries with more than 2,000 movies. This highlights geographical differences in the cost of premium content.

# Global Subscription Costs:
Calculate the total cost per month across all subscription types for all countries. This provides a global view of how much revenue is being generated from subscriptions.

# Country-Specific Analysis:
Identify the country with the highest cost per month for Premium subscriptions. This data helps to locate regions with the most expensive premium services and could inform pricing strategies.

# Conclusion:
This SQL-based project focuses on leveraging data analysis techniques to provide valuable insights into the movie and TV show industry. The queries designed here enable stakeholders to:

Analyze user behavior and demographics.
Understand content production and release trends.
Make informed decisions on pricing and subscription strategies.
Identify high-revenue-generating user segments and geographical regions.
The analysis ultimately helps stakeholders in the movie and subscription services industries improve business decisions, customer targeting, and content strategy.






