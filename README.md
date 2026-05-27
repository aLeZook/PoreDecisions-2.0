# Project Overview:
This project is aimed to create a skincare website that accurately displays ingredients, research on those ingredients, product highlights, product information etc.

After product information retrieval, the hardest part was cleaning data because of the amount of fluctuation there is for 6000+ products.

## Web Scraping Requirements:
- BeautifulSoup
- Playwright

## Data Cleanup Essentials:
- Python
- Pandas
- Json
- Regex (re)

## Data Cleanup Process
- Data Consists of strings of ingredients (One Whole String)
- Usually and MOST products have ingredients separated by commas
- Those products who don't need special edge case testing otherwise your code will fail or not display the right information on your website
- Sometimes special symbols appear on some products so that is why we use regex to take those away easily. (Also works for leading and tailing periods, exclamations etc...)
