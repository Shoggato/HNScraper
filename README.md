# Hacker News Scraper

## Overview

This Python script scrapes information from Hacker News (https://news.ycombinator.com) and retrieves the top stories with over 100 points. It utilizes the BeautifulSoup library to parse HTML and the Requests library to make HTTP requests.

## Dependencies

- Python 3.x
- BeautifulSoup
- Requests

Install dependencies using:

```bash
pip install beautifulsoup4 requests
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/your-username/hacker-news-scraper.git
cd hacker-news-scraper
```

2. Run the script:

```bash
python scraper.py
```

The script fetches data from the first and second pages of Hacker News, extracts relevant information, and prints the sorted list of stories based on votes.

## Structure

1. `scraper.py`: Main Python script containing the scraping logic.
2. `LICENSE`: License information for the project.
3. `README.md`: Documentation and information about the project.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Thanks to the creators of BeautifulSoup and Requests for providing powerful tools for web scraping in Python.
- Special thanks to ZerotoMastery's Andrei Neagoie for the inspiration. This project was undertaken purely for learning purposes, for basic web scraping, and also to have some morning coffee reading material. 😄
