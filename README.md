# Airlines_excel_project
Case Study: Analyzing Airline Data for Operational Efficiency
Background:
You are a data analyst working for a major airline company, SkyHigh Airlines. The management has provided you with a dataset containing flight operations data for the past year. Your task is to analyze the data to identify patterns, trends, and areas for improvement in operational efficiency. The company is particularly interested in understanding flight delays, cancellations, and their impact on customer satisfaction.

Dataset Overview:
The dataset includes the following columns:

Flight Number: Unique identifier for each flight.
Date: Date of the flight.
Origin: Airport where the flight originated.
Destination: Airport where the flight landed.
Scheduled Departure Time: The scheduled time the flight was supposed to depart.
Actual Departure Time: The actual time the flight departed.
Scheduled Arrival Time: The scheduled time the flight was supposed to arrive.
Actual Arrival Time: The actual time the flight arrived.
Flight Duration: The time duration of the flight (in minutes).
Delay (in minutes): The delay in departure or arrival, calculated as the difference between scheduled and actual times.
Cancellation: A binary indicator (Yes/No) for whether the flight was canceled.
Reason for Delay: The reason for delay (e.g., weather, technical issue, crew unavailability).
Number of Passengers: The number of passengers on the flight.
Customer Satisfaction Score: A score from 1 to 10 based on post-flight surveys.
Objectives:
Flight Delay Analysis:

Identify the average delay time for flights.
Determine which routes (Origin-Destination pairs) are most prone to delays.
Analyze the most common reasons for delays and their average impact on delay time.
Cancellation Analysis:

Calculate the percentage of flights canceled.
Identify trends in flight cancellations (e.g., specific routes, times of the year).
Analyze the impact of cancellations on customer satisfaction.
Passenger Load Analysis:

Determine the average number of passengers per flight.
Identify routes with consistently low passenger numbers.
Analyze the relationship between passenger load and flight delays.
Customer Satisfaction Analysis:

Analyze the average customer satisfaction score and identify key factors that influence it.
Determine the impact of delays and cancellations on customer satisfaction.
Provide recommendations for improving customer satisfaction based on the data.
Step-by-Step Analysis:
Data Cleaning:

Ensure that all date and time fields are in the correct format.
Handle any missing or inconsistent data, especially in critical fields like delay reasons or customer satisfaction scores.
Descriptive Statistics:

Calculate basic statistics (mean, median, mode) for key metrics like delay time, flight duration, number of passengers, and satisfaction scores.
Visualizations:

Bar Charts: Show the frequency of different delay reasons and their average delay times.
Heat Maps: Display delay trends across different routes and times of the year.
Box Plots: Compare the distribution of customer satisfaction scores across different flight conditions (on-time vs. delayed, canceled vs. completed).
Correlation Analysis:

Use scatter plots and correlation coefficients to examine the relationship between delays/cancellations and customer satisfaction scores.
Analyze the correlation between passenger load and flight delays.
Trend Analysis:

Perform a time series analysis to identify patterns in delays, cancellations, and passenger loads over the year.
Dashboard Creation:

Create an interactive Excel dashboard that allows the management to explore the data dynamically. Include filters for different routes, time periods, and other relevant factors.
