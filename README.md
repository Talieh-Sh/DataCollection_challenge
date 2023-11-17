# Mars Weather Data Analysis Project

## Project Overview
This project is focused on web scraping and data analysis of Mars weather data. It involves scraping titles and preview text from Mars news articles and analyzing weather data from Mars, using Python, Splinter, Beautiful Soup, Pandas, and Matplotlib.

## Completed Steps

### Part 1: Scrape Titles and Preview Text from Mars News
- Automated browser with Splinter to visit the Mars News Site.
- Created a Beautiful Soup object to extract text elements from the website.
- Extracted titles and preview text of news articles and stored each title-and-preview pair in a Python dictionary.
- Stored all dictionaries in a Python list and printed the list in the notebook.
- Exported the scraped data to a JSON file for ease of sharing.

### Part 2: Scrape and Analyze Mars Weather Data
- Used automated browsing to visit the Mars Temperature Data Site.
- Created a Beautiful Soup object to scrape data from an HTML table.
- Assembled scraped data into a Pandas DataFrame with appropriate headings matching the website's table.
- Examined and cast data types to appropriate formats (datetime, int, float).
- Analyzed the dataset to answer several key questions about Martian weather, including the number of Martian months and days, coldest and warmest months, and atmospheric pressure variations.
- Plotted the results of analyses using Matplotlib bar charts.
- Estimated the number of terrestrial days in a Martian year by plotting the daily minimum temperature.
- Exported the final DataFrame to a CSV file for further use and analysis.

## Tools Used
- Python
- Splinter
- Beautiful Soup
- Pandas
- Matplotlib
- HTML
- CSS
