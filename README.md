# Data_Collection_Curation_1
This is the first assignment of data collection and curation with the teacher Robin Huang
In this notebook I answered these questions:

For the attached covid-19 and country dataset, use Apache Spark to solve following questions. Note: You can use any programming language as long as you are using Apache Spark.

1.	Import the data [covid-19.csv] using inferred schema. Log the time taken to import.
2.	Define the schema and then import the data using your defined schema. Log the time taken to import
3.	Would you recommend creating a schema first before importing the data? Why?
4.	Provide summary statistics on the dataset
5.	Identify the top 10 countries suffering from covid-19 (you will define the criteria, whether based on death ratio, or total confirmed cases, etc.).
6.	For the 10 countries indentified in #5, plot the line charts to show the trend of deaths from Jan 22, 2020 to May 14, 2022. Your horizontal axis should be the date.
7.	For each country and date, calculate cumulative recovered cases. Formula: cumulative recovered cases = cumulative_total_cases - active_cases - cumulative_total_deaths.
8.	Plot the trend of the recovery rate (cumulative recovered cases / cumulative_total_cases) for the period Jan 22, 2020 to May 14, 2022. Your horizontal axis should be the date. Which 5 countries have a relatively higher recovery rate?
9.	As of May 14, 2022, aggregate the cumulative_total_cases, deaths, recovered cases and active cases group by continent. Hint: Utilize country.csv and the covid dataset.
10.	Which 5 countries have the highest growth rate on cumulative_total_cases 6 months after the 1st positive case was detected within the country?
11.	For step 9, export the results to a JSON file
