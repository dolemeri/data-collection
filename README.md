# UofT - Data Analysis Boot Camp

### Module 11 Challenge -  Data Collection

### Background

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

### This contains two technical products from the Mars news site:

1. Scrape titles and preview text from Mars news articles.
2. Scrape and analyze Mars weather data, which exists in a table.

### Part 1: Scrape Titles and Preview Text from Mars News

In the [notebook for Part 1](part_1_mars_news.ipynb), I scraped the site, extracted the article title and preview text, then saved the extracted data to [mars_news.json](mars_news.json).

See "part_1_mars_news.ipynb" file for commented code.
[part_1_mars_news](part_1_mars_news.ipynb)

#### Results

* Image of scraped Mars News as list of dictionaries

![1726166612290](image/README/1726166612290.png)

* Also exported scraped data to JSON file named mars_news.

### Part 2: Scrape and Analyze Mars Weather Data

See "part_2_mars_weather.ipynb" file for commented code.
[part_2_mars_weather](part_2_mars_weather.ipynb)

#### Results

* Image of scraped table in dataframe

![1726166474627](image/README/1726166474627.png)

* Data has been written to a CSV file
  [mars_weather_data](mars_weather_data)

#### Data Analysis

* The coldest and hottest months (of Curiosity's location) on Mars, sorted from coldest to warmest.
  On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest.

![1726166235247](image/README/1726166235247.png)

* Average atmospheric pressure. The atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.

![1726166346035](image/README/1726166346035.png)

* Earth days in a Martian year. The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.

![1726166387224](image/README/1726166387224.png)

After Analazing the data an graphs the results are reported visually by some of about graphs and question answered as below:

* How many months on Mars?
  - 12 months
* How many Martian days of data are there?
  - 1,867 days
* What are the coldest and warmest months on Mars?
  - Coldest: Month 3
  - Warmest: Month 8
* Which months have the hightest and lowest atmospheric pressure on Mars?
  - Hightest: Month 9
  - Lowest: Month 6
* About how many Earth days exist in a Martian year?
  - About 675 Earth days.
