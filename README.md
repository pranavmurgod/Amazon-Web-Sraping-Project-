# Amazon Products Data Extraction

## Project Overview
This project is designed to extract product information from an Amazon HTML page using Python and BeautifulSoup. The program parses the HTML file and retrieves essential product details such as names, prices, and reviews. It then exports the extracted data into an Excel file for easy analysis. This project demonstrates my ability to work with web scraping, data extraction, and Excel file handling, essential skills for a Business Analyst.

## Features
Parses Amazon product listings using BeautifulSoup.
Extracts product names, prices, and reviews from specified HTML classes.
Handles missing or unavailable information efficiently.
Exports data to a structured Excel file for reporting or analysis.

## Technical Tools and Skills
Python: Used to implement the web scraping logic.
BeautifulSoup: For parsing the HTML and extracting relevant data.
Pandas: Used to organize and export data into an Excel file.
Excel: The final output is stored in an Excel file for further analysis.

## Project Steps
1.  Read and Parse the HTML File:
The HTML file (amazon.html) is read and parsed using BeautifulSoup, allowing easy traversal of the document structure.

2. Extract Data from Specific HTML Elements:
I targeted specific div elements representing Amazon product listings.
For each product, I extracted:
Names: The product name from the span with class "a-size-medium a-color-base a-text-normal".
Prices: The product price from the span with class "a-price-whole".
Reviews: The review ratings from the span with class "a-icon-alt".
Proper error handling was implemented to ensure missing values don't break the extraction process.

3. Write Data to Excel:

After gathering the product names, prices, and reviews, I used the Pandas library to create a structured DataFrame.
The DataFrame was then exported into an Excel file named amazon_products.xlsx.

## How to Run the Project
Clone the repository.
Ensure you have the necessary libraries installed:
pip install beautifulsoup4 pandas openpyxl
Place the amazon.html file in the project directory.
Run the amazon_scraper.py script.
The extracted data will be saved in amazon_products.xlsx.

## Conclusion
This project demonstrates my ability to extract, clean, and organize data using web scraping techniques. It also highlights my understanding of Python libraries, such as BeautifulSoup and Pandas, and my ability to present structured data in Excel.

Feel free to check out the code and run the project!
