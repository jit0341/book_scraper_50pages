# 📚 Book Scraper - 50 Pages

![GitHub Repo stars](https://img.shields.io/github/stars/jit0341/book_scraper_50pages?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/jit0341/book_scraper_50pages)
![Repo size](https://img.shields.io/github/repo-size/jit0341/book_scraper_50pages)

This project scrapes book listings from [Books to Scrape](http://books.toscrape.com/) across **50 pages** and saves the data into an **Excel file** with proper formatting.

---

## ✅ Features

- Scrapes:
  - 📖 Title
  - 💰 Price (formatted as ₹)
  - ✅ Availability status
  - ⭐ Rating
- Handles **all 50 pages**
- Saves results to `books_data.xlsx`
- Clean and readable formatting
- Written in **Python** using:
  - `requests`
  - `BeautifulSoup`
  - `openpyxl`

---

## 🗂 Sample Output

| Title                        | Price (₹) | Availability     | Rating |
|-----------------------------|-----------|------------------|--------|
| A Light in the Attic        | ₹51.77    | In stock         | Three  |
| Tipping the Velvet          | ₹53.74    | In stock         | One    |
| ...                         | ...       | ...              | ...    |

---

## 🚀 How to Run

1. Install required packages:
    ```bash
    pip install requests beautifulsoup4 openpyxl
    ```

2. Run the script:
    ```bash
    python scraper.py
    ```

3. Output:
    ```
    books_data.xlsx
    ```

---

## 🛠️ Use Cases

- ✔️ Showcase of web scraping
- ✔️ Freelancing demo
- ✔️ Data cleaning + Excel export practice

---

## 👨‍💻 Author

Developed with 💻 by **Jitendra Bharti**  
📎 [GitHub Profile](https://github.com/jit0341)

---

⭐ If you found this useful, star the repo and share it!
