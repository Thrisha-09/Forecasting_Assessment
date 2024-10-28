For forecasting the dataset , I have used "PROPHET" ,which  is a powerful and flexible time-series forecasting tool.

I have used "PROPHET" because,
       ** It automatically identifies long-term trends and seasonal patterns.
       ** Handles missing data without needing extra cleaning.
       ** It has the ability to detect weekly seasonality which helped in creating accurate forecasts.

Steps that I have done:

   1.  Converted the 'Date' column to the correct format and prepared the ridership data.
   2.  For each column , i have fitted a Prophet model to capture historical patterns.
   3.  By using prophet,I have predicted forecast for the next 7 days and visualized it with confidence intervals (upper and lower bounds).

Advantages of Prophet:
    ** Works quickly even with larger datasets.
    ** Helps in understanding the range of possible outcomes.
