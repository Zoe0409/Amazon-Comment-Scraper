# Amazon-Comment-Scraper

A python-based program to collect reviews from any Amazon product page into a CSV file based on users' requirements including the ratings, the number of reviews, and the review content.

**Instructions:**

1. To install necessary dependencies of packages, run this command:
```pip3 install beautifulsoup4, selenium, tqdm```
2. Open up your Command Prompt or Terminal inside the "AmazonCommentScraper" folder and run this command:</br>
```python3 Main.py```<br><br>
3. Go to Amazon and locate your desired product and copy the product link. Example:</br>
```https://www.amazon.com/Web-Scraping-Python-Collecting-Modern/dp/1491985577/ref=sr_1_3?crid=P8E8ZN1LR7HO&keywords=python+web+scraping&qid=1582932375&sprefix=python+web%2Caps%2C143&sr=8-3```<br><br>
4. (Optional) If you are using Shopify make sure this name matches EXACTLY what your product name is at the end of the product link! <br><br>
5. Choose the minimum rating that you would like to gather. Example: input 3 to collect reviews that are 3 stars and above.<br><br>
6. Choose the number of comments that you would like the program to search for before terminating. Input 0 to search through all of them. <br><br>
7. Input any words that you would like to exclude from the comments. All reviews containing these words will be ignored.

**Advantages:**

You don't have to login or provide any information about your Amazon account. The whole process is very easy.

**Reference:**

The code was based on https://github.com/maxmonciardini/AmazonCommentScraper. Modification includes the code to locate which information should be scraped from the webpage, and to save the information into a csv file.

