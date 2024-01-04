# Website Metadata Scraper

This Python script scrapes meta title, description, and keywords from specified URLs and stores the results in an Excel file.

## Usage

1. Install required libraries:

   ```bash
   pip install requests beautifulsoup4 pandas

2. Run the script:

  ```bash
  python website_metadata_scraper.ipynb


```3. Enter multiple URLs separated by commas when prompted.

```4. The script will download an Excel file named scraped_metadata.xlsx containing the scraped data.




``**Code Structure**

```scrape_metadata(url): Function to scrape metadata from a single URL.
```User input: The script prompts the user to enter multiple URLs.
```Data storage: Scraped data is stored in a list of dictionaries.
```Pandas DataFrame: A DataFrame is created from the list of dictionaries.
```Excel export: The DataFrame is saved to an Excel file and downloaded.

```**Important Notes**

```- Respect website terms of service: Ensure compliance with target website's terms of service and robots.txt before scraping.
```- Handle errors gracefully: The script includes basic error handling, but consider more robust mechanisms for production use.
```- Consider rate limiting: Avoid excessive requests to a website in a short period to prevent being blocked.
```- Respect robots.txt: Check the website's robots.txt file to see if they allow scraping.
