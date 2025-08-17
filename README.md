# Web_Scraping_Project_Booktoscrap
Book to Scrap is a web scraping project that extracts book details such as title, price, rating, and availability from the website Books to Scrape and saves the data in a structured CSV file for analysis. This project uses Python, BeautifulSoup, and pandas to scrape and store the data in a structured format.
This project demonstrates practical skills in data extraction, parsing HTML content, handling pagination, and storing structured data for analysis.
Here’s a **complete, professional README** for your **Book to Scrap** project, fully formatted and ready for GitHub. It includes Anaconda, Jupyter Notebook setup, project workflow, and all necessary details.

---

## Features

* Scrapes **all 50 pages** of the Books to Scrape website.
* Extracts key details for each book:

  * **Title**
  * **Price**
  * **Rating**
  * **Availability**
* Saves data into **books.csv** for easy analysis.
* Easily expandable to scrape additional information like categories or product links.

---

## Technologies Used

* **Python 3.x**
* **Anaconda** – Python distribution with package management
* **Jupyter Notebook** – Interactive coding environment
* **BeautifulSoup4 (`bs4`)** – HTML parsing
* **Requests** – HTTP requests
* **Pandas** – Data handling and CSV export

---

## Project Workflow

1. **Send HTTP Requests** – Fetch HTML content of each page using `requests.get()`.
2. **Parse HTML** – Use BeautifulSoup to navigate and extract book data.
3. **Handle Pagination** – Loop through all 50 pages automatically.
4. **Extract Book Details** – Title, Price, Rating, Availability.
5. **Store Data** – Append data to a pandas DataFrame.
6. **Export CSV** – Save the final dataset as `books.csv` for analysis.

---

## Example Output

| Title                | Price  | Rating | Availability |
| -------------------- | ------ | ------ | ------------ |
| A Light in the Attic | £51.77 | Three  | In stock     |
| Tipping the Velvet   | £53.74 | One    | In stock     |
| Soumission           | £50.10 | One    | In stock     |

---

## Legal & Ethical Considerations

* Respect the website’s `robots.txt` rules.
* Avoid sending too many requests to prevent server overload.
* Only scrape publicly available data.

---

## Project Structure

```
Book_to_Scrap/
│
├── Book_to_scrap.ipynb       # Jupyter Notebook with scraping code
├── books.csv                 # CSV file containing scraped book data
└── README.md                 # Project documentation

```

## Future Enhancements

* Scrape additional book details like **categories, descriptions, or links**.
* Use **Selenium** for dynamic content scraping.
* Store data in **SQL/NoSQL databases** for larger datasets.
* Add **visualizations** for price distribution, ratings, and availability trends.
* Automate scraping via **scheduled scripts** for periodic updates.

---

## License

This project is for **educational purposes only**. Do not scrape real-world websites without permission.

---

