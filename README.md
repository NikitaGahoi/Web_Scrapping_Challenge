# Challenge 11 - Web Scraping

Module 11 assignment focused on honing our knowledge and skills of web scraping and data analysis. Here we demonstrate the usage of BeautifulSoup and Splinter with Selenium to extract data from websites and the use of Python libraries for the analysis of the extracted data

## Part 1, Mars News: Scrape Titles and Preview Text from Mars News 
In the notebook named "part_1_mars_news_Nikita.ipynb", I used automated browsing (with Splinter) to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). The titles and preview text of the news articles were scraped and extracted and the extracted information was stored in a list of dictionaries.

## Part 2, Mars Weather: Scrape and Analyze Mars Weather Data
In the notebook named "part_2_mars_weather-Nikita.ipynb", the HTML table was extracted into a Pandas DataFrame using Splinter and Beautiful Soup. The data was then cleaned and restructured assigning the appropriate data types. The extracted data was saved to mars_weather.csv. the data was then analyzed to answer some questions:

- How many months on Mars?<br>
  12 months
- How many Martian days of data are there?<br>
  1,867 days
- What are the coldest and warmest months on Mars?<br>
  Coldest: Month 3,<br>
  Warmest: Month 8
- Which months have the highest and lowest atmospheric pressure on Mars?<br>
  Highest: Month 9,<br>
  Lowest: Month 6
- About how many Earth days exist in a Martian year?<br>
  About 675 Earth days
