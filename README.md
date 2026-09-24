#  Amazon Product Data Scraper (Python)

This project focuses on scraping and analyzing product data from Amazon India using Python.
It walks through the complete process of extracting product details like title, price, rating, reviews, and availability and saving the data for further analysis.

---

##  Project Overview

The scraper uses BeautifulSoup and Requests to fetch HTML content from Amazon search results, and Pandas to organize and export the data.

---

##  Main Objectives of the Project

1️⃣ **Data Extraction**

● Fetch product links from Amazon search result pages.

● Extract detailed product information for each product:

  • Title
  
  • Price
  
  • Rating
  
  • Number of Reviews
  
  • Availability Status
  
● Handle missing or inconsistent data gracefully.



2️⃣ **Data Storage**

Save the extracted data into structured formats:

CSV file: amazon_data.csv

Excel file: amazon_data.xlsx


3️⃣ **Customization**

Easily modify the scraper for any product search query on Amazon.
Update the User-Agent to avoid request blocking.


---


##  Key Learnings

● Strengthened understanding of web scraping workflows with Python.

● Practiced parsing HTML using BeautifulSoup.

● Learned to clean and organize data using Pandas and NumPy.

● Learned to handle missing values and inconsistent formats in scraped data.

● Practiced exporting structured data into CSV and Excel.


---


##  Tools & Technologies

‣ Language: Python 3.x

‣ Libraries: BeautifulSoup, Requests, Pandas, NumPy

‣ Focus Areas: Web Scraping, Data Cleaning, Data Export


---


##  How to Use
1. Clone the Repository
git clone [https://github.com/gsthendaarnika/Amazon-product-Scraper]
cd amazon-web-scraper


2. Install Required Packages
pip install requests beautifulsoup4 pandas numpy openpyxl


3. Set User-Agent
In the script, replace the blank User-Agent line:
HEADERS = ({'User-Agent':'<YOUR_USER_AGENT>', 'Accept-Language': 'en-US, en;q=0.5'})
You can find your User-Agent by searching "my user agent" in Google.


4. Modify Product Search URL
Set your desired search query in the script:
URL = "https://www.amazon.in/s?k=mars+lipstick+set"


5. Run the script
python amazon_scraper.py


6. Check Output Files
amazon_data.csv
amazon_data.xlsx

Both files contain structured product data ready for analysis.


---


##  Example Output:-

| title                   | price | rating             | reviews       | availability |
| ----------------------- | ----- | ------------------ | ------------- | ------------ |
| MARS Matte Lipstick Set | ₹299  | 4.3 out of 5 stars | 1,245 ratings | In stock     |
| MARS Creamy Lip Set     | ₹249  | 4.1 out of 5 stars | 978 ratings   | In stock     |



---



##  Connect with Me
If you liked this project, feel free to connect with me on LinkedIn or check out my other projects!

Always open to feedback and collaboration 👩‍💻✨
