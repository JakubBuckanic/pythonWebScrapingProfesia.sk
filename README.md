# Profesia.sk Python Jobs Web Scraping Project

This repository contains the code for a web scraping project that extracts Python job listings from the Slovak job portal, Profesia.sk. The project is divided into three parts:

1. **Scraping the first Python job on the first page:** The script starts by extracting the details of the first Python job listing on the site.

2. **Scraping the whole page of Python jobs:** The script then proceeds to scrape all Python job listings on the first page of the site.

3. **Scraping all pages for a Python job link:** Finally, the script navigates through all the pages of a specific Python job link and scrapes the job listings on each page.

The extracted data includes the 'Name of Job', 'Company Name', 'Location', 'Salary', 'More Info', 'Added or Updated', and 'Date'. The script is designed to only store Python jobs that were added or updated within the last 24 hours.

The data is stored in a pandas DataFrame and exported to a CSV file for further analysis. The script is automated to run once a day and append the new data to the CSV file.

The specific link used for this project is: https://www.profesia.sk/praca/bratislava/?radius=radius30&search_anywhere=python&page_num=1

This project demonstrates the power of web scraping for data collection and can serve as a starting point for anyone interested in learning more about this technique. Please note that the code is intended for educational purposes and should be used responsibly, respecting the website's terms of service.
