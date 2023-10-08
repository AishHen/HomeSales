# HomeSales

**Description**

In this challenge, SparkSQL was used to determine key metrics about home sales data. Then, Spark was used to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

**Steps to Complete**

A. Imported the necessary PySpark SQL functions.

B. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

C. Created a temporary table called home_sales.

D. Ran queries using SparkSQL to answer the following questions:
*Answers are contained in the Outputs for each cell within the Notebook*
    1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    
    2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    
    3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    
    4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
    
E. Cached temporary table for home_sales, and confirmed cache

F. Using the cached data, ran the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determined the runtime and compared it to uncached runtime.

G. Partitioned by the "date_built" field on the formatted parquet home sales data

H. Created a temporary table for the parquet data called p_home_sales.

I. Ran the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determined the runtime and compared it to uncached runtime

J. Uncached the home_sales temporary table and verified using PySpark.

