# Day 14

On Day 14, I explored web scraping techniques to extract data from various websites. I learned how to scrape structured data from HTML pages using BeautifulSoup and practiced scraping Amazon product information from search results pages.

## Topics Covered

- **Web Scraping Basics**: Used BeautifulSoup to parse HTML and extract structured data from websites
- **Scraping Country Data**: Extracted country information (name, capital, population, area) from [scrapethissite.com](https://www.scrapethissite.com/)
- **Amazon Product Scraping**: Scraped Amazon product data including:
  - Product titles, prices, and ratings
  - Review counts
  - Brand names and ASIN
  - Product URLs
- **Multi-page Scraping**: Implemented pagination to scrape data across multiple search result pages

## Key Libraries Used

- `requests` - For making HTTP requests
- `beautifulsoup4` (bs4) - For parsing HTML and extracting data
- `pandas` - For data manipulation and storage
- `numpy` - For numerical operations
- `time` & `random` - For implementing delays and randomization

## Files in this Directory

- `fetching_data_using_web_scraping.ipynb` - Basic web scraping tutorial using scrapethissite.com
- `scraping_amazon_data.ipynb` - Initial Amazon scraping experiments
- `amazon_scrape_final.ipynb` - Complete Amazon product scraper with multi-page support
- `countries.csv` - Scraped country data
- `amazon_panty_liners.csv` - Scraped Amazon product data
