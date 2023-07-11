# Home_Sales
Determine metrics about home sales data using SparkSQL.

In this folder is the "Home_Sales_colab.ipynb" jupyter notebook which pulls in the following data:
    * "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv"

On that data, within the jupyter notebook, are the following Spark SQL queries:

    * What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    * What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    * What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?    Round off your answer to two decimal places.
    * What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

The last query is run before caching the table, after caching the table, and after partitioning the data and creating a temporary table view, with run times for each version of that last query.