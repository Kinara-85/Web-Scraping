# Player Stats Web Scraper

## Overview
This project scrapes NBA player statistics from Basketball Reference using Python and Pandas. It extracts, cleans, and visualizes the data.

## Steps

1. **Generate URL**
   - A URL is formatted for the 2024 season.
   - Option to loop through multiple years to fetch data for different seasons.

2. **Extract Data**
   - The webpage is read into a Pandas DataFrame using `pd.read_html()`.
   - The correct table is selected from the extracted data.

3. **Clean Data**
   - Duplicate player entries are removed to ensure unique records.

4. **Analyze Data**
   - A histogram is created using Seaborn to visualize the distribution of points per game (PTS).

## Requirements
- Python
- Pandas
- Seaborn

## How to Run
1. Install dependencies: `pip install pandas seaborn`
2. Run the script to scrape and analyze NBA player stats.

🏀



