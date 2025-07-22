# 📚 Bookstore Scraper

This project is a Python web scraper that collects book data from the site [Books to Scrape](https://books.toscrape.com/). It goes through multiple pages and extracts information like:

- 📖 Title
- 💲 Price
- 📦 Availability
- ⭐ Star Rating
- 🔗 Direct Link to the Book

All the scraped data is saved into a CSV file (`Scrap.csv`).

---

## 🔧 Technologies Used

- **Python 3**
- `requests` – for making HTTP requests
- `BeautifulSoup` – for parsing HTML
- `pandas` – for working with CSV files
- `urllib.parse` – for joining relative URLs

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/minku999/Bookstore-scraper.git
cd Bookstore-scraper
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the scraper
bash
Copy
Edit
python scraper.py
This will create a file called Scrap.csv containing the scraped data.

📝 Output Sample (Scrap.csv)
Title	Price($)	Availability	Rating	Link
A Light in the Attic	51.77	In stock	Three	https://books.toscrape.com/.../index.html
Tipping the Velvet	53.74	In stock	One	https://books.toscrape.com/.../index.html

📌 Features
Scrapes data from all 50+ pages

Cleans and structures the data using pandas

Handles relative URLs with urljoin

Saves output to CSV format

🎯 Future Improvements
 Convert star ratings like "Three" into numeric values (e.g., 3)

 Add retry/error handling for failed requests

 Support JSON or Excel output

 Add command-line options for number of pages or output type

🧠 Why I Built This
This was a beginner-friendly project to practice real-world web scraping, work with HTML structures, and store data efficiently. It helped reinforce my skills in Python, BeautifulSoup, and data handling.

📄 License
This project is licensed under the MIT License – feel free to use, modify, or share it.

yaml
Copy
Edit

---

Just copy and paste this into your `README.md` file and push it to GitHub:

```bash
git add README.md
git commit -m "Add README with project details"
git push origin main
