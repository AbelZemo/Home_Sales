# Home Sales Challenge

## File Renaming and Setup

    Renamed the Home_Sales_starter_code.ipynb file to Home_Sales.ipynb.
    Imported necessary PySpark SQL functions.
    Read the home_sales_revised.csv data into a Spark DataFrame.
    Created a temporary table named home_sales to facilitate data operations.
## Data Analysis and Queries

    Utilized SparkSQL to answer the following questions:

    Average Price for Four-Bedroom Houses by Year

    Rounded the average price to two decimal places.
    Average Price of Homes by Year Built (Three Bedrooms, Three Bathrooms)

    Rounded the average price to two decimal places.
    Average Price of Homes by Year (Three Bedrooms, Three Bathrooms, Two Floors, ≥ 2,000 Sq. Ft.)

    Rounded the average price to two decimal places.
    View Rating for Homes ≥ $350,000

    Determined runtime for this query, rounded to two decimal places.

## Data Caching

    Cached the temporary table home_sales.
    Checked if home_sales was successfully cached.

## Cached Data Analysis

    Using the cached data:

    Filtered out view ratings with an average price ≥ $350,000.
    Determined runtime and compared it to uncached runtime.

## Data Partitioning and Parquet Creation

    Partitioned by the date_built field on formatted parquet home sales data.
    Created a temporary table for the parquet data.
    Performance Analysis with Parquet Data
    Ran a query filtering out view ratings with an average price ≥ $350,000.
    Determined runtime and compared it to uncached runtime.

## Uncaching Data

    Uncached the home_sales temporary table.
    Verified uncaching using PySpark.

## Conclusion

This README summarizes the actions performed in the Home_Sales.ipynb notebook, including file setup, data analysis, caching, partitioning, and performance evaluation using SparkSQL operations.