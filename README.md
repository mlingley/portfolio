### Data Analyst Portfolio

# Analysis of Metacritic Games
### Click for interactive story on Tableau Public



[![Image 1](https://public.tableau.com/static/images/An/AnalysisofMetacriticGames/Story1/1_rss.png)](https://public.tableau.com/views/AnalysisofMetacriticGames/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)
[![Image 2](assets/images/page2.png)](https://public.tableau.com/views/AnalysisofMetacriticGames/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)
[![Image 3](assets/images/page3.png)](https://public.tableau.com/views/AnalysisofMetacriticGames/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)
[![Image 4](assets/images/page4.png)](https://public.tableau.com/views/AnalysisofMetacriticGames/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)
[![Image 5](assets/images/page5.png)](https://public.tableau.com/views/AnalysisofMetacriticGames/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)
[![Image 6](assets/images/page6.png)](https://public.tableau.com/views/AnalysisofMetacriticGames/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)


# Metacritic Data Analysis Project

### Showcasing my proficiency with Python

[`Click here to view the code used in this project.`](https://github.com/mlingley/portfolio/tree/main/metacritic_project)

Steps taken:
##### Webscraping phase:
1. Created a webscraper to get the URLs for all games with a Metacritic score (excluded mobile games).
2. Iterated through the list of URLs to scrape info for each game.

##### Data cleaning phase:
1. Cleaned the data to remove special characters and changed all titles to lowercase to reduce number of duplicates.
2. Merged Metacritic data with VGChartz data and dropped duplicated lines.
3. In excel, went through the data to delete any duplicated lines that couldn't be caught by normalizing the titles in python.
4. Filtered data down to "series" only in the "Console" field to separate game series from individual games.

##### Visualization phase:
1. Loaded the Game Series and Individual Games files into Tableau and joined
2. Created a collection of graphs to explore the data and answer questions I had about the data.
3. Combined the graphs into a series of dashboards.
4. Created a comprehensive Tableau Story to visualize the data and my takeaways from the information.
