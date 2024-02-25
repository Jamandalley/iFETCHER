# iFETCHER
A user-centered web scraper

# Overview
This Python application serves as a versatile web scraper, allowing users to extract data from various websites by specifying the URLs in a spreadsheet. Users can customize the application to scrape data from any website by providing the appropriate column name containing the URLs in the spreadsheet.

# Usage Instructions
1. Installation
Ensure you have Python 3.x installed on your system.
Install the required libraries using pip:
`pip install aiohttp beautifulsoup4 pandas openpyxl ttkthemes`

2. Prepare Your Data
Create an Excel spreadsheet (.xlsx) containing the URLs you wish to scrape.
Ensure that the URLs are listed in a column of the spreadsheet.

3. Customization
. Open the Python script (`.py file`) of the web scraper application in a text editor or an IDE.
. Locate the variable that specifies the column name containing the URLs in the spreadsheet.
. Replace the placeholder column name with the actual column name from your spreadsheet.

4. Execution
. Run the Python script of the web scraper application.
. The application will prompt you to select the Excel file you prepared.
. Once you select the file, the scraping process will begin.
. The progress of the scraping process will be displayed.
. Upon completion, the scraped data will be saved into a new Excel file.

# Customization Options
. Website Specification: Modify the Python script to customize the web scraping logic according to the structure of the website you intend to scrape.
. Column Name: Specify the name of the column containing the URLs in your spreadsheet by updating the corresponding variable in the script.

# Requirements
. Python 3.x
. aiohttp library
. BeautifulSoup library
. pandas library
. openpyxl library
. ttkthemes library (for styling)

# Note
This application provides a generic framework for web scraping and can be adapted to scrape data from various websites.
Users are responsible for understanding and complying with the terms of service and usage policies of the websites they intend to scrape.
Ensure that you have the necessary permissions to scrape data from the targeted website. Unauthorized scraping may violate terms of service and legal regulations.
