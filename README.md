# Twitter Data Scraper Notebook

This Jupyter Notebook allows you to scrape tweets and profile information from Twitter (via Nitter) for one or multiple users, and export the results to Excel for easy analysis.

> **Note:** Nitter-based scraping is working fine as of December 2024.

## Features

- **Scrape Tweets:**  
  Fetches recent tweets for any username, including tweet text, date, likes, and comments.
- **Profile Information:**  
  Extracts user profile details such as name, bio, location, website, join date, and follower stats.
- **Multiple Users:**  
  Scrape and save data for several Twitter usernames in one run.
- **Excel Export:**  
  Saves tweets and profile info for each user in separate sheets of a single Excel file.

## Requirements

- Python 3.7+
- Jupyter Notebook or VS Code
- The following Python packages:
  - ntscraper
  - pandas
  - xlsxwriter

Install dependencies with:

```sh
pip install ntscraper pandas xlsxwriter
```

## Usage

1. **Open the Notebook:**  
   Open `Twitter_Final (1).ipynb` in Jupyter or VS Code.

2. **Set Usernames:**  
   Edit the `usernames` list in the notebook to include the Twitter handles you want to scrape.

3. **Run All Cells:**  
   Execute all cells in order. The notebook will:
   - Scrape tweets and profile info for each username.
   - Save the results to `twitter_data_multiple_users.xlsx` in the current directory.

4. **View Results:**  
   Open the generated Excel file to see tweets and profile data, each in separate sheets per user.

## Notes

- **Nitter Backend:**  
  This notebook uses Nitter, an alternative Twitter frontend, for scraping. Data availability may vary.
- **Ethical Use:**  
  Use responsibly and respect Twitter’s and Nitter’s terms of service.

## File Structure

- `Twitter_Final (1).ipynb` — Main notebook for scraping and exporting Twitter data.

## License

For educational and research purposes only.
