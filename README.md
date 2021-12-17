# Web Scraping from Multiple Sources with Python

# 1. Project Overview

### 1.1 
This project invloved scraping for contact information from multiple sources. The clients request was to collect contact information from ~2,000 company names. No website links were given so a plan to locate the information had to be determined. Websites were collected from an approriate but specific search engine and the remaining data was collected from a combination of the same search engine, and from the website links collected from the search engine. 

Please note: Due to the sensitive nature of the data, no images which expose the data will be shown. 

### 1.2 Key Information Needed
* Name
* Phone number
* Email address
* Postcode

### 1.3 Tools Used
* **Python**
* **Excel**

# 2. Project Execution

### 2.1 Scraping the data using selenium package from Python
The Scrape Info.ipynb file contains the tool developed for scraping all information for this task. Firstly, some preliminary research was done to determine the best source for finding the website links. The first section of the script utilises this source to find the websites, phone numbers, and postcodes. Finally, regex and some additional qualifier elements were used to scrape email addresses from the websites obtained. 

### 2.2 Cleaning data in Excel
Once the data had been collected, some useful tools and functions in Excel were used to clean the data. For example, the function =TEXT(A2, "00000000000") was used to reformat the phone numbers. The find and replace was used to remove artifacts from the list collection in Python such as "'" and "[]". Finally, the spreadhseet was formatted, coloured, and checked over thouroughly before submitting to the client. 

