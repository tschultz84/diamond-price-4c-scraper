# diamond-price-4c-scraper
 A web scraper to pull data on 4Cs and prices. Uses Python 3.9.7.

 This is a simple a short set script that pulls data from real live webpages. It gets this data:
 * Carat weight
 * Shape code
 * Clarity
 * Color
 * Grading Laboratory
 * Natural / Lab Grown
 * Price

 The output are CSV files containing this information. 

 The "price_4c_scraper.ipynb" contains the scraping scripts. This contains two parts:

 * Robots_Review checks that the robots.txt file is ok (for James Allen, it is allowed to search prices).
* scrape_JamesAllen is a function to scrape James Allen webpages.
 
 Currently it reads in James Allen, but I hope to eventually include more.
