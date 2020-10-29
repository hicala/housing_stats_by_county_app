# Web Scraping using Beautiful Soup

## Summary

I am using Beautiful Soup for the this Python app. Beautiful Soup is a Python library for parsing data out of HTML and XML files (aka webpages). It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. 

The major concept with Beautiful Soup is that it allows you to access elements of your page by following the CSS structures, such as grabbing all links, all headers, specific classes, or more. It is a powerful library. Once we grab elements, Python makes it easy to write the elements or relevant components of the elements into other files, such as a CSV, that can be stored in a database or opened in other software.

The data I used came from U.S. Basic Housing Stats by County. American Community Survey 5-year Estimates (2010-2015). Reference: http://duspviz.mit.edu/_assets/data/county_housing_stats.html

## Main goal

+ To access all of the content from the source code of the webpage with Python
+ Parse and extract data. 
+ Save the info in CSV file for further analysis.

## Methodology

1. Import Modules
2. Get the URL link
3. Navigate the URL Data Structure
4. Testing out data requests
5. Write data to a file in pseudo-code:
    + Open up a file to write in and append data.
    + Set up parameters for the while loop. 
    + Write headers
    + Run while loop that will write elements of the array to file
    + When complete, close the file
6. The output file in CSV format.

## Data info extracted:

County, State, FIPS Code, Total Pop, Median Income ($), No. of Housing Units, Median Home Value ($), No. of Owner Occupied Housing Units, No. of Owner Occ. Housing Units with Debt, No. of Owner Occ. Housing Units without Debt


