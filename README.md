# Web-Scraping

Car Dealer Web Scraping
This Python script allows you to scrape car dealer information from the website "cars.com". It retrieves data such as the car name, mileage, dealer name, rating, review count, and price for Mercedes-Benz vehicles. The script utilizes the BeautifulSoup library for web scraping and the requests library for making HTTP requests.

Prerequisites- Make sure you have the following libraries installed:

1.BeautifulSoup
2.requests
3.pandas

You can install them using pip: pip install beautifulsoup4 requests pandas


Usage:


Set the website variable to the desired URL, which contains the search results for Mercedes-Benz vehicles on cars.com.

Run the script using a Python interpreter.

The script will scrape the data from the webpage and store it in a pandas DataFrame.

The resulting DataFrame will be saved to an Excel file named "car_dealer_single_page.xlsx" in the same directory as the script.

To scrape multiple pages, the script will automatically loop through pages 1 to 10 and retrieve the data. The data from all pages will be combined into a single DataFrame.
