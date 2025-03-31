**In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.**
Before You Begin
-Create a new repository for this project called, Home_Sales. Do not add this homework to an existing repository.

-Clone the new repository to your computer.

-Push your changes to GitHub.

**Files**
-Download the following files to help you get started:

-Module 22 Challenge filesLinks to an external site.

**Instructions**
-Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

-Import the necessary PySpark SQL functions for this assignment.

-Read the home_sales_revised.csv from the provided AWS S3 bucket location into a PySpark DataFrame.

-Create a temporary table called home_sales.

Answer the following questions using SparkSQL:
-
-What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

-What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

-What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

-What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.




