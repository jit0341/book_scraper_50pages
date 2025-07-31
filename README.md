# Book Scraper – Python Web Scraping Project

This Python script scrapes **book titles, prices, and availability** from all 50 pages of [BooksToScrape](http://books.toscrape.com), a website made for practicing web scraping.

## 📌 What it does
- Scrapes book titles, prices, and stock status
- Converts prices from £ to ₹ (₹1 = £105)
- Saves clean data into an Excel file
- Handles all 50 pages automatically

## 🛠 Tools & Libraries Used
- `requests` – fetches HTML pages
- `beautifulsoup4` – parses the HTML content
- `pandas` – handles and saves tabular data
- `openpyxl` – for saving to `.xlsx` format

## 🧪 Sample Output

| Title                           | Price (INR) | Availability |
|--------------------------------|-------------|--------------|
| A Light in the Attic           | ₹10605.00   | In Stock     |
| Tipping the Velvet             | ₹6300.00    | In Stock     |
| Soumission                     | ₹8190.00    | Out of Stock |

## ▶️ How to Run
```bash
python book_scraper.py

The output Excel file books_all.xlsx will be saved in the same directory.

🔥 Why this project matters

This is a real-world web scraping project for:

Beginners learning Python + BeautifulSoup

Freelancers offering data scraping services

Anyone building a scraping portfolio



---

🧑‍💻 Author

Jitendra Bharti
Python Learner | Freelance Developer
Connect on GitHub

