# Sqlalchemy-challenge

# Congratulations! You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii. To help with your trip planning, you decide to do a climate analysis about the area. The following sections outline the steps that you need to take to accomplish this task.

# Part 1: Analyze and Explore the Climate Data
In this section, you’ll use Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database. Specifically, you’ll use SQLAlchemy ORM queries, Pandas, and Matplotlib. To do so, complete the following steps:

Note that you’ll use the provided files (climate_starter.ipynb and hawaii.sqlite) to complete your climate analysis and data exploration.

Use the SQLAlchemy create_engine() function to connect to your SQLite database.

Use the SQLAlchemy automap_base() function to reflect your tables into classes, and then save references to the classes named station and measurement.

Link Python to the database by creating a SQLAlchemy session.

![image](https://github.com/user-attachments/assets/67d6115f-a56b-4c51-a861-4ee039872edf)


## Precipitation Analysis

Find the most recent date in the dataset:
'2017-08-23'
Using that date, get the previous 12 months of precipitation data by querying the previous 12 months of data.

Select only the "date" and "prcp" values.

Load the query results into a Pandas DataFrame. Explicitly set the column names.

Sort the DataFrame values by "date".

Plot the results by using the DataFrame plot method, as the following image shows:

![image](https://github.com/user-attachments/assets/601a1a02-7417-4bc3-91e5-585c5186e587)

Use Pandas to print the summary statistics for the precipitation data.

![image](https://github.com/user-attachments/assets/badafacb-b474-4cc5-8eb7-7b22f99afef6)

## Station Analysis
Design a query to calculate the total number of stations in the dataset.

Design a query to find the most-active stations (that is, the stations that have the most rows). To do so, complete the following steps:

List the stations and observation counts in descending order.

Answer the following question: which station id has the greatest number of observations?
'USC00519281',2772

