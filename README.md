# web-scraping-challenge
Module 11 Challenge for the Tec de Monterrey Data Analysis Bootcamp, Introduction to Webscraping

Jupyter Notebook files that scrape webpages in order to extract information, and both create dictionary structures in Python as well as create Dataframes that can be further analyzed.

Main_part1_mars_news.ipynb is the first file. It scrapes this website: https://static.bc-edx.com/data/web/mars_news/index.html, extracts text elements, and stores the result in the form of dictionaries that relate titles and previews of articles in said website.

Main_part2_mars_news.ipynb is the second file. It scrapes this website: https://static.bc-edx.com/data/web/mars_facts/temperature.html, extracts the information from the table inside of the site, and with that information, it constructs a Pandas DataFrame that has the following information for weather observations in Mars:
- id
- terrestrial_date
- sol
- ls
- month
- min_temp
- pressure

Then, the data types are changed to better allow for the analysis, which answers the following questions:
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
- Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
- About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

The results are plotted in bar and plot charts, and finally the Dataframe is exported to a CSV File.

The main files for this project exist on the main directory, which also contains the Output directory, where the created CSV File from the Part2 is.

Contributions:
- Data Analysis Bootcamp Classes
- https://chromedriver.chromium.org/home
- https://chromedriver.chromium.org/documentation
- https://pandas.pydata.org/docs/user_guide/index.html#user-guide
- https://matplotlib.org/stable/index.html
- https://stackoverflow.com/questions/29858752/error-message-chromedriver-executable-needs-to-be-available-in-the-path


