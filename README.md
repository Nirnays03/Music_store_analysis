# Music_store_analysis

Music Store Database Analysis

Project Overview

The Music Store Database Analysis project is designed to extract key business insights from a music store database using SQL queries. The objective is to analyze various aspects of the store's sales, customers, and music trends to support data-driven decision-making. This project showcases advanced SQL techniques to solve real-world business problems in the retail music industry.

Objectives

Identify key business metrics such as top customers, best-performing cities, and revenue trends.

Analyze customer preferences based on music genres and purchasing behaviors.

Optimize business growth strategies by providing insights into customer spending patterns and market trends.

Demonstrate proficiency in SQL by solving business-related queries using advanced SQL techniques.

Technology & Tools Used

Database: SQL-based relational database

Query Language: SQL (Structured Query Language)

SQL Techniques Used:

Aggregation Functions (SUM(), COUNT(), AVG())

Joins (INNER JOIN, LEFT JOIN)

Subqueries

Common Table Expressions (CTEs)

Recursive Queries

Window Functions (ROW_NUMBER(), PARTITION BY)

Key Business Questions & SQL Solutions

Question Set 1 - Easy Level

Who is the senior-most employee based on job title?

Used ORDER BY to rank employees based on job levels.

Which countries have the most invoices?

Utilized GROUP BY and COUNT() to determine the number of invoices per country.

What are the top 3 values of total invoice amounts?

Sorted invoice totals in descending order and used LIMIT to fetch the top 3 values.

Which city has the best customers (highest revenue)?

Used SUM() on invoice totals grouped by city to identify the top-performing location.

Who is the best customer (highest spending)?

Combined JOINs and SUM() functions to find the customer who spent the most.

Question Set 2 - Moderate Level

List of Rock Music listeners (Emails, Names, Genre).

Used JOINs to filter customers based on track genre and sorted results alphabetically by email.

Top 10 artists who have written the most Rock music.

Combined JOINs and COUNT() to rank artists based on their track count.

Tracks that are longer than the average song length.

Used subqueries to compare track lengths against the average length and sorted in descending order.

Question Set 3 - Advanced Level

How much money has each customer spent on each artist?

Implemented CTEs and JOINs to track customer spending per artist based on invoice line details.

Most popular music genre per country.

Used window functions (ROW_NUMBER()) to determine the highest purchased genre in each country.

Top-spending customer per country.

Used recursive queries and window functions to fetch top spenders for each country.

Key Insights & Findings

Top Customer: Identified the highest-spending customer who contributed significantly to store revenue.

Best-Performing City: The city with the highest sum of invoice totals was recommended for a promotional music festival.

Most Popular Genre by Country: Determined the leading genre for each country, useful for targeted marketing.

Revenue Contribution by Artist: Found which artist generated the most revenue, helping in artist collaborations.

Track Length Analysis: Identified songs longer than the average, which could be leveraged for premium content recommendations.

Project Highlights

✔ Data-Driven Business Insights: Provided actionable recommendations for business growth & strategy.

✔ Advanced SQL Proficiency: Applied CTEs, Recursive Queries, and Window Functions to handle complex queries efficiently.

✔ Real-World Application: Addressed customer segmentation, revenue optimization, and market trends for the music store.




SQL schema 

![MusicDatabaseSchema](https://github.com/user-attachments/assets/a8c6dff6-9d31-4b70-b64b-64235187bc26)

