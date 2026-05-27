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
- Before starting ingredient cleanup, have to verify products have the right ingredients/ no empty ingredients or wrong ingredient sentences.
- LOTS of products didn't have all ingredients or just grabbed one sentence instead of all ingredient sentences. (Usually when a product has an active, it grabbed the active part and not the inactive ingredient part)
- Go double check websites for accurate ingredients
- Checked against too little ingredients or too long of a sentence (signs of wrong ingredients string)

  
- Data Consists of strings of ingredients (One Whole String)
- Usually and MOST products have ingredients separated by commas
- Those products who don't need special edge case testing otherwise your code will fail or not display the right information on your website
- Sometimes special symbols appear on some products so that is why we use regex to take those away easily. (Also works for leading and tailing periods, exclamations etc...)
