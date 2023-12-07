Amazon Web Scraper
Overview
This Python program utilizes web scraping techniques to monitor the price of a favorite product, specifically salt for popcorn, on Amazon. The program extracts relevant information such as the product title, current price, and the date of the check. The data is then stored in a CSV file for future analysis.

Dependencies
Python 3.x
BeautifulSoup library
Requests library
Usage
Clone the repository or download the script.
Install the required libraries using the following command:
Copy code
pip install beautifulsoup4 requests
Run the script, and it will continuously check and record the product price on Amazon every 24 hours.
The collected data is stored in a CSV file named Amazon_web_scraper_data.csv.
Configuration
Modify the url variable to the Amazon product page you want to monitor.
Adjust the headers dictionary based on your User-Agent and preferences.
Notes
The program uses an infinite loop with a 24-hour delay between each price check.
The collected data includes product title, price, and the date of the check.
