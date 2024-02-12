# Web Scraping Project: Python Job Listings on Profesia.sk

This repository hosts the code for a web scraping project aimed at extracting Python job listings from Profesia.sk, a popular job portal in Slovakia. The project is structured into three stages:

1. **Single Job Scraping:** Initially, the script extracts the details of the first Python job listing on the site.

2. **Page-Wide Scraping:** Next, the script expands its scope to scrape all Python job listings on the first page of the site.

3. **Multi-Page Scraping:** In the final stage, the script traverses through all the pages of a specific Python job link, scraping the job listings on each page.

The data extracted includes 'Job Title', 'Company Name', 'Location', 'Salary', 'More Info', 'Added or Updated', and 'Date'. The script is configured to store only Python jobs that were updated or added within the last 24 hours.

The data is compiled into a pandas DataFrame and then exported to a CSV file for subsequent analysis. The script is set to run daily and appends new data to the existing CSV file.

The specific URL used for this project is: `https://www.profesia.sk/praca/bratislava/?radius=radius30&search_anywhere=python&page_num=1`

This project serves as a demonstration of the potential of web scraping for data collection and can be a useful reference for those interested in exploring this technique. Please remember that this code is intended for educational purposes and should be used responsibly, in compliance with the website's terms of service.

> Note: 'Date' refers to the day when the data was scraped from the website.
