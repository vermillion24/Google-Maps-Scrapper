# Google-Maps-Scrapper
This Python script utilizes the Playwright library to perform web scraping and data extraction from Google Maps. It is particularly designed for obtaining information about businesses, including their name, address, website, phone number, reviews, and more.

<br>

1. Install Python dependencies:
   pip install -r requirements.txt
   
2.Install Playwright browsers:
   playwright install

## Usage

Run the script with your desired search term and number of results:

```bash
python main.py -s "Coffee shops on the moon" -t 20
```

- `-s` or `--search`: Search query for Google Maps (default: "turkish stores in toronto Canada")
- `-t` or `--total`: Number of results to scrape (default: 1)
- `-o` or `--output`: Output CSV file path (default: result.csv)
- `--append`: Append results to the output file instead of overwriting (default: off)

## Notes
- Avoid running too many scrapes in a short period to prevent being blocked by Google.
