# Netflix-Movies-and-TV-Shows-Power-BI-Dashboard
Project Overview

This project focuses on analyzing Netflix movies and TV shows data using Power BI. The dashboard provides a comprehensive view of content distribution, including genres, ratings, release trends, and country-wise availability. It helps users understand patterns in Netflix content and supports data-driven insights.
________________________________________
Objectives

•	To To analyze the distribution of movies and TV shows on Netflix

•	To identify the most popular genres and ratings

•	To study content growth over the years

•	To explore country-wise content availability

•	To create an interactive and user-friendly dashboard
________________________________________
Tools & Technologies Used

•	Power BI – Dashboard creation and visualization

•	Excel / CSV – Dataset handling

•	Power Query – Data cleaning and transformation

•	DAX (Data Analysis Expressions) – Calculations and measures
________________________________________
Dataset Description

The dataset includes the following fields:

•	The dataset contains information about Netflix titles, including:

•	Title name

•	Type (Movie / TV Show)

•	Genre/category

•	Rating (TV-MA, PG, etc.)

•	Release year

•	Country

•	Date added

•	Total records: 8800+ titles

•	Coverage: 1925 to 2021
________________________________________
Data Pipeline

1.	Data stored in AWS S3 bucket

2.	Connected to Snowflake using Storage Integration

3.	Data loaded into Snowflake table using COPY INTO

4.	Data cleaned and transformed

5.	Connected Snowflake to Power BI for visualization
________________________________________
Dashboard Features

•	KPI Cards:

o	Total  titles

o	Total genres

o	 Total ratings

o	locations

•	Visualizations:

o	Bar chart for top genres

o	Donut chart for Movies vs TV Shows

o	Rating distribution analysis

o	Country-wise content map

o	Trend analysis of content by release year

o	Interactive filters and slicers
________________________________________
Key Insights

•	Movies dominate Netflix content (~69%) compared to TV Shows (~31%)

•	Drama and Documentary are the most popular genres

•	Majority of content is rated TV-MA and TV-14

•	Significant growth in content after the year 2000
________________________________________
How to Run the Project

1.	 Download the dataset (CSV file)

2.	Open Power BI Desktop

3.	Load the dataset into Power BI

4.	Apply data cleaning steps (Power Query)

5.	Load the dashboard file (.pbix)

6.	Refresh data to view updated visuals
________________________________________
Future Enhancements

•	Add Add recommendation system based on genres

•	Include real-time data updates

•	Add user-based filtering (age, preferences)

•	Improve UI with advanced visualizations

•	Integrate with SQL database for large-scale data
________________________________________
Author

Priyanka Kenganur BSC(Cs) Student | Aspiring Data Analyst

