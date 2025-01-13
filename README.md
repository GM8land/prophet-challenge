## Modele 8 Challenge: Time Series Forecasting with Prophet
### Challenge Instructions
You’re a growth analyst at Mercado LibreLinks to an external site.. With over 200 million users, Mercado Libre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

The instructions for this Challenge are divided into four steps, as follows:

Step 1: Find unusual patterns in hourly Google search traffic.

Step 2: Mine the search traffic data for seasonality.

Step 3: Relate the search traffic to stock price patterns.

Step 4: Create a time series model with Prophet.
### Requirements
- Find unusual patterns in hourly Google search traffic (25 points)
  - Read the search data into a DataFrame. (5 points)
  - Slice the data to just the month of May 2020. (5 points)
  - Calculate the total search traffic for the month.(5 points)
  - Compare the value to the monthly median across all months. (5 points)
  - Did the Google search traffic increase during the month that MercadoLibre released its financial results? Write your answer in the space provided in the starter file. (5 points)
- Mine the search traffic data for seasonality (20 points)
  - Group the hourly search data to plot the average traffic by the hour of day. (5 points)
  - Group the hourly search data to plot the average traffic by the day of the week (for example, Monday vs. Friday). (5 points)
  - Group the hourly search data to plot the average traffic by the week of the year. (5 points)
  - Are there any time based trends that you can see in the data? Write your answer in the space provided in the starter file. (5 points)
- Relate the search traffic to stock price patterns (35 points)
  - Read in and plot the stock price data. (5 points)
  - Concatenate the stock price data to the search data in a single DataFrame. (5 points)
  - Slice the data to just the first half of 2020 (2020-01 to 2020-06 in the DataFrame), and then plot the data. (5 points)
  - Create a new column in the DataFrame named “Lagged Search Trends” that offsets, or shifts, the search traffic by one hour. (5 points)
  - Create two additional columns:
  - “Stock Volatility”, which holds an exponentially weighted four-hour rolling average of the company’s stock volatility. (5 points)
  - “Hourly Stock Return”, which holds the percent change of the company's stock price on an hourly basis. (5 points)
  - Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns? Write your answer in the space provided in the starter file. (5 points)
- Create a time series model with Prophet (20 points)
  - Set up the Google search data for a Prophet forecasting model. (5 points)
  - After estimating the model, plot the forecast. (5 points)
  - Plot the individual time series components of the model. (5 points)
  - Answer the following questions in the space provided in the starter file:
  - What time of day exhibits the greatest popularity? (2 points)
  - Which day of the week gets the most search traffic? (2 points)
  - What's the lowest point for search traffic in the calendar year? (1 point)


### Grade: 96
### Feedback from Grader
Hey Geoff,

Congratulations on Challenge 8 submission, getting familiar with analyzing time series data and utilizing Prophet library to understand and predict trends over time.Your effort in exploring Google search traffic and its correlation with stock price patterns is commendable.

Here is a breakdown of your point total
I. Find Unusual Patterns in Hourly Google Search Traffic (23/25 points)
* Successfully read the search data into a DataFrame, sliced the data to May 2020, and calculated the total search traffic for the month.
* Accurately compared the value to the monthly median.
* While the explanation of the Google search traffic increase mentioned the peaks in the plot, it would have been more effective to discuss the ratio of traffic_may_2020 to median_monthly_traffic. This would provide a clearer quantitative analysis of the traffic increase.

II. Mine the Search Traffic Data for Seasonality (20/20 points)
* Successfully grouped the hourly search data to plot the average traffic by the hour of the day, day of the week, and week of the year.
* Provided a thorough explanation of the time-based trends observed in the data, demonstrating a strong understanding of the seasonal patterns.

III. Relate the Search Traffic to Stock Price Patterns (33/35 points)
* Successfully read in and plotted the stock price data, and concatenated it with the search data.
* Computed the necessary metrics and created the required columns for analysis.
* Provided a correlation matrix and basic explanation, a more thorough interpretation of the results would have been beneficial. Including more detailed insights about the correlations and their implications would strengthen the analysis. "There is a positive relationship indicating that increases in search trends are followed by increases in hourly stock returns."

IV. Create a Time Series Model with Prophet (20/20 points)
* Perfect execution of setting up the Google search data for a Prophet model, plotting the forecast, and answering all questions.

Overall, you did an excellent job! Keep up the momentum.


CG-SK
