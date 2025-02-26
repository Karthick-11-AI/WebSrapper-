# WebSrapper

# Drug Review Web Scraper  

This project is a **web scraper** that extracts drug reviews from [Drugs.com](https://www.drugs.com) and saves them into a CSV file for further analysis.  

## **Features**  
- Extracts patient reviews for a given drug.  
- Saves the data into a structured CSV format.  
- Automatically formats drug names for URL compatibility.  
- Handles pagination to fetch multiple reviews.  

## **Requirements**  
Ensure you have the following installed:  
- Python 3.x  
- `requests` (for fetching webpage content)  
- `BeautifulSoup` (for HTML parsing)  
- `csv` (for saving data)  

Install dependencies using:  
```sh
pip install requests beautifulsoup4
#To run the file#
python webscrap.py
```
Notes
This scraper respects website limitations and should not be used for excessive requests.
Ensure compliance with Drugs.com terms of use.
License
This project is for educational purposes. No warranties or guarantees are provided.

