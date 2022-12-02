# Linkedin and Twitter Jobs Scraper ![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

### Description

A bot to scrape jobs data from linkedin and twitter. A [scrapy](https://scrapy.org/) crawler is used to fetch the links and data is extracted from the tags using [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/).

## Running Linkedin bot

This repository can be downloaded using

```
git clone https://github.com/gautham-apa/LinkedinJobScraper.git
```

The search keywords required can be added in the `searchKeywords` list located in the `/linkedinbot/linkedinbot/spiders/linkedinSpider.py` file.
To run the bot use the following command

```
scrapy crawl linkedinSpider
```

The scraped data would be transformed to a json and written at location `/linkedinbot/linkedinbot/spiders/data` with current date and time.

#### Disclaimer

This bot has been built for educational purposes only and not intended for commercial deployment. Please use it wisely at your own risk.
