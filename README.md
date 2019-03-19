# news_reporter

Program is designed to answer a series of reporting questions about the associated 'news' database.  After linking to the database, the program prints out the results from three SQL queries to the console in plain text.

# Installation

To use news_reporter, first download the newsdata.sql file and open using psql to set up the database.  Then run news_reporter.py from the console using python3.  The associated responses will then be printed to the console.

# Usage

The program is designed using three functions:
* top_three_articles()
* top_authors()
* error_dates()

Each function links to the psql 'news' database and executes a single query from the associated tables.  Each function is then called in the main() function to report the answers to the following three questions:

* What are the most popular three articles of all time?
* Who are the most popular article authors of all time?
* On which days did more than 1% of requests lead to errors? 
