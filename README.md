
# Redbus Data Scraping with Selenium & Dynamic Filtering using Streamlit

This project integrates web scraping with dynamic data visualization to create an interactive tool for exploring bus route information.


Problem Statement:

1.	The "Redbus Data Scraping and Filtering with Streamlit Application" aims to revolutionize the transportation industry by providing a comprehensive solution for collecting, analysing, and visualizing bus travel data.
2.	By utilizing Selenium for web scraping, this project automates the extraction of detailed information from Redbus, including bus routes, schedules, prices, and seat availability.
3.	By streamlining data collection and providing powerful tools for data-driven decision-making, this project can significantly improve operational efficiency and strategic planning in the transportation industry.









## Features

-  Automated Web Scraping:
  Utilizes Selenium to collect detailed bus travel data from the RedBus website.
Gathers information on bus routes, schedules, prices, and seat availability.

- Data Processing and Storage:

Processes and cleans the scraped data using Pandas.
Stores the cleaned data in a MySQL database for efficient querying and management.

- Dynamic Data Filtering:

Implements a Streamlit web application to interactively filter and search the bus data.
Allows users to apply filters based on route, bus type, price range, departure time, rating, and seat availability.


- Data Visualization and Export:

Provides options to visualize filtered data in an interactive table.
Offers functionality to export filtered results to an Excel file.


## Tools

•  Python: Core programming language used for scripting and data processing.

•  Pandas: Library for data manipulation and analysis.

•  Selenium: Web automation tool for web scraping.

•  MySQL: Database system for storing and managing scraped data.

•  Streamlit: Framework for creating interactive web applications

## Approach

1. Web Scraping with Selenium:

    Initialize WebDriver: Set up Chrome WebDriver to interact with the RedBus site.
    
    Navigate and Extract Data: Use Selenium to navigate through pages, click pagination tabs, and extract bus route details. Handle errors to ensure continuous scraping.


2. Data Processing with Pandas:

    Create DataFrame: Compile scraped data into a Pandas DataFrame.

    Clean and Format: Convert times, extract numeric values, handle missing data, and ensure correct data types.

    Export Data: Save the processed DataFrame to a CSV file for further use.

3. Database Management with MySQL:

    Connect and Create Table: Connect to MySQL and create a table based on the DataFrame’s schema.

    Insert Data: Import cleaned data into the MySQL table with robust error handling and transaction management.

4. Dynamic Filtering with Streamlit:

    Develop Interface: Build a Streamlit app for users to filter and view data interactively.

    Generate Queries: Create and execute SQL queries based on user-selected filters.
    
    Export Options: Allow users to export filtered results to an Excel file.
## Contact

For more information or collaboration opportunities, you can reach me on [LinkedIn]

https://www.linkedin.com/in/nirmal-r-b265b331b/