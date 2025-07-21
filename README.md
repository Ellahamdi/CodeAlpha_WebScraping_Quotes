#  CodeAlpha - Task 1: Web Scraping (Quotes Project)

✅ **Internship Task:** Web Scraping  
✅ **Intern Name:** Ella Hamdi  
✅ **Project:** Extracting quotes from [http://quotes.toscrape.com](http://quotes.toscrape.com)  
✅ **Tools:** Python, Requests, BeautifulSoup, Pandas  
✅ **Company:** CodeAlpha - [www.codealpha.tech](https://www.codealpha.tech)

---

##  Project Workflow

1.  Analyze the website structure using browser developer tools.
2.  Build a Python scraper using `requests` and `BeautifulSoup`.
3.  Loop through all pages using pagination logic.
4.  Extract the quote, author, and tags.
5.  Clean and organize the data into a pandas DataFrame.
6. Export the dataset to a CSV file for further analysis or visualization.

---

##  Extracted Fields

| Field   | Description                      |
|---------|----------------------------------|
| Quote   | The actual quote text            |
| Author  | Name of the person quoted        |
| Tags    | Comma-separated related tags     |

---

## 🗃️ Project Files

| File Name            | Description                                 |
|----------------------|---------------------------------------------|
| `quotes_scraper.py`  | Main Python script for scraping             |
| `all_quotes.csv`     | Final CSV dataset of all scraped quotes     |
| `README.md`          | Project documentation (this file)           |

---

## How to Run the Project

1. 🔧 Install required libraries:

```bash
pip install requests beautifulsoup4 pandas
