# Amazon Web Scraper

A simple Python web scraper that pulls a product's title and price from an Amazon product page using `requests` and `BeautifulSoup`, then saves the result to a CSV file.

## What it does
- Sends a request to an Amazon product URL with a browser-like User-Agent header
- Parses the HTML with BeautifulSoup
- Extracts and cleans the product title and price
- Saves the data to `AmazonWebScraperDataset.csv`

## Tech stack
- Python 3
- requests
- beautifulsoup4

## Setup
```bash
pip install requests beautifulsoup4
```

## Usage
1. Open `Amazon_Web_Scraper_project.ipynb` in Jupyter.
2. Set the `URL` variable to the Amazon product page you want to scrape.
3. Run the cells in order — title and price get printed and saved to CSV.

## Disclaimer
For educational purposes only. Scraping Amazon may violate their Terms of Service.
