# Instagram_Web_Crawling
This Python script scrapes information from an Instagram profile, including account details and the top 25 posts. It uses Selenium and Beautiful Soup for web scraping and stores the data in a JSON file.

## Usage
1. **Prerequisites**:
   - Make sure you have Python installed.
   - Install the necessary libraries those are
  A. psycopg2
  B. selenium
  C. beautifulsoup4

2. **Results**:
   - The script will scrape the profile information and the top 25 posts.
   - The results will be saved in a JSON file named after the Instagram account.

## Important Notes

- This script relies on web scraping and may break if Instagram's web structure changes.
- Use this script responsibly and consider Instagram's terms of service.

# Code Overview
1. Code to import all the libraries and to login and open the profile automatically on Instagram.
2. Declaring chrome driver and beautiful soup.
3. Extracting name, followers, profile image url and bio through beautiful soup.
4. Extracting information of first 25 posts of that account.
5. Storing all information using JSON.

