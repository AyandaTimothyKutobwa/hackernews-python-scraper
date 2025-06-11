# Hacker News Python Scraper

This project scrapes top posts from Hacker News using Python, stores the data in CSV format, and visualizes it with bar charts.

## Features

- Scrapes top stories from Hacker News using BeautifulSoup
- Extracts title, score, and link from each post
- Saves data in structured CSV files
- Generates bar charts to visualize post scores
- Organized output into folders for easy access

## Folder Structure
- `/charts`: Contains bar chart PNGs
- `/csv`: Stores scraped post data
- `main.py`: The main scraping and analysis script

## How to Run
1. Install dependencies: Make sure you have Python 3.7+ installed.
2. Run the script: python main.py

This will scrape Hacker News, save data into `csv/top_posts.csv`, and generate a bar chart in `charts/top_scores_chart.png`.

---

## Tech Stack

- Python 3.x  
- requests  
- BeautifulSoup4  
- pandas  
- matplotlib  

---

## Author

Ayanda Timothy Kutobwa  
Cybersecurity Graduate Student @ Pace University  
Portfolio: https://ayandatimothykutobwa.github.io/ayandakutobwa.github.io  
GitHub: https://github.com/ayandatimothykutobwa  

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.
