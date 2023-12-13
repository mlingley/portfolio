## Metacritic Data Analysis Project

### Showcasing my proficiency with Python

This file contains the code I used to scrape data from Metacritic, as well as the steps taken to manipulate and clean that information within a Pandas dataframe.

I also used some data from VGChartz.com, credit to https://github.com/MikeGillotti/vgchartz-data whose webscraper I used to gather some info from this website. 
Since my project was primarily focused on Metacritic, I used their webscraper rather than building my own.

### Steps taken:
## Webscraping phase:
1. Created a webscraper to get the URLs for all games with a Metacritic score (excluded mobile games).
2. Iterated through the list of URLs to scrape info for each game.

## Data cleaning phase:
1. Cleaned the data to remove special characters and changed all titles to lowercase to reduce number of duplicates.
2. Merged Metacritic data with VGChartz data and dropped duplicated lines.
3. In excel, went through the data to delete any duplicated lines that couldn't be caught by normalizing the titles in python.
4. Filtered data down to "series" only in the "Console" field to separate game series from individual games.

## Visualization phase:
1. Loaded the Game Series and Individual Games files into Tableau and joined
2. Created a collection of graphs to explore the data and answer questions I had about the data.
3. Combined the graphs into a series of dashboards.
4. Created a comprehensive Tableau Story to visualize the data and my takeaways from the information.
